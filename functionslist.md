# Music Player Functions List Document

## Global Function
These functions be applicable to global
### uuid()
Retuen a uuid.
****

## Local function1
These functions be applicable to in the wss.on('connection', function connection(ws, req){} function.
### cmd(Command)
Run a Minecraft command.
<Command> String;The contents of the directive, with '/' added.
****
### log(Log)
output a Log for console.
<Log> String;Log Content.
****
### chat(Message)
Sends a generic message to the player,Tape Prefix.
<Message> String;Message Content.

****
### chatf(Message,Name,Color)
Sends an advanced message to the player.
<Message> String;Message Content.
<Name> String;Optional;Sender's name.
<Color> Number;Optional;Test color.<font color="#AA000">0 Red</font>;<font color="#FEFE54">1 Yellow</font>;<font color="#54FFFF">2 Blue</font>;<font color="#54FF54">3 Green</font>.

****
### playsound(Music)
Play a Music.
<Music> String;Music Name(ID of in the SoundPack)
****
### stopsound()
Stop all playeing Music.

## Local function2
These functions be applicable to in the ws.on('message',function (message,wsi){} function.
onSay(Message,Callback,Parameter)
The callback function is triggered when the player sends the specified message.
<Message> String;Trigger Message.
<Callback> String;name of rigger function.
<Parameter> Any;Optional;Callback's Parameter.