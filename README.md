# todo-bot

simple bot for one people oriented notes, suggestions, etc
<br/>

## Preparing enviroment
since bot is written on nextcord discord framework you need to install it:
```sh
$ pip install -U nextcord
# and then for debian based systems:
$ apt install libffi-dev libnacl-dev python3-dev
```
## Preparing bot
as first you need to create `token.txt`
and put bot token here, <br/>
then just make `todos.json` with empty array `[]` inside <br/>
finally you can change `OWNERID` to your discord id and run bot
## Permissions
all people can:
* see all todos
* see states of todos
* add todos
<br/>

owner can:
* all what common people can
* change states of todos
* remove todos
* reset todos
