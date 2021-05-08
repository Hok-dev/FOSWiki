## Commands 
###### `<>`: Required 
###### `[]`: Optional
- Informations
  - Help (`help`)
  - View Online (`online`)
    - aliases: `info`
  - User Info (`userinfo <user>`)
    - aliases: `ui`
  - Quote (`quote <message-link>`)
  - Suggest (`suggest <suggestion>`)
  - Color (`color <hex-color>`)
  - Avatar (`avtar <user>`)
    - aliases: `av`
  - Rule (`rule [rule-number]`)
  - Bot Info (`botinfo`)
    - aliases: `ping`, `uptime`
- Credits
  - Add Credit (`addcredit <amount> <user>`)
    - aliases: `ac`
  - Remove Credit (`removecredit <amount> <user>`)
  - Transfer Credit (`transfer <amount> <user>`)
    - aliases: `tip`
  - Credit (`credit <user>`)
  - Credit Leaderboard (`creditleaderboard [page]`)
    - aliases: `clb`
  - XP (`xp <user>`)
  - XP Leaderboard (`xpleaderboard [page]`)
    - aliases: `xplb`
- Workshops
  - Workshop (`workshop`)
    - aliases: `ws`
  - Create Workshop (`createworkshop`)
    - aliases: `cws`
  - Cancel Workshop (`cancelworkshop <workshop-id>`)
    - aliases: `cancelws`
- Time
  - Time (`time [user]`)
  - Get Time (`timeget <HH:mm> <timezone>`)
  - Set Timezone (`timeset <timezone>`)
  - Convert Time (`timeconvert <HH:mm> <timezone-from> <timezone-to>`)
  - Times (`times`)
  - Timezones (`timezone`)
- Timers
  - Start Timer (`timer <name>`)
  - Start Timer (`cancel <name>`)
  - View Timer (`viewtimer`)
  - Scheduled Timer (`schedule <HH:mm> <name>`)
- QOTD
  - Suggest QOTD (`suggestqotd`)
  - QOTD (`qotd "<wyr-1>~<wyr-2>" "<funfact>" "<question>"`)
  - Edit QOTD (`editqotd`)
- Birthday
  - Birthday (`birthday`)
    - aliases: `bday`
  - Set Birthday (`setbirthday`)
    - aliases: `setbday`, `setbd`
- Fun
  - Would You (`wouldyou`)
  - Anski (`anski`)
  - Gingy (`gingy`)
  - Flip (`flip`)
  - Dice (`dice`)
  - Simp (`simp [user]`)

## Other Features
### Credit System
`With the credits earned, you can use it in the shop channel.`

How you can gain credits:
* Every invite, you can gain 1 credit
* Helping out in the help channels
* Host a workshop (credit per 5 minutes of hosting)


### XP System
`The required xp to level up increases by 50% than previous required starting at 200 xp and capped at 1012 xp. (From Level 5, you would need 1012 more xp to levelup)`


```java
To  reach level 1: 200 xp
To  reach level 2: 300 xp (50% more than 200 xp)
~~~~~
To  reach level 5: 1012 xp 
To  reach level 6: 2024 xp (+1012 xp than previous)
~~~~~
```

How you can gain xp:
* Every minute, you can gain 1 xp by talking in a text channel
* Every few minutes, you can gain 1 xp by being in a voice channel 
(*XP will be added when you leave the voice channel*)

### Report Function
`When a user breaks one of the rules of the server, you can report (option for reporting anonymously)`

How to report:
* React to the message in rules channel for reporting
* Type `f!report` in the DM with the bot

How it goes:
1. Choose if report anonymously
2. Send the user-tag for the rule breaker
3. Send which rule they broke and proof if there is any
