# detachhead's filter lists

> [!IMPORTANT]
This project was originally called `ublock-filters` but it has since been renamed as it's no loger specific to uBlock Origin. Github should redirect old links, but I recommend updating your settings to point to the new URLs (details below) just to be safe.

## ublock/adguard filters

- [`list.txt`](./list.txt) - ads, malicious sites and right click/devtools blockers
- [`annoyances.txt`](./annoyances.txt) - annoying buttons, buttons in navs that are rarely used

### [subscribe](https://detachhead.github.io/filter-lists/)

## discord adblocker

[`list.txt`](./list.txt) contains filters for blocking discord ads. but that only works if you're using the discord web app in your browser. if you're using the desktop app, these filters are also available in [`discord.css`](./discord.css) - a theme that can be installed to a discord client mod such as [vencord](https://vencord.dev/).

note that the purpose of this list is strictly to block ads (eg. quests and promoted activites). if you would like to also block other elements such as nitro promotions, i recommend checking out [Disblock Origin](https://codeberg.org/AllPurposeMat/Disblock-Origin).

### installation

add the following URL to your client mod's theme settings:

```
https://raw.githubusercontent.com/DetachHead/filter-lists/refs/heads/master/discord.css
```

### blocking youtube ads in discord

i recommend also enabling the [YoutubeAdblock](https://github.com/vendicated/vencord/tree/main/src/plugins/youtubeAdblock.desktop) plugin:

![](./assets/youtubeadblock.png)
