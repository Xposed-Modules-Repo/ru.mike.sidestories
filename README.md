# Telegram Tweaks

<img src="https://i.postimg.cc/vHRBZtg4/2025-03-28-223254129.png" width="288" height="260">

An all-in-one collection of the known fixes:
- Action bar stories fix (hide or move to the drawer)
- Mute/unmute chat bottom button fix (make it chat/channel's notifications status label)
- Chat bottom gift button fix (hide it to prevent accidental taps)
- (Added) lspatch support
- (Added) block internal Telegram updates check

<img src="https://i.postimg.cc/Jhh72Tg2/2025-03-28-223330500.png" width="233" height="78">

## Install notes:
- install apk
- enable the module in your xposed manager app
- (for lsposed) select the Telegram app in the scope
- Enable preferred tweaks in the module's settings page
- reboot (in case of (Ed)xposed) or terminate the Telegram app (lsposed)
- profit!

## Author
[MikeZh](https://4pda.to/forum/index.php?showuser=683427), 2025

# Deprecated apps:

## SideStories & HideStories

Removing stories from the the Telegram messenger's action bar

In the official Telegram messenger client you can remove stories from the position above chats and (optionally) create a side menu item.

## SideStories:
Removes stories from the action bar and puts them in the side menu. You can open the stories either through the side menu item or by tapping on the avatars in the chat list. Open the story viewer and scroll through the stories by swiping left or right, or by tapping on the edges.

<img src="https://github.com/Xposed-Modules-Repo/ru.mike.sidestories/assets/69295889/d15dcb53-4baf-4a95-868e-64e136e97d16" width="143" height="259">

## HideStories:
Just removes stories. It is possible to open them only by tapping on the avatars, i.e. stories from people / channels to which you are not subscribed cannot be open!

<img src="https://github.com/Xposed-Modules-Repo/ru.mike.sidestories/assets/69295889/a5754147-4d86-481a-910f-7385bcaf9d54" width="233" height="185">

## UnmuteButtonFix (bonus):
Make chat's bottom mute/unmute button like a label with chat/channel's notifications status. Just for prevent accidentally switch it :-) Use action bar menu to toggle notifications instead as usual.

<img src="https://github.com/Xposed-Modules-Repo/ru.mike.sidestories/assets/69295889/321e6a32-6417-4c84-b022-e1dd605c3b73" width="233" height="185">

## Install notes:
- install apk
- enable the module in your xposed manager app
- (for lsposed) select the Telegram app in the scope
- reboot (in case of (Ed)xposed) or terminate the Telegram app (lsposed)
- profit!

## Author
[MikeZh](https://4pda.to/forum/index.php?showuser=683427), 2023-2024