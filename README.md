# WizardUI – Watermark Removal 

[![Version](https://img.shields.io/badge/version-1.5-blue)](https://github.com/GoldenLys/WizardUI) [![License](https://img.shields.io/badge/license-MIT-green)](https://github.com/GoldenLys/WizardUI/blob/main/LICENSE) [![Website](https://img.shields.io/badge/website-nebulys.eu-purple)](https://nebulys.eu/)

![WizardUI Preview](https://goldenlys.github.io/WizardUI/images/home.png)

**WizardUI** is a modular, fully customizable Discord theme made with 💖 by NEBULYS. This edit removes the watermark and allows you to enjoy the theme cleanly.

---

## Installation

1. Click on the Edit button next to the WizardUI theme in BetterDiscord.  
2. Delete all existing code.  
3. Copy and paste the code below:

```css
/**
* @name WizardUI
* @author NEBULYS
* @authorLink https://github.com/GoldenLys
* @version 1.5
* @invite SBuYeHh
* @description Modular and fully customizable theme by NEBULYS.
* @website https://nebulys.eu/
*/

@import url("https://fonts.googleapis.com/css?family=Quicksand&display=swap");
@import url("https://cdn.jsdelivr.net/gh/Mata0777/WizardUI-Watermark-Removal@main/base.css");
@import url("https://goldenlys.github.io/WizardUI/addons/PurpleServerList.css");
@import url("https://goldenlys.github.io/WizardUI/addons/LettersInPSL.css");
@import url("https://goldenlys.github.io/WizardUI/addons/AlternateFoldersInPSL.css");
@import url("https://goldenlys.github.io/WizardUI/addons/HoverMembers.css");
@import url("https://goldenlys.github.io/WizardUI/addons/UserIsTyping.css");
@import url("https://goldenlys.github.io/WizardUI/addons/EvenMoreColors/1.css");
@import url("https://goldenlys.github.io/WizardUI/addons/UniqueChatbar.css");

:root {
    /* Main Variables */
    --Watermark: "- WizardUI v" var(--version);
    --font: 'Quicksand', 'emoji', sans-serif;
    --Text: rgb(255, 255, 255);
    --logo: url(https://goldenlys.github.io/WizardUI/images/home.png);
    --sendmessage-text-lines: 8;

    /* Status Colors */
    --Online: rgb(0, 255, 6);
    --Idle: rgb(18, 100, 239);
    --Unavailable: rgb(228, 15, 0);
    --Offline: rgb(90, 95, 100);
    --Streaming: rgb(110, 0, 196);

    /* UI Colors */
    --grey: rgb(18,19,31);
    --grey5: rgba(18,19,31,.75);
    --darkgrey: rgb(10,10,20);
    --darkgrey5: rgba(10,10,20,.75);
    --ui-success: rgb(69,208,34);
    --ui-warning: rgb(238,165,30);
    --ui-error: rgb(208,34,34);

    /* Theme Colors */
    --Primary: rgb(117 76 205);
    --text-link: var(--Primary);
    --text-shadow: rgb(0 0 0);
    --Highlighted: rgba(117 76 205 / 50%);
    --MessageHover: transparent;
    --Unread: rgb(173,16,16);
    --Hover: rgb(18 19 31 / 50%);

    /* Backgrounds */
    --background: url(https://goldenlys.github.io/WizardUI/images/backgrounds/nebula.jpg);
    --bg-titlebar: rgba(0,0,0,0.65);
    --bg-servers: rgba(0,0,0,0.65);
    --bg-ui: rgba(0,0,0,0.65);
    --bg-chatbox: rgba(0,0,0,0.5);
    --bg-sendmessage: rgba(0,0,0,0.65);
    --bg-members: rgba(0,0,0,0.65);
    --bg-chat-elements: rgba(0,0,0,0.5);
    --bg-settings: var(--darkgrey);
    --bg-colorprofile: rgba(0,0,0,0.5);
    --bg-alt-message: transparent;

    /* Servers */
    --ServerSize: 45px;
    --ServerPills: var(--Primary);
    --ServerFoldersColor: var(--Primary);

    /* Rounding */
    --Rounding: 5px;
    --AvatarRounding: var(--Rounding);

    /* RGB Addon */
    --ColorTime: 2s;
    --Color2: rgb(0,225,255);
    --Color3: rgb(0 0 0);
    --Color4: rgb(0 0 0);
    --Color5: rgb(0 0 0);
    --Color6: rgb(0 0 0);
    --Color7: rgb(0 0 0);
    --Color8: rgb(0 0 0);
    --Color9: rgb(0 0 0);
    --Color10: rgb(0 0 0);

    /* Message Box Buttons */
    --Show_Gift_Button: none;
    --Show_GIF_Button: none;
    --Show_Sticker_Button: none;
    --Show_Apps_Button: flex;
}
