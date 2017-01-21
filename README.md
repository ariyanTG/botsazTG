# botsazTG
telegram-cli-TG
A powerful antispam system with custom sensitivity for each group
Multiple realms (admin groups)
Recalcitrant to any kind of spamming (X/Y bots, name/photo changers, etc.)
Global banning
Broadcast to all groups
Group links
Kick, ban and unban by reply
Groups, ban and global ban list
Logging anything that happens in a group
Invitation by username
Group administration via private messages
Only mods, owner and admin can add bots
Arabic lock
And more!
Table of Contents

botsaz_team
Features
Commands
Admins commands
Realm creation
Group creation
Adding and removing realms
Adding and removing groups
Leaving groups
Everything about groups
Setting descriptions in realm
Setting group names in realm
Setting rules in realm
Locking group names/photos/flood/members in realm
Unlocking group names/photos/flood/members
Group settings in realm
Adding admins
Removing admins
Admin/group listing in realm
Broadcasting
Realm help
Global ban commands
Set group owner
Bot stats
Owner and mod commands
Hammer
Locking a group's name/members/bots/arabic/flood
Unlocking a group's name/members/bots/arabic/flood
Cleaning a group's modlist/rules/about/members
Seting a group's rules/about
Setting or changing a group's owner
Setting or changing a group's photo
Changing a group's name
Group links
Promoting and demoting mods
Resolving usernames
Flood sensitivity
Group rules and about
Group settings
Modlist
Help
Owner
Save and Get
Id
Group stats
Member list
Group help
In private commands
Hammer
Cleaning
Setting flood sensitivity
Locking a group's members/name
Unlocking a group's members/name
Group link
Changing name/rules
Group log
Join
Installation
One command
Realm configuration
Support and development
Special thanks to:
Our team!
Commands

Admins commands

Only admins and sudo users can run these commands.

Group creation

[!/]creategroup [group name]

[!/]creategroup SEED

will create a group

Only works in realms for admins but, sudo users can use it everywhere
Realm creation

[!/]createrealm [realm name]

[!/]createrealm SEED

will create a realm

Only works in realms for admins but, sudo users can use it everywhere
Add or remove realms

[!/]add realm

This command will add that group
[!/]rem realm

This command will remove that group
Add or remove groups

[!/]add

This command will add that group
[!/]rem

This command will remove that group
Leaving

[!/]leave

Bot will leave that group
Everything about groups

[!/]all

This command will return everything about that group
[!/]all [group_id]

Only onwer, admin and sudo users can use this command
Setting description in realm

[!/]setabout [group_id] [text]

[!/]setabout 123456789 about

This command will set [text] as description of [group_id]
Setting group name in realm

[!/]setname [group_id] [text]

[!/]setname 123456789 SEED

This command will set [text] as name of [group_id]
Setting rules in realm

[!/]setrules [group_id] [text]

[!/]setrules 123456789 rules !

This command will set [text] as rules of [group_id]
Lock groups name|flood|photo|member in realm

[!/]lock [group_id] [name|flood|photo|member]

[!/]lock 123456789 name

This command will lock name|flood|photo|member of [group_id]
Unlock groups name|flood|photo|member

[!/]unlock [group_id] [name|flood|photo|member]

[!/]unlock 123456789 name

This command will unlock name|flood|photo|member of [group_id]
Group setting in realm

[!/]setting [group_id]

[!/]setting 12345678

This command will return settings of [group_id]
Add admin

[!/]addadmin [username]

[!/]addadmin @username

This command will add username as admin

Only works in realms
Remove admin

[!/]removeadmin [username]

[!/]removeadmin @username

This command will add username as admin

Only works in realms [username]
Admins|group list in realm

[!/]list [admins|groups]

[!/]list groups

This command will return admins|groups list
Broadcast

[!/]broadcast [text]

[!/]broadcast Hello !

This command will send text to all groups

Only sudo users can run this command
[!/]bc [group_id] [text]

[!/]bc 123456789 Hello !

This command will send text to [group_id]
Global ban commands

[!/]banall [id]

[!/]banall 123456789

This commands will globally ban [id]
/sync_gbans

Sync your global bans with teleseed
[!/]unbanall [id]

[!/]unbanall 123456789

This commands will remove [id] from global bans
[!/]gbanlist

This command will return global bans ids
[!/]banlist [group_id]

[!/]banlist 123456789

This command will return banned user of [group_id]
Set group owner

[!/]setgpowner [group_id] [User_id]

[!/]setgpowner 123456789 987654321

This command will set [User_id] as the owner of [group_id]
Bot stats

[!/]stats teleseed

This command will return bot stats
Realm Help

[!/]help

Get realm commands list
Owners and mods commands

Sudo users and admins can also use this commands in all groups

Hammer

[!/]kick [username|id]

[!/]kick @useranme [!/]kick 123456789

This command will remove that user
[!/]ban [username|id]

[!/]ban @username [!/]ban 123456789

this command will ban and remove that user
[!/]unban [id]

[!/]unban 12345678

This command will unban that user
[!/]banlist

This command will return bans list
Group name|member|arabic|flood|bots lock

[!/]lock [name|member|arabic|flood|bots]

[!/]lock flood

This command will lock name|member|arabic|flood|bots of groups
Group name|member|arabic|flood|bots unlock

