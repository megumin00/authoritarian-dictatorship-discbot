# LogBot
Basic discord bot written to compile messages for mostly administration purposes

## License
GPL-3.0 License

## Commands
trusted commands(ur user ID needs to be in self.trusted in __init__):


;bindserver (server ID)                 - binds all messages from that server to be redirected to this channel (needs bot inside that server)

;displayactive                          - displays all active servers 

;annoy (targetID/mention)               - you get annoyed.

;displayannoy                           - shows all victims of harassment

;award (targetID) (points)              - gives good boy points

;deduct (targetID) (points)             - takes away good boy points



admin commands(you need permissions lol):


;clear (x)                              - clears x amount of messages in chat

;kick (targetID/mention) (reason)       - kicks a member using their ID or mentioning them. Duh. (reason is optional)

;ban (targetID/mention) (days) (reason) - bans a user using their ID or mentioning them. Duh. (days and reason are optionals and days=0 by default)


user commands(anyone can use these(you pleb)):


;help                                   - displays help menu 

;ping                                   - replies with pong

;embedthis (title) (body)               - takes your mortal loser message and converts it into an embed

;points (targetID/mention)              - displays how much ~~good boy~~ points the user has

## Contributors
megumin00
