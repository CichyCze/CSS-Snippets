# CSS-Snippets
A compilation of CSS snippets for Discord and its custom clients.

![GitHub License](https://img.shields.io/github/license/SEELE1306/Modular?style=for-the-badge)
![Static Badge](https://img.shields.io/badge/supports-vesktop-red?style=for-the-badge)
![Static Badge](https://img.shields.io/badge/supports-vencord-red?style=for-the-badge)
![Static Badge](https://img.shields.io/badge/supports-betterdiscord-navy?style=for-the-badge)

> [!NOTE]
> This is a fork of the original [CSS-Snippets](https://github.com/SEELE1306/CSS-Snippets) which has, unfortunately, been archived. I'll try to keep it up-to-date as I use a few of those snippets myself. I'm not promising anything with my poor Discord's CSS knowledge and time unavailability tho.

> [!CAUTION]
> A [slight maintenance](https://github.com/CichyCze/CSS-Snippets/milestone/1) is going underway. That includes mostly some fixes, documentation edits, and bringing back the removed snippets.
>
> Also, `UserPanel` is currently a bit broken. Fix is planned (see [#1](../../issues/1)).

> [!WARNING]
> Because of a major revamp of the user profiles in the mid-2024, the original author decided to temporatily remove the `BetterProfiles` and `UserOptions` snippets. Their return is planned (see [#2](../../issues/2), [#3](../../issues/3) and [#4](../../issues/4)).

## List of available snippets
| Snippet | Description | Image |
| -------- | ------- | ------- |
| [BetterQuotes](Snippets/BetterQuotes/) | Improves blockquotes styling to make them more visible and appealing. | <img valign='middle' alt='BetterQuotes' src='./docs/_media/BetterQuotes.png'/> |
| [AccentColor](Snippets/ChangeColor/AccentColor/) | Replaces the Blurple [<img valign='middle' alt='blurple' src='https://readme-swatches.vercel.app/5865F2?style=circle&size=10'/>#5865F2] accent color with one of your choice. | <img valign='middle' alt='AccentColor' src='./docs/_media/AccentColor.png'/> |
| [ClientColor](Snippets/ChangeColor/ClientColor/) | Replaces the Grey [<img valign='middle' alt='grey' src='https://readme-swatches.vercel.app/313338?style=circle&size=10'/>#313338] client color with one of your choice. | <img valign='middle' alt='ClientColor' src='./docs/_media/ClientColor.png'/> |
| [OtherColors](Snippets/ChangeColor/OtherColors/) | Replaces other Discord colors (red, yellow, green, etc.) with Blurple [<img valign='middle' alt='blurple' src='https://readme-swatches.vercel.app/5865F2?style=circle&size=10'/>#5865F2].| <img valign='middle' alt='OtherColors' src='./docs/_media/OtherColors.png'/> |
| [ChannelSelections](Snippets/ChannelSelections/) | Adds more spacing between the channel icons and colored unread notifiers. | <img valign='middle' alt='ChannelSelections' src='./docs/_media/ChannelSelections.png' height='200px'/> |
| [ChatBubbles](Snippets/ChatBubbles/) | Wraps messages inside chat bubbles. Also, different colors for normal, reply, mention and automod messages are available. | <img valign='middle' alt='ChatBubbles' src='./docs/_media/ChatBubbles.png'/> |
| [GuildBoost](Snippets/GuildBoost/) | Replaces the guild boost bar with a more appealing one. | <img valign='middle' alt='GuildBoost' src='./docs/_media/GuildBoost.png' height='200px'/> |
| [MessageSection-v2](Snippets/MessageSection/v2/) | Makes the unread messages elements more appealing. | <img valign='middle' alt='MessageSection-v2' src='./docs/_media/MessageSection-v2_02.png'/> |
| [MessageTypes](Snippets/MessageUltilities/MessageTypes/) | Adds text descriptions to messages based on the action. Currently available in `Czech`, `English` and `German`. | <img valign='middle' alt='MessageTypes' src='./docs/_media/MessageTypes.png'/> |
| [TimestampBubbles](Snippets/MessageUltilities/TimestampBubbles/) | Applies a bubble styling to the message timestamps. | <img valign='middle' alt='TimestampBubbles' src='./docs/_media/TimestampBubbles.png'/> |
| [Username](Snippets/MessageUltilities/Username/) | Applies a bubble to the usernames that abide by role color. | <img valign='middle' alt='Username' src='./docs/_media/Username.png'/> <img valign='middle' alt='Username' src='./docs/_media/Username_ext.png'/>|
| [OnekoDM](Snippets/OnekoDM/) | Replaces the discord logo with Oneko! | <img valign='middle' alt='OnekoDM' src='./docs/_media/OnekoDM.png'/> |
| [UserPanel](Snippets/UserPanel/) | Replaces the user panel with a customizable and more appealing version. | <img valign='middle' alt='UserPanel' src='./docs/_media/UserPanel.png'/> |
| [ToolbarHide](Snippets/ToolbarHide/) | Hides the top toolbar for a cleaner layout. | <img valign='middle' alt='ToolbarHide' src='./docs/_media/ToolbarHide.png'/> |
| [StaffTags](Snippets/StaffTags/) | Applies styling to different staff tags for easier identification. | <img valign='middle' alt='StaffTags' src='./docs/_media/StaffTags.png'/> |
| [Titlebar](Snippets/Titlebar/) | Changes the default Discord titlebar to a more visually appealing one. Text and background color is customizable. | <img valign='middle' alt='Titlebar_01' src='./docs/_media/Titlebar_01.png'/> <img valign='middle' alt='Titlebar_02' src='./docs/_media/Titlebar_02.png'/> |
| [SpotifyControls](Snippets/SpotifyControls/) | Redesigns the Spotify Controls. | <img valign='middle' alt='SpotifyControls' src='./docs/_media/SpotifyControls.png'/> |

## List of temporarily unavailable snippets
| Snippet | Description | Image |
| -------- | ------- | ------- |
| BetterProfiles | Improves general layout of user profiles, improving readability and visual appeal. Credits to [Saltssaumure](https://github.com/Saltssaumure) for the role pills. | <img valign='middle' alt='BetterProfiles' src='./docs/_media/BetterProfiles.png' height='400px'/> |
| GuildList | Makes the guild/server list more more efficient and more appealing. | <img valign='middle' alt='GuildList' src='./docs/_media/GuildList.png'/> |
| UserOptions | Replaces the profile popout with more streamlined options | <img valign='middle' alt='UserOptions' src='./docs/_media/UserOptions.png'/> |

## Apply
There are several methods to apply these snippets. The methods below are for Vencord, however other clients have similar methods.

The `import.css` might not work properly on a client other than [Vesktop](https://github.com/Vencord/Vesktop). In case of issues, try using the `import-legacy.css`, if available.

### Methods
<details>
<summary>QuickCSS</summary>

1. Navigate to the snippet you'd like to use. There should be an `import.css` file present.
2. Click on the file and once it's loaded, click the `Raw` button.
3. Once the file opens in your browser, copy the URL.
4. On your Vencord client, open `Settings` > `Vencord` > `Edit QuickCSS`.
5. On top of your QuickCSS, put `@import url(URL OF THE FILE);`. The client should automatically apply the theme.
</details>

<details>
<summary>Online Themes</summary>

1. Navigate to the snippet you'd like to use. There should be an `import.css` file present.
2. Click on the file and once it's loaded, click the `Raw` button.
3. Once the file opens in your browser, copy the URL.
4. On your Vencord client, open `Settings` > `Themes` > `Online Themes`.
5. Inside the text box, paste the URL you coppied in step 3.
6. Click outside the text box for the theme to apply.
</details>

<details>
<summary>Local Themes</summary>

1. Navigate to the snippet you'd like to use. There should be an `import.css` file present.
2. Click on the file and once it's loaded, download the file via the `Download raw file` button.
3. On your Vencord client, open `Settings` > `Themes` > `Local Themes` > `Open Themes Folder`.
4. Once the folder opens, put the downloaded file inside. The client should automatically apply the theme.
</details>

## Special thanks to

- [Aoi](https://github.com/SEELE1306) for creating these lovely snippets ❤️
+ [ant0n-0x0000](https://github.com/ant0n-0x0000) for helping out with the snippets' descriptions!
+ [Saltssaumure](https://github.com/Saltssaumure), [Lexia](https://github.com/exterpolation), [UzinSG](https://github.com/UzinSG) for various elements within the snippets!