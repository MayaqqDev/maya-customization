# maya-customization
A repo with some stuff I use!

## Vencord
I have some css here that I use on discord, I use Vencord for this but you can use any other css loader like OpenAsar and others
```css
/* dracula theme */
@import url("https://slowstab.github.io/dracula/BetterDiscord/source.css");
@import url("https://mulverinex.github.io/legacy-settings-icons/dist-native.css");

[data-list-item-id^=channels___],
[class^=titleWrapper] > h1,
[class^=resultChannel],
[class^=placeholder][class*=slateTextArea]
{
    font-family: "Dashless", var(--font-primary);
}
/* profile panel thingy */
@import url("https://snare-hawk.github.io/snare-CSS/profile-panel-thingy.css");

/* minor tweaks, usually gets rid of nitro advertisments or annoying popups and buttons */
.tutorialContainer-1pL9QS .wrapper-3kah-n g path:not(:first-child){
    display: none;
}

[class^="channelTextArea"] [class^="buttons-"] > div:not(.expression-picker-chat-input-button):not([class^="separator-"]) {
    display: none !important;
}

[data-list-item-id^="private-channels-uid_"][data-list-item-id$="_nitro"] {
  display: none;
}

[aria-label="Help"] {
    display: none;
}

[aria-label="Send a gift"] {
    display: none;
}

.blockedSystemMessage-3FmE9n {
    display: none;
}

.threadSuggestionBar-3ExSyc {
    display: none;
}

/* twemoji everywhere */
@font-face {
    font-family: "TwemojiColor";
    src: url("https://vendicated.github.io/random-files/Twemoji.Mozilla.ttf");
}
:root {
    --font-primary: "gg sans", sans-serif, "TwemojiColor";
}
```
