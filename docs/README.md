# Usage

[Invite link](https://discord.com/api/oauth2/authorize?client_id=992849804197630003&permissions=2147485696&scope=bot%20applications.commands)

## `/sticker {character} {sticker}`

Sends a sticker to the channel

`character` should be someone who is currently covered by the sticker API from <https://wah.rest>

`sticker` should be one of their stickers

If the sticker is found, it's shown.
Otherwise, the bot will tell the user that the sticker wasn't found.

Examples:

Successful result

![Example 1 - Arguments are "burner" and "wah"](./images/example1-args.webp)
![Result 1 - A sticker is shown](./images/example1-result.webp)

Unsuccessful result

![Example 2 - Arguments are "burner" and "mow"](./images/example2-args.webp)
![Result 2 - A message telling the user that the sticker couldn't be found is shown](./images/example2-result.webp)

## `/invite`

Get an invite link to add the bot to your server.
This link is only shown to whoever used the command.
