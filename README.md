# [delete](https://telegram.me/Delete_TM)

**An advanced and powerful administration bot based on NEW TG-CLI


* * *

## Commands

| Use help |
|:--------|:------------|
| [#!/]help | just send help in your group and get the commands |

**You can use "#", "!", or "/" to begin all commands

* * *

# Installation

```sh
# Let's install the bot.
cd $HOME
git clone https://github.com/ramindel22/delete.git
cd delete
chmod +x delete.sh
./delete.sh install
./delete.sh 
# Enter a phone number & confirmation code.
```
### One command
To install everything in one command, use:
```sh
cd $HOME && git clone https://github.com/ramindel22/delete.git && cd delete && chmod +x delete.sh && ./delete.sh install && ./delete.sh
```

* * *

### Sudo

Open ./bot/bot.lua and add your ID to the "sudo_users" section in the following format:
```
    sudo_users = {
    240870611,
    0,
    YourID
  }
```
add your ID at line 72 in bot.lua and add your ID at line 2 in tools.lua, Then restart the bot.

# Support and Development

More information [delete Global Chat](https://t.me/joinchat/AAAAAEAYAluAzlzQS6PiYw)

### Our Telegram channel:

[@Delete_TM](https://telegram.me/Delete_TM)
