# MentionMe
Spigot plugin for hashtags and tagging people.
* Plugin Version: 0.4.2
* Tested Minecraft & Spigot Version: 1.11.2 and 1.10.2

---

### Current Features
* Tagging specific users with `@[name]`.
* `@[name]` messages are colored.
* Support for using partial names.
* Support for tab completions.
* Tagging the whole server with '@Everyone'.
* Sound and colors are customizable.
* Actionbar Support.
* Title Support.
* Toggles to turn certain features off.
* Permissions.
* Color `#[hashtag]` messages in chat.
* DeluxeChat Integration.
* VentureChat Integration.

### Planned Features
1. Hashtags with trending support for Today/This Week/All Time.
2. Bossbar support.
3. Ability to change colors with in-game chat.
4. Ability to toggle off being pinged.
5. Cooldown support.

---

**Default Config**:
```YAML
# The "everyone-notify" options toggle whether the @everyone tag will use the features listed.
# The "selftag-notify" option will use default "notify" values if set to true.
# The "title-time" option below is in server ticks. 20 = 1 second
# You can get a full list of sounds at: https://hub.spigotmc.org/javadocs/spigot/org/bukkit/Sound.html
# The MentionMe source code is available at: https://github.com/MoMoe0/MentionMe

notify-in-chat: true
notify-in-actionbar: true
notify-in-title: false
everyone-notify-chat: true
everyone-notify-actionbar: true
everyone-notify-title: true
selftag-notify: false
enable-sound: true
mention-color: '&e'
hashtag-color: '&b'
mention-message: '&eYou were mentioned by &f%player%&e!'
title-message: '&eMentioned by:'
subtitle-message: '&f%player%'
title-time: 50
sound: ENTITY_EXPERIENCE_ORB_PICKUP
```
[List of sounds available from Spigot docs](https://hub.spigotmc.org/javadocs/spigot/org/bukkit/Sound.html)

---

[This project is licensed under the terms of the MIT license.](https://github.com/MoMoe0/MentionMe/blob/master/LICSENSE.md)
