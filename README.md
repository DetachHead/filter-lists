# detachhead's filter lists

> [!IMPORTANT]
This project was originally called `ublock-filters` but it has since been renamed as it's no loger specific to uBlock Origin. Github should redirect old links, but I recommend updating your settings to point to the new URLs (details below) just to be safe.

## ublock/adguard filters

### [`list.txt`](./list.txt)

Ads, malicious sites and right click/devtools blockers (recommended for all users)

> [!NOTE]
> This list does not block many ads on its own -- it's intended to be used in addition to the the mainstream ad blocking lists (eg. easylist, adguard, etc.). I try to upstream them to one of those lists when I can, but not all of the ads this list blocks are considered ads by some upstream list maintainers for some reason ([example](https://github.com/easylist/easylist/pull/24724))

### [`annoyances.txt`](./annoyances.txt)

Annoying buttons, buttons in navs that are rarely used (more opinionated, so you may not agree with everything it blocks)

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