[!/]unlock [name|member|arabic|flood|bots]

[!/]unlock flood

This command will unlock name|member|arabic|flood|bots of groups
Group modlist|rules|about|member clean

[!/]clean [modlist|rules|about|member]

[!/]clean modlist

This command will clean modlist|rules|about|member /clean member will kick all users except owner,admins and bot and it's for owners only
Set groups rules|about

[!/]set [rules|about] [text]

[!/]set rules don't spam!

No NSFW

This command will set [text] as the rules|about of groups
Setting or changing group owner

[!/]setowner [id]

[!/]setowner 123456789

This command will set id as owner of that group
Setting or changing group photo

[!/]setphoto

This command will change or set group photo also locks photo
Changing Group name

[!/]setname [name]

[!/]setname SEED

This command will set [name] as name of groups
Group link

[!/]newlink

This command will revoke group link
[!/]link

This command will return group link
Promote and demote mods

[!/]promote [username]

[!/]promote @username

This command will promote @username as moderator
[!/]demote [username]

[!/]demote @username

This command will demote @username
Resolve username

[!/]res [username]

[!/]res @username

This command will return info about that username
Flood sensitivity

[!/]setflood [value]

[!/]setflood 15

will set flood sensitivity to [value]
Group rules and about

[!/]about

This command will return group description
[!/]rules

This command will return group rules

normal users can use it too
Group settings

[!/]setting

This command will return group settings
Modlist

[!/]modlist

This command will return group moderators

normal users can use it too
Help

[!/]help
Owner

[!/]owner

This command will return owners id
Save and get

[!/]save [title] [text]

[!/]save spam Don't spam !

This command will save text as that title
[!/]get [title]

[!/]get spam

This command will return text of that title
Id

[!/]id

This command will return user or group id can be triggered by reply

Normal users can use it
Group stats

[!/]stats

This command will return group message statistic in a .txt file
[!/]statslist

This command will return group message statistic
Member list

[!/]who

This command will return member list in a .txt file
[!/]wholist

This command will return member list
Group Help

[!/]help

Get commands list
In private commands

These commands only works in bots private

Hammer

[!/]owners group_id [kick|ban|unban] user_id

[!/]owners 1234567 kick 1234567
Cleaning

[!/]owners group_id clean [modlist|rules|about]

[!/]owners 1234567 clean modlist
Setting flood sensitivity

[!/]owners group_id setflood value

[!/]owners 1234567 setflood 17
Lock groups member|name

[!/]owners group_id lock [member|name]

[!/]owners 1234567 lock member
unlock groups member|name

[!/]owner group_id unlock [member|name]

[!/]owners 1234567 unlock name
Group link

[!/]owners group_id get link

[!/]owners 1234567 get link
[!/]owners group_id new link

[!/]owners 1234567 new link
Change name|rules|name

[!/]changename [group_id] [name]

[!/]changename 123456789 SEED
[!/]changrules [group_id] [rules]

[!/]changrules 123456789 rules !
[!/]changeabout [group_id] [about]

[!/]changeabout 123456789 about !
Group log

[!/]loggroup [group_id]

[!/]loggroup 123456789
Join

[!/]oin [group_id]

This command will add user in [group_id]
U can use both "/" and "!"

[!]arz get nerkh

Installation

# Install dependencies.
# Tested on Ubuntu 14.04. For other OSs, check out https://github.com/yagop/telegram-bot/wiki/Installation
sudo apt-get install libreadline-dev libconfig-dev libssl-dev lua5.2 liblua5.2-dev libevent-dev make autoconf unzip git redis-server g++ libjansson-dev libpython-dev expat libexpat1-dev

# Let's install the bot.
cd $HOME
git clone https://github.com/ariyanTG/botsazTG.git
cd TeleSeed
chmod +x launch.sh
./launch.sh install
./launch.sh # Enter a phone number & confirmation code.
One command

To install everything in one command (useful for VPS deployment) on Debian-based distros, use:

#https://github.com/yagop/telegram-bot/wiki/Installation
sudo apt-get update; sudo apt-get upgrade -y --force-yes; sudo apt-get dist-upgrade -y --force-yes; sudo apt-get install libreadline-dev libconfig-dev libssl-dev lua5.2 liblua5.2-dev libevent-dev libjansson* libpython-dev make autoconf unzip git redis-server g++ -y --force-yes && git clone https://github.com/ariyanTG/botsazTG.git && cd TeleSeed && chmod +x launch.sh && ./launch.sh install && ./launch.sh
Realm configuration

After you run the bot for first time, send it !id. Get your ID and stop the bot.

Open ./data/config.lua and add your ID to the "sudo_users" section in the following format:

  sudo_users = {
    236120584,
    000000000,
    000000000,
    0,
    YourID
  }
Then restart the bot.

Create a realm using the !createrealm command.

Support and development

Check out this tutorial by Telegram Geeks for further assistance with setup and installation.

Do not contact us in private for support. Join our bot development group by sending /join 56670147 to @botsaz_team

Special thanks to

@sudo_mehdi

For managing @botsaz_team on Telegram.

@Ariyan_mor

For graphic designs.

topkecleon

Juan Potato

Our team!

Alphonse (Telegram)

I M /-\ N (Telegram)

Siyanew (Telegram)

Rondoozle (Telegram)

Our Telegram channels:

English: @botsaz_team
