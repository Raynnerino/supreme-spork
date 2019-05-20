/*
This Theme Uses Code From The Following Themes I DO NOT TAKE CREDIT FOR THE CODE USED FROM THEM,
Please Check Them Out

Simplified-Green made by den -> https://github.com/denBot/Simplistic-CSS/blob/master/Simplified-Green.theme.css   
Server_Grid_2_Columns made by Jiiks -> https://gist.github.com/Jiiks/e1026d29aac91e7a7ad2d90dee87c90c 
Status picker by URI -> https://cmpdc.github.io/bdtf/themes/FullScreenStatusPicker/fullScreenStatusPicker.theme.css

*/

@import url('https://nfld99.github.io/Better-Discord/Notifications/Made_By_NFLD99.css');
@import url('https://nfld99.github.io/Better-Discord/Source_Code/FI/FIL.css');
@import url('https://nfld99.github.io/Better-Discord/Source_Code/FI/BL.css');
@import url('https://anti-betterdocs.github.io/BlockBetterDocs/code.css');
:root {
  --Update-Text: " Update #329 ";
  --File-Updated-2019-5-10: url(https://nfld99.com/images/REDOWNLOAD.png);
  --Settings-Dock-Colour: var(--Main-Colour);
  --BetterDocsBlockerRed: var(--Main-Colour);
  --BetterDocsBlockerWhite: var(--Main-Colour);
  --BetterDocsBlockerBlack1: rgb(22, 22, 22);
  --BetterDocsBlockerBlack2: rgba(0, 0, 0, 0.5);
  --ServerFolders-Guild-Columns: var(--Guild-Columns);
}

/* TEMP FIX FOR SERVER FOLDERS */
/* TEMP FIX FOR SERVER FOLDERS */
/* TEMP FIX FOR SERVER FOLDERS */
/* TEMP FIX FOR SERVER FOLDERS */

/* [id*="folder_"] > div.wrapper-sa6paO.pill-31IEus > span{
  display: none;
} */

/* TEMP FIX FOR SERVER FOLDERS */
/* TEMP FIX FOR SERVER FOLDERS */
/* TEMP FIX FOR SERVER FOLDERS */
/* TEMP FIX FOR SERVER FOLDERS */


/* THANKYOU URI FOR HELPING ME UPDATE THIS <3 */

[layer-id="user-settings"] .userSettingsAccount-2eMFVR~ :last-child:after {
  margin-top: 10px;
  margin-bottom: -3px;
  padding-top: 10px;
  padding-left: 10px;
  display: block;
  background: transparent;
  border: 1px solid var(--Main-Colour);
  border-radius: 5px;
  content: url('data:image/svg+xml; utf8, <svg xmlns="http://www.w3.org/2000/svg" viewBox="0 0 680 200" style="width:100%;height:100px;"><g style="fill: lime; font-size: .8em; font-family:verdana"><text y="20" style="font-size: 2em; fill: lime;">Links</text><text y="45" style="font-size: 1.1em;" x="37">Github Link: https://nfld99.com/github</text><text y="65" style="font-size: 1.1em;" x="37">Support Server Link: https://nfld99.com/discord</text><text y="85" style="font-size: 1.1em;" x="37">My Twitch: https://nfld99.com/twitch</text><text y="115" style="font-size: 2em; fill: lime;">Change Log</text><text y="140" style="font-size: 1.1em;" x="37">1.VC Fix.</text></g></svg>') var(--Theme-Variant)", "var(--Update-Text);
  text-align: center;
  animation: CLog 10s infinite linear;
  z-index: 9997;
  color: var(--Main-Colour);
}

.scrollerWrap-2lJEkd.firefoxFixScrollFlex-cnI2ix.scrollerWrap-NEo0f7.scrollerFade-1Ijw5y > div > div > div:nth-child(27) > div.keybindDescription-2RDbC2{
  font-size: 0;
}

.scrollerWrap-2lJEkd.firefoxFixScrollFlex-cnI2ix.scrollerWrap-NEo0f7.scrollerFade-1Ijw5y > div > div > div:nth-child(27) > div.keybindDescription-2RDbC2:after {
  content: "<3 Donator Easter Egg <3";
  color:var(--Main-Colour);
  font-size: 12px;
}

/* THANKYOU URI FOR HELPING ME UPDATE THIS <3 */

body:before {
  content: "Currently On" var(--Update-Text);
  background: var(--Background-Colour);
  border: 1px solid var(--Main-Colour);
  left: 50%;
  border-radius: 5px;
  padding: 5px 15px;
  transform: translate(-50%, -100%);
  animation: Notif 4s , CLog 10s infinite linear;
  text-align: center;
  position: absolute;
  top: 0;
  z-index: 9997;
  color: var(--Main-Colour);
}

#app-mount::after{
  color: var(--Main-Colour);
}

/* FUCK BETTERDOCS */
body:after {
  content: "Do Not Use Betterdocs/Discord Source";
  background: var(--Background-Colour);
  border: 1px solid var(--Main-Colour);
  left: 50%;
  border-radius: 5px;
  padding: 5px 15px;
  transform: translate(-50%, -100%);
  animation: Notif2 4s ease-in-out, CLog 10s infinite linear;
  text-align: center;
  position: absolute;
  top: 0;
  height: auto;
  width: auto;
  z-index: 9997;
  color: var(--Main-Colour);
}
/* FUCK BETTERDOCS */

[data-name="AccountDetailsPlus"]:after,
[data-name="AutoStartRichPresence"]:after,
[data-name="BetterFormattingRedux"]:after,
[data-name="BetterFriendCount"]:after,
[data-name="Channel History"]:after,
[data-name="Character Counter"]:after,
[data-name="CreationDate"]:after,
[data-name="Direct-Download"]:after,
[data-name="Discord Experiments"]:after,
[data-name="EditUsers"]:after,
[data-name="Extended Context Menu"]:after,
[data-name="GoogleTranslateOption"]:after,
[data-name="Guild Counter"]:after,
[data-name="JoinedAtDate"]:after,
[data-name="MemberCount"]:after,
[data-name="PinDMs"]:after,
[data-name="PluginRepo"]:after,
[data-name="Quoter"]:after,
[data-name="ReverseImageSearch"]:after,
[data-name="RoleMembers"]:after,
[data-name="SendLargeMessages"]:after,
[data-name="ServerFolders"]:after,
[data-name="ShowHiddenChannels"]:after,
[data-name="User Avatar And Server Icon Viewer"]:after {
  content: " (?) Plugin has Theme Support (?) ";
  color: var(--Main-Colour);
}

/* Boops */

.large-3ChYtB:not(.popout-2fzvxG)::after {
  white-space: pre;
  background-color: var(--Background-Colour) !important;
  box-shadow: 1px 1px 15px rgba(0, 216, 86, 0.9)!important;
  padding: 6px 10px;
  border-radius: 3px;
  font-size: 13px;
  z-index: 3000000;
  display: inline;
  position: relative;
  left: 100%;
  top: 50%;
  transform: translate(0, -50%);
  pointer-events: none;
  transition: 80ms ease;
  color: var(--Main-Colour);
  opacity: 0;
  animation: rainbow 3s infinite linear;
}

.large-3ChYtB:not(.popout-2fzvxG):hover::after {
  opacity: 1;
  transition: 180ms ease-in-out 100ms;
  animation: boop .5s 1 linear;
}

.large-3ChYtB:not(.popout-2fzvxG):not(:hover)::after {
  opacity: 0;
  transition: 180ms ease-in-out 150ms;
  animation: boop2 .5s 1 linear;
}

.large-3ChYtB:not(.popout-2fzvxG) {
  cursor: pointer;
}

.large-3ChYtB:not(.popout-2fzvxG)::before {
  color: rgba(0, 255, 0, .3);
  font-size: 13px;
  z-index: 1;
  position: absolute;
  left: 38.9%!important;
  top: 115%;
  padding-left: 2px;
  padding-right: 4px;
  border-radius: 2px;
  margin-left: -3px;
  transform: translate(0, 1px);
  cursor: pointer;
  transition: 100ms ease;
  pointer-events: initial;
  animation: Brainbow 3s infinite linear;
}

.large-3ChYtB:not(.popout-2fzvxG)::before, .large-3ChYtB:not(.popout-2fzvxG).large-3ChYtB:not(.popout-2fzvxG)::after, .large-3ChYtB:not(.popout-2fzvxG).large-3ChYtB:not(.popout-2fzvxG)::before, .large-3ChYtB:not(.popout-2fzvxG).large-3ChYtB:not(.popout-2fzvxG)::after {
  display: inline-block!important;
}

.avatar-17mtNa:hover {
  opacity: 1;
}

.large-3ChYtB:not(.popout-2fzvxG), .app, .appMount-3VJmYg, .appMount-3lHmkl {
  background-visibility: hidden!important;
}

.ragingDemon-bDcoXE,.symbolBackground-1w6i-M{
  margin-bottom: -3px;
  padding-top: 2%;
  padding-left: 23%;
  display: block;
  background: url(https://nfld99.com/Bkg/jyEFAiO.jpg) 50% 50%/cover !important;
  content: url('data:image/svg+xml; utf8, <svg xmlns="http://www.w3.org/2000/svg" viewBox="0 0 680 345" style="width:100%;height:100px;"><g style="fill: rgba(155,89,182,1); font-size: .8em; font-family:verdana"><text y="20" style="font-size: 2em; fill: rgba(155,89,182,1);">Thank you for using my theme!</text><text y="45" style="font-size: 1.1em;" x="37">Donators:</text><text y="65" style="font-size: 1.1em;" x="37">@Strato#4763.</text><text y="85" style="font-size: 1.1em;" x="37">@BLACKROOSTER#1395.</text><text y="105" style="font-size: 1.1em;" x="37">@Meowster Mewt#0817.</text><text y="125" style="font-size: 1.1em;" x="37">@mxngxxse#0666.</text><text y="145" style="font-size: 1.1em;" x="37">@TwinShadow#5717.</text><text y="165" style="font-size: 1.1em;" x="37">@Kiari#1204.</text><text y="185" style="font-size: 1.1em;" x="37">@Cpt_Corde#1945.</text><text y="205" style="font-size: 1.1em;" x="37">@FirePhox#5261.</text><text y="225" style="font-size: 1.1em;" x="37">@breadcat#6969.</text><text y="245" style="font-size: 1.1em;" x="37">@GhostieSpook#6565.</text><text y="265" style="font-size: 1.1em;" x="37">@Satela#1771.</text><text y="285" style="font-size: 1.1em;" x="37">@DragonStryder#1771.</text><text y="305" style="font-size: 1.1em;" x="37">@PoroUsedSnow#1771.</text><text y="325" style="font-size: 1.1em;" x="37">@Shiz#1771.</text></g></svg>');
}

/* Boops */

.wrapper-1Rf91z .scroller-2TZvBN>.guild:first-child {
  margin-top: 10px!important;
}

.theme-dark .chat, .native-toolbar .app-layer, .theme-dark .iconForeground-2c7s3m, .theme-dark .title-1aVOXw {
  background: transparent;
}

.native-toolbar .titlebar:after {
  content: ", " var(--Theme-Variant) ", " var(--Update-Text);
  position: absolute;
  left: 5px;
  bottom: 3px;
  color: Var(--Main-Colour) !important;
}

.appMount-3VJmYg, .appMount-3lHmkl {
  background: Var(--Title-Background)50% 50%/cover !important;
  background-color: rgba(0, 0, 0, var(--Background-Darkness)) !important;
}

.titleBar-AC4pGV {
  background: transparent !important;
}

.theme-dark .messagesWrapper-3lZDfY .messages :not(.red) span {
  color: var(--Main-Colour);
}

.theme-dark .messagesWrapper-3lZDfY .messages span, .theme-dark .messagesWrapper-3lZDfY .messages :not(.red) div {
  background: var(--Background-Colour);
}

.layers, .layer {
  background: transparent !important;
}

.app {
  background: var(--Chat-Background) 50% 50%/cover !important;
  animation: Load4 3s 1 linear, var(--StartUp) 3s 1 linear;
  font-family: var(--Chat-Font-Used)!important;
}

.app:not(.popout section) {
  text-shadow: 0 0 6px var(--Text-Shadow-Colour), 0 0 6px var(--Text-Shadow-Colour), 0 0 5px var(--Text-Shadow-Colour), 0 0 4px var(--Text-Shadow-Colour);
}

.popout section, .popout header {
  text-shadow: 0 0 0;
  background: var(--Background-Colour);
  color: var(--Main-Colour);
}

#rtc-connection-popout hr {
  border: 1px solid var(--background-color);
}

/* .theme-dark .ui-standard-sidebar-view .content-region {
  background: transparent !important;
} */

.theme-dark .message-group .mentioned .message-text {
  background: rgba(97, 13, 170, 0.11)!important;
}

/* .theme-dark .ui-standard-sidebar-view .content-region, .ui-standard-sidebar-view .content-region,  .theme-dark .ui-standard-sidebar-view .sidebar-region,  .ui-standard-sidebar-view .sidebar-region { 
  background: rgba(0,0,0,0.5) !important
} */

.theme-dark .ui-standard-sidebar-view .content-region, .ui-standard-sidebar-view .content-region, .theme-dark .ui-standard-sidebar-view .sidebar-region, .ui-standard-sidebar-view .sidebar-region {
  background: rgba(0, 0, 0, var(--Background-Darkness)) !important;
}

.theme-dark .ui-standard-sidebar-view, .theme-dark .standardSidebarView-3F1I7i {
  background: var(--Settings-Background) 50% 50%/cover !important;
}

.callout-backdrop, .modal-1UGdnR, .header-2BwW8b, .theme-dark .body-3iLsc4, .theme-dark .footer-1fjuF6 {
  background: rgba(0, 0, 0, var(--Background-Darkness))!important;
}

.backdrop-1ocfXc, .backdrop-1wrmKB {
  background: var(--Callout-Background) 50% 50%/cover !important;
}

.auth-background {
  background: url(https://nfld99.com/Bkg/DOFpZY5.jpg) 50% 50%/cover !important;
}

form.deprecated.auth-form {
  background: rgba(0, 0, 0, .6) !important;
  padding-top: 600px;
  padding-left: 500px;
  padding-right: 600px;
  padding-bottom: 600px;
}

form.deprecated.auth-form .btn-primary {
  padding: 10px 20px;
  padding-top: 0;
  padding-bottom: 0;
}

.auth-inner .auth-brand {
  display: none;
}

.auth-inner .auth-logo, .auth-inner .auth-name, .auth-inner .auth-name:after {
  background: rgba(0, 0, 0, 0) !important;
}

.connecting {
  background: transparent !important;
}

form.deprecated.auth-form h1, form.deprecated.auth-form .control-group input[type=email], form.deprecated.auth-form .control-group input[type=password], form.deprecated.auth-form .control-group input[type=text], form.deprecated.auth-form .btn-forgot-password {
  color: var(--Main-Colour);
  border-bottom-color: var(--Main-Colour);
}

form.deprecated.auth-form footer {
  color: var(--Secondary-Main-Colour);
}

.theme-dark #friends .friends-table .friends-table-header .friends-column, .theme-dark #friends .friends-table .friends-row .friends-column-name, .theme-dark #friends .friends-table .friends-row .friends-column-status {
  color: var(--Main-Colour);
}

.theme-dark #friends .friends-table .friends-table-header .friends-column-separator {
  background-color: var(--Main-Colour);
}

.form.deprecated .btn-primary {
  color: var(--Background-Colour);
}

.theme-dark .themed-popout .header {
  background-color: var(--Background-Colour)!important;
}

.theme-dark .private-channel-recipients-invite .friend.selected, .theme-dark .private-channel-recipients-invite .friend:hover {
  background: var(--Background-Colour);
}

.theme-dark .private-channel-recipients-invite .friend.selected, .theme-dark .private-channel-recipients-invite .friend {
  background: var(--Background-Colour);
}

.search-bar-tag {
  background: var(--Background-Colour);
  border: 1px solid var(--Main-Colour);
}

.headerNormal-1cioxU {
  background: var(--Background-Colour);
}

#qs_button {
  left: 400px;
}

#qs_button {
  font-size: 0;
}

#qs_button:after {
  content: " Save File (Shift To Save As).";
  font-size: 15px;
}

.downloadLink-1ywL9o {
  color: var(--Main-Colour)!important;
}

.anchor-3Z-8Bb:after {
  content: " ";
  font-size: 15px;
}

#friends, #friends .btn, .friends-header, .friends-table, .search-bar, .wrapper-1Rf91z, .channels-wrap, .guild-channels, .account, .links, .messagesWrapper-3lZDfY, .title-wrap, .content, .chat-empty, .message-group-blocked, .private-channels, .guild-header header, .ider-red span {
  background: transparent !important;
}

.channel:not(.selected) {
  transition: background .3s ease-out !important;
}

.channel:not(.selected):hover {
  background: transparent !important;
  transition: background .2s ease-in !important;
}

.friends-row:hover, .search-result:hover, .btn-friends.selected, .search-result.selected, .channel.selected.private, .channel.channel-text.selected {
  background: transparent !important;
}

.theme-dark #friends .friends-table .friends-row:hover {
  border-color: var(--Main-Colour);
  border-bottom: 2px solid var(--Main-Colour);
}

.guild-channels .channel-text.selected {
  background: var(--Background-Colour) !important;
}

.guild-channels .channel-text.selected:before, .guild-channels .channel-text.selected:hover:before, .guild-channels .channel-text:hover.channel-muted:before, .guild-channels .channel-text:hover:not(.unread):before, .private-channels .channel.selected:before, .private-channels .channel:hover:before {
  border-left: 3px solid var(--Main-Colour);
}

.guild-channels .channel-text:hover {
  background: var(--Background-Colour) !important;
}

.guild-channels ul .channel-text.unread:not(.selected):not(.channel-muted):before {
  left: -11px;
}

.guild-header ul {
  opacity: 0;
  transition: transform .5s cubic-bezier(0.18, 0.89, 0.32, 1.28);
}

.guild-header-open ul {
  opacity: 1;
}

.invite-btn {
  background-color: var(--Main-Colour) !important;
}

.private-channels .channel:hover:before {
  opacity: .25 !important;
}

.user-settings-modal button.preview-sound:before {
  -webkit-filter: hue-rotate(235deg) saturate(400%);
  filter: hue-rotate(235deg) saturate(400%);
}

.voice-connection-channel {
  color: var(--Background-Colour);
  font-size: 12px;
}

.inline {
  background-color: #23232323 !important;
  border-radius: 5px !important;
  font-size: 12px;
  color: var(--Main-Colour) !important;
  line-height: 22px;
}

.badge-2_fwUZ {
  background-color: var(--Main-Colour);
  border: 1px solid var(--Background-Colour);
  color: var(--Background-Colour);
  right: 10px;
}

.channel.channel-text.unread a {
  background: transparent !important;
}

.markup-2BOw-j {
  color: #ffffff;
  font-size: var(--Chat-Font-Size)!important;
}

.member.member-status.member-status-offline:hover {
  background-color: var(--Secondary-Background-Colour) !important;
}

.member.member-status.member-status-online:hover {
  background-color: var(--Secondary-Background-Colour) !important;
}

.notice {
  background-color: #a1a1a1;
  color: var(--Background-Colour);
}

.timestamp {
  color: var(--Secondary-Main-Colour) !important;
  font-size: 13px;
}

.ider span {
  background-color: #615900;
  margin-top: 5px;
  margin-bottom: 5px;
  color: #ffffff;
}

/*
::-webkit-input-placeholder {
  color: rgba(255, 255, 255, 0.6);
}*/

.chat>.title-wrap {
  box-shadow: none !important;
}

.member-activity {
  color: linear-gradient(to right, var(--Background-Colour), var(--Main-Colour)) !important;
}

.links li a:hover {
  color: var(--Main-Colour) !important;
}

.topic.topic-expandable {
  color: rgba(255, 255, 255, 0.8) !important;
  font-size: 12px !important;
}

.topic.topic-expandable a {
  color: var(--Main-Colour) !important;
}

.topic.topic-expandable:hover {
  color: rgba(255, 255, 255, 0.8) !important;
  font-size: 13px !important;
}

.member.member-status.member-status-online {
  background: transparent;
}

.messages {
  background: transparent;
  margin-top: 5px !important;
  margin-right: 2px !important;
}

.chat .title-wrap {
  padding-bottom: 1px;
  border-bottom: 1px solid var(--Main-Colour)!important;
  margin-top: 1px;
}

.guild-header header span {
  margin-left: 30%;
}

.guild-channels header {
  opacity: 0.9;
}

.scroller.channel-members {
  padding-top: 3 px;
}

.scroller-2TZvBN {
  transition: all 900ms ease !important;
}

.btn {
  width: auto !important;
}

.btn-group {
  opacity: 0.6 !important;
}

.account .username {
  width: 65px !important;
  font-size: 10px !important;
  white-space: nowrap;
  overflow: hidden;
  text-overflow: ellipsis;
}

span.ping {
  background-color: transparent !important;
  color: var(--Main-Colour) !important;
  transition: opacity 3s ease-in-out;
}

.voice-connection-quality-fine {
  font-size: 80% !important;
  padding-right: 30px !important;
  transition: opacity 3s ease-in-out;
}

.search-bar {
  box-shadow: none !important;
}

.guild-header.guild-header-open ul {
  background-color: #121212 !important;
  border-radius: 5px;
  margin-left: 1.2vh;
  width: 15vw;
}

.guild-header-open ul li a {
  color: var(--Main-Colour);
  opacity: 1 !important;
}

.voice-connection-quality-fine {
  transition: all 900ms ease !important;
}

.channel-members, .channel-members-wrap {
  transition: all 400ms ease;
}

.embed-video-actions {
  width: 90%;
  height: 90%;
}

.embed {
  border-radius: 15px !important;
}

.highlight {
  color: var(--Main-Colour);
}

.highlight:hover {
  background-color: var(--Background-Colour) !important;
  border-radius: 3px !important;
  color: var(--Main-Colour) !important;
}

.friends-icon {
  background-color: var(--Main-Colour);
}

.friendsOnline-2JkivW {
  color: #ffffff;
}

.guildSeparator-3s64Iy {
  border-top: 2px solid var(--Main-Colour);
  border-bottom: 2px solid var(--Main-Colour);
}

.guildSeparator-3s64Iy:after {
  background-color: transparent !important;
}

.speaking .avatar-small {
  border: 2px dotted var(--Main-Colour) !important;
}

.speaking .avatar-small:hover {
  border: 2px dotted var(--Main-Colour) !important;
}

.channel-members .member.popout-open {
  background: linear-gradient(to right, var(--Secondary-Background-Colour), var(--Main-Colour)) !important;
  border-left: 4px solid var(--Main-Colour);
}

.status {
  border-color: transparent !important;
}

/* Unread Channel Message */

.guild-channels .channel-text.unread:not(.selected):not(.channel-muted):before {
  background: var(--Main-Colour) !important;
}

/* Guild Unread Message */

.wrapper-1Rf91z .scroller-2TZvBN .container-1ETFDs.unread-2OHH1w:before {
  animation: opacity var(--Unread-Message-Speed) infinite linear;
  background-color: var(--Unread-Message-1);
}

/* Guild Unread Message */

.wrapper-1Rf91z .scroller-2TZvBN .container-1ETFDs.selected-nT-gM3:before {
  background: var(--Main-Colour) !important;
}

/* Private Chat */

.private-channels .scroller {
  background: none !important;
  border-radius: 5px !important;
  margin-left: 2vh;
}

.private-channels .channel.selected:before {
  background-color: linear-gradient(to right, var(--Main-Colour), var(--Background-Colour)) !important;
  border-left: 2px solid var(--Main-Colour);
}

.priavte-channels .channel:hover::before {
  border-left: 2px solid var(--Main-Colour) !important;
  background-color: linear-gradient(to right, var(--Main-Colour), var(--Background-Colour)) !important;
}

.friends-header {
  box-shadow: none;
  border: none !important;
}

.search-bar-inner input {
  font-size: 62% !important;
}

/* Friends */

#friends .friends-table .friends-table-body {
  background-color: var(--Secondary-Background-Colour) !important;
  border-radius: 5px !important;
  border: 1px solid var(--Main-Colour);
  margin-left: 1.6vw;
  margin-bottom: 2.5vh;
  margin-right: 2.5vh;
  opacity: 1;
}

#friends .friends-table .friends-table-header {
  background-color: var(--Secondary-Background-Colour) !important;
  border-radius: 5px !important;
  border: 1px solid var(--Main-Colour);
  border-bottom: 1px solid var(--Main-Colour)!important;
  margin-left: 1.6vw;
  height: 3vh;
  margin-bottom: 1.2vh;
  margin-right: 2.5vh;
}

#friends .friends-header {
  margin-left: 1.6vw;
}

.tab-bar-item:hover {
  background-color: transparent;
}

.new-messages-bar button {
  background-color: transparent !important;
  color: var(--Main-Colour) !important;
  text-shadow: 0 0 2px var(--Text-Shadow-Colour), 0 0 6px var(--Text-Shadow-Colour), 0 0 5px var(--Text-Shadow-Colour), 0 0 4px var(--Text-Shadow-Colour);
}

/* Tags */

span.botTagRegular-2HEhHi {
  background-color: rgba(0, 216, 86, 0.8) !important;
  animation: rainbow 20s infinite linear;
}

.kawaii-tag {
  background: #7289da;
  font-size: 10px;
  font-weight: 600;
  color: #fff!important;
  margin-left: 6px;
  padding: 1px 2px;
  border-radius: 3px;
  text-transform: uppercase;
  vertical-align: bottom;
  line-height: 16px;
  flex-shrink: 0;
  animation: rainbow 20s infinite linear;
}

.compact .kawaii-tag {
  margin: 0 3px 0 0;
}

.kawaii-tag-bright {
  color: #23272A!important;
}

.kawaii-tag-invert {
  background: #fff;
  color: #7289da!important;
}

/* Instant invite section */

.instant-invite-popout section {
  background-color: var(--Background-Colour) !important;
  border-bottom-right-radius: 10px !important;
  border-bottom-left-radius: 10px !important;
}

.instant-invite-popout header {
  background-color: var(--Main-Colour) !important;
}

.countdown {
  color: var(--Main-Colour) !important;
}

.checkbox span {
  color: #a8a8a8 !important;
}

/* Guilds 'Add' Button */

.container-1ETFDs.guildsAdd-21_Id {
  border-color: var(--Main-Colour) !important;
  border-style: groove !important;
  background: var(--Background-Colour);
}

.container-1ETFDs.guildsAdd-21_Id:hover {
  border-color: var(--Main-Colour) !important;
  background: var(--Background-Colour);
}

.wrapper-1Rf91z .guildsAdd-21_Id-inner {
  position: absolute;
  top: calc(50% - 22px);
  left: 22.4%;
  text-align: center;
}

/* Speech bubble CSS */

.tooltip, .tooltip.tooltip-black {
  background: linear-gradient(to top, var(--Secondary-Main-Colour), var(--Background-Colour), var(--Background-Colour), var(--Background-Colour), var(--Secondary-Main-Colour)) !important;
}

.tooltip.tooltip-right:after {
  border-right-color: var(--Background-Colour) !important;
}

.tooltip.tooltip-left:after {
  border-left-color: var(--Background-Colour) !important;
}

.tooltip.tooltip-top:after {
  border-top-color: var(--Background-Colour) !important;
}

.tooltip.tooltip-bottom:after {
  border-bottom-color: var(--Background-Colour) !important;
}

/** Delete comment window **/

.form-inner {
  background-color: var(--Background-Colour) !important;
}

.form-header header {
  color: var(--Main-Colour) !important;
}

.form-inner p {
  color: #ffffff !important;
}

.btn.btn-default.close {
  background-color: var(--Background-Colour) !important;
  color: var(--Main-Colour);
}

.form-header {
  background-color: var(--Background-Colour) !important;
}

.form-actions {
  background-color: var(--Background-Colour) !important;
}

ul li a {
  color: var(--Main-Colour);
}

.header.control-group {
  background-color: var(--Background-Colour) !important;
  border-top-right-radius: 10px;
  border-top-left-radius: 10px;
}

/** User settings */

.avatar-uploader-inner {
  background-color: var(--Background-Colour) !important;
  border-radius: 4px !important;
  border-color: var(--Main-Colour) !important;
}

#settings-username {
  border-radius: 4px;
  padding-left: 10px;
  border-color: var(--Main-Colour) !important;
}

#settings-email {
  border-radius: 4px;
  padding-left: 10px;
  border-color: var(--Main-Colour) !important;
}

#settings-current-password {
  border-radius: 4px;
  padding-left: 10px;
  border-color: var(--Main-Colour) !important;
}

.settings-actions {
  background-color: #121212 !important;
}

a.remove-button {
  color: var(--Main-Colour) !important;
}

.control-group label a {
  color: var(--Main-Colour) !important;
}

.tab-bar-item.selected {
  padding-left: 15px !important;
}

.checkbox-inner span {
  background-color: var(--Main-Colour) !important;
  border-color: var(--Background-Colour) !important;
}

.radio-inner {
  background-color: rgba(255, 255, 255, 0.3) !important;
}

.radio {
  color: #ffffff !important;
}

.tab-bar-item {
  margin-right: 5px !important;
  margin-left: 5px !important;
  padding-left: 5px !important;
  padding-right: 5px !important;
}

div p a {
  color: var(--Main-Colour) !important;
}

.radio-theme.dark label {
  border-color: var(--Main-Colour) !important;
}

.radio-theme.light label {
  border-color: #ffffff;
}

.action-icon:before {
  -webkit-filter: hue-rotate(305deg) saturate(400%) !important;
  filter: hue-rotate(305deg) saturate(400%) !important;
}

.themeDefault-24hCdX.valueChecked-m-4IJZ {
  background: var(--Main-Colour) !important;
}

.radio .radio-inner span:after {
  background: var(--Main-Colour) !important;
}

.tab-bar.TOP .tab-bar-item.selected {
  border-bottom: 2px solid var(--Main-Colour) !important;
}

#help-query {
  border-color: var(--Main-Colour);
  border-width: 3px;
}

/* User profile popup message box */

.avatar-16XVId.avatar-1jmnc-.popout-2fzvxG {
  border: none!important;
  background-color: rgba(255, 255, 255, 0) !important;
}

.mask-3OgeRz {
  border-radius: 0;
  -webkit-mask: none;
  mask: none;
}

.reset-voice-settings {
  color: var(--Main-Colour) !important;
}

/* Add new server popup window */

.form-inner header {
  color: var(--Main-Colour) !important;
}

.action-header {
  color: var(--Main-Colour) !important;
}

.action-icon {
  background-color: #ffffff !important;
}

.btn.btn-primary {
  background-color: var(--Main-Colour) !important;
}

/* Light Theme Support*/

span.channel-name, .private-channels .channel .channel-name, .chat>.title-wrap.title-wrap-dark .topic, .theme-dark .channelName-3stJzi, .theme-dark .groupDM-3qU0Ks .channelName-3stJzi, .theme-dark .groupDMManaged-1GyXtq .channelName-3stJzi, .theme-dark .input-autosize-input, .theme-dark .input-autosize-input:focus, .channel-2QD9_O.selected-1HYmZZ .name-2WpE7M, .channel-2QD9_O:hover .name-2WpE7M, .channel-2QD9_O.selected-1HYmZZ .name-2WpE7M, .channel-2QD9_O:hover .name-2WpE7M, .name-2WpE7M, .activity-525YDR, .privateChannels-1nO12o header, .theme-dark .username-XRo90I, .theme-dark .gameName-wzJptK, .theme-dark .activityActivityFeed-3xysim .content-3JfFJh, .theme-dark .activityActivityFeed-3xysim .details-38sfDr {
  color: var(--Main-Colour) !important;
}

a.channel-name.channel-private, .header-2o-2hj, .private-channels .channel .channel-activity, .private-channels header, .wrapper-2NJDcI {
  color: var(--Main-Colour) !important;
  box-shadow: none;
}

.nameDefault-Lnjrwm, .theme-dark .channel-members .member {
  color: var(--Secondary-Main-Colour);
}

.form-inner.loading {
  background-color: var(--Background-Colour) !important;
}

div.footer-2J5zqP, .theme-dark .footer-2yfCgX {
  background-color: var(--Background-Colour) !important;
}

#user-profile-modal .scroller {
  background: #fff;
  padding-top: 0;
  border-top-right-radius: 0;
  border-bottom-right-radius: 0;
  border-right: none;
  margin-top: 0;
  margin-bottom: 0;
}

.empty-message h1 {
  color: rgba(255, 255, 255, 0.8) !important;
}

img.image {
  width: 90%;
  height: 90%;
  border-radius: 10px;
}

#app-mount>div>span:nth-child(6)>div.modal>div>div>div>img {
  max-height: 700px !important;
  width: auto !important;
  max-width: 1000px;
  height: auto !important;
  margin-right: auto !important;
  margin-left: auto !important;
}

#app-mount>div>span:nth-child(6)>div.modal>div>div>a {
  opacity: 1 !important;
  text-align: center;
  color: #ffffff;
}

#app-mount>div>span:nth-child(6)>div.modal>div>div>a:hover {
  text-align: center;
  color: var(--Main-Colour);
}

div.form-inner {
  background-color: #232323 !important;
}

.connection-integrations.no-integrations div {
  color: #6b6b6b !important;
}

.connection-integrations.no-integrations {
  background-color: #ffffff !important;
}

.settings-panel-header.user-settings-modal-connections-header label {
  color: var(--Main-Colour) !important;
}

header.header {
  background: transparent !important;
}

div.sub-header {
  background-color: var(--Background-Colour) !important;
}

#user-profile-modal>div.tab-bar.TOP {
  background-color: var(--Background-Colour) !important;
}

div#user-profile-modal footer {
  background-color: var(--Background-Colour) !important;
}

.add-friend {
  background-color: var(--Main-Colour) !important;
  border: 1px solid white;
}

div.scroller.scroller-2TZvBN div.guild:hover {
  border-radius: 4px !important;
}

div.btn {
  background-color: var(--Main-Colour) !important;
  border: 1px solid white;
}

#user-profile-modal footer {
  background-color: rgba(255, 255, 255, 0.9) !important;
}

div.flex-horizontal.flex-spacer.content-inner label {
  color: #ffffff !important;
}

label.subtitle {
  color: var(--Main-Colour) !important;
}

label.title {
  color: var(--Main-Colour) !important;
}

div.control-group label {
  color: var(--Main-Colour) !important;
}

div.checkbox span {
  color: #a6a6a6 !important;
}

div.help-text {
  color: #ffffff !important;
}

.channel-pins-wrap {
  background: var(--Background-Colour) !important;
}

.channel-pins-wrap .header {
  background: var(--Main-Colour) !important;
}

.channel-pins .message-group {
  background: var(--Background-Colour) !important;
  border: 1px solid lime !important;
}

.action-buttons .jump-button {
  background: var(--Main-Colour) !important;
  border: 1px solid var(--Background-Colour) !important;
}

.guild-channels .channel a {
  opacity: 0.7;
}

.channel-members .member:hover {
  background: linear-gradient(to right, var(--Secondary-Background-Colour), var(--Secondary-Main-Colour)) !important;
  border-left: 2px solid var(--Main-Colour);
}

li div span {
  color: var(--Main-Colour) !important;
}

.channel-name:before {
  color: var(--Main-Colour) !important;
}

.action.create {
  background-color: #ffffff !important;
}

.action.join {
  background-color: #ffffff !important;
}

div.icon-friends {
  background-color: var(--Main-Colour) !important;
}

.channel-textarea-autocomplete {
  background-color: var(--Main-Colour) !important;
}

div.add-friend-popout header {
  background-color: var(--Main-Colour) !important;
}

div.notice {
  background-color: #474747 !important;
  color: #009499 !important;
}

div.tab-bar-item {
  background: transparent !important;
}

div.headerActivityText-3qBQRo {
  color: var(--Main-Colour) !important;
}

a.embed-title {
  color: var(--Main-Colour) !important;
}

.tab-bar.SIDE .tab-bar-item.selected:before {
  opacity: 0;
}

.tab-bar.SIDE {
  margin-right: -17px;
}

button.btn.btn-default {
  background: transparent !important;
  color: #ffffff !important;
}

.connect-container .btn {
  height: 50px !important;
  width: 50px !important;
}

#bd-pane .scroller-wrap div[style*="background:#2E3136; color:#ADADAD; height:30px; position:absolute; bottom:0; left:0; right:0;"] {
  background: #ffffff !important;
}

#bd-pane>div>div>div.bd-settings>div:nth-child(6)>span:nth-child(1) {
  color: #696969;
}

#bd-changelog {
  color: #696969;
}

div.new-messages-bar button {
  margin-top: 10px !important;
}

.tab-bar.SIDE {
  background-color: #232323 !important;
}

.tab-bar.SIDE .tab-bar-item {
  background: transparent !important;
  color: rgba(255, 255, 255, 0.5) !important;
}

.tab-bar.SIDE .tab-bar-item:hover {
  color: rgba(255, 255, 255, 0.9) !important;
}

.tab-bar.SIDE .tab-bar-item.hover:before, .tab-bar.SIDE .tab-bar-item:before {
  display: none !important;
}

/* Public Server CSS */

#pubs-container {
  background: var(--Background-Colour) !important;
  border-radius: 10px !important;
}

#pubs-header {
  background-color: #232323 !important;
  border-top-right-radius: 5px !important;
  border-top-left-radius: 5px !important;
}

#pubs-container>div.server-row.server-pinned {
  background-color: var(--Background-Colour) !important;
  border-bottom: 3px solid #232323 !important;
}

#pubs-list>div {
  background-color: var(--Background-Colour) !important;
  transition: all .3s ease-in-out;
}

.server-row button {
  background-color: var(--Main-Colour) !important;
  border-radius: 5px;
  transition: all .3s ease-in-out;
}

.server-row button:hover {
  background-color: var(--Main-Colour) !important;
  border-radius: 5px;
  transition: all .3s ease-in-out;
}

.server-info span {
  color: #fff !important;
}

.bd-dropdown-select {
  background-color: var(--Main-Colour) !important;
  transition: all .3s ease-in-out;
  color: #fff !important;
  border-radius: 5px;
}

input#pubs-sterm {
  background-color: var(--Main-Colour) !important;
  transition: all .3s ease-in-out;
  color: #fff !important;
  padding-left: 7px;
  border-radius: 5px;
  width: 120px !important;
  margin-right: 10px !important;
  margin-left: -10px !important;
}

button#pubs-searchbtn {
  background-color: var(--Main-Colour) !important;
  transition: all .3s ease-in-out;
  color: #fff !important;
  border-radius: 5px;
}

div.bd-dropdown-list {
  background: transparent !important;
}

.pubs-cat-select-li {
  background: transparent !important;
  background-color: var(--Main-Colour) !important;
  transition: all .3s ease-in-out;
  color: #fff !important;
}

.server-row .server-icon {
  border-radius: 5px !important;
  border: 2px solid var(--Main-Colour);
}

#pubs-select-dropdown>div>ul {
  border-bottom-left-radius: 5px !important;
  margin-top: -2px !important;
}

div.bd-dropdown {
  background: transparent !important;
  transition: all .3s ease-in-out;
}

.server-official {
  color: var(--Main-Colour) !important;
  animation: color_change 1s infinite alternate;
}

#pubs-footer {
  background: var(--Background-Colour) !important;
  border-bottom-right-radius: 10px !important;
  border-bottom-left-radius: 10px !important;
  border-top: 1px solid rgba(255, 255, 255, 0.3);
}

/* Styling thanks to Nyxxay#8107 */

#rmenu {
  background: var(--Main-Colour) !important;
  border: 1px solid var(--Main-Colour);
}

.emoji-picker .search-bar input {
  animation: searchpulse 2s infinite;
}

.bda-dark #bda-qem {
  background: transparent !important;
  border: 1px solid var(--Main-Colour) !important;
  border-bottom: transparent!important;
}

.bda-dark #bda-qem button {
  background: var(--Background-Colour) !important;
  border: 1px solid var(--Background-Colour) !important;
}

.bda-dark #bda-qem button.active {
  background: var(--Background-Colour) !important;
  border: 1px solid var(--Main-Colour) !important;
}

.bda-dark #bda-qem-favourite-container, .bda-dark #bda-qem-twitch-container, .bda-dark .emoji-picker, .bda-dark .emoji-picker .category, .bda-dark .emoji-picker .header .search-bar {
  background: var(--Background-Colour) !important;
}

.emoji-picker .sticky-header {
  background: var(--Background-Colour) !important;
}

.guild-settings-modal-members {
  border: 1px solid var(--Background-Colour) !important;
  background-image: url(https://nfld99.com/Bkg/nekmRkx.jpg) !important;
  background-size: cover;
}

.channel-textarea-autocomplete-inner {
  background: var(--Background-Colour);
}

.channel-textarea-autocomplete-inner header {
  background: var(--Background-Colour);
}

.theme-dark .channel-members h2, .theme-dark .membersGroup-v9BXpm {
  border-bottom: 6px !important;
  background: linear-gradient(to right, transparent, var(--Background-Colour), var(--Secondary-Main-Colour)) !important;
}

.channel-members h2, .membersGroup-v9BXpm {
  border-radius: 3px !important;
  margin-left: 2px !important;
  padding-top: 0px !important;
  white-space: wrap !important;
  font-size: 12px !important;
  margin-top: 13px !important;
  text-transform: uppercase !important;
  height: 20px !important;
  color: var(--Main-Colour);
}

.theme-dark .membersGroup-v9BXpm {
  color: var(--Main-Colour);
}

.title-wrap {
  box-shadow: none !important;
  background-color: #121212;
}

.markup-2BOw-j a {
  color: var(--Main-Colour) !important;
}

.message-group {
  background-color: rgba(35, 35, 35, 0) !important;
  border-radius: 5px !important;
  padding-left: 20px !important;
}

.guild-header header {
  position: absolute;
  right: 20px;
  border: transparent;
  color: #ffffff;
  height: 58px;
  background-color: #232323;
  width: 120%;
}

div.guild-header header {
  background-color: #121212;
}

.theme-dark .inner-zqa7da textarea {
  padding-left: 10px!important;
  margin-bottom: 0;
  color: var(--Chat-Input-Colour) !important;
  background-color: transparent !important;
  margin-top: 0px!important;
  padding-top: 15px;
  vertical-align: middle;
  text-shadow: 0 0 6px var(--Text-Shadow-Colour), 0 0 6px var(--Text-Shadow-Colour), 0 0 5px var(--Text-Shadow-Colour), 0 0 4px var(--Text-Shadow-Colour);
}

.theme-dark .inner-zqa7da {
  background: var(--Chat-Input-Background) 50% 50%/cover !important;
  border-radius: 4px;
  border: 1px solid var(--Main-Colour) !important;
  margin-top: 1.6px;
  margin-left: 2px;
  margin-bottom: -13px;
  vertical-align: middle;
}

.account {
  border: none !important;
  margin-top: 1.6px !important;
  margin-left: 2px !important;
  margin-bottom: 5px !important;
  padding-left: 10px !important;
  width: auto !important;
  border-top-right-radius: 4px !important;
  border-top-left-radius: 4px !important;
}

.channel-members {
  background-color: rgba(35, 35, 35, 0) !important;
  margin-right: 2px !important;
  margin-top: 3px !important;
  margin-bottom: 5px !important;
}

.username {
  transition: all 900ms ease !important;
}

.account .avatar-small {
  border-radius: 3px;
  margin-left: 4px !important;
  border: 1px solid var(--Main-Colour);
}

div.channel-textarea-inner textarea {
  padding-left: 10px;
}

div.flex-spacer.flex-vertical form {
  background-color: #121212;
}

.wrapper-1Rf91z {
  background: transparent !important;
}

.scroller-2TZvBN {
  transition: all 900ms ease !important;
  border-right-width: 5px !important;
  border-color: #121212 !important;
  border-style: solid !important;
  width: 70px !important;
  padding-top: 17px !important;
}

.wrapper-1Rf91z .guilds-error:hover {
  background: linear-gradient(to left, var(--Secondary-Main-Colour), transparent, transparent, var(--Secondary-Main-Colour));
  animation: Spin 2s ease-in-out infinite alternate;
}

.wrapper-1Rf91z .guilds-error {
  height: 40px;
  width: 40px;
  background: linear-gradient(to left, var(--Secondary-Main-Colour), transparent, transparent, var(--Secondary-Main-Colour));
}

#app-mount>div>div.app.flex-vertical.theme-dark>div>section>div.wrapper-1Rf91z>div {
  background-color: rgba(35, 35, 35, 0.7) !important;
}

.voice-connection-quality-fine {
  color: var(--Main-Colour) !important;
}

span.text, span.text.strong {
  font-size: 10px !important;
  color: var(--Main-Colour) !important;
}

spinner-pulsing-ellipsis .spinner-item {
  background-color: var(--Main-Colour) !important;
}

/*User Status*/

/* ONLINE */

.channel.private .status-online {
  opacity: 1 !important;
}

.account .status-online {
  opacity: 1 !important;
}

/* IDLE */

.channel.private .status-idle {
  opacity: 1 !important;
}

.account .status-idle {
  opacity: 1 !important;
}

/* Do Not Desterb*/

.channel.private .status-dnd {
  opacity: 1 !important;
}

.account .status-dnd {
  opacity: 1 !important;
}

/* Offline*/

.channel.private .status-offline, .channel.private .status-invisible {
  opacity: 1 !important;
}

.account .status-offline, .account .status-invisible {
  opacity: 1 !important;
}

.theme-dark .memberOnline-1CIh-0 {
  color: var(--Main-Colour) !important;
}

.theme-dark .memberOffline-2lN7gt {
  color: var(--Secondary-Main-Colour) !important;
}

.theme-dark .activity-1IYsbk {
  color: var(--Secondary-Main-Colour) !important;
}

.image-33JSyf, .status-oxiHuE {
  border-radius: 0%;
}

.theme-dark .member-3W1lQa:hover .content-OzHfo4, .theme-dark .member-3W1lQa.popout-open .content-OzHfo4, .theme-dark .member-3W1lQa.popout-open:hover .content-OzHfo4 {
  background: linear-gradient(to right, transparent, var(--Background-Colour), var(--Secondary-Main-Colour));
  color: var(--Main-Colour) !important;
}

/* Keyframs */

/* @keyframes DropDown {
  from {
      transform: translate(0, 100vh);
      opacity: 0;
  }
  to {
      transform: translate(0, 0);
      opacity: 1;
  }
} */

@keyframes Notif {
  from, to {
    transform: translate(-50%, -100%);
    opacity: 0;
  }
  20%, 80% {
    transform: translate(-50%, 10%);
    opacity: 1;
  }
}

@keyframes Notif2 {
  from, to {
    transform: translate(-50%, -50%);
    opacity: 0;
  }
  20%, 80% {
    transform: translate(-50%, 112%);
    opacity: 1;
  }
}

@keyframes CLog {
  from {
    -webkit-filter: hue-rotate(0deg);
  }
  to {
    -webkit-filter: hue-rotate(360deg);
  }
}

@keyframes Everyone {
  0% {
    box-shadow: 0px 0px 15px 0px var(--Secondary-Main-Colour);
  }
  50% {
    box-shadow: 0px 0px 15px 5px var(--Secondary-Main-Colour);
  }
  100% {
    box-shadow: 0px 0px 15px 0px var(--Secondary-Main-Colour);
  }
}

@keyframes Everyone2 {
  0% {
    transform: translate(0, -200%) scale(0);
  }
  100% {
    transform: translate(0, 0) scale(1);
  }
}

@keyframes auth {
  from {
    -webkit-filter: hue-rotate(0deg);
  }
  to {
    -webkit-filter: hue-rotate(360deg);
  }
}

@keyframes Popoutinvite {
  from {
    width: 0px;
  }
  to {
    width: 920px;
  }
}

/* Keyframs */

/*Thanks to Nomuit#7411 For Helping me find this */

.connectedAccountVerifiedIcon-1Ms4J8 g {
  display: none;
}

/*Thanks to Nomuit#7411 For Helping me find this */

.button-2b6hmh>svg {
  fill: transparent;
}

.flex-1xMQg5.flex-1O1GKY.horizontal-1ae9ci.horizontal-2EEEnY.flex-1O1GKY.directionRow-3v3tfG.justifyStart-2NDFzi.alignStretch-DpGPf3.noWrap-3jynv6 {
  background: transparent;
  border-radius: 15px;
  opacity: 7;
}

.flex-1xMQg5.flex-1O1GKY.horizontal-1ae9ci.horizontal-2EEEnY.flex-1O1GKY.directionRow-3v3tfG.justifyStart-2NDFzi.alignCenter-1dQNNs.noWrap-3jynv6.marginReset-3RfdVe>div:nth-child(1)>div>svg>path {
  Fill: var(--Background-Colour)!important;
}

#app-mount>div>div.app.flex-vertical.theme-dark>div>section>div.chat.flex-vertical.flex-spacer>div.content.flex-spacer.flex-horizontal>div.flex-spacer.flex-vertical>div>div>div>div:nth-child(37)>div.comment>div.message.mentioned>div.body-3rkFrF>div>div.markup-2BOw-j {
  background: transparent !important;
  border-top-right-radius: 5px !important;
  border-top-left-radius: 5px !important;
}

.bda-dark .server-info button {
  background-color: var(--Main-Colour) !important;
}

#bd-themes-pane>ul>li {
  background-color: var(--Background-Colour) !important;
}

#bd-themes-pane>ul>li>div.bda-left>div>div {
  color: #fff !important;
}

#bd-plugins-pane>ul>li {
  background-color: var(--Background-Colour) !important;
}

#bd-plugins-pane>ul>li>div.bda-left>div>div {
  color: #fff !important;
}

#bd-emotes-sidebar.selected, #bd-customcss-sidebar.selected, #bd-themes-sidebar.selected, #bd-settings-sidebar .ui-tab-bar-item.selected, #bd-plugins-v.selected, #bd-settings-sidebar .ui-tab-bar-item:hover {
  color: var(--Main-Colour) !important;
  background: linear-gradient(to right, transparent, var(--Background-Colour), var(--Notification-Colour)) !important;
}

#app-mount>div>span:nth-child(6)>div.modal>div>form>div.settings-right>div:nth-child(1)>div>div>div.control-groups>div>div>div.user-settings-streamer-mode-enable-inner>ul>li>div.help-text>a {
  color: var(--Main-Colour) !important;
}

.tip>a {
  color: var(--Main-Colour) !important;
}

#app-mount>div>span:nth-child(6)>div.modal>div>form>div.settings-right>div:nth-child(1)>div>div>div>div>div>div:nth-child(2)>div>label .selected {
  border-color: var(--Main-Colour) !important;
}

#app-mount>div>span:nth-child(6)>div.modal>div>form>div.settings-right>div:nth-child(1)>div>div>div.tab-bar.TOP>div .selected {
  color: var(--Main-Colour) !important;
}

a {
  color: var(--Main-Colour) !important;
}

.win-close {
  background-image: url('https://ditmcouk.ipage.com/noottech/discord-icons/green/green-closewindow.svg') !important;
  opacity: 0.4 !important;
}

.win-minimize {
  background-image: url('https://ditmcouk.ipage.com/noottech/discord-icons/green/minimise.svg') !important;
  opacity: 0.4 !important;
}

.win-maximize {
  background-image: url('https://ditmcouk.ipage.com/noottech/discord-icons/green/green-maximise.svg') !important;
  opacity: 0.4 !important;
}

.win-close:hover {
  background-image: url('https://ditmcouk.ipage.com/noottech/discord-icons/green/green-closewindow.svg') !important;
  opacity: 1 !important;
}

.win-minimize:hover {
  background-image: url('https://ditmcouk.ipage.com/noottech/discord-icons/green/minimise.svg') !important;
  opacity: 1 !important;
}

.win-maximize:hover {
  background-image: url('https://ditmcouk.ipage.com/noottech/discord-icons/green/green-maximise.svg') !important;
  opacity: 1 !important;
}

#friends>div.friends-header>div.tab-bar.UNIQUE>div {
  color: var(--Main-Colour) !important;
}

#friends>div.friends-header>div.btn {
  color: var(--Main-Colour) !important;
}

#app-mount>div>span.theme-dark>div>div>div.body-3rkFrF, #app-mount>div>span.theme-dark>div>div>div.footer-2J5zqP, #app-mount>div>span.theme-light>div>div>div.body-3rkFrF, #app-mount>div>span.theme-light>div>div>div.footer-2J5zqP {
  background-color: var(--Background-Colour) !important;
}

#app-mount>div>span.theme-dark>div>div>div.body-3rkFrF>div>div, #app-mount>div>div.app.flex-vertical.theme-dark>div>section>div.wrapper-1Rf91z>div>button {
  color: var(--Main-Colour) !important;
}

#app-mount>div>div.app.flex-vertical.theme-light>div>section>div.wrapper-1Rf91z>div>button {
  color: var(--Main-Colour) !important;
  opacity: 0.4 !important;
}

#app-mount>div>div.app.flex-vertical.theme-light>div>section>div.wrapper-1Rf91z>div>button:hover:after {
  opacity: 1 !important;
}

div.settings-right>div.settings-actions {
  background-color: var(--Background-Colour) !important;
}

/* Exclamation, Invite, Mobile and Twitter SVGs */

.chat .welcome-message .item-container .icon.exclamation {
  background-image: url('https://ditmcouk.ipage.com/noottech/discord-icons/green/exclamation.svg');
}

#app-mount>div>div.app.flex-vertical.theme-dark>div>section>div.chat.flex-vertical.flex-spacer>div.content.flex-spacer.flex-horizontal>div.flex-spacer.flex-vertical>div>div>div>div>div:nth-child(3)>div {
  background-image: url('https://ditmcouk.ipage.com/noottech/discord-icons/green/invite.svg') !important;
}

#app-mount>div>div.app.flex-vertical.theme-dark>div>section>div.chat.flex-vertical.flex-spacer>div.content.flex-spacer.flex-horizontal>div.flex-spacer.flex-vertical>div>div>div>div>div:nth-child(4)>div {
  background-image: url('https://ditmcouk.ipage.com/noottech/discord-icons/green/mobile.svg') !important;
}

#app-mount>div>div.app.flex-vertical.theme-dark>div>section>div.chat.flex-vertical.flex-spacer>div.content.flex-spacer.flex-horizontal>div.flex-spacer.flex-vertical>div>div>div>div>div:nth-child(5)>div {
  background-image: url('https://ditmcouk.ipage.com/noottech/discord-icons/green/twitter.svg') !important;
}

.scroller-2TZvBN .avatar-small {
  border: none !important;
}

.spinner-inner {
  position: relative;
  display: inline-block;
  width: 45px;
  height: 45px;
}

.spinner-wandering-cubes .spinner-item {
  background-color: var(--Main-Colour);
  width: 10px;
  height: 10px;
  position: absolute;
  top: 0;
  left: 0;
  animation: spinner-wandering-cubes 1.8s infinite ease-in-out;
}

.jump-to-present-bar button, .chat .jump-to-present-bar .spinner {
  background-color: transparent !important;
  color: var(--Background-Colour) !important;
}

.chat .new-messages-bar, div[class*=" unreadBar-"], .mention-1f5kbO, .theme-dark .chat .jump-to-present-bar, .channels-wrap>div:last-child:hover>div:last-child:hover {
  background: linear-gradient(to right, var(--Background-Colour), var(--Secondary-Main-Colour), var(--Secondary-Main-Colour), var(--Background-Colour)) !important;
  color: var(--Background-Colour) !important;
}

.theme-dark .chat .has-more button {
  background: transparent !important;
  color: var(--Main-Colour) !important;
}

.spinner-pulsing-ellipsis .spinner-item {
  background-color: var(--Main-Colour) !important;
  margin-bottom: -10px !important;
}

div.tab-bar-item.selected {
  color: var(--Main-Colour) !important;
}

.guild-header header {
  position: absolute;
  right: 0;
  border: transparent;
  color: #ffffff;
  height: 58px;
  width: 140%;
}

.checkbox span {
  color: #a6a6a6;
  padding-left: 30px;
  margin-top: 3px !important;
  margin-bottom: 3px !important;
}

.checkbox .checkbox-inner span {
  border-radius: 10px;
  height: 22px;
  width: 50px;
  padding-bottom: 11px;
  background-color: #a8a8a8 !important;
  background-image: url(https://nfld99.com/Bkg/XVZz4KO.png) !important;
  background-size: 44%;
  background-repeat: no-repeat;
  border: none;
}

.checkbox .checkbox-inner input[type=checkbox]:checked+span:after {
  margin-left: 15px !important;
  border: none !important;
}

.checkbox .checkbox-inner input[type=checkbox]:checked+span {
  width: 50px;
  transform: rotate(180deg) !important;
  background-color: var(--Main-Colour) !important;
}

.checkbox-3kaeSU span {
  color: #a6a6a6;
  padding-left: 30px;
  margin-top: 3px !important;
  margin-bottom: 3px !important;
  transition: 500ms all;
}

.checkbox-3kaeSU .checkboxInner-3yjcPe span {
  border-radius: 10px;
  height: 22px;
  width: 50px;
  padding-bottom: 11px;
  background-color: #a8a8a8 !important;
  background-image: url(https://nfld99.com/Bkg/XVZz4KO.png) !important;
  background-size: 44%;
  background-repeat: no-repeat;
  border: none;
  transition: 500ms all;
}

.checkbox-3kaeSU .checkboxInner-3yjcPe input[type=checkbox]:checked+span:after {
  margin-left: 15px !important;
  border: none !important;
  transition: 500ms all;
}

.checkbox-3kaeSU .checkboxInner-3yjcPe input[type=checkbox]:checked+span {
  width: 50px;
  transform: rotate(180deg) !important;
  background-color: var(--Main-Colour) !important;
  transition: 500ms all;
}

div.avatar-uploader-inner {
  margin-top: 0px !important;
  width: 170px !important;
  height: 170px !important;
  background-size: cover !important;
}

button.btn.icon.icon-logout:hover {
  background-color: var(--Main-Colour) !important;
  border-radius: 5px;
}

div.avatar-small {
  border-radius: 4px !important;
}

.welcome-message h1 {
  color: var(--Main-Colour) !important;
}

.item-group .item {
  background: var(--Background-Colour) !important;
  color: var(--Main-Colour) !important;
}

.emoji-picker .scroller .emoji-item.selected {
  border-bottom: 1px solid var(--Main-Colour);
}

.emoji-picker {
  border-top: transparent!important;
  border: 1px solid var(--Main-Colour);
}

.emoji-picker .categories .item.selected {
  border-bottom-color: var(--Main-Colour) !important;
}

#bd-themes-pane>ul>li {
  border: none !important;
}

.bda-slist li {
  border: none !important;
}

.scroller .bda-description {
  border: none !important;
}

.option-popout .small-popout-box {
  background-color: #232323 !important;
}

.option-popout .small-popout-box .btn-item {
  background-color: #232323 !important;
  color: var(--Main-Colour) !important;
}

div.option-popout.small-popout-box, div.context-menu, .context-menu .context-menu, .theme-dark.context-menu .item, .context-menu .item:not(.item-subMenu) {
  background: var(--Background-Colour) !important;
  background-color: var(--Background-Colour) !important;
  color: var(--Secondary-Main-Colour)!important;
}

div.option-popout.small-popout-box:hover, div.context-menu:hover, .context-menu .context-menu:hover, .theme-dark.context-menu .item:hover, .context-menu .item:hover {
  background: var(--Background-Colour) !important;
  background-color: var(--Background-Colour) !important;
  color: var(--Main-Colour)!important;
}

div.option-popout.small-popout-box:hover, div.context-menu:hover, .context-menu .context-menu:hover {
  background: var(--Background-Colour) !important;
  background-color: var(--Background-Colour) !important;
  border: 2px solid var(--Main-Colour) !important;
}

div.option-popout.small-popout-box, div.context-menu, .context-menu .context-menu:not(.item-subMenu) {
  background: var(--Background-Colour) !important;
  background-color: var(--Background-Colour) !important;
  border: 2px solid var(--Secondary-Main-Colour) !important;
}

div.btn-item {
  background-color: var(--Background-Colour) !important;
  color: var(--Secondary-Main-Colour) !important;
  border: none;
}

div.btn-item:hover {
  background-color: var(--Background-Colour) !important;
  color: var(--Main-Colour) !important;
  border: none;
}

.context-menu .item-toggle .checkbox {
  pointer-events: none;
  transform: scale(.8);
  cursor: pointer!important;
  right: 10px;
  margin-top: -5px;
  position: absolute;
  overflow: visible !important;
}

div.flex-spacer.flex-vertical form {
  background: none;
}

/* Server Stuff*/

.guild-header header {
  box-shadow: none;
}

.layers {
  background: rgba(0, 0, 0, .5) !important;
}

.item-subMenu .context-menu .item.item-toggle {
  position: relative!important;
}

.channel-members-loading {
  display: none;
}

/* nitro thing */

.avatar-large[style*="a_"]+.comment .message.first .body-3rkFrF .username-wrapper:after {
  content: url(https://nfld99.com/Bkg/rzf0lV7.png);
  color: lime;
  margin-left: 5px;
  background: transparent;
  line-height: 16px;
  text-transform: uppercase;
  vertical-align: bottom;
  border-radius: 3px;
  margin-left: 6px;
  padding: 1px 2px;
  font-size: 10px;
  font-weight: 600;
  cursor: text;
}

.member.member-status>.avatar-small[style*="a_"]+.member-inner .member-username:after {
  content: '?';
  color: lime;
  margin-left: 5px;
  background: transparent;
  line-height: 15px;
  height: 14px;
  text-transform: uppercase;
  vertical-align: bottom;
  border-radius: 3px;
  margin-left: 6px;
  padding: 1px 2px;
  font-size: 10px;
  font-weight: 600;
  animation: rainbow 3s infinite linear;
}

.channel-textarea-autocomplete-inner .avatar-small[style*="a_"]+.discord-tag:after, .channel-textarea-autocomplete-inner .avatar-small[style*="a_"]+.username:after {
  content: '';
  position: absolute;
  background: url(https://canary.discordapp.com/assets/65f0a0df5563e21de7b1aeeafaf31d78.svg);
  background-size: 20px;
  width: 20px;
  height: 15px;
  margin-left: 5px;
}

.channel.channel-voice:not(.collapsed) .avatar-small[style*="a_"]+span:after {
  content: '';
  position: absolute;
  background: url(https://canary.discordapp.com/assets/65f0a0df5563e21de7b1aeeafaf31d78.svg);
  background-size: 20px;
  width: 20px;
  height: 15px;
  margin-top: 1.5px;
  margin-left: 5px;
}

/* nitro thing */

.container-PNkimc, .wrapper-2NJDcI, .private-channels .channel.selected a, .private-channels .channel:hover a {
  background: transparent !important;
}

.contentSelectedText-3wUhMi, .contentHoveredText-2HYGIY, .contentHoveredVoice-3qGNKh:active, .contentSelectedVoice-gTtYM9:active, .userHovered-2_fT4Z:active, .contentHoveredVoice-3qGNKh:hover, .contentSelectedVoice-gTtYM9:hover, .userHovered-2_fT4Z:hover {
  background: linear-gradient(to right, transparent, var(--Background-Colour), var(--Notification-Colour)) !important;
}

.vertical-V37hAW {
  background: transparent !important;
}

.container-2Thooq, .theme-dark .message-group h2 strong {
  background: transparent !important;
  color: var(--Main-Colour);
}

.container-1UB9sr {
  background: transparent !important;
  border-bottom: transparent !important;
}

.scroller-2v3d_F {
  padding-right: 1px;
}

.hljs {
  background: var(--Background-Colour) !important;
  border-radius: 4px !important;
  border-color: #666666 !important;
  font-size: 16px;
  font-style: normal;
  font-weight: normal;
}

.name-3M0b8v {
  color: var(--Main-Colour);
  font-size: 14px;
}

.modal-image {
  text-align: center;
  display: flex;
  flex-flow: column;
  max-height: 130%;
  pointer-events: none;
}

.modal-image .scroller-wrap {
  position: fixed;
  width: 100%;
  height: 100%;
  left: 0;
  top: 0;
}

.modal-image .scroller-wrap .scroller {
  overflow: visible;
}

.modal-image img {
  position: fixed;
  max-width: calc(100% - 80px);
  max-height: calc(100% - 80px);
  top: 50%;
  left: 50%;
  transform: translateX(-50%) translateY(-50%);
  pointer-events: auto;
}

.modal-image .download-button {
  position: absolute;
  left: 300px;
  bottom: 6px;
  pointer-events: auto;
}

.modal-image .qs_button {
  position: absolute;
  left: 450px;
  bottom: 6px;
  pointer-events: auto;
}

.image.image-loading {
  opacity: .9;
}

.modal-image .image.image-loading::before {
  background: transparent;
}

.deprecated-settings-modal .settings-inner {
  background-color: var(--Background-Colour);
  background-position: 0 100%;
  background-size: 100%, auto;
  background-repeat: no-repeat;
  min-height: 0;
  overflow: hidden;
}

.ui-standard-sidebar-view .bda-slist li:nth-child(odd) {
  background: transparent;
  -webkit-box-shadow: 0 0 1px 0 var(--Main-Colour);
  box-shadow: 0 0 1px 0 var(--Main-Colour);
}

.ui-standard-sidebar-view .bda-slist li {
  background: transparent;
  -webkit-box-shadow: 0 0 1px 0 var(--Main-Colour);
  box-shadow: 0 0 1px 0 var(--Main-Colour);
}

.bda-slist li {
  background: var(--Background-Colour);
  padding: 5px;
  border-bottom: 1px solid var(--Background-Colour);
  min-height: 22%;
  max-height: 100%;
}

.content-region .CodeMirror, .content-region .cm-s-material .CodeMirror-gutters, #bd-customcss-detach-container .CodeMirror, #bd-customcss-detach-container .cm-s-material .CodeMirror-gutters, .content-region #bd-customcss-attach-controls, #bd-customcss-detach-container #bd-customcss-attach-controls {
  background: rgba(25, 0, 43, 0.3) !important;
}

.upload-modal {
  width: 520px;
  min-height: 258px;
  background-color: var(--Background-Colour);
  border-radius: 10px;
  display: -webkit-box;
  display: -ms-flexbox;
  display: flex;
  -webkit-box-orient: vertical;
  -webkit-box-direction: normal;
  -ms-flex-direction: column;
  flex-direction: column;
  -webkit-perspective: 1000;
  perspective: 1000;
  -webkit-filter: blur(0);
  filter: blur(0);
}

.upload-modal .footer {
  background-color: var(--Background-Colour);
}

.popout-menu .popout-menu-item:hover {
  background: linear-gradient(to right, var(--Background-Colour), var(--Background-Colour), var(--Main-Colour)) !important;
  opacity: 1;
  color: var(--Background-Colour);
}

.popout-menu .popout-menu-item {
  background-color: var(--Background-Colour) !important;
  display: -webkit-box;
  display: -ms-flexbox;
  display: flex;
  padding: 10px 14px;
  cursor: pointer;
  box-sizing: border-box;
  color: #ffffff;
  margin: 0;
  font-size: 15px;
  line-height: 18px;
  -webkit-box-align: center;
  -ms-flex-align: center;
  align-items: center;
}

.channel-members-loading {
  background-color: transparent !important;
}

.channel-members-loading .background {
  background: var(--Main-Colour);
  opacity: .1;
  animation: rainbow 2.8s infinite linear;
}

.theme-dark .message-group .comment .markup-2BOw-j code.inline, .theme-dark .message-group .comment .markup-2BOw-j pre code {
  background: var(--Background-Colour) !important;
}

.message-group .mentioned .message-text:after {
  position: absolute;
  top: 0;
  left: -6px;
  bottom: 0;
  content: " ";
  width: 2px;
  background: rgba(0, 68, 9, 0);
  border-left: 4px solid #005a06;
  border-radius: 2px 0 0 2px;
}

.theme-dark .message-group .comment .markup-2BOw-j .mention:hover {
  background-color: rgba(124, 0, 134, 0.7);
}

.theme-dark .message-group .comment .markup-2BOw-j .mention {
  background-color: rgba(115, 139, 215, .1);
}

.markup-2BOw-j .edited {
  text-shadow: none;
}

.mentioned .mention:hover {
  color: var(--Main-Colour);
  text-decoration: underline;
}

.mentioned .mention, .mentioned .mention:hover {
  background: transparent !important;
}

.mention:hover {
  cursor: pointer;
  color: var(--Main-Colour);
  background-color: var(--Secondary-Background-Colour);
}

.message-group .comment .markup-2BOw-j .mention, .nameHovered-28u_Fz, .nameSpeaking-3ROx9q, .nameDefault-2s3kbY {
  color: var(--Main-Colour);
  animation: rainbow 3s infinite linear;
}

/*
.mention {
  color: #00e5ff;
  background: #d6ff00;
  font-weight: 500;
  transition: background-color .05s,color .05s;
}
*/

.theme-dark .channel-members-loading .member:nth-child(2n-4), .theme-dark .channel-members-loading .member, .theme-dark .channel-members-loading .heading, .theme-dark .channel-members-loading .member:nth-child(7n-1), .theme-dark .channel-members-loading, .theme-dark .channel-members-loading .member:nth-child(3n+2), .theme-dark .channel-members-loading .member:nth-child(7n+4) {
  background: transparent;
}

.theme-dark .private-channel-call {
  background-color: transparent !important;
}

.userPopout-4pfA0d {
  background: var(--Background-Colour);
}

.userPopout-4pfA0d .body-3rkFrF, .headerNormal-1cioxU, .footer-2J5zqP, .quick-message {
  background: transparent !important;
  background-color: transparent !important;
}

.userPopout-4pfA0d .quick-message {
  color: var(--Main-Colour);
}

.userPopout-4pfA0d .avatar-16XVId {
  background-clip: padding-box;
  position: relative;
  background: 50% 50%/cover;
  border-radius: 10px!important;
  -ms-flex-negative: 0;
  flex-shrink: 0;
  width: 200px!important;
  height: 200px!important;
  border: none;
}

.userPopout-4pfA0d .footer-2J5zqP {
  display: none;
}

#user-profile-modal .header:after {
  background: transparent !important;
  background-color: var(--Background-Colour) !important;
}

#user-profile-modal .tab-bar-container {
  background: transparent !important;
  background-color: var(--Background-Colour) !important;
  border-bottom: 1px solid var(--Background-Colour);
}

#user-profile-modal .empty {
  background: var(--Background-Colour) !important;
}

#user-profile-modal .avatar-wrapper {
  background: transparent !important;
}

#user-profile-modal .avatarWrapper-2Gfmp1, #user-profile-modal .scroller {
  background-color: var(--Background-Colour);
}

#user-profile-modal .header .header-info .header-info-inner .discord-tag, #user-profile-modal .header .header-info .header-info-inner .discord-tag .headerDiscriminator-3fLlCR, .headerTagNormal-KyD3_J, .headerUsernameNoNickname-1iGxNP {
  color: var(--Main-Colour)!important;
}

.wrapper-1Rf91z .scroller-2TZvBN .guild, .wrapper-1Rf91z .scroller-2TZvBN .container-1ETFDs.wrapper-2lTRaf a {
  width: 40px;
  height: 40px;
}

.theme-dark .themed-popout {
  background-color: var(--Background-Colour);
  border: 1px solid rgba(192, 255, 0, 0.6);
  -webkit-box-shadow: 0 2px 10px 0 var(--Background-Colour);
  box-shadow: 0 2px 10px 0 rgba(253, 28, 28, 0);
}

ul.bda-slist>li[data-reactid^=".3.$scroller.$pcolumn.1:$plugin-list.$"]>div:nth-child(2):not(.bad-right) {
  color: white !important;
}

.wrapper-2lTRaf[style*="background-color: rgb"] {
  border-radius: 1px!important;
}

.button-2KyEfG:hover {
  background-color: var(--Main-Colour);
}

.instant-invite-modal {
  position: relative;
  width: 440px;
  height: 246px;
  background: var(--Background-Colour);
  border-radius: 5px;
}

div.form-inner, .form-actions {
  background-color: var(--Background-Colour) !important;
}

#instant-invite-modal .clipboard-input-inner input {
  color: #00c416;
  font-size: 24px;
  line-height: 30px;
  font-weight: 400;
  background-color: var(--Background-Colour);
}

.itemDefaultSelected-1UAWLe, .itemBrandSelected-3LxxzT, .itemDefault-3NDwnY:hover, .itemBrand-mC9YR4:hover, .private-channels .channel.selected a, .private-channels .channel:hover a, .side-8zPYf6 .itemSelected-1qLhcL, .channel-2QD9_O.selected-1HYmZZ a, .channel-2QD9_O.selected-1HYmZZ a, .channel-2QD9_O:hover a {
  color: var(--Main-Colour) !important;
  background: linear-gradient(to right, transparent, var(--Background-Colour), var(--Notification-Colour)) !important;
}

.itemDefault-3NDwnY:not(.role-3wi9Tf), .itemBrand-mC9YR4:not(.role-3wi9Tf), #bd-settings-sidebar .ui-tab-bar-item:not(.role-3wi9Tf) {
  color: var(--Secondary-Main-Colour)!important;
}

.search-bar.search-bar-light .search-bar-inner {
  background: transparent;
  border: 1px solid var(--Main-Colour);
}

.itemBrand-mC9YR4 {
  color: rgba(255, 255, 255, 0.7);
}

.separator-gCa7yv, #bd-settings-sidebar .ui-tab-bar-separator {
  background: var(--Secondary-Main-Colour)!important;
}

#bd-settings-sidebar .ui-tab-bar-separator {
  background: var(--Secondary-Main-Colour)!important;
}

.header-2RyJ0Y, #bd-settings-sidebar .ui-tab-bar-header {
  color: var(--Main-Colour)!important;
}

.theme-dark .link-1IoFq-:hover .foreground-26ym5y {
  fill: var(--Main-Colour);
}

.cardPrimary-ZVL9Jr {
  background: transparent!important;
}

.theme-dark .search-results-wrap .search-result.expanded .search-result-message.hit {
  border-top: 2px solid rgba(28, 36, 43, .6);
  box-sizing: border-box;
  background-color: var(--Background-Colour);
  border: 2px solid var(--Main-Colour);
}

.theme-dark .search-results-wrap .search-header {
  background-color: var(--Background-Colour);
  -webkit-box-shadow: 0 1px 0 var(--Background-Colour);
  box-shadow: 0 1px 15px rgba(0, 255, 0, .2);
}

.theme-dark .search-results-wrap {
  background-color: var(--Background-Colour);
}

.theme-dark .search-results-wrap .channel-separator .channel-name {
  color: #fff;
  background-color: var(--Background-Colour);
}

.theme-dark .search-results-wrap .search-result .search-result-message.hit {
  border: 2px solid var(--Main-Colour);
}

.theme-dark .search-results-wrap .search-result .hit {
  background-color: var(--Background-Colour);
  -webkit-box-shadow: 0 0 10px 6px #2f3136;
  box-shadow: 0 0 10px 6px rgba(0, 216, 84, 0.6);
}

.theme-dark .search-results-wrap .search-result:after {
  background-image: -webkit-gradient(linear, left top, left bottom, from(rgba(47, 49, 54, 0)), to(rgba(0, 216, 84, 0)));
  background-image: linear-gradient(180deg, rgba(47, 49, 54, 0), rgba(0, 216, 84, 0));
}

.theme-dark .search-results-wrap .search-result:before {
  background-image: -webkit-gradient(linear, left bottom, left top, from(rgba(47, 49, 54, 0)), to(rgba(47, 49, 54, 0)));
  background-image: linear-gradient(0deg, rgba(47, 49, 54, 0), rgba(47, 49, 54, 0));
}

.bf-toolbar {
  -webkit-user-select: none;
  -moz-user-select: none;
  -ms-user-select: none;
  user-select: none;
  white-space: nowrap;
  font-size: 85%;
  display: -webkit-box;
  display: -ms-flexbox;
  display: flex;
  position: absolute;
  color: var(--Main-Colour);
  width: auto;
  bottom: auto;
  border-radius: 0;
  margin: 0;
  height: 27px;
  top: 0;
  -webkit-transform: translate(0, -100%);
  -ms-transform: translate(0, -100%);
  transform: translate(0, -100%);
  opacity: 1;
  display: block;
  overflow: hidden;
  pointer-events: none;
}

.theme-dark .message-group .edit-message .edit-operation {
  margin-top: 5px;
  margin-right: 0px;
  color: var(--Secondary-Main-Colour);
}

.theme-dark .message-group .embed {
  border-color: var(--Main-Colour);
}

.wrapper-232cHJ {
  border-radius: 3px;
  background-clip: padding-box;
  background-color: var(--Main-Colour);
  color: var(--Background-Colour);
  -webkit-box-shadow: none;
  box-shadow: none;
  font-size: 12px;
  font-weight: 500;
  line-height: 12px;
  display: inline-block;
  padding: 3px 6px;
  text-shadow: 0 1px 0 rgba(0, 0, 0, .25);
}

.new-messages-indicator .new-messages-indicator-mention, .unread-mentions-indicator-bottom, .unreadMentionsIndicatorTop-gA6RCh {
  background-color: transparent;
  color: var(--Main-Colour);
  text-shadow: 0 0 2px var(--Text-Shadow-Colour), 0 0 6px var(--Text-Shadow-Colour), 0 0 5px var(--Text-Shadow-Colour), 0 0 4px var(--Text-Shadow-Colour);
}

.wrapper-1Rf91z .scroller-2TZvBN .container-1ETFDs.badge-2_fwUZ {
  position: absolute;
  bottom: -8px;
  right: 9px;
  pointer-events: none;
}

.container-37-TX2:hover {
  color: var(--Main-Colour);
}

.container-37-TX2 {
  color: var(--Secondary-Main-Colour);
}

.wrapperHoveredVoice-3tbfNN {
  background: linear-gradient(to right, transparent, var(--Background-Colour), var(--Main-Colour)) !important;
}

.avatarSpeaking-1wJCNq {
  animation: Talking 3s infinite linear;
}

.chat>.title-wrap>.topic .aka {
  background: var(--Background-Colour);
  font-size: 10px;
  font-weight: 500;
  color: var(--Main-Colour);
  margin-right: 8px;
  padding: 1px 3px;
  border-radius: 3px;
  text-transform: uppercase;
  vertical-align: bottom;
  line-height: 22px;
  -ms-flex-negative: 0;
  flex-shrink: 0;
}

/* scrollbars */

*::-webkit-scrollbar-track-piece {
  border: none !important;
  background: transparent !important;
}

*::-webkit-scrollbar-thumb {
  background: transparent !important;
  border: 1px solid var(--Scroller-Colour) !important;
}

*:not(:hover)::-webkit-scrollbar-thumb {
  background: transparent !important;
  border: 0px solid transparent !important;
}

::-webkit-scrollbar {
  max-width: 10px !important;
}

.scrollerThemed-2oenus.themeDark-2cjlUp.scrollerTrack-1ZIpsv>.scroller-2FKFPG::-webkit-scrollbar-track, .theme-dark .scrollerWrap-2lJEkd.scrollerTrack-1ZIpsv>.scroller-2FKFPG::-webkit-scrollbar-track, .theme-light .scrollerThemed-2oenus.themeDark-2cjlUp.scrollerTrack-1ZIpsv>.scroller-2FKFPG::-webkit-scrollbar-track {
  background-color: rgba(0, 0, 0, 0);
}

.description-2ydcYn.margin-bottom-20 {
  display: none;
}

.title-1VcOOr.margin-bottom-8:after {
  content: "Do You Wish To See Members Of The Itty Bitty Titty Committee?";
  display: block;
  font-size: 16px;
  line-height: 16px;
  margin-top: 8px;
  margin-bottom: 12px;
  color: var(--Main-Colour);
}

.theme-dark .image-2LqJex {
  background-image: url(https://nfld99.com/Bkg/PBwzzZX.jpg);
}

.actionRed-1J19Tx, .actionRed-1J19Tx:hover {
  Background: var(--Secondary-Main-Colour);
}

.theme-dark .modal-3HD5ck, .theme-dark .message-2qRu38 {
  Background: var(--Background-Colour);
  box-shadow: 0 0 0 1px rgb(255, 0, 0), 2px 2px 2px 0 rgb(255, 0, 0);
}

#app-mount>div.app-19_DXt.platform-win>div>div.layers-3iHuyZ.flex-vertical.flex-spacer>div:nth-child(2)>div>div.content-region>div>div>div>div.content-column.default>div>div.userSettingsAccount-2WOnTW>div>div>div>div:nth-child(2)>div:nth-child(2)>div, .multiInput-1e2xJ7 {
  transition: filter .15s ease-in-out;
}

#app-mount>div.app-19_DXt.platform-win>div>div.layers-3iHuyZ.flex-vertical.flex-spacer>div:nth-child(2)>div>div.content-region>div>div>div>div.content-column.default>div>div.userSettingsAccount-2WOnTW>div>div>div>div:nth-child(2)>div:nth-child(2)>div:not(:hover), .multiInput-1e2xJ7:not(:hover) {
  filter: blur(6px);
}

.description-3_Ncsb.formText-1L-zZB.margin-bottom-20.modeDefault-3a2Ph1.primary-2giqSn {
  Display: none;
}

.theme-dark .cardPrimary-1Hv-to, .theme-dark .cardPrimaryOutline-29Ujqw, .theme-dark .cardPrimaryEditable-3KtE4g, .theme-dark .ui-standard-sidebar-view .btn-close {
  border-color: var(--Secondary-Main-Colour);
}

.theme-dark .ui-standard-sidebar-view .btn-close:hover {
  background: var(--Secondary-Main-Colour);
  animation: Spin 2.8s infinite linear;
}

.theme-dark .ui-standard-sidebar-view .esc-text, #bd-settingspane-container .ui-switch-item .style-description, .ui-standard-sidebar-view .bda-slist .bda-description, .theme-dark .description-3_Ncsb, .theme-dark .labelDescriptor-1BebCl {
  color: var(--Secondary-Main-Colour);
}

.theme-dark .defaultColor-1_ajX0, #bd-settingspane-container h2.ui-form-title, #bd-settingspane-container .ui-switch-item h3, .theme-dark .h5-18_1nd, .theme-dark .user-settings-account .view-body {
  color: var(--Main-Colour);
}

.theme-dark .item-3eFBNF {
  box-shadow: inset 0 -1px 0 0 var(--Secondary-Main-Colour);
}

#bd-settingspane-container .ui-switch-item .style-description {
  border-bottom-color: var(--Secondary-Main-Colour);
}

.theme-dark .cardPrimary-1Hv-to, .theme-dark .cardPrimaryOutline-29Ujqw, .theme-dark .cardPrimaryEditable-3KtE4g {
  background: transparent!important;
}

#bd-settingspane-container .ui-switch-item .ui-switch-wrapper .ui-switch, .switchWrapperDefaultActive-2IdHq2:hover .switch-3wwwcV, .switch-3wwwcV {
  background: var(--Background-Colour);
}

#bd-settingspane-container .ui-switch-item .ui-switch-wrapper .ui-switch.checked, .switchWrapperDefaultActive-2IdHq2:hover .switch-3wwwcV.checked-7qfgSb, .switch-3wwwcV.checked-7qfgSb {
  background: var(--Main-Colour);
}

.theme-dark .friends-table .messages>span, .theme-dark .messagesWrapper-3lZDfY .messages>span, .markup-2BOw-j, .member.member-status .member-activity {
  text-shadow: 0 0 6px var(--Text-Shadow-Colour), 0 0 6px var(--Text-Shadow-Colour), 0 0 5px var(--Text-Shadow-Colour), 0 0 4px var(--Text-Shadow-Colour);
}

.user-settings-security-image {
  display: none;
}

.theme-dark .user-settings-connections .connect-account-btn .connect-account-btn-inner {
  background-color: Transparent;
  border-color: var(--Main-Colour);
}

.premium-settings .subscription.active, .premium-settings .subscription {
  background: transparent;
}

.buttonBrandInvertedDefault-uUmgsD:hover, .fancy-credit-input {
  background-color: var(--Main-Colour);
  color: var(--Background-Colour);
}

.buttonBrandInverted-VFL7Yc, .premium-payment-modal {
  background-color: var(--Background-Colour);
  color: var(--Main-Colour);
}

.premium-payment-modal .premium-animation {
  display: none;
}

.premium-settings .billing-history-list li.failed .billing-label, .premium-settings .billing-history-list li.reversed .billing-label {
  background-color: RED;
  margin-Right: -90px;
}

.theme-dark .bar-2Qqk5Z {
  background-color: var(--Background-Colour);
}

.barFill-23-gu- {
  background-color: var(--Main-Colour);
}

.cardWarning-2yPNAa, .cardWarningOutline-1cs56O, .theme-dark .user-settings-games .now-playing, .theme-light .user-settings-games .now-playing, .theme-dark .add-game-popout, .theme-dark .ui-select .Select-option {
  background-color: var(--Background-Colour);
  border-color: var(--Main-Colour);
}

.theme-dark .ui-hover-card:before, .theme-dark .user-settings-keybinds .keybind-group {
  background-color: transparent;
  border-color: var(--Main-Colour);
}

.theme-dark .user-settings-games .game {
  box-shadow: 0 1px 0 0 var(--Main-Colour);
}

.theme-dark .user-settings-games .game-name {
  color: var(--Main-Colour);
}

.theme-dark .user-settings-games .last-played, .theme-dark .user-settings-games .overlay-status-text {
  color: var(--Secondary-Main-Colour);
}

.horizontalReverse-2eTKWD>.flexChild-1KGW5q:first-child, .create-guild-container.deprecated .action.join .action-icon, .create-guild-container.deprecated .action.create .action-icon {
  display: none;
}

.create-guild-container.deprecated .action.join .btn, .create-guild-container.deprecated .action .btn {
  margin-top: 15px;
}

.action.create, .action.join, .create-guild-container.deprecated .create-or-join .actions .or {
  background: transparent!important;
}

.theme-dark .friends-table .messages .message-group-blocked .message-group-blocked-btn, .theme-dark .messagesWrapper-3lZDfY .messages .message-group-blocked .message-group-blocked-btn {
  background: transparent;
  color: var(--Main-Colour);
}

.message-group-blocked {
  border: 1px solid var(--Main-Colour)!important;
}

.buttonBrandFilled-3Mv0Ra, button.btn.btn-primary, .ui-standard-sidebar-view .bda-slist .bda-right button, .themeClear-1EjkE4.valueChecked-m-4IJZ, .themeClear-1EjkE4.valueChecked-m-4IJZ, .themeClear-1EjkE4.valueChecked-m-4IJZ, .theme-dark .messages-popout-wrap .has-more button {
  color: var(--Main-Colour)!important;
  background-color: transparent!important;
  border: 1px solid var(--Main-Colour)!important;
}

.ui-form-item.connection-list {
  opacity: .75;
}

.typing {
  bottom: -7px!important;
}

.theme-dark .ui-select .Select-option.is-focused, .theme-dark .ui-select .Select-option:hover, .theme-dark .ui-select .Select-option.is-selected:hover {
  background: Var(--Background-Colour);
  Color: var(--Main-Colour);
}

.theme-dark .ui-select .Select-option.is-selected {
  background: Var(--Background-Colour);
  border: .5px solid var(--Main-Colour);
}

.theme-dark .private-channel-call.minimum .private-channel-call-actions .center {
  border: 1px Solid var(--Main-Colour);
  background-color: Var(--Background-Colour);
}

.buttonRedFilled-1NjJNj {
  color: var(--Main-Colour);
  background-color: Var(--Background-Colour);
  border: 1px Solid var(--Main-Colour);
}

.buttonRedFilled-1NjJNj:hover {
  color: var(--Background-Colour);
  background-color: Var(--Main-Colour);
  border: 1px Solid var(--Background-Colour);
}

/* Search */

.theme-dark .theme-light .calendarPicker-2yf6Ci .react-datepicker, .theme-light .calendarPicker-2yf6Ci .react-datepicker, .theme-dark .theme-light .calendarPicker-2yf6Ci .react-datepicker__day--disabled, .theme-dark .theme-light .calendarPicker-2yf6Ci .react-datepicker__day--outside-month, .theme-light .calendarPicker-2yf6Ci .react-datepicker__day--disabled, .theme-light .calendarPicker-2yf6Ci .react-datepicker__day--outside-month, .theme-dark .theme-light .calendarPicker-2yf6Ci .react-datepicker__day, .theme-light .calendarPicker-2yf6Ci .react-datepicker__day {
  background-color: var(--Secondary-Background-Colour)!important;
  color: var(--Secondary-Main-Colour)!important;
  border-left-color: var(--Secondary-Main-Colour)!important;
  border-top-color: var(--Secondary-Main-Colour)!important;
}

.theme-dark .theme-light .calendarPicker-2yf6Ci .react-datepicker__day.react-datepicker__day--selected:hover, .theme-dark .theme-light .calendarPicker-2yf6Ci .react-datepicker__day:hover, .theme-light .calendarPicker-2yf6Ci .react-datepicker__day.react-datepicker__day--selected:hover, .theme-light .calendarPicker-2yf6Ci .react-datepicker__day:hover, .theme-dark .theme-light .calendarPicker-2yf6Ci .react-datepicker__header, .theme-light .calendarPicker-2yf6Ci .react-datepicker__header, .theme-dark .theme-light .calendarPicker-2yf6Ci .react-datepicker__current-month, .theme-light .calendarPicker-2yf6Ci .react-datepicker__current-month, .theme-dark .theme-light .calendarPicker-2yf6Ci .react-datepicker__day-name, .theme-light .calendarPicker-2yf6Ci .react-datepicker__day-name {
  background-color: var(--Background-Colour)!important;
  color: var(--Main-Colour)!important;
}

.theme-dark .theme-light .calendarPicker-2yf6Ci .react-datepicker__week .react-datepicker__day:last-of-type, .theme-light .calendarPicker-2yf6Ci .react-datepicker__week .react-datepicker__day:last-of-type {
  border-right-color: var(--Secondary-Main-Colour)!important;
}

.theme-dark .theme-light .calendarPicker-2yf6Ci .react-datepicker__week:last-of-type .react-datepicker__day, .theme-light .calendarPicker-2yf6Ci .react-datepicker__week:last-of-type .react-datepicker__day {
  border-bottom-color: var(--Secondary-Main-Colour)!important;
}

.search-popout .date-picker .date-picker-hint .hint {
  color: var(--Secondary-Main-Colour)!important;
}

.theme-dark .theme-light .calendarPicker-2yf6Ci .react-datepicker__navigation.react-datepicker__navigation--next, .theme-dark .theme-light .calendarPicker-2yf6Ci .react-datepicker__navigation.react-datepicker__navigation--previous, .theme-light .calendarPicker-2yf6Ci .react-datepicker__navigation.react-datepicker__navigation--next, .theme-light .calendarPicker-2yf6Ci .react-datepicker__navigation.react-datepicker__navigation--previous, .theme-dark .theme-light .calendarPicker-2yf6Ci .react-datepicker__current-month, .theme-light .calendarPicker-2yf6Ci .react-datepicker__current-month {
  border-color: var(--Secondary-Main-Colour)!important;
}

.search-popout .date-picker .date-picker-hint {
  border-top-color: var(--Secondary-Main-Colour)!important;
}

.theme-dark .theme-light .calendarPicker-2yf6Ci .react-datepicker__day.react-datepicker__day--selected:after, .theme-light .calendarPicker-2yf6Ci .react-datepicker__day.react-datepicker__day--selected:after {
  background-color: var(--Main-Colour)!important;
}

.theme-dark .searchAnswer-3Dz2-q, .theme-dark .searchFilter-2ESiM3 {
  background-color: var(--Background-Colour)!important;
  color: var(--Main-Colour)!important;
}

.theme-dark .search .DraftEditor-root, .search-popout .results-group .header, .search-popout .option.user .display-username {
  color: var(--Main-Colour)!important;
}

.search-popout .option strong, .search-popout .option.user .displayed-nick {
  color: var(--Secondary-Main-Colour)!important;
}

.search-popout, .search-popout .option, .search-popout .option:after, .search-popout .search-option .answer, .search-popout .search-option .filter {
  background: var(--Background-Colour)!important;
  color: var(--Secondary-Main-Colour)!important;
}

.search-popout .option.selected:hover, .search-popout .option.selected, .search-popout .option:hover {
  border: 1px solid var(--Main-Colour);
  background: var(--Background-Colour)!important;
}

/* Search */

/* .esc-text:after,.keybind-KpFkfr:after {
  content: "Made By NFLD99";
  font-size: 15px;
} */
/* water marks */
.esc-text:after, .keybind-KpFkfr:after {
  content: url('data:image/png;base64,iVBORw0KGgoAAAANSUhEUgAAAEAAAAAOCAYAAACfOxrCAAAABGdBTUEAALGPC/xhBQAAAAlwSFlzAAAOwwAADsMBx2+oZAAAABh0RVh0U29mdHdhcmUAcGFpbnQubmV0IDQuMS4zjST9ZwAABHNJREFUSEvNVl2IVkUYHsOItL+LtP8yyqgosDAiomSpMCoDr7SwhDDtIiIqspvwpqCLoosiWIouttz2nJmzrlstrGuuSmmFIHVjXZSp++05M+dz2+wHzNyv531nzpxzvm9iP+2iXniYM+88887MMz/nFSLW2z1kdo+omtTbfJtKe5xvY61PCMqsElF2h5BmjOvSSNGXzuf+7RalD3b0Jyg9gvm8LFR+vWOWNti8AfN4D+N8BRzH9y4RZ6+JrdlFjmGt1ToD/VeAsxWYwDwylKNCZesdA6ZMy0PqHc5rTem/fFucrmafNH21PkHkL0KwFYg343yZiKfO5/7tJs2T9b5tkGYKQqxxbMwpfwxx/wxylQY3X8q8fa0zWfggj6B3Q+hz6gIQZPoEByD7PwhAkOagiCYXiCRdiJhHgpwCdBp6sfikubIyfhhx9mxAAP09js4cntxsAki9F0E2YMHra4j1ktMUYL9I8g3wPYO+dLyLcU7g2N4rBs0yzMnGlKaJ7zvFcGMe/A/B94fl62mhpq5Cn4FK/zHRf+hSMTozH/W3vV+Z7Z0CEGIDZWCzCpD1sS9kpyOA1B86r+D7rMxh36ayRyFuT8nF/RfCbtTmxoXwpa5tWnyULgI3tjzMQZryVCfZSsejGJ+VAkjzm/9W5pAYmTmrixMwJqLmfXjwKtDXMq9bAWKzrhKvFKAXO6vMd76NBTB3+5hS/4BysRg5toAfb2V+tTwIwCfAbHZ1Wts7zKMrFOtXK/6KAMqcQNBPy8bsKZSzCQB19ck2DOD5ndO1AFF6NRZnFzqbAFHzMnAmS5/+BfUpfLvjz5jGWFfCvxY46Xg0LzyQDFwnx20TgCawtlLfj/ouX+/+EUxOSQCyoeaNiPs5ducD5wkLQG+T1C+gXuy2hd2IYiwrAL0Nygzx4qvc6qnuECDJH0agg7aRg2rfFhQAO6DwaFaRmLdOWQCyCEc01o+7muAF0IPsx4IAZPxvx1VI9LAd03wD3isojeNaAciiw2eD8zTav2au1Dvxm3zD8QICKL0c5QN1n0NYgH4xigSHkpwC9HaQVQWQRvNDRb+nKoq/TbuRPzG3oj8ELsZyApAN5efCt5jHpkXG+mLMpVMA2ogtPy/idppb7z7KDR7xMYMCbBqfi/LLuh8IvgFd/gU4caGY2Rc1DJrrbMaYv1lH9j76/OTH4WzP3MULirKb8b0D7ZPgrhHxxBJ8vwtOcd+PQrxLxHhrLsrVaGsAO5FHLAN/Kb4P+LgSGaKv2M7L3eR7QCyOr8W/EeCfkDSwy90kQvpb7OQFvItS7wlyCkijePyB9CZ8/x7kEGhuUboqLABZrD+utf0XAlB/Ogl0HQpL8tswbiPIVXpcJEcuZ94mvBUy3Yi2zrSZ/gRSv848JAyfeFQH6p+4BUembKOHhyzOn6/4nmNfyGR6Owap9A9gUF+DvOH+YFuM9yVBjrDl6BUuYmmUa8QZZXQ/YtHHUW5D+ZIYaZ7nGNZIBMpT6FQofQzzwbUxw5w5sgnxNyB3m34raxnsAAAAAElFTkSuQmCC');
  animation: CLog 10s infinite linear;
}

#app-mount > div > div > div.layers-3iHuyZ.vertical-V37hAW.flex-1O1GKY.directionColumn-35P_nr.spacer-1fA9zc > div > div > div.flex-1xMQg5.flex-1O1GKY.vertical-V37hAW.flex-1O1GKY.directionColumn-35P_nr.justifyStart-2NDFzi.alignStretch-DpGPf3.noWrap-3jynv6.base-3dtUhz > div.flex-1xMQg5.flex-1O1GKY.horizontal-1ae9ci.horizontal-2EEEnY.flex-1O1GKY.directionRow-3v3tfG.justifyStart-2NDFzi.alignStretch-DpGPf3.noWrap-3jynv6.spacer-29U_x8.firefoxFixScrollFlex-cnI2ix > div.channels-Ie2l6A.vertical-V37hAW.flex-1O1GKY.directionColumn-35P_nr > div.container-2Thooq > div.accountDetails-3k9g4n.nameTag-m8r81H > span.discriminator:after {
  content: "  NFLD99.com  " !important;
  font-weight: bolder;
}

#app-mount > div > div > div > div > div > div > div > div > div > div > span.discriminator:after {
  content: "  NFLD99.com  " !important;
  font-weight: bolder;
}
/* water marks */

.esc-text:after, .keybind-KpFkfr {
  font-size: 0px;
}

.theme-dark .keybind-KpFkfr {
  color: var(--Secondary-Main-Colour);
}

.theme-dark .closeButton-1tv5uR {
  border-color: var(--Secondary-Main-Colour);
  background-color: var(--Secondary-Background-Colour);
}

.theme-dark .closeButton-1tv5uR:hover {
  border-color: var(--Background-Colour);
  background-color: var(--Main-Colour);
}

.closeButton-1tv5uR>svg>g>path.fill {
  fill: var(--Secondary-Main-Colour)
}

.closeButton-1tv5uR:hover>svg>g>path.fill {
  fill: var(--Background-Colour)
}

#user-profile-modal .avatar-wrapper {
  position: absolute;
  top: 40px;
  left: 40px;
  background-color: transparent!important;
}

.avatar-profile {
  border-radius: 5px!important;
}

.typing {
  text-shadow: 0 0 6px Black, 0 0 6px Black, 0 0 5px Black, 0 0 4px Black;
  border-radius: 5px !important;
}

.theme-dark .invite-button {
  background-color: transparent;
  border-color: var(--Main-Colour);
}

.channels-wrap [class^="scroller"]>[style^="width: 100%; height: 0"] {
  overflow: visible!important;
}

.avatarHint-2i5XWK {
  border-radius: 0;
}

::-webkit-input-placeholder {
  color: var(--Secondary-Main-Colour)!important;
}

.spinner {
  align-items: initial;
}

/* Web Ver Of Discord */

.imagesInner-lrmOIH, .stats-22hutn, .buttonBlurple-HN5AKD, .callout-2s8mFN, .footerBackgroundBlurple-1Ulhgr {
  display: none!important;
}

.themeBrand-SmLCC0, .footerBlurple-BUhVUG, .fieldButton-2ES_NP, .fieldWrapClosed-2bqTxU, .fieldForm-qnusX2, .desktopMoreList-3GyfO6, .desktopMoreListItem-yTZpxg {
  background: transparent!important;
  background-color: transparent!important;
}

.separator-3v7eD_ {
  margin: 13px 0;
}

.container-2lgZY8, .theme-dark .title-3qD0b-, .theme-dark .chat form, .channels-Ie2l6A {
  background-color: transparent !important;
  box-shadow: 0 -1px 5px rgba(0, 243, 255, 0)!important;
}

.text-NLHgOm h4:after {
  content: ". Ya fucked it, Please reload.";
  max-width: 4000px;
  max-height: 200px;
  line-height: 26px;
  text-transform: none;
}

.text-NLHgOm h4 {
  font-size: 18px;
  text-shadow: 0 0 6px var(--Text-Shadow-Colour), 0 0 6px var(--Text-Shadow-Colour), 0 0 5px var(--Text-Shadow-Colour), 0 0 4px var(--Text-Shadow-Colour);
}

.theme_dark-2FtE3l .note-3vX6oT {
  display: none;
}

.theme_dark-2FtE3l, .themeDark-3Ap_7i {
  background-color: var(--Background-Colour);
  background-image: url(https://media.giphy.com/media/XMc1Ui9rAFR1m/source.gif);
  color: var(--Main-Colour);
}

.themeDark-3Ap_7i .image-3zK3Wt {
  display: none;
}

.text-NLHgOm, .themeDark-3Ap_7i .note-3vX6oT {
  color: var(--Main-Colour);
}

.theme_dark-2FtE3l {
  background-color: var(--Background-Colour);
  background-image: url(https://media.giphy.com/media/XMc1Ui9rAFR1m/source.gif);
  color: var(--Main-Colour);
}

.theme_dark-2FtE3l .image-3zK3Wt {
  display: none;
}

.wordmark-2iDDfm:after {
  content: var(--Theme-Variant) ", " var(--Update-Text);
  color: Var(--Main-Colour) !important;
  font-size: 13px;
  font-weight: 700;
  position: absolute;
  width: 4000px;
  top: 5px;
  padding-left: 3px;
}

.wordmark-2iDDfm {
  animation: TextScroll 60s infinite linear;
}

.typeMacOS-3EmCyP:after {
  content: var(--Theme-Variant) ", " var(--Update-Text);
  color: Var(--Main-Colour) !important;
  font-size: 13px;
  font-weight: 700;
  position: absolute;
  width: 4000px;
  top: 1px;
  padding-left: 125%;
}

.theme-dark .iconForeground-2c7s3m, .theme-dark .title-1aVOXw, .theme-dark [class*='activityFeed-'], .theme-dark .body-2WmNzl, .theme-dark .activity-3tgXuD {
  background: transparent;
  color: var(--Main-Colour);
  border-color: var(--Secondary-Main-Colour);
}

.splashArt-2R_m_a {
  -webkit-filter: grayscale(0%)!important;
  -webkit-mask: none!important;
  filter: grayscale(0%)!important;
  mask: none!important;
}

.form.deprecated .control-group input[type=email], .form.deprecated .control-group input[type=number], .form.deprecated .control-group input[type=password], .form.deprecated .control-group input[type=text], .form.deprecated .control-group textarea {
  background: var(--Background-Colour);
  border: 1px solid var(--Secondary-Main-Colour);
  border-bottom: 1px solid var(--Secondary-Main-Colour);
  color: var(--Main-Colour)!important;
}

.avatar-profile .status {
  width: 600%;
  height: 10%;
  -webkit-box-sizing: border-box;
  box-sizing: border-box;
  border: none;
  border-radius: 5px;
  top: -31%;
  left: -100%;
  animation: pulse 3s infinite linear;
  opacity: 0.5!important;
}

.userPopout-4pfA0d .status-oxiHuE {
  width: 150%!important;
  height: 5px!important;
  top: -7%;
  left: -20%;
  border-radius: 0px!important;
  border-color: transparent!important;
  animation: pulse 3s infinite linear;
  opacity: 0.5!important;
}

#user-profile-modal .scroller-2TZvBN .section .connected-accounts .connected-account, #user-profile-modal .scroller-2TZvBN .section+.section {
  border: none!important;
}

#user-profile-modal .scroller-2TZvBN .guild:hover {
  background: transparent;
  border: none;
}

/* Tac Nuke */

.updateIconForeground-3tnNZn {
  fill: transparent !important;
}

svg[name="Nova_Download"]{
  background: url(https://nfld99.com/Bkg/80u9AQy.gif) 50% 50%/cover;
}

/* Tac Nuke */


.tooltips {
  left: 0;
  position: absolute;
  right: 0;
  top: -1%!important;
  z-index: auto;
}

.popout-menu .popout-menu-item:hover {
  background: linear-gradient(to top, var(--Main-Colour), var(--Background-Colour), var(--Background-Colour), var(--Main-Colour)) !important;
  opacity: 1;
  color: var(--Main-Colour);
}

.popout-menu .popout-menu-separator {
  -webkit-box-sizing: border-box;
  border: 1px solid var(--Background-Colour);
  box-sizing: border-box;
}

.popout-menu .popout-menu-item {
  background-color: var(--Background-Colour) !important;
  color: var(--Secondary-Main-Colour);
}

.popout-menu {
  background: transparent;
  border-radius: 5px;
  overflow: hidden;
  width: 216px;
}

.status-picker .popout-menu-item .helper {
  display: none;
}

.theme-dark .wrapper-35wsBm {
  background: rgba(47, 49, 54, .0);
  border-color: var(--Main-Colour);
}

.theme-dark .buttonPrimaryOutlinedDefault--H0hhk, .theme-dark .buttonPrimaryOutlinedSubmitting-3m3eFx {
  border-color: var(--Main-Colour);
  color: var(--Main-Colour);
}

.onlineCount-w6_WmG, .theme-dark .guildName-2hvnt_ {
  color: var(--Main-Colour);
}

#app-mount>div.app-19_DXt.platform-win>div.app.flex-vertical.theme-dark>div.layers.flex-vertical.flex-spacer>div>div>div.flex-1xMQg5.flex-1O1GKY.vertical-V37hAW.flex-1O1GKY.directionColumn-35P_nr.justifyStart-2NDFzi.alignStretch-DpGPf3.noWrap-3jynv6.base-3dtUhz>div.flex-1xMQg5.flex-1O1GKY.horizontal-1ae9ci.horizontal-2EEEnY.flex-1O1GKY.directionRow-3v3tfG.justifyStart-2NDFzi.alignStretch-DpGPf3.noWrap-3jynv6.spacer-29U_x8>div.chat.flex-vertical.flex-spacer>div.content.flex-spacer.flex-horizontal>div.flex-spacer.flex-vertical>div.messagesWrapper-3lZDfY>div>div>div.message-group.hide-overflow>div.comment>div>div.accessory>div>div>div.flex-1xMQg5.flex-1O1GKY.vertical-V37hAW.flex-1O1GKY.directionColumn-35P_nr.justifyCenter-3D2jYp.alignStretch-DpGPf3.noWrap-3jynv6.guildInfo-1STtYi>div.guildDetail-1nRKNE.small-29zrCQ.size12-3R0845.height16-2Lv3qA.weightSemiBold-NJexzi>div>span:nth-child(4) {
  color: var(--Secondary-Main-Colour);
}

#app-mount>div.app-19_DXt.platform-win>div.app.flex-vertical.theme-dark>div.layers.flex-vertical.flex-spacer>div>div>div.flex-1xMQg5.flex-1O1GKY.vertical-V37hAW.flex-1O1GKY.directionColumn-35P_nr.justifyStart-2NDFzi.alignStretch-DpGPf3.noWrap-3jynv6.base-3dtUhz>div.flex-1xMQg5.flex-1O1GKY.horizontal-1ae9ci.horizontal-2EEEnY.flex-1O1GKY.directionRow-3v3tfG.justifyStart-2NDFzi.alignStretch-DpGPf3.noWrap-3jynv6.spacer-29U_x8>div.chat.flex-vertical.flex-spacer>div.content.flex-spacer.flex-horizontal>div.flex-spacer.flex-vertical>div.messagesWrapper-3lZDfY>div>div>div.message-group.hide-overflow>div.comment>div>div.accessory>div>div>div.flex-1xMQg5.flex-1O1GKY.vertical-V37hAW.flex-1O1GKY.directionColumn-35P_nr.justifyCenter-3D2jYp.alignStretch-DpGPf3.noWrap-3jynv6.guildInfo-1STtYi>div.guildDetail-1nRKNE.small-29zrCQ.size12-3R0845.height16-2Lv3qA.weightSemiBold-NJexzi>div>span:nth-child(4):before {
  color: var(--Secondary-Main-Colour);
  content: " Out  Of  "
}

.statusOffline-37RKt7 {
  background-color: transparent;
  display: none;
}

.upload-modal .inner .file .icon.image {
  -webkit-box-shadow: 0 2px 8px rgba(0, 0, 0, .4);
  -webkit-box-sizing: border-box;
  box-sizing: border-box;
  background-color: transparent;
  background-size: contain;
  border: none;
  border-radius: 8px;
  box-shadow: 0 2px 8px rgba(0, 0, 0, .4);
  top: 32%;
  left: -3%;
  width: 100%;
}

.upload-modal .inner {
  -ms-flex: 1;
  -webkit-box-flex: 1;
  border: none;
  border-radius: 0 0 0 0;
  color: var(--Secondary-Main-Colour);
  flex: 1;
  margin: 0;
}

.button {
  background: transparent!important;
  border: 1px solid Var(--Secondary-Main-Colour)!important;
  border-radius: 3px!important;
  color: Var(--Secondary-Main-Colour)!important;
}

.button:hover {
  background: transparent!important;
  border: 1px solid Var(--Main-Colour);
  border-radius: 3px;
  color: Var(--Main-Colour)!important;
}

/* New UserPopouts */

.userPopout-4pfA0d .avatar-16XVId {
  background-clip: padding-box!important;
  position: relative!important;
  background: 50% 50%/cover!important;
  border-radius: 10px!important;
  -ms-flex-negative: 0!important;
  flex-shrink: 0!important;
  width: 200px!important;
  height: 200px!important;
  border: none!important;
}

.popout-2fzvxG {
  height: 150px;
  width: 150px;
}

.avatarHint-2i5XWK {
  position: absolute!important;
  top: 0!important;
  left: 0!important;
  bottom: 0!important;
  right: 0!important;
  z-index: 2!important;
  border-radius: 5%!important;
  -webkit-box-shadow: inset 0 0 120px rgba(0, 0, 0, .75)!important;
  box-shadow: inset 0 0 120px rgba(0, 0, 0, .75)!important;
  font-weight: 700!important;
  font-size: 10px!important;
  line-height: 12px!important;
  text-transform: uppercase!important;
  margin: 3px!important;
  opacity: 0!important;
  -webkit-transition: opacity .1s ease!important;
  transition: opacity .1s ease!important;
}

.userPopout-4pfA0d .footer-2J5zqP, .emptyIconFriends-2q_v-C, #user-profile-modal .empty .empty-icon-friends {
  display: none !important;
}

.emptyText-6tYmO5:after, #user-profile-modal .empty .empty-text:after {
  content: ". You Should Get Out More.";
  max-width: 4000px;
  max-height: 200px;
  line-height: 26px;
  text-transform: none;
  color: var(--Popout-Main-Colour)!important;
}

.mask-3OgeRz {
  border-radius: 0!important;
  -webkit-mask: none!important;
  mask: none!important;
}

.avatar-16XVId.avatar-1jmnc-.popout-2fzvxG, .connectedAccountIcon-2nYV8J, .activity-AFBUEw, .headerPlaying-2eYqm9, .topSectionPlaying-1J5E4n, .headerStreaming-3F-wjT, .topSectionStreaming-1Tpf5X {
  border: none!important;
  background-color: rgba(255, 255, 255, 0) !important;
}

.userPopout-4pfA0d .status-oxiHuE {
  width: 150%!important;
  height: 5%!important;
  top: -7%!important;
  left: -20%!important;
  border-radius: 0px!important;
  border-color: transparent!important;
  animation: pulse 3s infinite linear!important;
  opacity: 0.5!important;
}

#user-profile-modal .scroller-2TZvBN .container-1ETFDs.status, .listAvatarStatus-1Egz5B {
  width: 10%!important;
  height: 100%!important;
  top: -6%!important;
  left: -22%!important;
  border-radius: 0px!important;
  border-color: transparent!important;
  animation: pulse 3s infinite linear!important;
  opacity: 6!important;
}

#user-profile-modal .scroller-2TZvBN .guild:hover, #user-profile-modal .scroller-2TZvBN .section .connected-accounts .connected-account, #user-profile-modal .scroller-2TZvBN .section+.section, #user-profile-modal .avatarWrapper-2Gfmp1, #user-profile-modal .scroller, #user-profile-modal .avatar-wrapper, #user-profile-modal .empty, #user-profile-modal .tab-bar-container, #user-profile-modal .header:after, .userPopout-4pfA0d .body-3rkFrF, .headerNormal-1cioxU, .footer-2J5zqP, .quick-message, #user-profile-modal .header, .userPopout-4pfA0d, .topSectionNormal-2LlRG1, .theme-dark .body-3ND3kc {
  background: transparent!important;
  border: none!important;
}

.avatar-profile, .inner-1JeGVc {
  border-radius: 0!important;
}

#user-profile-modal .header .header-info .header-info-inner .discord-tag, #user-profile-modal .header .header-info .header-info-inner .discord-tag .discriminator, #user-profile-modal .tab-bar .tab-bar-item.selected, #user-profile-modal .tab-bar .tab-bar-item, #user-profile-modal .scroller-2TZvBN .section .section-header, .note textarea, #user-profile-modal .scroller-2TZvBN .section .connected-accounts .connected-account .connected-account-name-inner .connected-account-name, #user-profile-modal .scroller-2TZvBN .guild, #user-profile-modal .scroller-2TZvBN .container-1ETFDs.guild-nick, .headerUsernameNoNickname-1iGxNP, .headerTagNormal-KyD3_J, .headerActivityText-3qBQRo, .bodyTitleText-hSiL7d, #user-profile-modal .header .header-info .header-info-inner .activity, .discriminator-xUhQkU, .username-3gJmXY, .tab-bar.tabBar-2MuP6- .tabBarItem-1b8RUP.selected, .tab-bar.tabBar-2MuP6- .tabBarItem-1b8RUP, .userInfoSectionHeader-CBvMDh, .connectedAccountName-3EFj01, .theme-dark .listRow-hutiT_, .headerName-2N8Pdz, .headerTagUsernameNoNickname-1gGsAP, .headerTag-3zin_i, .theme-dark .activityProfile-2pymp0 .headerText-1HLrL7, .theme-dark .activityUserPopout-1nmgaw .headerText-1HLrL7, .theme-light .activityProfile-2pymp0 .headerText-1HLrL7, .theme-light .activityUserPopout-1nmgaw .headerText-1HLrL7, .theme-dark .activityProfile-2pymp0 .content-3JfFJh, .theme-dark .activityProfile-2pymp0 .details-vSFjFG, .theme-dark .activityProfile-2pymp0 .name-8onsv0, .theme-dark .activityUserPopout-1nmgaw .content-3JfFJh, .theme-dark .activityUserPopout-1nmgaw .details-vSFjFG, .theme-dark .activityUserPopout-1nmgaw .name-8onsv0, .theme-light .activityProfile-2pymp0 .content-3JfFJh, .theme-light .activityProfile-2pymp0 .details-vSFjFG, .theme-light .activityProfile-2pymp0 .name-8onsv0, .theme-light .activityUserPopout-1nmgaw .content-3JfFJh, .theme-light .activityUserPopout-1nmgaw .details-vSFjFG, .theme-light .activityUserPopout-1nmgaw .name-8onsv0, .emptyText-6tYmO5, #user-profile-modal .empty .empty-text {
  color: var(--Popout-Main-Colour)!important;
}

.avatarHint-2i5XWK {
  border-radius: 0!important;
  width: 100%!important;
  height: 100%!important;
  top: -1.5%!important;
  left: -1.5%!important;
}

#user-profile-modal, .userPopout-4pfA0d, .inner-1JeGVc {
  background: var(--Popout-Background)50% 50%/cover!important;
  text-shadow: 0 0 6px var(--Popout-Text-Shadow-Colour), 0 0 6px var(--Popout-Text-Shadow-Colour), 0 0 5px var(--Popout-Text-Shadow-Colour), 0 0 4px var(--Popout-Text-Shadow-Colour)!important;
}

.member-roles .member-role {
  background-color: rgba(243, 243, 243, 0);
  border: 1px solid #dbdde1;
  border-radius: 3px;
  color: var(--Popout-Main-Colour);
}

.avatar-profile .status, .statusProfile-3ynqtt {
  width: 766%!important;
  height: 10%!important;
  -webkit-box-sizing: border-box!important;
  box-sizing: border-box!important;
  border: none!important;
  border-radius: 0px!important;
  top: -20%!important;
  animation: pulse 3s infinite linear!important;
  opacity: 0.5!important;
  left: -100%!important;
}

.theme-dark .headerNormal-T_seeN {
  background-color: transparent;
}

.header-2BwW8b {
  color: var(--Popout-Main-Colour);
  line-height: 20px;
}

.theme-dark .body-3iLsc4, .theme-dark .footer-1fjuF6 {
  background-color: transparent;
  color: var(--Popout-Main-Colour);
}

.userPopout-3XzG_A {
  background: var(--Popout-Background) 50% 50%/cover;
  border: 1px solid var(--Secondary-Main-Colour);
}

.headerName-fajvi9, .headerTagUsernameNoNickname-2_H881, .headerTag-2pZJzA, .bodyTitle-Y0qMQz, .theme-dark .note-3kmerW textarea {
  color: var(--Popout-Main-Colour)!important;
}

.theme-dark .note-3kmerW textarea:focus {
  background-color: var(--Secondary-Background-Colour);
}

.headerSpotify-zpWxgT, .headerPlaying-j0WQBV, .headerStreaming-2FjmGz, .lookGhost-2Fn_0-.colorGrey-4JijJ1:active, .lookGhost-2Fn_0-.colorBrand-3PmwCE {
  background: transparent;
}

.lookOutlined-3sRXeN.colorWhite-rEQuAQ:hover, .lookGhost-2Fn_0-.colorGrey-4JijJ1:active {
  border-color: var(--Secondary-Main-Colour);
  color: var(--Secondary-Main-Colour);
}

.lookOutlined-3sRXeN.colorWhite-rEQuAQ:hover:hover, .lookGhost-2Fn_0-.colorBrand-3PmwCE {
  border-color: var(--Main-Colour);
  color: var(--Main-Colour);
}

#app-mount>div.app-19_DXt.platform-win>div>div.layers-3iHuyZ.flex-vertical.flex-spacer>div:nth-child(2)>div>div.content-region>div.notice-region>div, .regionSelect-3lf4eE:hover button {
  background: transparent!important;
}

.theme-dark .elevationHigh-1PneE4 {
  box-shadow: none;
}

.theme-dark .message-c9-HCF, #app-mount>div.app-19_DXt.platform-win>div>div.layers-3iHuyZ.flex-vertical.flex-spacer>div:nth-child(2)>div>div.content-region>div.notice-region>div>div>div.flex-1xMQg5.flex-1O1GKY.horizontal-1ae9ci.horizontal-2EEEnY.flex-1O1GKY.directionRow-3v3tfG.justifyEnd-2E6vba.alignStretch-DpGPf3.noWrap-3jynv6>button.resetButton-1zF_G8.button-1x2ahC.lookFilled-1Gx00P.colorBrand-3pXr91.lookLink-3VWONr.colorPrimary-2KuK5O.sizeSmall-2cSMqn.grow-25YQ8u>div>span, .regionSelect-3lf4eE button, .create-guild-container.deprecated h5 {
  color: var(--Main-Colour)!important;
}

.form-inner p {
  color: var(--Secondary-Main-Colour)!important;
}

.form-deprecated .form-actions, .form.deprecated .form-actions {
  border-top-color: var(--M-Color);
}

.regionSelect-3lf4eE .regionSelectInner-1cIYbU, .regionSelect-3lf4eE button {
  border-color: var(--Secondary-Main-Colour);
}

.regionSelect-3lf4eE:hover .regionSelectInner-1cIYbU, .regionSelect-3lf4eE:hover button {
  border-color: var(--Main-Colour);
}

.need-help-modal.deprecated .header input[type=text] {
  box-shadow: none;
}

.form-deprecated .control-group input[type=email]:focus, .form-deprecated .control-group input[type=number]:focus, .form-deprecated .control-group input[type=password]:focus, .form-deprecated .control-group input[type=text]:focus, .form-deprecated .control-group textarea:focus, .form.deprecated .control-group input[type=email]:focus, .form.deprecated .control-group input[type=number]:focus, .form.deprecated .control-group input[type=password]:focus, .form.deprecated .control-group input[type=text]:focus, .form.deprecated .control-group textarea:focus {
  border-bottom-color: var(--Main-Colour);
}

/* New UserPopouts */

::selection {
  background: var(--Secondary-Main-Colour)!important;
}

.wrapper-1Rf91z .scroller-2TZvBN .guildSeparator-3s64Iy {
  margin-top: 10px;
}

.theme-dark .attachButtonPlus-rUdX-B {
  fill: var(--Secondary-Main-Colour);
}

.spriteNormal-1wvG5n {
  -webkit-filter: grayscale(50%);
  filter: grayscale(50%);
  opacity: .5;
}

#app-mount>div.app-19_DXt.platform-win>div.app.flex-vertical.theme-dark>div.layers.flex-vertical.flex-spacer>div>div>div.flex-1xMQg5.flex-1O1GKY.vertical-V37hAW.flex-1O1GKY.directionColumn-35P_nr.justifyStart-2NDFzi.alignStretch-DpGPf3.noWrap-3jynv6.base-3dtUhz>div.flex-1xMQg5.flex-1O1GKY.horizontal-1ae9ci.horizontal-2EEEnY.flex-1O1GKY.directionRow-3v3tfG.justifyStart-2NDFzi.alignStretch-DpGPf3.noWrap-3jynv6.spacer-29U_x8>div.channels-Ie2l6A.vertical-V37hAW.flex-1O1GKY.directionColumn-35P_nr>div.container-2Thooq>div.flex-1xMQg5.flex-1O1GKY.horizontal-1ae9ci.horizontal-2EEEnY.flex-1O1GKY.directionRow-3v3tfG.justifyStart-2NDFzi.alignStretch-DpGPf3.noWrap-3jynv6>div.button-2b6hmh>svg>path {
  display: none;
}

.member-roles .member-role {
  background-color: rgba(243, 243, 243, 0);
  border: 1px solid #dbdde1;
  border-radius: 3px;
  color: var(--Main-Colour);
}

.container-16j22k {
  background: var(--Chat-Background) 50% 50%/cover !important;
}

#app-mount>div.typeWindows-1za-n7.titleBar-AC4pGV.horizontalReverse-3tRjY7.flex-1O1GKY.directionRowReverse-m8IjIq.justifyStart-2NDFzi.alignStretch-DpGPf3>div:nth-child(4)>svg, #app-mount>div.typeWindows-1za-n7.titleBar-AC4pGV.horizontalReverse-3tRjY7.flex-1O1GKY.directionRowReverse-m8IjIq.justifyStart-2NDFzi.alignStretch-DpGPf3>div.winButtonClose-1HsbF-.winButton-iRh8-Z.center-1MLNrE.flex-1O1GKY.justifyCenter-3D2jYp.alignCenter-1dQNNs>svg>polygon, #app-mount>div.app-19_DXt.platform-win>div.app.flex-vertical.theme-dark>div.layers.flex-vertical.flex-spacer>div>div>div.flex-1xMQg5.flex-1O1GKY.vertical-V37hAW.flex-1O1GKY.directionColumn-35P_nr.justifyStart-2NDFzi.alignStretch-DpGPf3.noWrap-3jynv6.base-3dtUhz>div.flex-1xMQg5.flex-1O1GKY.horizontal-1ae9ci.horizontal-2EEEnY.flex-1O1GKY.directionRow-3v3tfG.justifyStart-2NDFzi.alignStretch-DpGPf3.noWrap-3jynv6.spacer-29U_x8>div.chat.flex-vertical.flex-spacer>div.titleWrapper-1l0xT9.theme-dark>div>div.flex-1xMQg5.flex-1O1GKY.horizontal-1ae9ci.horizontal-2EEEnY.flex-1O1GKY.directionRow-3v3tfG.justifyStart-2NDFzi.alignCenter-1dQNNs.noWrap-3jynv6>svg:nth-child(1)>g>path, #app-mount>div.app-19_DXt.platform-win>div.app.flex-vertical.theme-dark>div.layers.flex-vertical.flex-spacer>div>div>div.flex-1xMQg5.flex-1O1GKY.vertical-V37hAW.flex-1O1GKY.directionColumn-35P_nr.justifyStart-2NDFzi.alignStretch-DpGPf3.noWrap-3jynv6.base-3dtUhz>div.flex-1xMQg5.flex-1O1GKY.horizontal-1ae9ci.horizontal-2EEEnY.flex-1O1GKY.directionRow-3v3tfG.justifyStart-2NDFzi.alignStretch-DpGPf3.noWrap-3jynv6.spacer-29U_x8>div.chat.flex-vertical.flex-spacer>div.titleWrapper-1l0xT9.theme-dark>div>div.flex-1xMQg5.flex-1O1GKY.horizontal-1ae9ci.horizontal-2EEEnY.flex-1O1GKY.directionRow-3v3tfG.justifyStart-2NDFzi.alignCenter-1dQNNs.noWrap-3jynv6>svg:nth-child(2)>g>path.iconForeground-2c7s3m, #app-mount>div.app-19_DXt.platform-win>div.app.flex-vertical.theme-dark>div.layers.flex-vertical.flex-spacer>div>div>div.flex-1xMQg5.flex-1O1GKY.vertical-V37hAW.flex-1O1GKY.directionColumn-35P_nr.justifyStart-2NDFzi.alignStretch-DpGPf3.noWrap-3jynv6.base-3dtUhz>div.flex-1xMQg5.flex-1O1GKY.horizontal-1ae9ci.horizontal-2EEEnY.flex-1O1GKY.directionRow-3v3tfG.justifyStart-2NDFzi.alignStretch-DpGPf3.noWrap-3jynv6.spacer-29U_x8>div.chat.flex-vertical.flex-spacer>div.titleWrapper-1l0xT9.theme-dark>div>div.flex-1xMQg5.flex-1O1GKY.horizontal-1ae9ci.horizontal-2EEEnY.flex-1O1GKY.directionRow-3v3tfG.justifyStart-2NDFzi.alignCenter-1dQNNs.noWrap-3jynv6>svg.iconActive-AKd_jq.icon-1R19_H.iconMargin-2YXk4F>g>path, #app-mount>div.app-19_DXt.platform-win>div.app.flex-vertical.theme-dark>div.layers.flex-vertical.flex-spacer>div>div>div.flex-1xMQg5.flex-1O1GKY.vertical-V37hAW.flex-1O1GKY.directionColumn-35P_nr.justifyStart-2NDFzi.alignStretch-DpGPf3.noWrap-3jynv6.base-3dtUhz>div.flex-1xMQg5.flex-1O1GKY.horizontal-1ae9ci.horizontal-2EEEnY.flex-1O1GKY.directionRow-3v3tfG.justifyStart-2NDFzi.alignStretch-DpGPf3.noWrap-3jynv6.spacer-29U_x8>div.chat.flex-vertical.flex-spacer>div.titleWrapper-1l0xT9.theme-dark>div>div.flex-1xMQg5.flex-1O1GKY.horizontal-1ae9ci.horizontal-2EEEnY.flex-1O1GKY.directionRow-3v3tfG.justifyStart-2NDFzi.alignCenter-1dQNNs.noWrap-3jynv6>svg:nth-child(6)>path, #app-mount>div.app-19_DXt.platform-win>div.app.flex-vertical.theme-dark>div.layers.flex-vertical.flex-spacer>div>div>div.flex-1xMQg5.flex-1O1GKY.vertical-V37hAW.flex-1O1GKY.directionColumn-35P_nr.justifyStart-2NDFzi.alignStretch-DpGPf3.noWrap-3jynv6.base-3dtUhz>div.flex-1xMQg5.flex-1O1GKY.horizontal-1ae9ci.horizontal-2EEEnY.flex-1O1GKY.directionRow-3v3tfG.justifyStart-2NDFzi.alignStretch-DpGPf3.noWrap-3jynv6.spacer-29U_x8>div.chat.flex-vertical.flex-spacer>div.titleWrapper-1l0xT9.theme-dark>div>div.flex-1xMQg5.flex-1O1GKY.horizontal-1ae9ci.horizontal-2EEEnY.flex-1O1GKY.directionRow-3v3tfG.justifyStart-2NDFzi.alignCenter-1dQNNs.noWrap-3jynv6>svg:nth-child(7)>g, .foreground-2W-aJk, #app-mount>div.app-19_DXt.platform-win>div.app.flex-vertical.theme-dark>div.layers.flex-vertical.flex-spacer>div>div>div.flex-1xMQg5.flex-1O1GKY.vertical-V37hAW.flex-1O1GKY.directionColumn-35P_nr.justifyStart-2NDFzi.alignStretch-DpGPf3.noWrap-3jynv6.base-3dtUhz>div.flex-1xMQg5.flex-1O1GKY.horizontal-1ae9ci.horizontal-2EEEnY.flex-1O1GKY.directionRow-3v3tfG.justifyStart-2NDFzi.alignStretch-DpGPf3.noWrap-3jynv6.spacer-29U_x8>div.chat.flex-vertical.flex-spacer>div.titleWrapper-1l0xT9.theme-dark>div>div.titleText-3X-zRE>span>svg>path, #app-mount>div.app-19_DXt.platform-win>div.app.flex-vertical.theme-dark>div.layers.flex-vertical.flex-spacer>div>div>div.flex-1xMQg5.flex-1O1GKY.vertical-V37hAW.flex-1O1GKY.directionColumn-35P_nr.justifyStart-2NDFzi.alignStretch-DpGPf3.noWrap-3jynv6.base-3dtUhz>div.flex-1xMQg5.flex-1O1GKY.horizontal-1ae9ci.horizontal-2EEEnY.flex-1O1GKY.directionRow-3v3tfG.justifyStart-2NDFzi.alignStretch-DpGPf3.noWrap-3jynv6.spacer-29U_x8>div.channels-Ie2l6A.vertical-V37hAW.flex-1O1GKY.directionColumn-35P_nr>div.flex-1xMQg5.flex-1O1GKY.vertical-V37hAW.flex-1O1GKY.directionColumn-35P_nr.justifyStart-2NDFzi.alignStretch-DpGPf3.noWrap-3jynv6.container-PNkimc>div.scrollerWrap-2lJEkd.scrollerThemed-19vinI.themeGhostHairlineChannels-2lQojW.scrollerFade-28dRsO>div>div.container-5>div:nth-child(3)>div>div>div:nth-child(1)>svg>path.background-2OVjk_, #app-mount>div.theme-dark.popouts>div>div>div.body-3rkFrF>div:nth-child(1)>svg>path, #app-mount>div.theme-dark.popouts>div>div>div.body-3rkFrF>div:nth-child(3)>svg>path {
  fill: var(--Secondary-Main-Colour) !important;
}

#app-mount>div.typeWindows-1za-n7.titleBar-AC4pGV.horizontalReverse-3tRjY7.flex-1O1GKY.directionRowReverse-m8IjIq.justifyStart-2NDFzi.alignStretch-DpGPf3>div:nth-child(3)>svg>rect, #app-mount>div.app-19_DXt.platform-win>div.app.flex-vertical.theme-dark>div.layers.flex-vertical.flex-spacer>div>div>div.flex-1xMQg5.flex-1O1GKY.vertical-V37hAW.flex-1O1GKY.directionColumn-35P_nr.justifyStart-2NDFzi.alignStretch-DpGPf3.noWrap-3jynv6.base-3dtUhz>div.flex-1xMQg5.flex-1O1GKY.horizontal-1ae9ci.horizontal-2EEEnY.flex-1O1GKY.directionRow-3v3tfG.justifyStart-2NDFzi.alignStretch-DpGPf3.noWrap-3jynv6.spacer-29U_x8>div.channels-Ie2l6A.vertical-V37hAW.flex-1O1GKY.directionColumn-35P_nr>div.flex-1xMQg5.flex-1O1GKY.vertical-V37hAW.flex-1O1GKY.directionColumn-35P_nr.justifyStart-2NDFzi.alignStretch-DpGPf3.noWrap-3jynv6.container-PNkimc>div.flexChild-1KGW5q>div>header>svg>g>path:nth-child(2), #app-mount>div.app-19_DXt.platform-win>div.app.flex-vertical.theme-dark>div.layers.flex-vertical.flex-spacer>div>div>div.flex-1xMQg5.flex-1O1GKY.vertical-V37hAW.flex-1O1GKY.directionColumn-35P_nr.justifyStart-2NDFzi.alignStretch-DpGPf3.noWrap-3jynv6.base-3dtUhz>div.flex-1xMQg5.flex-1O1GKY.horizontal-1ae9ci.horizontal-2EEEnY.flex-1O1GKY.directionRow-3v3tfG.justifyStart-2NDFzi.alignStretch-DpGPf3.noWrap-3jynv6.spacer-29U_x8>div.channels-Ie2l6A.vertical-V37hAW.flex-1O1GKY.directionColumn-35P_nr>div.flex-1xMQg5.flex-1O1GKY.vertical-V37hAW.flex-1O1GKY.directionColumn-35P_nr.justifyStart-2NDFzi.alignStretch-DpGPf3.noWrap-3jynv6.container-PNkimc>div.flexChild-1KGW5q>div>header>svg>g>path:nth-child(3) {
  stroke: var(--Secondary-Main-Colour) !important;
}

* svg>path, * svg>polygon, .theme-dark .foreground-26ym5y {
  fill: var(--Secondary-Main-Colour) !important;
}

.winButtonClose-1HsbF-:hover {
  background: transparent!important;
}

.popout-menu-icon {
  display: none;
}

.iconCollapsed-1INdMX, .iconDefault-xzclSQ, .nameCollapsed-3_ChMu, .nameDefault-Lnjrwm {
  color: var(--Secondary-Main-Colour);
}

.iconHovered-3PRzOR, .iconHoveredCollapsed-jNYgOD, .nameHovered-1YFSWq, .nameHoveredCollapsed-2c-EHI {
  color: var(--Main-Colour);
}

.tab-bar.TOP .tab-bar-item:hover {
  border-bottom: 2px solid var(--Secondary-Main-Colour);
}

.nameMutedText-1YDcP-, .nameMutedVoice-26k4cP, .iconMuted-Hb4ttQ, .nameMuted-1n0LSj {
  opacity: .5!important;
  color: var(--Main-Colour);
}

.theme-dark .iconForeground-2c7s3m, .theme-dark .title-1aVOXw {
  color: var(--Secondary-Main-Colour);
}

#autocomplete-popout .row.selected, #autocomplete-popout .row:hover {
  background: -webkit-gradient(linear, left top, right top, from(#000), to(#000));
  background: linear-gradient(90deg, #000, #000);
  border-radius: 5px;
  border: .02px solid var(--Main-Colour);
}

.avatar-large+.comment .timestamp {
  text-shadow: 0 0 2px var(--Text-Shadow-Colour), 0 0 6px var(--Text-Shadow-Colour), 0 0 5px var(--Text-Shadow-Colour), 0 0 4px var(--Text-Shadow-Colour);
  color: var(--Main-Colour) !important;
  font-size: 13px;
}

.chat .new-messages-bar, div[class*=" unreadBar-"], .mention-1f5kbO, .theme-dark .chat .jump-to-present-bar, .channels-wrap>div:last-child:hover>div:last-child:hover {
  background: linear-gradient(to right, var(--Background-Colour), var(--Secondary-Main-Colour), var(--Secondary-Main-Colour), var(--Background-Colour)) !important;
  color: var(--Background-Colour) !important;
}

.invite-modal .scroller, .invite-modal .invite-body {
  background: transparent;
  color: var(--Main-Colour);
}

.invite-modal .invite-splash {
  display: none;
}

.theme-dark .body-SKIE6r {
  background-color: var(--Secondary-Background-Colour)!important;
}

.theme-dark .gameName-Ivkyss, .theme-dark .sectionTitle-le2fuz, .theme-dark .username-1cRqpK, .theme-dark .activityActivityFeed-2gIGSa .content-3JfFJh, .theme-dark .activityActivityFeed-3xysim .details-38sfDr, .theme-dark .description-12ntlD, .theme-dark .title-bYqmgP, .theme-dark .gameName-ZXDRa6 {
  color: var(--Main-Colour);
}

.theme-dark .discriminator-20nIyt, .theme-dark .playTime-2KDQrS, .theme-dark .voiceChannelIcon-Ac0fPK, .theme-dark .discriminator-1Kma2g, .theme-dark .playTime-2SuPqW, .theme-dark .icon-2oIyBi {
  color: var(--Secondary-Main-Colour)!important;
}

.tabBarContainer-1s1u-z, .theme-dark .userInfoSection-2acyCx+.userInfoSection-2acyCx {
  border-color: rgba(0, 0, 0, 0);
}

#user-profile-modal, .userPopout-4pfA0d, .inner-1JeGVc {
  border: .5px solid Black;
  border-radius: 5px!important;
}

.roleName-32vpEy {
  color: var(--Popout-Main-Colour);
}

.roleCircle-3xAZ1j {
  display: none;
}

.role-2irmRk {
  border: 2px solid;
}

.hljs {
  white-space: pre-wrap !important;
}

.message-group .message .markup-2BOw-j a[href="https://t.co/fERO36wNAg?amp=1"], .markup-2BOw-j>a[href="https://t.co/fERO36wNAg?amp=1"] {
  font-size: 0;
}

.message-group .message .markup-2BOw-j a[href="https://t.co/fERO36wNAg?amp=1"]:after, .markup-2BOw-j>a[href="https://t.co/fERO36wNAg?amp=1"]:after {
  content: "Net Neutrality Battle";
  color: var(--Main-Colour);
  font-size: 15px;
}

.message-group .message .markup-2BOw-j a[href="https://youtu.be/MGu8zOvITb8"], .markup-2BOw-j>a[href="https://youtu.be/MGu8zOvITb8"] {
  font-size: 0;
}

.message-group .message .markup-2BOw-j a[href="https://youtu.be/MGu8zOvITb8"]:after, .markup-2BOw-j>a[href="https://youtu.be/MGu8zOvITb8"]:after {
  content: "How To Use Font Nano Theme ";
  font-size: 15px;
  color: var(--Main-Colour);
}

.message-group .message .markup-2BOw-j a[href*="https://github.com/0mniscient"], .markup-2BOw-j>a[href*="https://github.com/0mniscient"] {
  font-size: 0;
}

.message-group .message .markup-2BOw-j a[href*="https://github.com/0mniscient"]:after, .markup-2BOw-j>a[href*="https://github.com/0mniscient"]:after {
  content: "Banned Github";
  color: rgba(255, 65, 85, 1);
  font-size: 15px;
}

.message-group .message .markup-2BOw-j a[href*="https://gyazo.com"], .markup-2BOw-j>a[href*="https://gyazo.com"] {
  font-size: 0;
}

.message-group .message .markup-2BOw-j a[href*="https://gyazo.com"]:after, .markup-2BOw-j>a[href*="https://gyazo.com"]:after {
  content: " This website is not supported by anyone who like previews.";
  font-size: 15px;
  animation: Links 2s infinite linear;
}

.theme-dark .noChannel-Z1DQK7 {
  background: transparent!important;
}

.theme-dark .headerNormal-1cioxU .creationDate, .theme-dark .topSectionNormal-2-vo2m .creationDate, .theme-light [class*='topSection']:not(.topSectionNormal-2-vo2m) .creationDate, .theme-dark [class*='topSection'] .creationDate, .theme-light .header-2BwW8b:not(.headerNormal-T_seeN) .creationDate, .theme-dark .header-2BwW8b .creationDate {
  color: var(--Popout-Main-Colour);
  text-shadow: 0 0 6px var(--Popout-Text-Shadow-Colour), 0 0 6px var(--Popout-Text-Shadow-Colour), 0 0 5px var(--Popout-Text-Shadow-Colour), 0 0 4px var(--Popout-Text-Shadow-Colour)!important;
}

.theme-dark .card-FDVird:before {
  background-color: Transparent;
  border-color: Var(--Secondary-Main-Colour);
}

.buttonGreyFilled-3qPP_J, .pill-1nbD-Z, .buttonGreenFilled-6QHNrw {
  background-color: Transparent;
  border: 1px solid Var(--Secondary-Main-Colour);
  color: Var(--Secondary-Main-Colour);
}

.pill-1nbD-Z:hover, .buttonGreenFilledDefault-_lLQaz:hover {
  background-color: Transparent;
  border: 1px solid Var(--Main-Colour);
  color: Var(--Main-Colour);
}

.theme-dark .reportButton-3Yuq49 {
  color: Var(--Main-Colour);
}

.theme-dark .max-mvI_jT, .theme-dark .wrapperDefault-NeXRmD, .theme-dark .wrapperFull-2_7g2- {
  background-color: Var(--Background-Colour);
  color: Var(--Main-Colour);
  border: 1px solid Var(--Main-Colour);
}

.theme-dark .max-mvI_jT:before {
  display: none
}

.count-25CzCS {
  -ms-flex: 1 1 auto;
  -webkit-box-flex: 1;
  flex: 1 1 auto;
  padding-right: -4px;
  border-right: 1px solid Var(--Secondary-Main-Colour);
}

.theme-dark .contentLocked-33_aJm, .theme-dark .descriptionColor-2woJAm {
  color: Var(--Secondary-Main-Colour);
}

.emptyUser-3FRJaF {
  background: transparent;
  border-radius: 50%;
  border: 1px solid Var(--Secondary-Main-Colour);
  height: 20px;
  width: 20px;
}

.moreUsers-1s5Her {
  background: transparent;
  color: Var(--Secondary-Main-Colour);
  border: 1px solid Var(--Secondary-Main-Colour);
}

.top-28JiJ- .item-PXvHYJ {
  color: var(--Secondary-Main-Colour) !important;
  background: linear-gradient(to bottom, transparent, var(--Background-Colour), var(--Secondary-Main-Colour)) !important;
}

.theme-dark .top-28JiJ- .itemSelected-1qLhcL {
  border-bottom-color: transparent;
  color: var(--Main-Colour) !important;
  background: linear-gradient(to bottom, transparent, var(--Background-Colour), var(--Main-Colour)) !important;
}

.theme-dark .gameDefault-2SBp6B:focus, .theme-dark .gameDefault-2SBp6B:hover {
  background-color: transparent;
  border-color: var(--Secondary-Main-Colour);
}

.profileBadgePremium-3kZ9Qj {
  background-image: url(https://discordapp.com/assets/386884eecd36164487505ddfbac35a9d.svg);
}

.profileBadgeHypesquad-1YIe7Z {
  background-image: url(https://discordapp.com/assets/17ebd99540a6e983bade13c3afff7946.svg);
}

.profileBadges-2vWUYb {
  animation: PFB 3s 1 ease-in;
}

.status-picker .popout-menu-item {
  margin-left: -20px;
}

*[style*='74822222203584512'] {
  background-image: url(https://cdn.discordapp.com/avatars/74822222203584512/be7bc7f7cd3080b4681e089a612c5b53.webp?size=128) !important;
}

.theme-dark .incoming-call-inner {
  background: var(--Background-Colour);
  border-color: var(--Main-Colour);
  padding: 20px 10px 10px;
}

.incoming-call-inner {
  border: 1px solid;
  border-radius: 5px;
  text-align: center;
}

.embed .embed-thumbnail-gifv:after {
  right: 0px;
  top: -25px;
}

.theme-dark .layers-3iHuyZ {
  background: rgba(0, 0, 0, var(--Background-Darkness)) !important;
}

.theme-dark .layer-3QrUeG {
  background: transparent;
}

#app-mount>div.app-19_DXt.platform-win>div>div.layers-3iHuyZ.flex-vertical.flex-spacer>div>div>div.flex-1xMQg5.flex-1O1GKY.vertical-V37hAW.flex-1O1GKY.directionColumn-35P_nr.justifyStart-2NDFzi.alignStretch-DpGPf3.noWrap-3jynv6.base-3dtUhz>div.flex-1xMQg5.flex-1O1GKY.horizontal-1ae9ci.horizontal-2EEEnY.flex-1O1GKY.directionRow-3v3tfG.justifyStart-2NDFzi.alignStretch-DpGPf3.noWrap-3jynv6.spacer-29U_x8>div.channels-Ie2l6A.vertical-V37hAW.flex-1O1GKY.directionColumn-35P_nr>div.container-2Thooq>div.flex-1xMQg5.flex-1O1GKY.horizontal-1ae9ci.horizontal-2EEEnY.flex-1O1GKY.directionRow-3v3tfG.justifyStart-2NDFzi.alignStretch-DpGPf3.noWrap-3jynv6>div.button-2b6hmh>svg>path {
  display: none;
}

.theme-dark .premium-settings .premium-settings-background {
  background: transparent !important;
}

#app-mount>div.app-19_DXt.platform-win>div>div.layers-3iHuyZ.flex-vertical.flex-spacer>div:nth-child(2)>div>div:nth-child(2)>div>div>div>div.content-column.default>div>div.userSettingsSecurity-1hjwAn.marginTop60-3PGbtK>div>div>div.flex-1xMQg5.flex-1O1GKY.horizontal-1ae9ci.horizontal-2EEEnY.flex-1O1GKY.directionRow-3v3tfG.justifyStart-2NDFzi.alignCenter-1dQNNs.noWrap-3jynv6 {
  display: none;
}

.premiumPaymentModal-3SpIbo .premiumAnimation-kyGkpE {
  display: none;
}

.premiumPaymentModal-3SpIbo {
  background: var(--Background-Colour);
}

.premiumPaymentModal-3SpIbo .premiumPaymentForm-1UbSRI .premiumPaymentTitle-1EZFkv {
  color: var(--Main-Colour);
}

div.option-popout.small-popout-box, div.context-menu, .context-menu .context-menu:not(.item-subMenu), .contextMenu-HLZMGh, .contextMenu-HLZMGh.disabled-dlOjhg .checkbox {
  background: var(--Background-Colour) !important;
  background-color: var(--Background-Colour) !important;
  border: 2px solid var(--Secondary-Main-Colour) !important;
}

.theme-dark .typing-2GQL18, .typing-2GQL18 {
  background-color: rgba(0, 0, 0, 0)!important;
  bottom: -4px!important;
}

.text-1rI06- {
  text-shadow: 0 0 6px Black, 0 0 6px Black, 0 0 5px Black, 0 0 4px Black;
  border-radius: 5px !important;
  color: var(--Main-Colour)!important;
  bottom: -7px!important;
}

.upload-modal .footer, .uploadModal-2ifh8j .footer-4pOKm8 {
  background-color: rgba(0, 0, 0, 0);
}

.userPopout-4pfA0d, .inner-1JeGVc {
  border: .5px solid Black;
  border-radius: 5px!important;
}

#user-profile-modal, .userPopout-4pfA0d, .inner-1JeGVc {
  background: var(--Popout-Background)50% 50%/cover!important;
  text-shadow: 0 0 6px var(--Popout-Text-Shadow-Colour), 0 0 6px var(--Popout-Text-Shadow-Colour), 0 0 5px var(--Popout-Text-Shadow-Colour), 0 0 4px var(--Popout-Text-Shadow-Colour)!important;
}

.upload-modal .inner .file .icon.image, .uploadModal-2ifh8j {
  -webkit-box-shadow: 0 2px 8px rgba(0, 0, 0, .4);
  -webkit-box-sizing: border-box;
  box-sizing: border-box;
  background-color: transparent;
  background-size: contain;
  border: none;
  border-radius: 8px;
  box-shadow: 0 2px 8px rgba(0, 0, 0, .4);
  top: 32%;
  left: -3%;
  width: 100%;
}

.uploadModal-2ifh8j .inner-1-09ZV {
  border: .5px solid transparent;
}

.uploadModal-2ifh8j .inner-1-09ZV .file-XhJJS_ .icon-19bbE_.image-sUU6Oh {
  -webkit-box-shadow: 0 2px 8px rgba(0, 0, 0, .4);
  -webkit-box-sizing: border-box;
  box-sizing: border-box;
  background-color: transparent;
  background-size: contain;
  border: none;
  border-radius: 8px;
  box-shadow: 0 2px 8px rgba(0, 0, 0, 0);
  top: 400px !important;
  left: 0%;
  width: 100%;
  height: 104px;
  margin-left: 0px;
  margin-right: 0px;
  margin-top: -7px;
}

.uploadModal-2ifh8j .inner-1-09ZV .comment-1faMgX .label-Cfxxz9 {
  color: var(--Main-Colour);
}

.theme-dark .item-1Yvehc:hover {
  background: var(--Background-Colour) !important;
  background-color: var(--Background-Colour) !important;
  color: var(--Main-Colour)!important;
}

.theme-dark .item-1Yvehc {
  background: var(--Background-Colour) !important;
  background-color: var(--Background-Colour) !important;
  color: var(--Secondary-Main-Colour)!important;
}

.theme-dark .userSettingsSecurity-3IYeMF .codeCheckbox-1T0TTy {
  color: var(--Main-Colour)!important;
}

.bd-pfbtn:hover, .bda-slist .bda-footer button:hover {
  color: var(--Main-Colour);
  background-color: Var(--Background-Colour);
  border: 1px Solid var(--Main-Colour);
}

.bd-pfbtn:not(:hover), .bda-slist .bda-footer button:not(:hover) {
  color: var(--Secondary-Main-Colour);
  background-color: Var(--Background-Colour-Colour);
  border: 1px Solid var(--Secondary-Main-Colour);
}

/* .popout-3sVMXz {
  min-height: 96px!important;
  min-width: 216px!important;
} */

.menu-Sp6bN1
/*, .item-1GzJrl */

  {
  color: var(--Secondary-Main-Colour);
  background: var(--Background-Colour);
  border: 2px solid var(--Secondary-Main-Colour);
}

.item-1GzJrl, .item-1GzJrl:hover {
  padding: 6px 9px !important;
}

.alt-2vq4VR .item-1GzJrl .helper-3X2gjI
/*, .separator-2zcjq8 */

  {
  display: none;
}

.alt-2vq4VR .item-1GzJrl {
  max-width: 100%;
}

.theme-dark .select-2TCrqx .Select-menu-outer {
  background: var(--Background-Colour);
  border-color: var(--Secondary-Main-Colour);
}

.theme-dark .select-2TCrqx .Select-menu-outer:hover {
  background: var(--Background-Colour);
  border-color: var(--Main-Colour);
}

.theme-dark .select-2TCrqx .Select-option.is-selected {
  background: var(--Background-Colour);
  border-color: var(--Main-Colour);
  border: 1px solid var(--Background-Colour);
}

.theme-dark .select-2TCrqx .Select-option:hover {
  background: var(--Background-Colour);
  color: var(--Main-Colour);
  border: 1px solid var(--Secondary-Main-Colour);
}

.theme-dark .select-2TCrqx .Select-option {
  background: var(--Background-Colour);
  color: var(--Secondary-Main-Colour);
  border: 1px solid var(--Secondary-Main-Colour);
}

.wrapper-1Rf91z .scroller-2TZvBN .friendsOnline-2JkivW {
  color: var(--Secondary-Main-Colour);
}

.marginReset-3RfdVe>div:nth-child(2)>svg>path, .marginReset-3RfdVe>div:nth-child(1)>svg>path {
  fill: var(--Background-Colour)!important;
}

.theme-dark .select-3JqNgs .has-value.is-pseudo-focused.Select--single>.Select-control .Select-value .Select-value-label, .theme-dark .select-3JqNgs .has-value.Select--single>.Select-control .Select-value .Select-value-label, .theme-dark .title-31JmR4, .theme-dark .descChecked-XkfPsU, .theme-dark .titleChecked-2wg0pd, .theme-dark .radioGroup-1GBvlr, .theme-dark .input-1UhAnY, .theme-dark .buttonGreyGhost-SfY7zU {
  color: var(--Main-Colour)!important;
}

.theme-dark .checked-3_4uQ9 {
  background: var(--Background-Colour)!important;
  border: 1px solid var(--Secondary-Main-Colour)!important;
}

.theme-dark .cardPrimaryEditable-3KtE4g, #app-mount>div.app-19_DXt.platform-win>div>div.layers-3iHuyZ.flex-vertical.flex-spacer>div:nth-child(2)>div>div:nth-child(2)>div>div>div>div.content-column.default>div>div>div.ui-form-item.margin-bottom-20>div>div:nth-child(1) {
  border: 1px solid var(--Secondary-Main-Colour)!important;
}

.theme-dark .expandIconForeground-1h4s61 {
  stroke: var(--Main-Colour)!important;
}

.user-settings-games .overlay-toggle-icon-off .fill {
  fill: var(--Secondary-Main-Colour);
}

.theme-dark .content-8biNdB p, .theme-dark .content-8biNdB ul li {
  color: var(--Secondary-Main-Colour);
}

#bd-settings-sidebar>span>div:nth-child(2), #bd-settings-sidebar>span>div:nth-child(3) {
  color: var(--Secondary-Main-Colour)!important;
}

.theme-dark #autocomplete-popout section, .theme-dark #autocomplete-popout .row.selected, .theme-dark #autocomplete-popout .autocomplete-arrow, .theme-dark #autocomplete-popout .autocomplete-header-background {
  background: var(--Background-Colour);
}

.theme-dark .input-cIJ7To:focus {
  border-color: var(--Secondary-Main-Colour);
}

.theme-dark .input-cIJ7To:hover {
  border-color: var(--Main-Colour);
}

.theme-dark .input-cIJ7To {
  color: var(--Main-Colour);
  border-color: var(--Secondary-Main-Colour);
}

.theme-dark .buttonPrimaryLinkDefault-1PQflF, .theme-dark .buttonPrimaryLinkDisabled-3Ey7-S, .theme-dark .buttonPrimaryLinkSubmitting-RbBzR4 {
  color: var(--Secondary-Main-Colour);
}

.theme-dark .buttonPrimaryLinkDefault-1PQflF:active .contents-4L4hQM, .theme-dark .buttonPrimaryLinkDefault-1PQflF:hover .contents-4L4hQM {
  background-image: linear-gradient(0deg, transparent, transparent 1px, var(--Main-Colour) 0, var(--Main-Colour) 2px, transparent 0);
  color: var(--Main-Colour);
}

.theme-dark .checkbox-1ix_J3 {
  border-color: var(--Secondary-Main-Colour);
}

.theme-dark .connection-1fbD7X {
  background-color: transparent;
  border-color: var(--Secondary-Main-Colour);
}

.theme-dark .connection-1fbD7X:hover {
  background-color: transparent;
  border-color: var(--Main-Colour);
}

.connectionHeader-2MDqhu {
  background: transparent !important;
}

.connectionDelete-2Odoln:after, .connectionDelete-2Odoln:before {
  border-color: var(--Secondary-Main-Colour);
}

.connectionDelete-2Odoln:after, .connectionDelete-2Odoln:before:after, .connectionDelete-2Odoln:after, .connectionDelete-2Odoln:before:before {
  background: var(--Secondary-Main-Colour);
}

.connectionDelete-2Odoln:after, .connectionDelete-2Odoln:before:hover {
  border-color: var(--Main-Colour);
}

.theme-dark .primary-jw0I4K {
  color: Var(--Main-Colour)!important;
}

.clipboardInputInner-1EXMA3 {
  background: var(--Background-Colour)!important;
  border: 1px solid var(--Main-Colour);
  overflow: hidden;
}

.wrapper-O5i5-0 .instantInviteModal-5L33Qh .clipboardInputInner-dxVheg input {
  color: var(--Main-Colour);
}

input {
  background-color: transparent;
}

.wrapper-O5i5-0 .instantInviteModal-5L33Qh .copy-2xFKb_, .Select-control {
  background-color: var(--Background-Colour);
}

.clipboardInputInner-1EXMA3 button {
  border-left: 1px solid var(--Main-Colour);
  color: var(--Main-Colour);
}

.clipboardInputInner-1EXMA3 button:first-of-type:before {
  background: transparent;
}

.wrapper-O5i5-0 .instantInviteModal-5L33Qh .expireText-NeAc7v, .wrapper-O5i5-0 .instantInviteModal-5L33Qh .blurb-ArHxCz, div.checkbox span {
  color: var(--Secondary-Main-Colour)!important;
}

.Select--single>.Select-control .Select-value, .Select-placeholder, .has-value.is-pseudo-focused.Select--single>.Select-control .Select-value .Select-value-label, .has-value.Select--single>.Select-control .Select-value .Select-value-label {
  color: var(--Main-Colour)!important;
}

.form-deprecated .Select-option.is-focused, .form.deprecated .Select-option.is-focused {
  background: var(--Background-Colour);
  color: var(--Main-Colour);
}

.form-deprecated .Select-option, .form.deprecated .Select-option {
  color: var(--Secondary-Main-Colour);
}

.Select-control, .Select-menu-outer, .Select-option {
  background: var(--Background-Colour)!important;
  border-color: var(--Main-Colour)!important;
}

div.help-text {
  color: var(--Secondary-Main-Colour)!important;
}

button.btn.btn-default {
  background: transparent !important;
  color: var(--Main-Colour) !important;
}

.form-deprecated .btn-default, .form.deprecated .btn-default {
  border-bottom: 2px solid var(--Main-Colour);
}

.theme-dark .messages-popout-wrap .messages-popout .channel-separator .guild-name, .theme-dark .recent-mentions-popout .tab-bar-item, .theme-dark .recent-mentions-popout .mention-filter .label {
  color: var(--Secondary-Main-Colour) !important;
}

.theme-dark .themed-popout .header .title, .theme-dark .recent-mentions-popout .mention-filter .value, .theme-dark .recent-mentions-popout .tab-bar-item {
  color: var(--Main-Colour) !important;
}

.theme-dark .themed-popout {
  background-color: var(--Background-Colour)!important;
  border: 1px solid var(--Main-Colour)!important;
}

.theme-dark .messages-popout-wrap .messages-popout .message-group:hover .action-buttons {
  -webkit-box-shadow: 0 0 6px 4px var(--Background-Colour);
  background-color: var(--Background-Colour);
  box-shadow: 0 0 6px 4px var(--Background-Colour);
}

.theme-dark .themed-popout .header .subtitle, .theme-dark .themed-popout .text {
  color: var(--Main-Colour) !important;
}

.theme-dark .messages-popout-wrap .messages-popout .message-group .action-buttons .jump-button {
  background-color: var(--Background-Colour);
  color: var(--Main-Colour);
}

.need-help-modal.deprecated .footer {
  background: var(--Background-Colour)!important;
  border-color: var(--Main-Colour)!important;
  color: var(--Secondary-Main-Colour);
}

.need-help-modal.deprecated .header h1 {
  color: var(--Main-Colour);
}



#app-mount>div:nth-child(5)>div.modal-1UGdnR>div>div>div>div>div>div.inviteTitle-2yNtkC, .keyboard-shortcuts-modal .modal-title {
  color: var(--Main-Colour);
}

.create-guild-container.deprecated .action .action-body, .inviteModal-34DdOm .inviteBody-1kVhyx, .inviteModal-34DdOm .inviteCancel-2dlgcH, .keyboard-shortcuts-modal .keyboard-shortcut-list .keybind-group .keybind-description, .keyboard-shortcuts-modal .modal-subtitle, .keybind-shortcut {
  color: var(--Secondary-Main-Colour);
}

#app-mount>div:nth-child(5)>div.modal-1UGdnR>div>div>div>div.scroller-wrap.fade>div>div>div>div.keybind-shortcuts>div>span>svg>g {
  fill: var(--Secondary-Main-Colour);
}

.create-guild-container.deprecated .create-or-join .actions .or {
  display: none;
}

.create-guild-container.deprecated .create-or-join {
  top: 20%;
}

.create-guild-container.deprecated {
  background: var(--Background-Colour);
}

.create-guild-container.deprecated .create-or-join .form-inner {
  background: transparent;
  height: 100%;
}

#app-mount>div:nth-child(5)>div.modal-1UGdnR>div {
  background: transparent;
}

.keybind-shortcut span {
  -webkit-box-shadow: inset 0 -4px 0 var(--Secondary-Main-Colour);
  border: 1px solid var(--Secondary-Main-Colour);
  border-radius: 2px;
  box-shadow: inset 0 -4px 0 var(--Secondary-Main-Colour);
}

.keybind-shortcut.dim span {
  background-color: var(--Background-Colour);
  color: var(--Secondary-Main-Colour);
}

.create-guild-container.deprecated .action:hover.join .btn, .keyboard-shortcuts-modal {
  color: var(--Main-Colour) !important;
  background-color: Var(--Background-Colour) !important;
  border: 1px Solid var(--Main-Colour) !important;
}

.create-guild-container.deprecated .action:not(:hover).join .btn {
  color: var(--Secondary-Main-Colour) !important;
  background-color: Var(--Background-Colour-Colour) !important;
  border: 1px Solid var(--Secondary-Main-Colour) !important;
}

.create-guild-container.deprecated .create-or-join header {
  display: none;
}

.userPopout-4pfA0d, .inner-1JeGVc {
  border: 1px Solid transparent !important;
}

.uploadModalIn-1z07Bv .uploadDropModal-2kTwbc .bgScale-1i4Cp3 {
  background: var(--Background-Colour);
}

.uploadModalIn-1z07Bv .uploadDropModal-2kTwbc .inner-1-09ZV {
  border: 2px dashed var(--Main-Colour);
  color: var(--Main-Colour);
}

/* ICONS
.uploadModalIn-1z07Bv .uploadDropModal-2kTwbc .inner-1-09ZV .icon-19bbE_.one-3Z3WUg {
  background-image: url(/assets/60c3eaf0d7173c929482362ea1d2543a.svg);
}

.uploadModalIn-1z07Bv .uploadDropModal-2kTwbc .inner-1-09ZV .icon-19bbE_.two-3djYgO {
  background-image: url(/assets/4ab2ee5027741df387151ca717ae5614.svg);
}

.uploadModalIn-1z07Bv .uploadDropModal-2kTwbc .inner-1-09ZV .icon-19bbE_.three-jJjLhh {
  background-image: url(/assets/a4ef7d20760cef4c165825770fd12ac7.svg);
}

.uploadModalIn-1z07Bv .uploadDropModal-2kTwbc .inner-1-09ZV .instructions-KnejBP {
  color:  var(--Secondary-Main-Colour);
}
 ICONS */

.inviteModal-34DdOm .scroller {
  background: var(--Background-Colour);
}

.bd-modal-wrapper .bd-modal-inner {
  border: 1px solid red !important;
  box-shadow: 0 2px 10px 10px rgba(255, 0, 0, 0.66);
}

.bd-modal-wrapper .table-header {
  color: var(--Main-Colour);
  border-bottom: 1px solid var(--Secondary-Main-Colour);
}

.bd-modal-wrapper .error {
  border-bottom: 1px solid var(--Secondary-Main-Colour);
}

.bd-modal-wrapper .tab-bar-container {
  background: var(--Background-Colour);
  box-shadow: 0 2px 3px 0 rgba(0, 0, 0, 0);
}

.bd-modal-wrapper .bd-modal-body {
  background-color: var(--Background-Colour);
  color: var(--Main-Colour);
}

.bd-modal-wrapper .header {
  background-color: var(--Background-Colour);
  box-shadow: 0 2px 3px 0 rgba(0, 0, 0, 0);
  color: var(--Main-Colour);
}

.bd-modal-wrapper .error {
  color: var(--Main-Colour);
}

.bd-modal-wrapper .tab-bar-container .tab-bar-item {
  color: var(--Main-Colour)!important;
}

.bd-modal-wrapper .footer button {
  background: transparent!important;
  border: 1px solid Var(--Secondary-Main-Colour)!important;
  border-radius: 3px!important;
  color: Var(--Secondary-Main-Colour)!important;
}

.bd-modal-wrapper .footer button:hover {
  background: transparent!important;
  border: 1px solid Var(--Main-Colour);
  border-radius: 3px;
  color: Var(--Main-Colour)!important;
}

/* Thanks to Uri#0001 */

.toast {
  background: var(--Background-Colour)!important;
  border: 1px solid Var(--Main-Colour)!important;
  border-radius: 3px!important;
  color: Var(--Main-Colour)!important;
  right: 10px!important;
}

.bd-toast {
  background: var(--Background-Colour)!important;
  border: 1px solid Var(--Main-Colour)!important;
  border-radius: 3px!important;
  color: Var(--Main-Colour)!important;
}

.bd-toasts, .toasts {
  width: calc(100% - 10px)!important;
  height: calc(100% - 70px)!important;
  position: absolute;
  top: initial!important;
  right: initial!important;
  bottom: 0px!important;
  left: initial!important;
  display: flex;
  flex-flow: column;
  justify-content: flex-end;
}

.bd-toasts {
  left: 10px!important;
  align-items: flex-start!important;
}

.toasts {
  right: 10px!important;
  align-items: flex-end!important;
}

[class*="toast"] {
  font-size: 10px!important;
}

/* Thanks to Uri#0001 */

.regionSelectModal-12e-57 {
  background: var(--Popout-Background);
}

.regionSelectModal-12e-57 .regionSelectModalOption-3giLPN {
  background-color: var(--Secondary-Background-Colour);
  border: 2px solid var(--Secondary-Main-Colour);
}

.regionSelectModal-12e-57 .regionSelectModalOption-3giLPN:hover {
  background-color: var(--Background-Colour);
  border: 2px solid var(--Main-Colour);
}

.regionSelectModal-12e-57 .regionSelectModalHeader-33y0EU, .regionSelectName-2-2FWh {
  color: var(--Main-Colour);
}

.regionSelectModal-12e-57 .regionSelectModalFooter-1a5bzj {
  color: var(--Secondary-Main-Colour);
}

.buttonWhiteOutlined-2KwPTg, .buttonBrandGhost-1-Lmhc {
  background: transparent!important;
  border: 1px solid Var(--Secondary-Main-Colour)!important;
  border-radius: 3px!important;
  color: Var(--Secondary-Main-Colour)!important;
}

.buttonWhiteOutlined-2KwPTg:hover {
  background: transparent!important;
  border: 1px solid Var(--Main-Colour);
  border-radius: 3px;
  color: Var(--Main-Colour)!important;
}

.theme-dark .container-1s4HBn.hover-1civje {
  border-color: Var(--Secondary-Main-Colour)!important;
}

.theme-dark .container-1nZlH6 {
  border-color: Var(--Secondary-Main-Colour)!important;
  background: transparent!important;
}

.buttonGreyGhost-SfY7zU {
  background-color: transparent!important;
  color: Var(--Secondary-Main-Colour)!important;
  border: 1px solid Var(--Secondary-Main-Colour)!important;
}

.theme-dark .invite-settings-invite-row, .theme-dark .quickSelect-3BxO0K, .theme-dark .searchBar-1MOL6S .input-yt44Uw, .theme-dark .inputDefault-A2ud2y, .theme-dark .userHook-3AdCBF, .theme-dark .auditLog-3jNbM6 strong, .theme-dark .headerClickable-1jGUp8, .theme-dark .headerDefault-1wrJcN {
  color: Var(--Main-Colour)!important;
}

.theme-dark .timestamp-1mruiI, .theme-dark .headerExpanded-CUEwZ5 {
  color: Var(--Secondary-Main-Colour)!important;
}

.theme-dark .auditLog-3jNbM6 {
  border-color: Var(--Secondary-Main-Colour)!important;
  background: transparent!important;
  color: Var(--Secondary-Main-Colour)!important;
}

.theme-dark .headerExpanded-CUEwZ5 {
  background: transparent!important;
  color: Var(--Secondary-Main-Colour)!important;
}

.theme-dark .input-cIJ7To.focused-1mmYsC {
  border-color: var(--Main-Colour);
}

.foldercontent .container-1ETFDs.selected-nT-gM3 .wrapper-2lTRaf a[style*=font] {
  background-color: transparent;
}

.headerSpotify-1fSJPO, .topSectionSpotify-1lI0-P {
  background: transparent;
}

.buttonGreenInverted-3wLrIA {
  color: var(--Main-Colour);
  background-color: Var(--Secondary-Background-Colour);
  border: 1px Solid var(--Main-Colour);
}

.buttonGreenInverted-3wLrIA:hover {
  color: var(--Main-Colour);
  background-color: Var(--Background-Colour);
  border: 1px Solid var(--Main-Colour);
}

.bar-3urHkF {
  background-color: Var(--Secondary-Background-Colour);
}

.barInner-3NDaY_ {
  background-color: Var(--Secondary-Background-Colour);
  border: 1px solid var(--Secondary-Main-Colour);
}

.text-AOoUen {
  color: var(--Main-Colour);
}

.theme-dark .preview-yX6Nx7 {
  border-color: var(--Secondary-Main-Colour);
}

.theme-dark .invite-18yqGF {
  background: var(--Secondary-Background-Colour);
}

.theme-dark .header-Hg_qNF, .theme-dark .subHeader-27gFHC, .theme-dark .name-GG2Mcs, .theme-dark .partyStatus-6AjDud {
  color: var(--Secondary-Main-Colour);
}

.buttonBrandLinkDefault-1bjP4F:active .contents-4L4hQM, .buttonBrandLinkDefault-1bjP4F:hover .contents-4L4hQM {
  background-image: linear-gradient(0deg, transparent, transparent 1px, var(--Main-Colour) 0, var(--Main-Colour) 2px, transparent 0);
}

.buttonBrandLink-3csEAP {
  color: var(--Secondary-Main-Colour);
}

.theme-dark .attachPopoutRowText-1tIocA {
  color: var(--Main-Colour)!important;
}

.attachPopoutIcon-26Np2W {
  display: none;
}

.theme-dark .attachment-33OFj0 {
  background: transparent;
  border-color: transparent;
}

.theme-dark .invite-18yqGF {
  background: var(--Secondary-Background-Colour);
  border: 5px ridge var(--Main-Colour);
}

.coverImageActionable-1TMryE.blurred-eylnMq {
  display: none;
}

.theme-dark .artworkSpotifySessionEnded-11d_If {
  display: none;
}

.theme-dark .container-1If-HZ, .theme-dark .reactors-Blmlhw {
  background: var(--Background-Colour);
}

.theme-dark .reactionSelected-1pqISm, .theme-dark .sidebar-1-SQro {
  background: transparent;
}

.theme-dark .discriminator-byOsvi {
  color: var(--Secondary-Main-Colour);
}

.theme-dark .reaction {
  background: var(--Secondary-Background-Colour)!important;
  border: 1px ridge var(--Main-Colour)!important;
}

.theme-dark .reaction .reaction-count {
  color: var(--Secondary-Main-Colour);
}

.reaction.reaction-me .reaction-count, .theme-dark .reaction.reaction-me .reaction-count {
  color: var(--Main-Colour);
}

.theme-dark .input-2VB9rf, .theme-dark .quickswitcher-3JagVE {
  -webkit-box-shadow: 0 2px 5px rgba(0, 0, 0, 0), 0 0 0 1px rgba(0, 0, 0, 0);
  background-color: var(--Secondary-Background-Colour);
  box-shadow: 0 2px 5px rgba(0, 0, 0, 0), 0 0 0 1px rgba(0, 0, 0, 0);
  color: var(--Secondary-Main-Colour);
  border: 1px solid var(--Main-Colour)!important;
}

.theme-dark .contentDefault-16dKSY, .theme-light .resultFocused-2geRUA {
  color: var(--Secondary-Main-Colour);
}

.theme-dark .resultFocused-3aIoYe {
  background-color: var(--Secondary-Background-Colour);
  border: 1px solid var(--Main-Colour)!important;
}

.theme-dark .tipsWithoutResults-lGY-De, .theme-dark .tipsWithResults-HhTE9b {
  background: transparent!important;
  color: var(--Secondary-Main-Colour)!important;
}

.dark-2Ll8iS span {
  -webkit-box-shadow: inset 0 -4px 0 rgba(35, 39, 42, 0);
  background-color: var(--Secondary-Background-Colour);
  border-color: var(--Secondary-Main-Colour);
  box-shadow: inset 0 -4px 0 rgba(35, 39, 42, 0);
  color: var(--Secondary-Main-Colour);
}

.dark-2Ll8iS span .bindArrow-3Mm64N g {
  fill: var(--Secondary-Main-Colour);
}

.botTagInvert-18-95s {
  background-color: rgba(0, 216, 86, 0.8) !important;
  animation: rainbow 20s infinite linear;
}

.bda-slist .checkbox {
  margin-top: 0px;
}

.checkbox .checkbox-inner span {
  bottom: 10%;
  box-sizing: border-box;
  left: 0%;
  right: 0%;
  top: 0;
  transition: .54s;
}

[id*="plugin-settings"] div.checkbox>div>span {
  bottom: 10%;
  box-sizing: border-box;
  left: 3209%;
  right: -3209%;
  top: -40%;
  transition: .54s;
}

.theme-dark .note-3kmerW textarea:focus {
  background: var(--Secondary-Background-Colour);
}

.emojiPicker-3m1S-j .categories-jw8z2h .item-lsWB-j.selected-1LQfcZ {
  border-bottom-color: var(--Secondary-Main-Colour);
}

}

a[href="https://github.com/Inve1951/BetterDiscordStuff"] {
  font-size: 0;
}

a[href="https://github.com/Inve1951/BetterDiscordStuff"]:after {
  content: "Square's repo";
  color: var(--Main-Colour);
  font-size: 15px;
}

a[href="https://github.com/rauenzi/BetterDiscordAddons"] {
  font-size: 0;
}


a[href="http://www.youtube.com/c/Raynnerino"]:after {
  content: "Zerebos' repo";
  color: var(--Main-Colour);
  font-size: 15px;
}


a[href="http://www.youtube.com/c/Raynnerino"]:after {
  font-size: 0;
}


a[href="http://www.youtube.com/c/Raynnerino"]:after {
  content: "Raynnerino's repo";
  color: var(--Main-Colour);
  font-size: 15px;
}

a[href="Raynnerino"] {
  font-size: 0;
}

a[href="http://www.youtube.com/c/Raynnerino"]:after {
  content: "Raynnerino's Youtube Channel";
  color: var(--Main-Colour);
  font-size: 15px;
}

/* 
a[href="Raynnerino"] {
  font-size: 0;
}

a[href="http://www.youtube.com/c/Raynnerino"]:after {
  content: "Raynnerino's Youtube Channel";
  color:var(--Main-Colour);
  font-size: 15px;
}

a[href="Raynnerino"] {
  font-size: 0;
}

a[href="http://www.youtube.com/c/Raynnerino"]:after {
  content: "Raynnerino's Youtube Channel";
  color:var(--Main-Colour);
  font-size: 15px;
}

a[href="Raynnerino"] {
  font-size: 0;
}

a[href="http://www.youtube.com/c/Raynnerino"]:after {
  content: "Raynnerino's Youtube Channel";
  color:var(--Main-Colour);
  font-size: 15px;
}

a[href="Raynnerino"] {
  font-size: 0;
}

a[href="http://www.youtube.com/c/Raynnerino"]:after {
  content: "Raynnerino's Youtube Channel";
  color:var(--Main-Colour);
  font-size: 15px;
}

a[href="https://nfld99.com/discord"] {
  font-size: 0;
}

a[href="http://www.youtube.com/c/Raynnerino"]:after {
  content: "Raynnerino's Youtube Channel";
  color:var(--Main-Colour);
  font-size: 15px;
} */

a[href="https://github.com/mwittrien/BetterDiscordAddons"] {
  font-size: 0;
}

a[href="https://github.com/mwittrien/BetterDiscordAddons"]:after {
  content: "DevilBro's repo";
  color: var(--Main-Colour);
  font-size: 15px;
}

a[href="https://github.com/DevilsLynAvenged/DevilsLynAvenged"] {
  font-size: 0;
}

a[href="https://github.com/DevilsLynAvenged/DevilsLynAvenged"]:after {
  content: "DevilsLynAvenged's repo";
  color: var(--Main-Colour);
  font-size: 15px;
}

a[href="https://github.com/hammy1/BDPlugins"] {
  font-size: 0;
}

a[href="https://github.com/hammy1/BDPlugins"]:after {
  content: "Hammy's repo";
  color: var(--Main-Colour);
  font-size: 15px;
}

[class*="lookFilled-"]:hover {
  background-color: var(--Secondary-Background-Colour)!important;
  color: var(--Main-Colour)!important;
  border: 1px solid var(--Main-Colour)!important;
}

[class*="lookFilled-"] {
  background-color: var(--Secondary-Background-Colour)!important;
  color: var(--Secondary-Main-Colour)!important;
  border: 1px solid var(--Secondary-Main-Colour)!important;
}

.theme-dark .lookLink-9FtZy-.colorPrimary-3b3xI6:hover .contents-4L4hQM, .lookLink-9FtZy-.colorGrey-2DXtkV:hover .contents-4L4hQM:hover .contents-4L4hQM {
  background-image: linear-gradient(0deg, transparent, transparent 1px, var(--Main-Colour) 0, var(--Main-Colour) 2px, transparent 0);
}

.theme-dark .add-game-popout .cancel-button {
  color: var(--Main-Colour);
}

.theme-dark .lookOutlined-3sRXeN.colorPrimary-3b3xI6:hover {
  border-color: var(--Main-Colour);
  color: var(--Main-Colour);
}

.theme-dark .lookOutlined-3sRXeN.colorPrimary-3b3xI6 {
  border-color: var(--Secondary-Main-Colour);
  color: var(--Secondary-Main-Colour);
}

.theme-dark .lookLink-9FtZy-.colorPrimary-3b3xI6 {
  color: var(--Main-Colour);
}

.theme-dark .user-settings-games .not-detected, .theme-light .user-settings-games .not-detected {
  background-color: var(--Secondary-Background-Colour);
}

.theme-dark .user-settings-games .not-detected .game-name, .theme-light .user-settings-games .not-detected .game-name {
  color: var(--Main-Colour);
}

.theme-dark .user-settings-games .not-detected .last-played, .theme-light .user-settings-games .not-detected .last-played {
  color: var(--Secondary-Main-Colour);
}

.theme-dark .user-settings-games .game-name-input:focus, .theme-dark .user-settings-games .game-name-input:hover {
  background-color: var(--Background-Colour);
  border-color: var(--Main-Colour);
}

.theme-dark .incomingCallInner-2rV0UJ .members-39w8ve {
  color: var(--Main-Colour);
}

.incomingCallInner-2rV0UJ .subtitle-3es__m {
  color: var(--Secondary-Main-Colour);
}

.theme-dark .incomingCallInner-2rV0UJ {
  background: var(--Popout-Background);
  border-color: var(--Main-Colour);
}

/* 
[class*="notice"] {
  background-color: var(--Background-Colour);
  color: var(--Main-Colour);
  border: 1px solid var(--Main-Colour);
} 
*/

.container-2VW0UT {
  background: var(--Background-Colour)!important;
  border: 1px solid var(--Secondary-Main-Colour);
}

.container-2VW0UT:hover {
  border: 1px solid var(--Main-Colour);
}

.button-1MICoQ:hover, .noticeStreamerMode-2TSQpg .button-1MICoQ:hover, .streamerModeEnabledBtn-2ZJ2eq:hover {
  background: var(--Background-Colour);
  color: var(--Main-Colour);
  border: 1px solid var(--Main-Colour);
}

.button-1MICoQ, .streamerModeEnabledBtn-2ZJ2eq {
  background: var(--Secondary-Background-Colour);
  color: var(--Secondary-Main-Colour);
  border: 1px solid var(--Secondary-Main-Colour);
}

.theme-dark .streamerModeEnabledImage-3vynUz {
  background: none;
}

.questionMark-CWEQZn div .icon-1oniCb {
  color: var(--Secondary-Main-Colour);
}

.questionMark-CWEQZn div .icon-1oniCb:hover {
  color: var(--Main-Colour);
}

.theme-dark .questionMark-CWEQZn div {
  background-color: transparent;
}

.theme-dark .questionMark-CWEQZn div:hover {
  background-color: transparent;
}

#friends .friends-table .friends-row .friends-column+.friends-column {
  margin-left: 4px;
}

#friends .friends-table .friends-table-header .friends-column-separator {
  margin: 0 9.5px;
}

.theme-dark #friends .tab-bar .tab-bar-item {
  color: var(--Secondary-Main-Colour);
}

.theme-dark #friends .tab-bar .tab-bar-item.tab-bar-item-primary {
  color: var(--Main-Colour);
}

.member-username-inner[style="color: rgb(255, 255, 255);"], .user-name[style="color: rgb(255, 255, 255);"] {
  font-weight: bold!important;
  color: var(--Secondary-Main-Colour)!important;
}

#discord-logger-log-window>div.modal-1UGdnR>div>div>div {
  min-height: 95%!important;
}

#dl-log-button:not(:hover) {
  font-weight: bold!important;
  text-transform: none!important;
  color: var(--Secondary-Main-Colour)!important;
}

#dl-log-button:hover {
  font-weight: bold!important;
  text-transform: none!important;
  color: var(--Secondary-Main-Colour)!important;
}

/* Support For Clock */

#clockPluginClock {
  color: var(--Main-Colour)!important;
  background: transparent;
  bottom: 0px;
  right: 258px;
}

/* Support For Clock */

/* Support For Switch Fix */

.ui-switch-checkbox:checked+.ui-switch {
  background: var(--Main-Colour);
}

.ui-switch-wrapper .ui-switch {
  background: var(--Background-Colour);
}

/* Support For Switch Fix */

/* Support For Better Formatting Redux */

.bf-toolbar:before {
  background: var(--Secondary-Background-Colour)!important;
}

.upload-modal .bf-toolbar {
  top: 13px!important;
}

.bf-toolbar .format:hover {
  background: var(--Secondary-Main-Colour)!important;
  color: var(--Main-Colour)!important;
}

.bf-toolbar {
  top: 25px!important;
}

/* Support For Better Formatting Redux */

/* Support For Horizontal Server List */

.app {
  --guild-column-count: calc(26 / 17);
}

/* Support For Horizontal Server List */

/* Support For Avatar Hover */

#AvatarHover {
  box-shadow: 1px 1px 15px var(--Main-Colour)!important;
}

/* Support For Avatar Hover */

/* Support For Date Viewer */

#dv-mount {
  background: transparent!important;
  bottom: 0;
  box-sizing: border-box;
  color: var(--Main-Colour)!important;
  height: 95px;
  position: absolute;
  width: 100%;
  z-index: 10;
}

#dv-main {
  border-color: transparent;
  color: var(--Main-Colour)!important;
}

/* Support For Date Viewer */

/* Support For Copy Images */

.modal-image .download-button:nth-of-type(1) {
  position: absolute;
  left: 200px;
  bottom: 6px;
  pointer-events: auto;
}

.modal-image .download-button:nth-of-type(2) {
  position: absolute;
  left: 300px;
  bottom: 6px;
  pointer-events: auto;
}

/* Support For Copy Images */

/* Support For tagID */

#tagID {
  font-size: 10px;
  letter-spacing: 0.025rem;
  position: relative;
  top: -0.4ex;
  height: 9px;
  margin-left: -3px;
  margin-right: 6px;
  text-shadow: 0 1px 3px black;
  background: var(--Background-Colour);
  border-radius: 3px;
  font-weight: 500;
  padding: 3px 5px;
  color: var(--Main-Colour);
  font-family: 'Roboto', 'Inconsolata', 'Whitney', sans-serif;
}

/* Support For name IDs */

/* Support For Server Folders */

.serverfolders-modal .form-tabcontent, .serverfolders-modal .form-tabcontent, .serverfolders-modal .form-tab, .serverfolders-modal .control-group label, .serverfolders-modal .form-tab button, .serverfolders-modal .modal-inner {
  background: var(--Background-Colour)!important;
  background-color: var(--Background-Colour)!important;
}

.serverfolders-modal .form-tablinks.active {
  border: 1px solid var(--Main-Colour)!important;
  background-color: var(--Background-Colour)!important;
}

.serverfolders-modal [class^="ui-icon-picker-icon"], .serverfolders-modal input {
  border: .5px solid var(--Secondary-Main-Colour)!important;
}

.ui-icon-picker-icon.selected {
  border: 1px solid var(--Main-Colour)!important;
  background-color: var(--Secondary-Main-Colour)!important;
}

/* Support For Server Folders */

/* Support For Server Folders 2 */

.foldercontent {
  background: var(--Background-Colour) !important;
  border: 1px solid var(--Main-Colour) !important;
}

.wrapper-1Rf91z.foldercontent.foldercontentopen>div {
  width: 60px!important;
}

.foldercontentopen>.scroller-wrap {
  width: 50.5px!important;
  padding-left: 5px;
}

.foldercontent {
  width: 62px!important;
  border-radius: 4px;
}

.scroller-2TZvBN {
  transition: all 900ms ease !important;
  border-right-width: 1px !important;
  border-color: transparent !important;
  border-style: solid !important;
  width: 60px !important;
  padding-top: 0px !important;
}

.container-1ETFDs.folder .badge-2_fwUZ.folder.count {
  background: transparent !important;
  border-color: transparent !important;
  height: 10px !important;
  top: 12.5px !important;
  right: 5px !important;
  left: 5px !important;
  color: var(--Main-Colour) !important;
}

.wrapper-1Rf91z.folderopen .scroller-wrap {
  overflow: visible !important;
  width: 110px!important;
}

.wrapper-1Rf91z.folderopen .scroller-2TZvBN {
  overflow: visible !important;
  width: 170px;
}

.wrapper-1Rf91z.folderopen {
  overflow: visible !important;
  width: 114.5px;
}

.layers-3iHuyZ.flex-vertical.flex-spacer>div>div>div.layer-3QrUeG>.flex-1xMQg5.flex-1O1GKY.vertical-V37hAW.flex-1O1GKY.directionColumn-35P_nr.justifyStart-2NDFzi.alignStretch-DpGPf3.noWrap-3jynv6.base-3dtUhz>div.flexChild-faoVW3 {
  display: none;
}

.layer-3QrUeG>.flex-1xMQg5.flex-1O1GKY.horizontal-1ae9ci.horizontal-2EEEnY.flex-1O1GKY.directionRow-3v3tfG.justifyStart-2NDFzi.alignStretch-DpGPf3.noWrap-3jynv6>.wrapper-1Rf91z.folderopen .scroller-wrap, .layer-3QrUeG>.flex-1xMQg5.flex-1O1GKY.horizontal-1ae9ci.horizontal-2EEEnY.flex-1O1GKY.directionRow-3v3tfG.justifyStart-2NDFzi.alignStretch-DpGPf3.noWrap-3jynv6>.wrapper-1Rf91z.folderopen .scroller-wrap.folderopen {
  overflow: visible !important;
  width: 110px!important;
}

.wrapper-1Rf91z.folderopen, .wrapper-1Rf91z.folderopen .scroller-wrap, .wrapper-1Rf91z.folderopen .scroller-2TZvBN {
  overflow: visible !important;
  width: 170px!important;
  min-width: 10px!important;
  transition: all .1s;
}

.layer-3QrUeG>.flex-1xMQg5.flex-1O1GKY.horizontal-1ae9ci.horizontal-2EEEnY.flex-1O1GKY.directionRow-3v3tfG.justifyStart-2NDFzi.alignStretch-DpGPf3.noWrap-3jynv6>.wrapper-1Rf91z.folderopen {
  overflow: visible !important;
  width: 114.5px;
  min-width: 114.5px;
  transition: all .1s;
}

.foldercontent {
  animation: SFA .3s 1 linear;
}

.folderclosing>div>div>div>.foldercontent {
  animation: SFC .3s 1 linear;
  transition: none !important;
}

.foldercontentclosed {
  opacity: 0;
  transition: all 500ms;
}

.foldercontentopen {
  opacity: 1;
  transition: all 500ms;
}

/* Support For Server Folders 2 */

/* Support For Repo Plugins */

.pluginrepo-modal .pluginEntry.downloadable .btn-download, .pluginrepo-modal .pluginEntry.updated .btn-download, .themerepo-modal .themeEntry.downloadable .btn-download, .themerepo-modal .themeEntry.downloadable .btn-download {
  color: var(--Main-Colour)!important;
  background-color: Var(--Secondary-Background-Colour)!important;
  border: 1px Solid var(--Main-Colour)!important;
}

.pluginrepo-modal .pluginEntry.downloadable .btn-download:hover, .pluginrepo-modal .pluginEntry.updated .btn-download:hover, .themerepo-modal .themeEntry.downloadable .btn-download:hover, .themerepo-modal .themeEntry.updated .btn-download {
  color: var(--Main-Colour)!important;
  background-color: Var(--Background-Colour)!important;
  border: 1px Solid var(--Main-Colour)!important;
}

/* Support For Repo Plugins */

/* Support For Member Count */

.theme-dark #memberCount {
  background: transparent!important;
  color: var(--Secondary-Main-Colour)!important;
}

/* Support For Member Count */

/* Support For ChannelHistory */

.channelHistoryButtons .btn {
  position: flex;
}

.channelHistoryButtons {
  position: absolute;
  left: 50%!important;
}

.btn.back {
  color: var(--Main-Colour);
  font-weight: bold;
  border: 1px solid var(--Main-Colour);
  background: transparent!important;
}

.btn.back.cant {
  color: var(--Main-Colour);
  font-weight: bold;
  border: 1px solid var(--Main-Colour);
  background: transparent!important;
}

.btn.forward.cant {
  color: var(--Secondary-Main-Colour);
  font-weight: bold;
  border: 1px solid var(--Secondary-Main-Colour);
  background: transparent!important;
}

.btn.forward {
  color: var(--Secondary-Main-Colour);
  font-weight: bold;
  border: 1px solid var(--Secondary-Main-Colour);
  background: transparent!important;
}

/* Support For ChannelHistory */

/* Support For ServerSearch */

.theme-dark .selectableItem-1MP3MQ {
  color: var(--Secondary-Main-Colour);
}

.theme-dark .popoutList-T9CKZQ {
  background: var(--Background-Colour);
}

.theme-dark .selectableItem-1MP3MQ:hover {
  background-color: var(--Secondary-Background-Colour);
  color: var(--Main-Colour);
}

/* Support For ServerSearch */

/* User Status 2 */

/* DND */

.statusDnd-2DDKST:not(.statusProfile-3ynqtt), .avatar-small .status-dnd {
  width: 114%!important;
  height: 114%!important;
  box-sizing: border-box;
  top: -6.3%!important;
  left: -6.3%!important;
  border: 2.5px solid #f04747!important;
  border-radius: 5px !important;
  background: none;
  opacity: 1 !important;
  animation: Dnd 3s linear infinite !important;
}

/* ONLINE */

.statusOnline-1FlpW_:not(.statusProfile-3ynqtt), .avatar-small .status-online {
  width: 114%!important;
  height: 114%!important;
  box-sizing: border-box;
  top: -6.3%!important;
  left: -6.3%!important;
  border: 2.5px solid #43b581!important;
  border-radius: 5px !important;
  background: none;
  opacity: 1 !important;
  animation: Online 3s linear infinite !important;
}

/* AWAY */

.statusIdle-1XoSCz:not(.statusProfile-3ynqtt), .avatar-small .status-idle {
  width: 114%!important;
  height: 114%!important;
  box-sizing: border-box;
  top: -6.3%!important;
  left: -6.3%!important;
  border: 2.5px solid #faa61a!important;
  border-radius: 5px !important;
  background: none;
  opacity: 1 !important;
  animation: Away 3s linear infinite !important;
}

/* STREAM */

.statusStreaming-2eqoUF:not(.statusProfile-3ynqtt) {
  width: 114%!important;
  height: 114%!important;
  box-sizing: border-box;
  top: -6.3%!important;
  left: -6.3%!important;
  border: 2.5px solid #593695!important;
  border-radius: 5px !important;
  background: none;
  opacity: 1 !important;
  animation: Stream 3s linear infinite !important;
}

/* OFFLINE */

.avatarOffline-3GF27z {
  top: -6.3%!important;
  left: -6.3%!important;
  border: 2.5px solid #747f8d!important;
  border-radius: 5px !important;
  animation: Offline 3s linear infinite !important;
}

.statusOffline-3R-4Bv:not(.statusOfflineProfile-9tGGr-), .avatar-small .status-invisible, .avatar-small .status-offline {
  width: 114%!important;
  height: 114%!important;
  box-sizing: border-box;
  top: -6.3%!important;
  left: -6.3%!important;
  border: 2.5px solid #747f8d!important;
  border-radius: 5px !important;
  background: none;
  opacity: 1 !important;
  animation: Offline 3s linear infinite !important;
}

/* User Status 2 */

/* User Status 3 */

/* DND */

.dnd-1_xrcq:not(.statusProfile-3ynqtt):not(.status-3fQvEa):not(.popout-2fzvxG) {
  width: 114%!important;
  height: 114%!important;
  box-sizing: border-box;
  top: -6.3%!important;
  left: -6.3%!important;
  border: 2.5px solid #f04747!important;
  border-radius: 5px !important;
  background: none;
  opacity: 1 !important;
  animation: Dnd 3s linear infinite !important;
}

/* ONLINE */

.online-2S838R:not(.statusProfile-3ynqtt):not(.status-3fQvEa):not(.popout-2fzvxG) {
  width: 114%!important;
  height: 114%!important;
  box-sizing: border-box;
  top: -6.3%!important;
  left: -6.3%!important;
  border: 2.5px solid #43b581!important;
  border-radius: 5px !important;
  background: none;
  opacity: 1 !important;
  animation: Online 3s linear infinite !important;
}

/* AWAY */

.idle-3DEnRT:not(.statusProfile-3ynqtt):not(.status-3fQvEa):not(.popout-2fzvxG) {
  width: 114%!important;
  height: 114%!important;
  box-sizing: border-box;
  top: -6.3%!important;
  left: -6.3%!important;
  border: 2.5px solid #faa61a!important;
  border-radius: 5px !important;
  background: none;
  opacity: 1 !important;
  animation: Away 3s linear infinite !important;
}

/* STREAM */

.streaming-2_dnHe:not(.statusProfile-3ynqtt):not(.status-3fQvEa):not(.popout-2fzvxG) {
  width: 114%!important;
  height: 114%!important;
  box-sizing: border-box;
  top: -6.3%!important;
  left: -6.3%!important;
  border: 2.5px solid #593695!important;
  border-radius: 5px !important;
  background: none;
  opacity: 1 !important;
  animation: Stream 3s linear infinite !important;
}

/* OFFLINE */

.invisible-1kp8Z0:not(.statusProfile-3ynqtt):not(.status-3fQvEa):not(.popout-2fzvxG), .offline-3qoTek:not(.statusProfile-3ynqtt):not(.status-3fQvEa):not(.popout-2fzvxG) {
  width: 114%!important;
  height: 114%!important;
  box-sizing: border-box;
  top: -6.3%!important;
  left: -6.3%!important;
  border: 2.5px solid #747f8d!important;
  border-radius: 5px !important;
  background: none;
  opacity: 1 !important;
  animation: Offline 3s linear infinite !important;
}

/* Status Popup */

.status-3fQvEa {
  display: none;
}

/* User Status 3 */

.avatar-large {
  border: 2.5px solid var(--Main-Colour) !important;
  width: 32px;
  height: 32px;
  border-radius: 4px !important;
  background-size: cover !important;
  margin-left: 3px !important;
  left: -5.2px;
}

.theme-dark .members-1998pB {
  background-color: transparent !important;
}

.placeholderAvatar-uzH8f6, .placeholderUsername-236yYU {
  background: var(--Secondary-Main-Colour)!important;
}

.memberGroupsPlaceholder-3mwPub {
  -webkit-animation: none!important;
  animation: none!important;
  background: transparent!important;
  background-size: 0% 0%!important;
}

.memberGroupsPlaceholder-3mwPub:after {
  content: 'Loading...';
  font-size: 13px;
  font-weight: 700;
  position: absolute;
  width: 4000px;
  top: 15px;
  padding-left: 3px;
  border-radius: 3px !important;
  color: var(--Main-Colour) !important;
  margin-left: 2px !important;
  padding-top: 0px !important;
  white-space: wrap !important;
  font-size: 12px !important;
  margin-top: 13px !important;
  text-transform: uppercase !important;
  height: 20px !important;
}

.placeholder-oNR4zO.member-3W1lQa {
  -webkit-animation: none!important;
  animation: rainbow 3.2s ease-in-out infinite!important;
}

.placeholder-oNR4zO.member-3W1lQa:nth-child(1n) {
  -webkit-animation-delay: .1s!important;
  animation-delay: .1s!important
}

.placeholder-oNR4zO.member-3W1lQa:nth-child(2n) {
  -webkit-animation-delay: .2s!important;
  animation-delay: .2s!important
}

.placeholder-oNR4zO.member-3W1lQa:nth-child(3n) {
  -webkit-animation-delay: .3s!important;
  animation-delay: .3s!important
}

.placeholder-oNR4zO.member-3W1lQa:nth-child(4n) {
  -webkit-animation-delay: .4s!important;
  animation-delay: .4s!important
}

.placeholder-oNR4zO.member-3W1lQa:nth-child(5n) {
  -webkit-animation-delay: .5s!important;
  animation-delay: .5s!important
}

.placeholder-oNR4zO.member-3W1lQa:nth-child(6n) {
  -webkit-animation-delay: .6s!important;
  animation-delay: .6s!important
}

.placeholder-oNR4zO.member-3W1lQa:nth-child(7n) {
  -webkit-animation-delay: .7s!important;
  animation-delay: .7s!important
}

.placeholder-oNR4zO.member-3W1lQa:nth-child(8n) {
  -webkit-animation-delay: .8s!important;
  animation-delay: .8s!important
}

.placeholder-oNR4zO.member-3W1lQa:nth-child(9n) {
  -webkit-animation-delay: .9s!important;
  animation-delay: .9s!important
}

.placeholder-oNR4zO.member-3W1lQa:nth-child(10n) {
  -webkit-animation-delay: 1s!important;
  animation-delay: 1s!important
}

.placeholder-oNR4zO.member-3W1lQa:nth-child(11n) {
  -webkit-animation-delay: 1.1s!important;
  animation-delay: 1.1s!important
}

.placeholder-oNR4zO.member-3W1lQa:nth-child(12n) {
  -webkit-animation-delay: 1.2s!important;
  animation-delay: 1.2s!important
}

.placeholder-oNR4zO.member-3W1lQa:nth-child(13n) {
  -webkit-animation-delay: 1.3s!important;
  animation-delay: 1.3s!important
}

.placeholder-oNR4zO.member-3W1lQa:nth-child(14n) {
  -webkit-animation-delay: 1.4s!important;
  animation-delay: 1.4s!important
}

.placeholder-oNR4zO.member-3W1lQa:nth-child(15n) {
  -webkit-animation-delay: 1.5s!important;
  animation-delay: 1.5s!important
}

.placeholder-oNR4zO.member-3W1lQa:nth-child(16n) {
  -webkit-animation-delay: 1.6s!important;
  animation-delay: 1.6s!important
}

.placeholder-oNR4zO.member-3W1lQa:nth-child(17n) {
  -webkit-animation-delay: 1.7s!important;
  animation-delay: 1.7s!important
}

.placeholder-oNR4zO.member-3W1lQa:nth-child(18n) {
  -webkit-animation-delay: 1.8s!important;
  animation-delay: 1.8s!important
}

.placeholder-oNR4zO.member-3W1lQa:nth-child(19n) {
  -webkit-animation-delay: 1.9s!important;
  animation-delay: 1.9s!important
}

.placeholder-oNR4zO.member-3W1lQa:nth-child(20n) {
  -webkit-animation-delay: 2s!important;
  animation-delay: 2s!important
}

.placeholder-oNR4zO.member-3W1lQa:nth-child(21n) {
  -webkit-animation-delay: 2.1s!important;
  animation-delay: 2.1s!important
}

.placeholder-oNR4zO.member-3W1lQa:nth-child(22n) {
  -webkit-animation-delay: 2.2s!important;
  animation-delay: 2.2s!important
}

.placeholder-oNR4zO.member-3W1lQa:nth-child(23n) {
  -webkit-animation-delay: 2.3s!important;
  animation-delay: 2.3s!important
}

.placeholder-oNR4zO.member-3W1lQa:nth-child(24n) {
  -webkit-animation-delay: 2.4s!important;
  animation-delay: 2.4s!important
}

.placeholder-oNR4zO.member-3W1lQa:nth-child(25n) {
  -webkit-animation-delay: 2.5s!important;
  animation-delay: 2.5s!important
}

.placeholder-oNR4zO.member-3W1lQa:nth-child(26n) {
  -webkit-animation-delay: 2.6s!important;
  animation-delay: 2.6s!important
}

.placeholder-oNR4zO.member-3W1lQa:nth-child(27n) {
  -webkit-animation-delay: 2.7s!important;
  animation-delay: 2.7s!important
}

.placeholder-oNR4zO.member-3W1lQa:nth-child(28n) {
  -webkit-animation-delay: 2.8s!important;
  animation-delay: 2.8s!important
}

.placeholder-oNR4zO.member-3W1lQa:nth-child(29n) {
  -webkit-animation-delay: 2.9s!important;
  animation-delay: 2.9s!important
}

.placeholder-oNR4zO.member-3W1lQa:nth-child(30n) {
  -webkit-animation-delay: 3s!important;
  animation-delay: 3s!important
}

.placeholder-oNR4zO.member-3W1lQa:nth-child(31n) {
  -webkit-animation-delay: 3.1s!important;
  animation-delay: 3.1s!important
}

.placeholder-oNR4zO.member-3W1lQa:nth-child(32n) {
  -webkit-animation-delay: 3.2s!important;
  animation-delay: 3.2s!important
}

.theme-dark .popout .messages-popout-wrap .messages-popout .message-group {
  border-color: var(--Main-Colour)!important;
}

.theme-dark .message-group .comment .markup-2BOw-j pre {
  border-color: var(--Secondary-Main-Colour)!important;
  background: var(--Background-Colour)!important;
}

.theme-dark .messages-popout-wrap .messages-popout .message-group .action-buttons .jump-button {
  background-color: var(--Background-Colour)!important;
  color: var(--Secondary-Main-Colour)!important;
  border: 1px solid var(--Secondary-Main-Colour)!important;
}

.theme-dark .messages-popout-wrap .messages-popout .message-group .action-buttons .jump-button:hover {
  background-color: var(--Background-Colour)!important;
  color: var(--Main-Colour)!important;
  border: 1px solid var(--Main-Colour)!important;
}

.theme-dark .popout .messages-popout-wrap .messages-popout .message-group {
  border-color: var(--Secondary-Main-Colour)!important;
}

.theme-dark .popout .messages-popout-wrap .messages-popout .message-group:hover {
  border-color: var(--Main-Colour)!important;
}

.theme-dark .callAvatarWrapper-TICyxO .ripple-2djlB0 {
  background-color: transparent;
  border: 1px solid var(--Secondary-Main-Colour);
}

.callAvatar-v-u4BM.voice-3qolcc {
  border-radius: 7px;
}

.callAvatarBorder-1D_KaE.voice-3qolcc.speaking-dRlv0T, .callAvatarBorder-1D_KaE.video-WCePbA.speaking-dRlv0T {
  -webkit-box-shadow: inset 0 0 0 2px var(--Main-Colour);
  border-radius: 7px;
  box-shadow: inset 0 0 0 2px var(--Main-Colour);
}

.callAvatarWrapper-TICyxO.voice-3qolcc .ripple-2djlB0 {
  border-radius: 7px;
}

.nameTag-m8r81H, .username-1cB_5E {
  white-space: pre-wrap!important;
}

.theme-dark .friends-table .messages .message-group-blocked .message-group-blocked-btn:hover, .theme-dark .messagesWrapper-3lZDfY .messages .message-group-blocked .message-group-blocked-btn:hover {
  background: var(--Secondary-Background-Colour);
}

[style*="avatars/187615613944856576"].avatar-large+.comment h2 strong {
  text-shadow: 0 0 6px rgba(0, 0, 0, .6), 0 0 6px rgba(0, 0, 0, .6), 0 0 5px rgba(0, 0, 0, .6), 0 0 4px rgba(0, 0, 0, .6);
}

.theme-dark .imageError-2OefUi {
  background: url(https://nfld99.com/Bkg/96Ymjfy.png) 50% 50%/contain;
  background-repeat: no-repeat!important;
}

.backgroundBlur-dazcBE, .theme-dark .pictureInPictureVideo-20ZvXn {
  background: transparent!important;
}

.backgroundBlurOverlay-1JS5RF, .backgroundBlur-dazcBE, .theme-dark .pictureInPictureVideo-20ZvXn, .private-channel-call .private-channel-call-video-wrapper, .wrapper-3eE7AX, .video-1kutKI {
  background-color: transparent;
}

.theme-dark .body-1SVoBw {
  Display: none;
}

.theme-dark .gameName-1W6Ym- {
  color: var(--Main-Colour);
}

.theme-dark .publisher-2ZxPEd {
  color: var(--Secondary-Main-Colour);
}

.theme-dark .gamePreview-9weYR2 {
  border: 1px solid var(--Secondary-Main-Colour);
  border-radius: 3px!important;
}

.uploadModal-2ifh8j .inner-1-09ZV, .theme-dark .filename-3eBB_v, .controls-2g-WJ6, .wrapperPaused-3y2mev, .wrapperPlaying-2LSSsa {
  color: var(--Main-Colour);
}

.theme-dark .size-1Arx_I {
  color: var(--Secondary-Main-Colour);
}

.progress-3Rbvu0 {
  background: var(--Secondary-Background-Colour)!important;
}

.progressBar-3u8FBM.small-1CUeBa {
  background: var(--Secondary-Main-Colour)!important;
}

.icon-1kp3fr {
  display: none;
}

.activityName-1IaRLn {
  color: var(--Main-Colour);
}

.theme-dark .attachment-33OFj0 {
  background: var(--Secondary-Background-Colour)!important;
  border: 1px solid var(--Secondary-Main-Colour);
}

.member-3W1lQa {
  height: initial!important;
  min-height: 0px!important;
  overflow: visible!important;
  transition: all 400ms ease-in-out!important;
  border-bottom: 1px solid var(--Secondary-Main-Colour);
}

.member-3W1lQa:hover {
  border-bottom: 1px solid var(--Main-Colour);
  transition: all 200ms ease-in-out!important;
}

.member-3W1lQa {
  height: initial!important;
}

.membersGroup-v9BXpm {
  margin-top: 0!important;
}

.activityText-sLG0UL {
  white-space: pre-wrap;
}

.themeDark-3Ap_7i {
  background-color: var(--Background-Colour);
  background-image: url(https://media.giphy.com/media/XMc1Ui9rAFR1m/source.gif);
  color: var(--Main-Colour);
}

.channelNotices-41mJbj .channelNotice-1-XFjC.invite-1D-l1h.new-R6EGhf, .channelNotices-41mJbj .channelNotice-1-XFjC.invite-1D-l1h.new-R6EGhf .headerTint-2TF8xq, .channelNotices-41mJbj .channelNotice-1-XFjC.invite-1D-l1h.new-R6EGhf .message-1SsTiA {
  background: var(--Background-Colour);
  color: var(--Main-Colour);
}

.channelNotices-41mJbj .channelNotice-1-XFjC.invite-1D-l1h.new-R6EGhf .message-1SsTiA .inviteInput-10_P2g {
  background: var(--Secondary-Background-Colour);
  color: var(--Secondary-Main-Colour);
  border: 1px solid var(--Secondary-Main-Colour);
}

.channelNotices-41mJbj .channelNotice-1-XFjC.invite-1D-l1h.new-R6EGhf .message-1SsTiA .inviteInput-10_P2g:hover {
  background: var(--Background-Colour);
  color: var(--Main-Colour);
  border: 1px solid var(--Main-Colour);
}

.search-bar .search-bar-inner {
  border: 1px solid var(--Main-Colour);
}

.theme-dark .inviteRow-2poi6Q:hover {
  background: var(--Background-Colour);
}

.theme-dark .inviteRowName-1P-Jpg {
  color: var(--Main-Colour);
}

.lookOutlined-3sRXeN.colorGreen-29iAKY:active {
  color: var(--Secondary-Main-Colour);
  border-color: var(--Secondary-Main-Colour);
}

.theme-dark .checkBoxLabel-PnMaNi, .theme-dark .footerText-1FMLWO {
  color: var(--Secondary-Main-Colour);
}

.search-bar input {
  color: var(--Main-Colour);
}

.channelNotices-41mJbj .channelNotice-1-XFjC {
  padding-top: 2px;
}

.item-1GzJrl.invite-YM1l0n {
  color: var(--Secondary-Main-Colour);
}

.item-1GzJrl:hover.invite-YM1l0n {
  color: var(--Main-Colour);
}

.popout {
  box-shadow: none;
}

.theme-dark .searchPopout-1vUlP3 {
  border: 1px solid var(--Secondary-Main-Colour);
  background: var(--Background-Colour);
}

.theme-dark .resultsGroup-r_nuzN .header-1pJ5N1 {
  color: var(--Main-Colour);
}

.theme-dark .searchOption-zQ-1l6 .filter-3Y_im-, .theme-dark .option-96V44q .answer-9L5NhD, .theme-dark .option-96V44q .nonText-1oayCI, .theme-dark .option-96V44q strong {
  color: var(--Main-Colour);
}

.theme-dark .searchOption-zQ-1l6 .answer-1n6g43, .theme-dark .option-96V44q .filter-3kZ3tT, .theme-dark .searchResultChannelCategory-1l0lSn, .theme-dark .searchResultChannelIcon-1DnTme {
  color: var(--Secondary-Main-Colour);
}

.theme-dark .option-96V44q.selected-_bTXUG {
  background: linear-gradient(to right, transparent, var(--Background-Colour), var(--Secondary-Main-Colour));
}

.theme-dark .option-96V44q.selected-_bTXUG:before {
  display: none;
}

.theme-dark .calendarPicker-2yf6Ci .react-datepicker {
  background: var(--Background-Colour);
}

.theme-dark .calendarPicker-2yf6Ci .react-datepicker__header {
  border: none;
  background: var(--Background-Colour);
}

.theme-dark .calendarPicker-2yf6Ci .react-datepicker__day.react-datepicker__day--disabled, .theme-dark .calendarPicker-2yf6Ci .react-datepicker__day.react-datepicker__day--disabled:hover {
  color: var(--Secondary-Main-Colour);
  background: var(--Background-Colour);
}

.theme-dark .calendarPicker-2yf6Ci .react-datepicker__day {
  border-left-color: var(--Secondary-Main-Colour);
  border-top-color: var(--Secondary-Main-Colour);
  color: var(--Main-Colour);
}

.theme-dark .calendarPicker-2yf6Ci .react-datepicker__day.react-datepicker__day--selected:hover, .theme-dark .calendarPicker-2yf6Ci .react-datepicker__day:hover {
  color: var(--Main-Colour);
  background: var(--Background-Colour);
  border: 1px solid var(--Main-Colour)!important;
}

.theme-dark .calendarPicker-2yf6Ci .react-datepicker__day.react-datepicker__day--selected:after {
  background-color: var(--Main-Colour);
}

.theme-dark .calendarPicker-2yf6Ci .react-datepicker__week .react-datepicker__day:last-of-type {
  border-right-color: var(--Secondary-Main-Colour);
}

.theme-dark .calendarPicker-2yf6Ci .react-datepicker__week:last-of-type .react-datepicker__day {
  border-bottom-color: var(--Secondary-Main-Colour);
}

.theme-dark .calendarPicker-2yf6Ci .react-datepicker__current-month {
  color: var(--Main-Colour);
  border: none;
}

.theme-dark .calendarPicker-2yf6Ci .react-datepicker__navigation.react-datepicker__navigation--next, .theme-dark .calendarPicker-2yf6Ci .react-datepicker__navigation.react-datepicker__navigation--previous {
  color: var(--Main-Colour);
  border: none;
}

.theme-dark .calendarPicker-2yf6Ci .react-datepicker__day-name {
  color: var(--Main-Colour);
}

.theme-dark .popout .messages-popout-wrap .footer {
  display: none;
}

.messages-popout .empty-placeholder .image {
  display: none;
}

.theme-dark .popout .messages-popout-wrap .messages-popout .empty-placeholder .body {
  color: var(--Secondary-Main-Colour);
}

.theme-dark .datePicker--XZbmJ .datePickerHint-1iW7Wz {
  display: none;
}

.theme-dark .search .search-bar .public-DraftEditorPlaceholder-root {
  color: var(--Secondary-Main-Colour);
}

.theme-dark .option-96V44q.user-1TwSRF .displayedNick-1487Dr {
  color: var(--Main-Colour);
}

.theme-dark .option-96V44q.user-1TwSRF .displayUsername-3PmTeH {
  color: var(--Secondary-Main-Colour);
}

.theme-dark .keybindShortcut-1BD6Z1 span {
  color: var(--Main-Colour);
  background: var(--Background-Colour);
}

.theme-dark .searchQuery-1B7rtx {
  color: var(--Main-Colour);
}

.theme-dark .search-results-wrap .search-result .hit {
  box-shadow: none;
}

.theme-dark .search-results-wrap .search-header {
  box-shadow: none;
}

.theme-dark .search-results-wrap .search-header .tab, .theme-dark .search-results-wrap .search-header .total-results {
  color: var(--Main-Colour);
}

.theme-dark .search-results-wrap .search-header .tab.selected, .theme-dark .search-results-wrap .search-header .tab:hover {
  border: none;
  background: linear-gradient(to bottom, transparent, var(--Background-Colour), var(--Background-Colour), var(--Background-Colour), var(--Secondary-Main-Colour));
}

.typeWindows-1za-n7.titleBar-AC4pGV.horizontalReverse-3tRjY7.flex-1O1GKY.directionRowReverse-m8IjIq.justifyStart-2NDFzi.alignStretch-DpGPf3>div:nth-child(4)>svg>rect {
  stroke: var(--Secondary-Main-Colour)!important;
}

.typeWindows-1za-n7.titleBar-AC4pGV.horizontalReverse-3tRjY7.flex-1O1GKY.directionRowReverse-m8IjIq.justifyStart-2NDFzi.alignStretch-DpGPf3>div:nth-child(5)>svg>rect {
  fill: var(--Secondary-Main-Colour)!important;
}

[class*="winButton"]:hover {
  background: transparent;
}

.theme-dark .modalTitle-37O4n6 {
  background-color: var(--Background-Colour);
}

.theme-dark .keyboardShortcutList-13cQ-8 .keybindGroup-BB3G2K .keybindDescription-2RDbC2 {
  border: none;
  color: var(--Secondary-Main-Colour);
}

.theme-dark .keyboardShortcutList-13cQ-8 .keybindGroup-BB3G2K .keybindDescription-2RDbC2, .theme-dark .modalSubtitle-1Pj5nv {
  color: var(--Main-Colour);
}

.fade>div>div>div:nth-child(26)>div.keybindDescription-2RDbC2 {
  font-size: 0;
}

.fade>div>div>div:nth-child(26)>div.keybindDescription-2RDbC2:after {
  content: "<3 Donator Easter Egg <3";
  font-size: 12px;
}

.theme-dark .messagesPopoutWrap-1MQ1bW, .theme-dark .messagesPopoutWrap-1MQ1bW .header-ykumBX {
  background: var(--Background-Colour);
}

.icon-2doZ3q {
  background: none!important;
  display: initial!important;
  width: 1px;
  margin-right: 4px;
}

.popout-3sVMXz {
  box-shadow: none;
}

.theme-dark .item-1GzJrl:hover {
  background: var(--Background-Colour);
  color: var(--Main-Colour);
}

.theme-dark .item-1GzJrl.invite-YM1l0n, .theme-dark .item-1GzJrl {
  color: var(--Secondary-Main-Colour);
}

.theme-dark .item-1GzJrl.invite-YM1l0n:hover, .theme-dark .item-1GzJrl:hover {
  color: var(--Main-Colour);
}

.popout-3sVMXz .popoutBottom-U6AdMj {
  width: calc(100% + 10px) !important;
}

.theme-dark .messagesPopoutWrap-1MQ1bW .header-ykumBX .title-1SAkRa, .theme-dark .mentionFilter-1PQ6ey .value-NdVIa2, .theme-dark .messagesPopoutWrap-1MQ1bW .messagesPopout-24nkyi .channelSeparator-1MxuvT .channelName-3kBz6H {
  color: var(--Main-Colour);
}

.theme-dark .headerTabBarWrapper-27xBDe .tab-bar.TOP .tab-bar-item, .theme-dark .mentionFilter-1PQ6ey .label-3EbduD, .theme-dark .messagesPopoutWrap-1MQ1bW .messagesPopout-24nkyi .channelSeparator-1MxuvT .guildName-1Bc3Ta {
  color: var(--Secondary-Main-Colour);
}

.theme-dark .messagesPopoutWrap-1MQ1bW .messagesPopout-24nkyi .message-group {
  border-color: var(--Secondary-Main-Colour);
}

.theme-dark .messagesPopoutWrap-1MQ1bW .messagesPopout-24nkyi .message-group:hover {
  border-color: var(--Main-Colour);
}

.theme-dark .messagesPopoutWrap-1MQ1bW .messagesPopout-24nkyi .message-group:hover .actionButtons-1sUUug {
  -webkit-box-shadow: none;
  background-color: var(--Background-Colour);
  box-shadow: none;
}

.theme-dark .messagesPopoutWrap-1MQ1bW .messagesPopout-24nkyi .message-group .actionButtons-1sUUug .jumpButton-3DTcS_ {
  color: var(--Secondary-Main-Colour);
  background: var(--Background-Colour);
  border: 1px solid var(--Secondary-Main-Colour);
}

.theme-dark .messagesPopoutWrap-1MQ1bW .messagesPopout-24nkyi .message-group .actionButtons-1sUUug .jumpButton-3DTcS_:hover {
  color: var(--Main-Colour);
  background: var(--Background-Colour);
  border: 1px solid var(--Main-Colour);
}

.theme-dark .messagesPopoutWrap-1MQ1bW .footer-1kmXd4 {
  display: none;
}

.scrollingFooterWrap-3FDlMn {
  display: none;
}

.theme-dark .messagesPopoutWrap-1MQ1bW .messagesPopout-24nkyi .emptyPlaceholder-1zh-Eu .body-bvcIjN {
  font-size: 0;
}

.theme-dark .messagesPopoutWrap-1MQ1bW .messagesPopout-24nkyi .emptyPlaceholder-1zh-Eu .body-bvcIjN:after {
  content: " Nothing to see here.";
  color: var(--Main-Colour);
  font-size: 15px;
}

.image-2JDb81 {
  background: var(--Background-Colour)!important;
}

.theme-dark .messagesPopoutWrap-1MQ1bW .messagesPopout-24nkyi {
  -webkit-box-shadow: none;
  box-shadow: none;
  color: var(--Main-Colour);
  background: var(--Background-Colour);
  border: 1px solid var(--Main-Colour);
}

.theme-dark .messagesPopoutWrap-1MQ1bW .hasMore-sul95G button, .theme-dark .messagesPopoutWrap-1MQ1bW .hasMore-sul95G button {
  color: var(--Secondary-Main-Colour);
  background: var(--Background-Colour);
  border: 1px solid var(--Secondary-Main-Colour);
}

.hasMore-sul95G button {
  color: var(--Secondary-Main-Colour);
  background: var(--Background-Colour);
}

.theme-dark .messagesPopoutWrap-1MQ1bW .header-ykumBX {
  -webkit-box-shadow: none;
  box-shadow: none;
}

.theme-dark .subtitle-2BzAeG {
  background-color: transparent;
}

.theme-dark .subtitle-Qv5s8c, .theme-dark .subtitle-Qv5s8c {
  font-size: 0;
  color: var(--Main-Colour);
}

.theme-dark .subtitle-Qv5s8c:after {
  content: "Jammin Out With";
  font-size: 13px;
}

.avatarMasked-3y6o4j {
  -webkit-mask-image: none!important;
  mask-image: none!important;
}

.avatarDefault-35WC3R, .avatarSpeaking-1wJCNq {
  border-radius: 5px;
}

.bda-dark .emoji-picker, .bda-dark .emojiPicker-3m1S-j {
  background-color: var(--Popout-Background);
}

.bda-dark .emoji-picker .category, .bda-dark .emojiPicker-3m1S-j .category-2U57w6 {
  background-color: var(--Secondary-Background-Colour);
}

.emojiPicker-3m1S-j .category-2U57w6 {
  color: var(--Main-Colour);
}

.emojiPicker-3m1S-j .stickyHeader-3LjM5X {
  background-color: transparent;
}

.contentHoveredText-2D9B-x, .contentHoveredVoice-3p_NEO:active, .contentSelectedVoice-1WDIBM:active {
  background: linear-gradient(to right, transparent, var(--Background-Colour), var(--Notification-Colour));
}

.contentUnreadText-2vNnZc:hover, .contentUnreadText-2vNnZc {
  background: linear-gradient(to left, transparent, var(--Background-Colour), var(--Notification-Colour));
}

.unread-1Dp-OI {
  content: "";
  width: calc(100% - 36px - 8px);
  height: 150%;
  position: absolute;
  display: block;
  left: 53px;
  top: 1px;
  background: linear-gradient(to right, transparent, var(--Secondary-Background-Colour), var(--Notification-Colour), var(--Secondary-Background-Colour), transparent);
  animation: shakeUnread 2s ease-in-out infinite alternate;
}

.iconCollapsed-3hFp_8, .iconDefault-3Gr8d2, .nameCollapsed-34uFWo, .nameDefault-2DI02H, .theme-dark .activityProfile-2bJRaP .content-3JfFJh, .theme-dark .activityProfile-2bJRaP .details-38sfDr, .theme-dark .activityProfile-2bJRaP .name-29ETJS, .theme-dark .activityUserPopout-2yItg2 .content-3JfFJh, .theme-dark .activityUserPopout-2yItg2 .details-38sfDr, .theme-dark .activityUserPopout-2yItg2 .name-29ETJS, .theme-light .activityProfile-2bJRaP .content-3JfFJh, .theme-light .activityProfile-2bJRaP .details-38sfDr, .theme-light .activityProfile-2bJRaP .name-29ETJS, .theme-light .activityUserPopout-2yItg2 .content-3JfFJh, .theme-light .activityUserPopout-2yItg2 .details-38sfDr, .theme-light .activityUserPopout-2yItg2 .name-29ETJS, .theme-dark .item-1GzJrl.invite-271nFU, .theme-dark .mentionFilter-1PQ6ey .label-12YslM {
  color: var(--Secondary-Main-Colour)!important;
}

.iconHovered-2L3-fB, .iconHoveredCollapsed-3caIIZ, .nameHovered-1gxhWH, .nameHoveredCollapsed-2orEWB, .theme-dark .activityProfile-2bJRaP .headerText-1HLrL7, .theme-dark .activityUserPopout-2yItg2 .headerText-1HLrL7, .theme-light .activityProfile-2bJRaP .headerText-1HLrL7, .theme-light .activityUserPopout-2yItg2 .headerText-1HLrL7, .theme-dark .item-1GzJrl:hover.invite-271nFU, .theme-dark .topic-2QX7LI, .theme-dark .itemDefault-3Jdr52:not(.role-3wi9Tf), .theme-dark .itemHover-EnbcjT {
  color: var(--Main-Colour)!important;
}

.theme-dark .topSectionNormal-2-vo2m {
  background: transparent;
}

.theme-dark .emptyIconFriends-BrjhY9 {
  display: none;
}

.theme-dark .side-8zPYf6 .itemDefault-3Jdr52:hover, .theme-dark .side-8zPYf6 .itemHover-EnbcjT:hover, .contentHoveredVoice-3p_NEO, .contentSelectedVoice-1WDIBM {
  background: linear-gradient(to right, transparent, var(--Background-Colour), var(--Main-Colour));
  color: var(--Main-Colour);
}

.lookOutlined-3sRXeN.colorWhite-rEQuAQ {
  color: var(--Secondary-Main-Colour);
  border-color: var(--Secondary-Main-Colour);
}

.lookGhost-2Fn_0-.colorGrey-2DXtkV {
  color: var(--Secondary-Main-Colour);
  border-color: var(--Secondary-Main-Colour);
}

.lookGhost-2Fn_0-.colorBrand-3pXr91 {
  color: var(--Main-Colour);
  border-color: var(--Main-Colour);
}

.theme-dark .emoji-alias-input .emoji-input {
  background: var(--Background-Colour);
}

.theme-dark .emoji-alias-placeholder {
  color: var(--Main-Colour);
}

.content-1rPSz4 {
  color: var(--Main-Colour)!important;
}

.theme-dark .friends-table .messages .divider.divider-red>span, .theme-dark .messagesWrapper-3lZDfY .messages .divider.divider-red>span, .theme-dark .friends-table .messages .divider:not(.red) span, .theme-dark .messagesWrapper-3lZDfY .messages .divider:not(.red) span {
  color: var(--Main-Colour);
}

.theme-dark .friends-table .messages .divider:before, .theme-dark .friends-table .messages .divider span, .theme-dark .messagesWrapper-3lZDfY .messages .divider:before, .theme-dark .messagesWrapper-3lZDfY .messages .divider span {
  background: var(--Background-Colour);
}

.theme-dark .friends-table .messages .divider.divider-red>div, .theme-dark .messagesWrapper-3lZDfY .messages .divider.divider-red>div, .theme-dark .friends-table .messages .divider:not(.red) div, .theme-dark .messagesWrapper-3lZDfY .messages .divider:not(.red) div {
  background: var(--Background-Colour);
}

.theme-dark .iconForeground-3y9f0B, .theme-dark .title-1aVOXw, .theme-dark .messagesPopoutWrap-1MQ1bW .header-ykumBX .title-3pkaKd, .theme-dark .mentionFilter-1PQ6ey .value-2k8Drt, .theme-dark .mentionFilter-1PQ6ey {
  color: var(--Main-Colour)!important;
}

.nameHovered-21k1eo, .nameSpeaking-3UhoEZ {
  color: var(--Main-Colour);
}

.popout-3sVMXz header, .popout-3sVMXz section {
  background: transparent;
  color: var(--Popout-Main-Colour);
}

.container-3nXdBP section p {
  color: var(--Popout-Main-Colour);
}

.container-3nXdBP {
  background: var(--Popout-Background);
}

.container-3nXdBP hr {
  border: none;
}

.theme-dark .item-30Gz8g {
  color: var(--Main-Colour)!important;
}

.theme-dark .itemValue-JNy0LV {
  color: var(--Secondary-Main-Colour)!important;
}

.theme-dark .modalTitle-37O4n6 {
  background: transparent;
}

.theme-dark .modalTitle-37O4n6 {
  color: var(--Main-Colour);
}

.theme-dark .keyboardShortcutList-13cQ-8 .keybindGroup--6Qp-w .keybindDescription-2RDbC2 {
  color: var(--Main-Colour)!important;
}

.theme-dark .option-96V44q.selected-rZcOL- {
  background: linear-gradient(to right, transparent, var(--Background-Colour), var(--Main-Colour));
  color: var(--Main-Colour);
}

.theme-dark .option-96V44q .answer-1n6g43, .theme-dark .option-96V44q .nonText-3CRkO0, .theme-dark .option-96V44q strong, .theme-dark .resultsGroup-r_nuzN .header-2N-gMV, .theme-dark .datePicker--XZbmJ .datePickerHint-3Q1Udw .hint-165cR4 {
  color: var(--Main-Colour)!important;
}

.theme-dark .option-96V44q .filter-3Y_im- {
  color: var(--Secondary-Main-Colour)!important;
}

.theme-dark .datePicker--XZbmJ .datePickerHint-3Q1Udw .hintValue-29ny8Z {
  background-color: var(--Secondary-Background-Colour);
  color: var(--Secondary-Main-Colour);
  border: 1px solid var(--Secondary-Main-Colour);
}

.theme-dark .datePicker--XZbmJ .datePickerHint-3Q1Udw .hintValue-29ny8Z:hover {
  background-color: var(--Background-Colour);
  color: var(--Main-Colour);
  border: 1px solid var(--Main-Colour);
}

.theme-dark .calendarPicker-2yf6Ci .react-datepicker__day--disabled, .theme-dark .calendarPicker-2yf6Ci .react-datepicker__day--outside-month {
  background: transparent;
}

.iconMuted-1HVBGH, .nameMuted-1MCOt4 {
  color: var(--Secondary-Main-Colour);
}

.bda-dark .emoji-picker, .bda-dark .emojiPicker-3m1S-j {
  background: var(--Popout-Background) 50% 50%/cover!important;
}

.emojiPicker-3m1S-j .category-2U57w6 {
  color: var(--Main-Colour);
}

.emojiPicker-3m1S-j .stickyHeader-1SS0JU {
  background: transparent;
}

.emojiPicker-3m1S-j .scroller-3vODG7 .emojiItem-109bjA.selected-39BZ4S {
  background-color: var(--Secondary-Background-Colour);
}

.scrollerThemed-2oenus.themeLight-1_DWyY.scrollerTrack-1ZIpsv>.scroller-2FKFPG::-webkit-scrollbar-track, .theme-dark .scrollerThemed-2oenus.themeLight-1_DWyY.scrollerTrack-1ZIpsv>.scroller-2FKFPG::-webkit-scrollbar-track, .theme-light .scrollerWrap-2lJEkd.scrollerTrack-1ZIpsv>.scroller-2FKFPG::-webkit-scrollbar-track {
  background: transparent;
}

.emojiPicker-3m1S-j .categories-1feg4n .item-16cXuq.selected-39BZ4S {
  border-bottom-color: var(--Main-Colour);
}

.search-bar.search-bar-light input {
  color: var(--Main-Colour);
}

.emojiPicker-3m1S-j .no-search-results .sad-discord {
  display: none;
}

.emojiPicker-3m1S-j .no-search-results, .theme-dark .userSettingsAccount-2eMFVR .viewBody-2Qz-jg {
  color: var(--Main-Colour);
}

.userSettingsAccount-2eMFVR>div>div>div>div:nth-child(2)>div:nth-child(2)>div:nth-child(2):hover {
  transition: filter .15s ease-in-out;
}

.userSettingsAccount-2eMFVR>div>div>div>div:nth-child(2)>div:nth-child(2)>div:nth-child(2):not(:hover) {
  filter: blur(6px);
  transition: filter .15s ease-in-out;
}

.lookInverted-2D7oAl.colorBrand-3pXr91, .lookOutlined-3sRXeN.colorBrand-3pXr91, .lookInverted-2D7oAl.colorGreen-29iAKY {
  background-color: var(--Secondary-Background-Colour);
  color: var(--Secondary-Main-Colour);
  border: 1px solid var(--Secondary-Main-Colour);
}

.lookInverted-2D7oAl.colorBrand-3pXr91:hover, .lookOutlined-3sRXeN.colorBrand-3pXr91:hover, .lookInverted-2D7oAl.colorGreen-29iAKY:hover {
  background-color: var(--Background-Colour);
  color: var(--Main-Colour);
  border: 1px solid var(--Main-Colour);
}

.premium-settings .subscription, .theme-dark .premium-settings .card-description strong {
  color: var(--Main-Colour);
}

.theme-dark .headerBar-UHpsPw {
  background: transparent;
}

.theme-dark .wrapper-1cBijl .addFriendInput-4bcerK {
  color: var(--Main-Colour);
}

.theme-dark #friends .friends-table .friend-table-add-wrapper .friend-table-add-header {
  background: transparent;
}

.theme-dark #friends .friends-table .friend-table-add-description, .theme-dark #friends .friends-table .friend-table-add-wrapper .friend-table-add-header .connect-accounts h3 {
  color: var(--Secondary-Main-Colour);
}

.theme-dark #friends .friends-table .friend-table-add-wrapper h2 {
  color: var(--Main-Colour);
}

.inner-2Y6JuD:hover {
  background-color: var(--Secondary-Background-Colour);
  border: 1px solid var(--Main-Colour);
}

.inner-2Y6JuD {
  border: 1px solid var(--Secondary-Main-Colour);
}

.theme-dark #friends .friends-table .friend-table-add-wrapper .friend-table-add-header {
  border: none;
}

#friends .friends-table .friend-table-add-wrapper .friend-table-suggestions-header {
  padding: 0px 30px 0px;
}

.theme-dark #friends .friends-empty.section-add-friend-no-connection .empty-state-image {
  display: none;
}

.theme-dark #friends .friends-empty p {
  color: var(--Main-Colour);
}

#friends .btn:hover {
  background-color: var(--Background-Colour);
  color: var(--Main-Colour);
  border: 1px solid var(--Main-Colour);
}

#friends .btn {
  background-color: var(--Secondary-Background-Colour);
  color: var(--Secondary-Main-Colour);
  border: 1px solid var(--Secondary-Main-Colour);
}

.theme-dark .connection-1fbD7X {
  background: var(--Secondary-Background-Colour)!important;
}

.theme-dark .accountBtnInner-sj5jLs:hover {
  background-color: var(--Background-Colour);
  color: var(--Main-Colour);
  border: 1px solid var(--Main-Colour);
}

.theme-dark .accountBtnInner-sj5jLs {
  background-color: var(--Secondary-Background-Colour);
  color: var(--Secondary-Main-Colour);
  border: 1px solid var(--Secondary-Main-Colour);
}

.theme-dark .card-7JP0BX {
  background-color: transparent;
  border-color: transparent;
  color: var(--Main-Colour);
}

.theme-dark .tag-10JqWu {
  color: var(--Main-Colour);
}

.theme-dark .discriminator-pIKHPn, .theme-dark .playTime-1laRtO {
  color: var(--Secondary-Main-Colour);
}

.aka-1mqp34 {
  background-color: var(--Background-Colour);
  color: var(--Main-Colour);
  border: 1px solid var(--Main-Colour);
}

*:not(.badge-2_fwUZ):not(.wrapper-232cHJ) {
  text-shadow: 0 0 1px var(--Text-Shadow-Colour), 0 0 1px var(--Text-Shadow-Colour), 0 0 1px var(--Text-Shadow-Colour), 0 0 1px var(--Text-Shadow-Colour)!important;
}

.uploadModal-2ifh8j .footer-3mqk7D {
  background: transparent;
}

.uploadModal-2ifh8j .inner-3nWsbo {
  border: none;
  color: var(--Main-Colour);
}

.uploadModal-2ifh8j .inner-3nWsbo .file-34mY5K .icon-kyxXVr.image-2yrs5j {
  border: none;
  background-color: transparent;
  width: 100%;
  height: 100%;
  margin-left: 0px;
  margin-right: 0px;
  margin-top: -3px;
  box-shadow: none;
}

.theme-dark .typing-2GQL18 span {
  color: var(--Main-Colour);
}

.uploadModal-2ifh8j .inner-3nWsbo .file-34mY5K .icon-kyxXVr.image-2yrs5j {
  background-size: contain;
}

.uploadModal-2ifh8j .inner-3nWsbo .file-34mY5K {
  height: 193px;
}

.nameUnreadText-DfkrI4, .nameUnreadVoice-EVo-wI {
  filter: brightness(1.5)
}

.theme-dark .keyboardShortcutsModal-3piNz7 {
  background-color: var(--Secondary-Background-Colour);
}

.nameMutedText-3Vj4bM, .nameMutedVoice-3oxyQZ {
  color: var(--Secondary-Main-Colour);
}

.theme-dark .descriptionDiscriminator-3vUOCc, .theme-dark .description-11DmNu, .theme-dark .descriptionUsername-J_75O8 {
  color: var(--Secondary-Main-Colour);
}

.theme-dark .description-11DmNu, .theme-dark .descriptionUsername-J_75O8, .theme-dark .contentTitle-2tG_sM, .marginLeft8-1YseBe {
  color: var(--Main-Colour);
}

.theme-dark .autocomplete-1vrmpx, .autocomplete-1vrmpx {
  background: var(--Popout-Background) 50% 50%/cover!important;
}

.autocompleteInner-zh20B_ {
  border: 1px solid var(--Secondary-Main-Colour);
  background: rgba(0, 0, 0, var(--Background-Darkness));
}

.theme-dark .selectorSelected-1_M1WV, .selectorSelected-1_M1WV {
  background: linear-gradient(to top, var(--Secondary-Main-Colour), transparent, transparent, transparent, var(--Secondary-Main-Colour)) !important;
}

.theme-dark .connectedAccount-36nQx7, .theme-dark .userInfoSection-2acyCx+.userInfoSection-2acyCx {
  border-color: var(--Secondary-Main-Colour);
}

.connectedAccountName-f8AEe2 {
  color: var(--Main-Colour);
}

.title-223e2Y {
  display: none;
}

.theme-dark .listeningAlong-2UPsxf {
  background: var(--Secondary-Background-Colour);
}

.inviteModal-34DdOm .avatar-xxxlarge {
  background-color: transparent;
}

.inviteModal-34DdOm .inviteTitle-2-D7Bk {
  color: var(--Main-Colour);
}

.inviteModal-34DdOm .inviteBody-1Y3j7y, .inviteModal-34DdOm .inviteCancel-3lWPwu {
  color: var(--Secondary-Main-Colour);
}

.inviteModal-34DdOm {
  width: 920px;
  animation: Popoutinvite 2s 1 linear;
}

.container-2Yth53 .button-ey5-M_ {
  width: 100%;
}

.theme-dark .pill-1dHPfk {
  background-color: var(--Secondary-Background-Colour);
}

.theme-dark .pillMessage-1btqlx {
  color: var(--Main-Colour)!important;
}

.pill-1dHPfk {
  border: 1px solid var(--Secondary-Main-Colour)!important;
}

.iconInactive-98JN5i {
  border-radius: 0%;
}

.theme-dark .contentWrapper-3WC1ID {
  background: transparent;
}

.theme-dark .contentWrapper-3WC1ID {
  background-color: var(--Secondary-Background-Colour);
  background-image: url(https://nfld99.com/Bkg/Mcvi43u.png);
  background-size: contain;
  height: 440px;
  position: relative;
  width: 920px;
  animation: Popoutinvite 2s 1 linear;
}

.image-1SwJLX.loaded-1CMjvT {
  background: var(--Callout-Background) 50% 50%/cover !important;
  filter: blur(0px);
  object-position: 9999px 9999px;
}

.canvas-3XuBXe {
  object-position: 9999px 9999px;
  background: rgba(0, 0, 0, var(--Background-Darkness)) !important;
  filter: blur(0px);
}

.wrapper-3Q5DdO {
  background: var(--Callout-Background) 50% 50%/cover !important;
  filter: blur(0px);
  object-position: 9999px 9999px;
}

.image-2jyRAK.loaded-3PtF_J {
  object-position: 9999px 9999px;
  background: rgba(0, 0, 0, var(--Background-Darkness)) !important;
  filter: blur(0px);
}

.authBox-hW6HRx {
  background: var(--Secondary-Background-Colour);
  color: var(--Secondary-Main-Colour);
}

.white-2qwKC7, .white100-1kM2ad, .white200-3zgO-Z, .white300-9aRwFJ, .white400-18yif1, .white500-2pqdDy {
  color: var(--Main-Colour);
}

.subTitle-3TUjmF {
  color: var(--Secondary-Main-Colour);
}

.wrapper-3Q5DdO {
  overflow-y: hidden;
}

.lookLink-9FtZy-.colorBrand-3pXr91 {
  color: var(--Main-Colour);
}

.logo-2iEHEq {
  background: url(https://nfld99.com/Bkg/UI9uFRU.png) 50% 50%/contain;
  background-repeat: no-repeat;
  width: 140px;
  height: 70px;
}

.theme-dark .alt-3btY0e .helper-2c73HK {
  display: none;
}

.alt-3btY0e .item-1GzJrl .statusIconText-3b4TkH {
  width: calc(100% + 20px) !important;
}

.statusIconText-3b4TkH>span {
  margin-right: 3px!important;
}

.root-3-B5F3 {
  max-height: 200px;
  overflow: scroll;
  overflow-x: hidden;
  overflow-y: auto;
}

.scrollerWrap-2lJEkd.scrollerThemed-2oenus.themeGhostHairline-DBD-2d.scrollerFade-1Ijw5y>div>div>a>div>div>span>span {
  display: inline-block;
  left: 40px;
  top: 10px
}

.root-3-B5F3:-webkit-scrollbar-track-piece {
  border: none !important;
  background: transparent !important;
  border: 1px solid var(--Scroller-Colour) !important;
}

.root-3-B5F3:-webkit-scrollbar-thumb {
  background: transparent !important;
  border: 1px solid var(--Scroller-Colour) !important;
}

.root-3-B5F3:not(:hover):-webkit-scrollbar-thumb {
  background: transparent !important;
  border: 0px solid transparent !important;
  border: 1px solid var(--Scroller-Colour) !important;
}

.root-3-B5F3:-webkit-scrollbar {
  max-width: 10px !important;
  background: transparent !important;
  border: 1px solid var(--Scroller-Colour) !important;
}

.body-3ND3kc>div>div>div>div>div>div>svg {
  display: none;
}

.theme-dark .passthroughSelected-1Eq0Kl {
  border: 1px solid #747f8d;
  background: transparent;
}

.denySelected-1mh2mZ {
  background: transparent;
}

.allowSelected-25S_i5 {
  background: transparent;
}

.bar-2Qqk5Z[style="background: rgb(251, 184, 72);"] {
  background-color: var(--Background-Colour)!important;
}

.barFill-23-gu-[style="background: rgb(105, 196, 154); width: 45.5385%;"] {
  background-color: var(--Secondary-Main-Colour)!important;
}

.userSettingsVoice-iwdUCU .inputSensitivityToggle-2LKb8o.manual-36Evg9 .microphone-2rtdHw .fill-3eUagR {
  -webkit-transition: width 35ms ease;
  background-color: var(--Main-Colour);
  height: 100%;
  transition: width 35ms ease;
}

.inviteModal-34DdOm .scroller-3__pG8 {
  background-color: var(--Secondary-Background-Colour);
  background-image: url(https://nfld99.com/Bkg/EMb6GWq.png);
  height: 100%;
  position: relative;
  width: 400px;
}

.inviteModal-34DdOm .button-ey5-M_ {
  width: 100%;
}

.theme-dark .option-96V44q.user-O3Czj0 .displayedNick-3xxvzU {
  color: var(--Main-Colour);
}

.theme-dark .option-96V44q.user-O3Czj0 .displayUsername-Qekxml {
  color: var(--Secondary-Main-Colour);
}

.theme-dark .text-GwUZgS, .theme-dark .title-2BxgL2 {
  color: var(--Main-Colour);
}

.flex-1xMQg5.flex-1O1GKY.vertical-V37hAW.flex-1O1GKY.directionColumn-35P_nr.justifyCenter-3D2jYp.alignCenter-1dQNNs.noWrap-3jynv6.wrapper-r-6rrt.margin-top-20>div.image-1GzsFd.margin-bottom-40 {
  display: none;
}

.theme-dark .verticalDockItemName-1HqTzt {
  color: var(--Main-Colour);
}

.theme-dark .headerText-2niCs_ {
  border-top: 1px solid var(--Secondary-Background-Colour);
  color: var(--Main-Colour);
}

.verticalDockItemSplash-jI35yB, .splashArt-3yFzRe, .background-17WUpK {
  -webkit-filter: grayscale(0%);
  -webkit-mask: radial-gradient(100% 100% at top left, rgba(0, 0, 0, var(--Background-Darkness)) 0, rgba(0, 0, 0, var(--Background-Darkness)) 100%);
  filter: grayscale(0%);
  mask: radial-gradient(100% 100% at top left, rgba(0, 0, 0, var(--Background-Darkness)) 0, rgba(0, 0, 0, var(--Background-Darkness)) 100%);
}

.theme-dark .verticalDockFooterText-2t4w2m {
  color: var(--Secondary-Main-Colour);
}

.theme-dark .header-1RC2Wb:hover {
  background-color: rgba(10, 10, 10, var(--Background-Darkness));
}

.splashArt-3yFzRe {
  background-size: cover;
}

.theme-dark .header-1RC2Wb {
  background-color: rgba(0, 0, 0, var(--Background-Darkness));
  border-bottom-color: rgba(32, 34, 37, .6);
}

.description-13oVu5, .subtitle-rPfx7J {
  color: var(--Secondary-Main-Colour);
}

.title-1oZsbs {
  color: var(--Main-Colour);
}

.newsLink-38Naqi:hover {
  background-color: rgba(10, 10, 10, var(--Background-Darkness));
}

.news-2GDtLJ {
  background-color: rgba(0, 0, 0, var(--Background-Darkness));
}

.theme-dark .sectionTitle-1snBOS {
  color: var(--Main-Colour);
}

.theme-dark .sectionLine-JjseS9 {
  background-color: var(--Secondary-Background-Colour);
}

.articleType-3SqiEI {
  color: var(--Secondary-Main-Colour);
}

.gameName-ZXDRa6 {
  color: var(--Main-Colour);
}

.dot-2Q_mMZ {
  background-color: var(--Main-Colour);
}

.article-FleDq5 {
  background-color: rgba(0, 0, 0, var(--Background-Darkness));
}

.background-17WUpK {
  max-width: 100%;
  min-width: 100%;
  max-height: 100%;
  min-height: 100%;
  background-size: contain!important;
}

.theme-dark .body-2iXqIL, .theme-dark .buttonHint-2OxJB8 {
  color: var(--Main-Colour);
}

.theme-dark .header-3_S6dz, .theme-dark .buttonHint-2OxJB8 strong {
  color: var(--Main-Colour);
}

.popouttop-left>form>div.footer-2aTx0s>div {
  font-size: 0;
}

.popouttop-left>form>div.footer-2aTx0s>div:after {
  content: "Maybe don't be a fuck and mention a role instead of EVERYONE?";
  color: var(--Main-Colour);
  font-size: 12px;
}

.popouttop-left>form>div.footer-2aTx0s>svg>g>path {
  fill: var(--Main-Colour);
}

.theme-dark .footer-2aTx0s {
  background-color: var(--Secondary-Background-Colour);
}

.theme-dark .everyonePopout-nEbJY3 {
  background: var(--Background-Colour)!important;
  animation: Everyone 2.5s infinite linear, Everyone2 2s 1 linear;
  text-shadow: 0 0 6px var(--Text-Shadow-Colour), 0 0 6px var(--Text-Shadow-Colour), 0 0 5px var(--Text-Shadow-Colour), 0 0 4px var(--Text-Shadow-Colour);
}

#app-mount > div.theme-dark.popouts-3dRSmE > div.noArrow-3BYQ0Z.noShadow-321ZPm.popout-3sVMXz.popoutTopLeft-b5Eb3O.popouttop-left.theme-undefined > form > div.body-2iXqIL > div.animation-3GofIz > svg > g > g > g > path{
  fill: var(--Secondary-Main-Colour)!important;
}

.bda-dark .emoji-picker, .bda-dark .emojiPicker-3m1S-j, .bda-dark #bda-qem-favourite-container, .bda-dark #bda-qem-twitch-container, .bda-dark .emoji-picker, .bda-dark .emoji-picker .category, .bda-dark .emoji-picker .header .search-bar {
  background: var(--Emote-Popout-Background) 50% 50%/cover !important;
  border: 1px solid var(--Main-Colour) !important;
}

.bda-dark #bda-qem button.active {
  background: var(--Secondary-Main-Colour) !important;
}

.emojiPicker-3m1S-j .stickyHeader-1SS0JU {
  display: none;
}

.theme-brand .content-Qb0rXO {
  color: var(--Main-Colour);
}

.iconSizeLarge-161qtT {
  height: 40px;
  width: 40px;
}

/* Thanks to Sato#4997 For this Fix */

.container-2Thooq .status-2kJpnA {
  pointer-events: none;
}

/* Thanks to Sato#4997 For this Fix */

.theme-dark .container-1rPqdX {
  background: var(--Background-Colour) !important;
  background-color: var(--Background-Colour) !important;
  border: 2px solid var(--Secondary-Main-Colour) !important;
}

.theme-dark .button-1ZXqCA:hover {
  background: var(--Background-Colour) !important;
  background-color: var(--Background-Colour) !important;
  color: var(--Main-Colour)!important;
}

.theme-dark .button-1ZXqCA {
  background: var(--Background-Colour) !important;
  background-color: var(--Background-Colour) !important;
  color: var(--Secondary-Main-Colour)!important;
}

.theme-dark .wrapper-29NfPK {
  background-color: var(--Secondary-Background-Colour);
}

.nameCollapsed-34uFWo, .nameDefault-2DI02H, .nameHovered-1gxhWH, .nameHoveredCollapsed-2orEWB, .nameMuted-1MCOt4, .nameUnread-njOjIS, .nameConnectedText-3CzNQn, .nameConnectedVoice-MHUX5F, .nameDefaultText-24KCy5, .nameDefaultVoice-3WUH7s, .nameHoveredText-1uO31y, .nameHoveredVoice-YJ1Vfd, .nameLockedText-3pqQcL, .nameLockedVoice-26MhB1, .nameMutedText-3Vj4bM, .nameMutedVoice-3oxyQZ, .nameSelectedText-sp_EUw, .nameSelectedVoice-1qSph5, .nameUnreadText-DfkrI4, .nameUnreadVoice-EVo-wI, .private-channels .channel .channel-name, .private-channels .channel .channel-activity strong, .channel-2QD9_O.selected-1HYmZZ .name-2WpE7M, .channel-2QD9_O:hover .name-2WpE7M, .activity-525YDR, .theme-dark .activityActivityFeed-3xysim .content-3JfFJh, .theme-dark .activityActivityFeed-3xysim .details-38sfDr, .ellipsis-1XUmPN {
  white-space: pre-wrap !important;
  line-height: inherit;
}

.isMentionedCozy-3isp7y:after {
  border-color: var(--Main-Colour);
  background: transparent;
}

.theme-dark .isMentioned-N-h9aa {
  background: var(--Secondary-Background-Colour);
  border: 1px solid var(--Secondary-Main-Colour);
}

.theme-dark .markup-2BOw-j code, .theme-dark .markup-2BOw-j code.inline {
  background: var(--Background-Colour);
}

.theme-dark .wrapper-3WhCwL:hover, .theme-dark .isMentioned-N-h9aa .mention:hover, .theme-light .isMentioned-N-h9aa .mention:hover, .theme-dark .wrapperHover-1GktnT:hover {
  background: var(--Secondary-Background-Colour);
  color: var(--Secondary-Main-Colour);
  animation: rainbow 3s infinite linear;
}

.theme-dark .wrapper-3WhCwL, .theme-dark .isMentioned-N-h9aa .mention, .theme-light .isMentioned-N-h9aa .mention, .theme-dark .wrapperHover-1GktnT {
  background: var(--Secondary-Background-Colour);
  color: var(--Main-Colour);
  animation: rainbow 3s infinite linear;
}

.theme-dark .timestampCozy-2hLAPV, .theme-dark .timestamp-1E3uAL {
  color: var(--Timestamp-Colour);
}

.theme-dark .guildDetail-1nRKNE {
  color: var(--Secondary-Main-Colour);
}

.theme-dark .item-2J1YMK {
  color: var(--Secondary-Main-Colour);
}

.theme-dark .item-2J1YMK:hover {
  color: var(--Main-Colour);
}

.theme-dark .item-2J1YMK:active, .theme-dark .item-2J1YMK:hover {
  background-color: var(--Secondary-Background-Colour);
  color: var(--Main-Colour);
}

.theme-dark .container-3cGP6G {
  background: var(--Background-Colour);
  border: 1px solid var(--Secondary-Main-Colour);
}

.headerCozy-2N9HOL>div>div {
  border-radius: 4px;
  border: 3px solid var(--Main-Colour);
}

.large-3ChYtB {
  height: 32px!important;
  width: 32px!important;
}

.theme-dark .desc-2Dttbk {
  color: var(--Secondary-Main-Colour);
}

.connectionDelete-2Odoln {
  border: 1px solid var(--Secondary-Main-Colour);
}

.connectionDelete-2Odoln:hover {
  border: 1px solid var(--Main-Colour);
}

.connectionHeader-2MDqhu {
  background: var(--Secondary-Background-Colour);
  border-bottom: 1px solid var(--Secondary-Main-Colour);
}

.theme-dark .elevationLow-2lY09M {
  box-shadow: 0 1px 5px 0 var(--Secondary-Main-Colour);
}

.theme-dark .popout-3sVMXz.popout-googletranslate .themedPopout-25DgLi {
  -webkit-box-shadow: 0 2px 10px 0 rgba(0, 0, 0, 0);
  background-color: var(--Background-Colour);
  border: 1px solid var(--Main-Colour);
  box-shadow: 0 2px 10px 0 rgba(0, 0, 0, 0);
}

.theme-dark .username-_4ZSMR {
  color: var(--Main-Colour);
}

.container-1ETFDs {
  height: 40px;
  width: 40px;
}

.container-1ETFDs .wrapper-2lTRaf a {
  height: 40px;
  width: 40px;
}

.theme-dark .container-1ETFDs .wrapper-2lTRaf {
  background: transparent!important;
}

.unreadMentionsIndicatorBottom-BXS58x>div>svg {
  display: none;
}

.theme-dark .messageGroupWrapper-o-Zw7G {
  background-color: var(--Secondary-Background-Colour);
  border-color: var(--Secondary-Main-Colour);
}

.theme-dark .messageGroupWrapper-o-Zw7G:hover {
  background-color: var(--Secondary-Background-Colour);
  border-color: var(--Main-Colour);
}

.theme-dark .messageGroupWrapper-o-Zw7G:hover .actionButtons-1sUUug {
  -webkit-box-shadow: none;
  background-color: transparent;
  box-shadow: none;
}

.theme-dark .jumpButton-3DTcS_ {
  background-color: var(--Secondary-Background-Colour);
  color: var(--Secondary-Main-Colour);
  border: 1px solid var(--Secondary-Main-Colour);
}

.theme-dark .jumpButton-3DTcS_:hover {
  background-color: var(--Secondary-Background-Colour);
  color: var(--Main-Colour);
  border: 1px solid var(--Main-Colour);
}

.container-1ETFDs .avatar-small {
  background-size: cover;
}

.container-1ETFDs .avatar-small {
  background-size: 50px 50px;
  border-radius: 0%;
  height: 40px;
  width: 40px;
}

.theme-dark .circleIconButton-jET_ig {
  background: var(--Secondary-Background-Colour);
  border-color: var(--Secondary-Main-Colour);
  color: var(--Secondary-Main-Colour);
}

.theme-dark .circleIconButton-jET_ig:hover {
  background: var(--Secondary-Background-Colour);
  border-color: var(--Main-Colour);
  color: var(--Main-Colour);
}

.theme-dark .chat-3bRxxu, .theme-dark .chat-3bRxxu form, .theme-dark .content-yTz4x3 {
  background: transparent;
}

.theme-dark .divider-3gKybi:before {
  background-color: var(--Secondary-Background-Colour);
}

.theme-dark .divider-3gKybi.dividerRed-MKoLlr>div, .theme-dark .divider-3gKybi:not(.red-1YQ4s7) div {
  background: var(--Main-Colour);
  opacity: .4;
}

.theme-dark .divider-3gKybi.dividerRed-MKoLlr>span, .theme-dark .divider-3gKybi:not(.red-1YQ4s7) span {
  color: var(--Main-Colour);
}

.theme-dark .divider-3gKybi span {
  background-color: var(--Background-Colour);
}

.container-1YxwTf {
  overflow: visible;
}

.theme-dark .dividerEnabled-2TTlcf {
  border-bottom-color: hsla(0, 0%, 100%, .1);
}

.theme-dark .channelTextArea-rNsIhG {
  border-top: 1px solid hsla(0, 0%, 100%, .1);
}

.newMessagesBar-mujexs button:last-child {
  color: var(--Secondary-Main-Colour);
}

.newMessagesBar-mujexs button, .newMessagesBar-mujexs button:last-child:hover {
  color: var(--Main-Colour);
}

.newMessagesBar-mujexs {
  background-color: var(--Background-Colour);
  border-radius: 0 0 5px 5px;
  border: 1px solid var(--Secondary-Main-Colour);
  color: var(--Secondary-Main-Colour);
}

.newMessagesBar-mujexs:hover {
  background-color: var(--Background-Colour);
  border-radius: 0 0 5px 5px;
  border: 1px solid var(--Main-Colour);
  color: var(--Main-Colour);
}

.theme-dark .hasMore-3e72_v button {
  background-color: var(--Background-Colour);
  border-radius: 0 0 5px 5px;
  border: 1px solid var(--Secondary-Main-Colour);
  color: var(--Secondary-Main-Colour);
}

.theme-dark .hasMore-3e72_v button:hover {
  background-color: var(--Background-Colour);
  border-radius: 0 0 5px 5px;
  border: 1px solid var(--Main-Colour);
  color: var(--Main-Colour);
}

.theme-dark .quickMessage-1yeL4E {
  background-color: var(--Secondary-Background-Colour);
  border-color: var(--Secondary-Main-Colour);
  color: var(--Main-Colour);
}

.protip-YaFfgO {
  display: none;
}

.search-bar-light .searchBarInner-1_Tg2R {
  background-color: var(--Secondary-Background-Colour);
  border: 1px solid var(--Main-Colour);
}

.bda-dark .emoji-picker .search-bar input, .bda-dark .emojiPicker-3m1S-j .search-bar input {
  color: var(--Main-Colour);
}

.typing-2GQL18>span.ellipsis-19qdx6>span {
  width: 28px
}

.theme-dark .messageGroupBlocked-3wrQQX .messageGroupBlockedBtn-1PBBh-, .theme-dark .messageGroupBlocked-3wrQQX .messageGroupBlockedBtn-1PBBh-, .theme-dark .messageGroupBlocked-3wrQQX.revealed-1_RKsf {
  background: var(--Secondary-Background-Colour);
}

.theme-dark .messageGroupBlocked-3wrQQX .messageGroupBlockedBtn-1PBBh-, .theme-dark .messageGroupBlocked-3wrQQX.revealed-1_RKs {
  color: var(--Main-Colour);
}

.theme-dark .messageGroupBlocked-3wrQQX .messageGroupBlockedBtn-1PBBh-, .theme-dark .messageGroupBlocked-3wrQQX .messageGroupBlockedBtn-1PBBh-, .theme-dark .messageGroupBlocked-3wrQQX.revealed-1_RKsf, .theme-dark .messageGroupBlocked-3wrQQX {
  background: var(--Secondary-Background-Colour);
  border-color: var(--Secondary-Main-Colour);
}

.theme-dark .messageGroupBlocked-3wrQQX .messageGroupBlockedBtn-1PBBh-, .theme-dark .messageGroupBlocked-3wrQQX .messageGroupBlockedBtn-1PBBh-, .theme-dark .messageGroupBlocked-3wrQQX.revealed-1_RKsf {
  border-color: var(--Secondary-Main-Colour);
  box-shadow: none;
}

.theme-dark .messageGroupBlocked-3wrQQX .messageGroupBlockedBtn-1PBBh-:hover, .theme-dark .messageGroupBlocked-3wrQQX .messageGroupBlockedBtn-1PBBh-:hover, .theme-dark .messageGroupBlocked-3wrQQX.revealed-1_RKsf:hover, .theme-dark .messageGroupBlocked-3wrQQX:hover {
  background: var(--Secondary-Background-Colour);
  border-color: var(--Main-Colour);
}

.jumpToPresentBar-9P20AM button, .jumpToPresentBar-9P20AM button:last-child {
  color: var(--Secondary-Main-Colour);
}

.theme-dark .jumpToPresentBar-9P20AM {
  background: var(--Background-Colour);
  border: 1px solid var(--Secondary-Main-Colour);
}

.jumpToPresentBar-9P20AM button:hover, .jumpToPresentBar-9P20AM button:last-child:hover {
  color: var(--Main-Colour);
}

.theme-dark .jumpToPresentBar-9P20AM:hover {
  background: var(--Background-Colour);
  border: 1px solid var(--Main-Colour);
}

.theme-dark .container-2x5lvQ header, .theme-dark .container-2x5lvQ section {
  background: var(--Background-Colour);
}

.theme-dark .container-2x5lvQ section p {
  color: var(--Secondary-Main-Colour);
}

.theme-dark .container-2x5lvQ section strong {
  color: var(--Main-Colour);
}

.container-2x5lvQ {
  border: 1px solid var(--Main-Colour);
  border-radius: 3px;
}

.theme-dark .gameLibrary-TTDw4Y {
  background: transparent;
}

.theme-dark .rowWrapper-2fB6P0+.rowWrapper-2fB6P0 .row-ZLfFhY {
  border-top-color: var(--Secondary-Main-Colour);
}

.rowWrapper-2fB6P0+.rowWrapper-2fB6P0 .row-ZLfFhY {
  border-top: 1px solid transparent;
}

.theme-dark .row-ZLfFhY {
  color: var(--Main-Colour);
}

.theme-dark .headerCellSorted-3a5AzJ {
  color: var(--Main-Colour);
}

.theme-dark .headerCell-3L6rFG {
  border-left-color: var(--Secondary-Main-Colour);
}

.theme-dark .header-39GIC8 {
  border-bottom-color: var(--Secondary-Main-Colour);
  color: var(--Secondary-Main-Colour);
}

.theme-dark .headerCell-3L6rFG:hover:not(.headerCellSorted-3a5AzJ) {
  color: var(--Main-Colour);
}

.rowBackground-3MeNoN {
  -webkit-filter: none;
  -webkit-mask: radial-gradient(100% 100% at top left, var(--Secondary-Background-Colour) 0, var(--Secondary-Background-Colour));
  background-repeat: no-repeat;
  background-size: cover;
  border-radius: 5px;
  bottom: 0;
  filter: none;
  left: 0;
  mask: radial-gradient(100% 100% at top left, var(--Secondary-Background-Colour) 0, var(--Secondary-Background-Colour));
  position: absolute;
  top: 0;
  width: 272px;
}

.theme-dark .rowWrapperActive-2L7i9f {
  -webkit-box-shadow: 0 2px 5px 0 var(--Secondary-Main-Colour);
  background-color: transparent;
  box-shadow: 0 2px 5px 0 var(--Secondary-Main-Colour);
}

.theme-dark .actionIconBase-2L-mPj {
  color: var(--Main-Colour);
}

.container-1YxwTf .container-1e22Ot {
  display: flex;
  flex-flow: row wrap;
}

.container-1YxwTf .container-1e22Ot>*:not(:last-of-type) {
  margin-right: 10px;
}

.container-1YxwTf .container-1e22Ot>* {
  margin-top: 5px;
}

.reactions {
  width: 100%;
  flex: 100%;
  order: 9999999999;
}

.welcomeMessage-3_Mcht {
  display: none;
}

.guildsError-3cFMtY {
  -webkit-box-sizing: border-box;
  border-radius: 50%;
  border-style: solid;
  border-width: 2px;
  box-sizing: border-box;
  display: block;
  font-size: 20px;
  font-weight: 700;
  height: 40px;
  line-height: 37px;
  padding: 0;
  text-align: center;
  width: 40px;
}

.theme-dark .guildsError-3cFMtY {
  background: var(--Secondary-Main-Colour);
  border-color: var(--Main-Colour);
  color: var(--Background-Colour);
}

.theme-dark .guildsError-3cFMtY:hover {
  background-color: var(--Main-Colour);
}

.need-help-modal.form.deprecated .header input[type=text] {
  background: transparent;
}

.need-help-modal.form.deprecated .header h1 {
  color: var(--Main-Colour);
}

.need-help-modal.form.deprecated .footer {
  color: var(--Secondary-Main-Colour);
}

.theme-dark .headerClickable-2IVFo9, .theme-dark .headerDefault-1wrJcN {
  color: var(--Secondary-Main-Colour);
}

.theme-dark .auditLog-3jNbM6:hover .expandForeground-1nZ4VR {
  stroke: var(--Main-Colour);
}

.theme-dark .auditLog-3jNbM6 .expandForeground-1nZ4VR {
  stroke: var(--Secondary-Main-Colour);
}

.icon-4lJsMQ {
  display: none;
}

.theme-dark .markValue-2DwdXI {
  color: var(--Secondary-Main-Colour);
}

.theme-dark .markDash-3hAolZ {
  background: var(--Secondary-Main-Colour);
}

.theme-dark .fontScaleLarge-3xtq7i, .theme-dark .fontScaleSmall-368quy {
  color: var(--Main-Colour);
}

.theme-dark .divider-3573oO {
  background: var(--Secondary-Main-Colour);
}

.checked-3_4uQ9>svg>g>polyline {
  stroke: var(--Secondary-Main-Colour);
}

.theme-dark .content-8biNdB ul li:before {
  background-color: var(--Secondary-Main-Colour);
}

.theme-dark .close-18n9bP {
  color: var(--Main-Colour);
}

.Select-clear-zone {
  color: var(--Secondary-Main-Colour);
}

.Select-clear-zone:hover {
  color: var(--Main-Colour);
}

.theme-dark .select-2TCrqx .Select-control .Select-arrow {
  border-color: var(--Secondary-Main-Colour) transparent transparent;
}

.theme-dark .select-2TCrqx .Select-control .Select-arrow:hover {
  border-color: var(--Main-Colour) transparent transparent;
}

.theme-dark .reaction-1ELvT8.reactionMe-23mbRf {
  background: var(--Secondary-Background-Colour);
  border: 1px solid var(--Main-Colour);
}

.theme-dark .reaction-1ELvT8.reactionMe-23mbRf .reactionCount-2ddRoS {
  color: var(--Main-Colour);
}

.theme-dark .reactionCount-2ddRoS {
  color: var(--Secondary-Main-Colour);
}

.theme-dark .reaction-1ELvT8 {
  background: var(--Secondary-Background-Colour);
  border: 1px solid var(--Secondary-Main-Colour);
}

.theme-dark .edited-DL9ECl {
  color: var(--Secondary-Main-Colour);
}

.base-34jWEe h1 {
  color: var(--Main-Colour);
}

.flexChild-faoVW3>div>header>svg>g>path:nth-child(2), .flexChild-faoVW3>div>header>svg>g>path:nth-child(3) {
  stroke: var(--Main-Colour);
}

#charcounter {
  color: var(--Secondary-Main-Colour);
}

#charcounter.over2k {
  color: var(--Main-Colour);
}

.image-1GzsFd.margin-bottom-40 {
  display: none;
}

.theme-dark .paymentRow-2e7VM6 {
  border-bottom: 1px solid var(--Secondary-Background-Colour);
}

.theme-dark .paymentPane-3bwJ6A {
  background-color: var(--Secondary-Background-Colour);
  color: var(--Main-Colour);
}

.theme-dark .paginator-166-09 {
  background: transparent;
}

.theme-dark .paginator-2CA79G {
  color: var(--Secondary-Main-Colour);
}

.theme-dark .summaryInfo-2QFKUg {
  color: var(--Main-Colour);
}

.theme-dark .payment-xT17Mq {
  background-color: var(--Secondary-Background-Colour);
  color: var(--Secondary-Main-Colour);
}

.theme-dark .hoverablePayment-Yc6mK7:hover {
  background-color: var(--Secondary-Background-Colour);
}

.theme-dark .pageIndicator-1gAbyA {
  border-color: var(--Secondary-Main-Colour);
  color: var(--Secondary-Main-Colour);
}

.theme-dark .pageIndicator-1gAbyA:hover {
  border-color: var(--Main-Colour);
  color: var(--Main-Colour);
}

.theme-dark .disabled-BrLY9Y:hover {
  border-color: var(--Main-Colour);
  color: var(--Main-Colour);
}

.theme-dark .disabled-BrLY9Y {
  border-color: var(--Secondary-Main-Colour);
  color: var(--Secondary-Main-Colour);
}

.theme-dark .title-PMZpEi {
  color: var(--Main-Colour);
}

.theme-dark .description-1W0DiL {
  color: var(--Secondary-Main-Colour);
}

.theme-dark .premium-33BYwD, .theme-light .premium-33BYwD {
  background: transparent;
}

.theme-dark .premiumHeader-29chIr, .theme-light .premiumHeader-29chIr {
  color: var(--Main-Colour);
}

.theme-dark .premiumSubheader-3wX8Bc, .theme-light .premiumSubheader-3wX8Bc {
  color: var(--Secondary-Main-Colour);
}

.theme-dark .betaTag-1tngRx, .theme-light .betaTag-1tngRx {
  background-color: var(--Secondary-Background-Colour);
  color: var(--Main-Colour);
  border: 1px solid var(--Main-Colour);
}

.arcadeImage-1oQgXQ {
  display: none;
}

.attendeeCTA-3ZZQWt {
  color: var(--Secondary-Main-Colour);
}

.theme-dark .introBlurb-3gFgTQ {
  color: var(--Secondary-Main-Colour);
}

.theme-dark .introHeader-4MPach {
  color: var(--Main-Colour);
}

.theme-dark .prompt-kcCNXs {
  color: var(--Main-Colour);
}

.theme-dark .selectYourAnswer-2lDJj_ {
  color: var(--Secondary-Main-Colour);
}

.theme-dark .separator-PE-_y1 {
  background-color: var(--Secondary-Main-Colour);
}

.statusRed-21U8Tp {
  color: var(--Main-Colour);
}

.lookGhost-2Fn_0-.colorGrey-2DXtkV {
  background-color: var(--Secondary-Background-Colour);
  color: var(--Secondary-Main-Colour);
}

.selected-mKYnfr.option-n0icdO {
  -webkit-box-shadow: none;
  background-color: transparent;
  border: 1px solid var(--Main-Colour);
  box-shadow: none;
  opacity: 1;
}

.option-n0icdO:hover {
  -webkit-box-shadow: none;
  background-color: transparent;
  border: 1px solid var(--Main-Colour);
  box-shadow: none;
  opacity: 1;
}

.option-n0icdO {
  -webkit-box-shadow: none;
  background-color: transparent;
  border: 1px solid var(--Secondary-Main-Colour);
  box-shadow: none;
  opacity: 1;
}

.wrapper-3jrx9n {
  -webkit-box-shadow: none;
  background-color: transparent;
  border: 1px solid var(--Secondary-Main-Colour);
  box-shadow: none;
  opacity: 1;
}

.Select-control {
  background: var(--Main-Colour)
}

.theme-dark .select-2TCrqx .is-open .Select-control .Select-arrow {
  border-color: transparent transparent var(--Main-Colour);
}

.theme-dark .select-2TCrqx .Select-control:hover .Select-arrow {
  border-color: var(--Main-Colour) transparent transparent;
}

.theme-dark .sound-2QlACh {
  color: var(--Main-Colour);
}

.theme-dark .notificationsSound-27jFSh {
  -webkit-box-shadow: inset 0 -1px 0 0 var(--Secondary-Main-Colour);
  box-shadow: inset 0 -1px 0 0 var(--Secondary-Main-Colour);
}

.theme-dark .button-mM-y8i {
  -webkit-box-shadow: none;
  background-color: var(--Secondary-Background-Colour);
  box-shadow: none;
}

.theme-dark .card-FDVird:before {
  background-color: transparent;
  border-color: var(--Secondary-Main-Colour);
}

.theme-dark .card-FDVird {
  background-color: transparent;
  border-color: var(--Secondary-Main-Colour);
}

.theme-dark .user-settings-games .now-playing-add, .theme-light .user-settings-games .now-playing-add {
  color: var(--Secondary-Main-Colour);
}

.theme-dark .user-settings-games .overlay-toggle-icon-on .fill {
  fill: var(--Main-Colour);
}

.user-settings-games .overlay-warning-icon {
  display: none;
}

#user-settings>div>div:nth-child(2)>div>div>div>div.content-column.default>div>div.userSettingsSecurity-3IYeMF.marginTop60-3PGbtK>div>div>div>div>h5>img {
  display: none;
}

.flex-1xMQg5.flex-1O1GKY.horizontal-1ae9ci.horizontal-2EEEnY.flex-1O1GKY.directionRow-3v3tfG.justifyStart-2NDFzi.alignCenter-1dQNNs.noWrap-3jynv6>span:nth-child(1)>svg>g>path:nth-child(2) {
  stroke: var(--Main-Colour);
}

.theme-dark .guildIconImage-3qTk45 {
  background-color: transparent;
}

.botTagInvert-18-95s, .botTagRegular-2HEhHi, span.botTagRegular-2HEhHi {
  background-color: var(--Secondary-Background-Colour) !important;
  color: var(--Main-Colour);
  border: 1px solid var(--Main-Colour);
  animation: rainbow 20s infinite linear;
}

.premiumPromo-yVfLiA {
  background-color: var(--Background-Colour);
}

.premiumPromoTitle-1SQQfF {
  color: var(--Main-Colour);
}

.premiumPromoDescription-2Mn515 {
  color: var(--Secondary-Main-Colour);
}

.premiumPromo-yVfLiA>img {
  content: url(https://nfld99.com/Bkg/mTBPNOQ.png);
  height: 25%;
}

.flex-1xMQg5.flex-1O1GKY.horizontal-1ae9ci.horizontal-2EEEnY.flex-1O1GKY.directionRow-3v3tfG.justifyStart-2NDFzi.alignStretch-DpGPf3.wrap-ZIn9Iy.marginReset-236NPn>svg>g>polyline {
  stroke: var(--Main-Colour);
}

.theme-dark .colorPickerSwatch-5GX3Ve.noColor-1pdBDm .colorPickerDropperFg-3jYKWI {
  fill: var(--Main-Colour);
}

.theme-dark .colorPickerSwatch-5GX3Ve.noColor-1pdBDm {
  border-color: var(--Secondary-Main-Colour);
}

.theme-dark .member-1q7VfX .overflowIconFg-QMRRFI {
  fill: var(--Main-Colour);
}

.theme-dark .actionButton-VzECiy {
  border-color: var(--Secondary-Main-Colour);
  color: var(--Secondary-Main-Colour);
}

.theme-dark .actionButton-VzECiy:hover {
  border-color: var(--Main-Colour);
  color: var(--Main-Colour);
}

.theme-dark .guild-settings-banned-user .username {
  color: var(--Main-Colour);
}

.theme-dark .guild-settings-banned-user-modal .reason, .theme-dark .guild-settings-banned-user-modal .user-discrim, .theme-dark .guild-settings-banned-user .username .discrim {
  color: var(--Secondary-Main-Colour);
}

.theme-dark .guild-settings-banned-user-modal .reason-header {
  color: var(--Main-Colour);
}

.theme-dark .inviteRowName-1tVaxu {
  color: var(--Main-Colour);
}

.theme-dark .inviteRow-2L02ae:hover {
  background-color: var(--Secondary-Background-Colour);
  box-shadow: 0px 0px 4px 0px var(--Main-Colour);
}

.lookOutlined-3sRXeN.colorGreen-29iAKY {
  border-color: var(--Secondary-Main-Colour);
  color: var(--Secondary-Main-Colour);
}

.theme-dark .checkBoxLabel-4PWfpk, .theme-dark .footerText-2a7NxZ, .theme-dark .subText-bCySlS {
  color: var(--Secondary-Main-Colour);
}

.theme-dark .select-2TCrqx .is-focused .Select-control .Select-arrow {
  border-color: var(--Secondary-Main-Colour) transparent transparent;
}

.lookLink-9FtZy-.colorWhite-rEQuAQ:hover .contents-18-Yxp {
  background-image: linear-gradient(0deg, transparent, transparent 1px, var(--Main-Colour) 0, var(--Main-Colour) 2px, transparent 0);
}

.lookLink-9FtZy-.colorWhite-rEQuAQ {
  color: var(--Main-Colour);
}

.buttonInvertedPurple-WtBglX {
  border: 1px solid var(--Secondary-Main-Colour);
  color: var(--Secondary-Main-Colour);
  background: transparent;
}

.buttonInvertedPurple-WtBglX:hover {
  border: 1px solid var(--Main-Colour);
  color: var(--Main-Colour);
}

.profileBadgeHypeSquadOnlineHouse2-3jBpXR {
  background-image: url(https://discordapp.com/assets/48cf0556d93901c8cb16317be2436523.svg)!important;
}

.profileBadgeHypeSquadOnlineHouse1-xN6tES {
  background-image: url(https://discordapp.com/assets/1115767aed344e96a27a12e97718c171.svg)!important;
}

.profileBadgeHypeSquadOnlineHouse3-1YbjMX {
  background-image: url(https://discordapp.com/assets/2a085ed9c86f3613935a6a8667ba8b89.svg)!important;
}

[class*="membershipDialogHouse"] {
  background-color: var(--Secondary-Background-Colour)!important;
}

.flex-1xMQg5.flex-1O1GKY.horizontal-1ae9ci.horizontal-2EEEnY.flex-1O1GKY.directionRow-3v3tfG.justifyStart-2NDFzi.alignCenter-1dQNNs.noWrap-3jynv6.selectableItem-1MP3MQ.actionItem-11pIwh.selected-31soGA {
  background-color: var(--Secondary-Background-Colour)!important;
  color: var(--Main-Colour)!important;
}

.regionSelectModal-12e-57 .regionSelectModalOption-2DSIZ3:hover {
  border-color: var(--Main-Colour);
}

.regionSelectModal-12e-57 .regionSelectModalOption-2DSIZ3 {
  border-color: var(--Secondary-Main-Colour);
  background: var(--Secondary-Background-Colour);
}

.regionSelectModal-12e-57 .regionSelectModalFooter-20C5iA, .regionSelectModal-12e-57 .regionSelectModalHeader-21khC1 {
  color: var(--Main-Colour);
}

.lookGhost-2Fn_0-.colorBrand-3pXr91 {
  background-color: var(--Secondary-Background-Colour);
  color: var(--Main-Colour);
  border: 1px solid var(--Main-Colour);
}

.lookGhost-2Fn_0-.colorGrey-2DXtkV {
  background-color: var(--Secondary-Background-Colour);
  color: var(--Secondary-Main-Colour);
  border: 1px solid var(--Secondary-Main-Colour);
}

.avatar-uploader-inner>* {
  color: var(--Main-Colour);
}

.flex-1xMQg5.flex-1O1GKY.horizontal-1ae9ci.horizontal-2EEEnY.flex-1O1GKY.directionRow-3v3tfG.justifyStart-2NDFzi.alignStart-H-X2h-.noWrap-3jynv6>div:nth-child(1)>label>span:nth-child(1)>svg>path:nth-child(1) {
  fill: transparent!important;
}

.connectionDelete-2Odoln:after, .connectionDelete-2Odoln:before {
  background-color: var(--Secondary-Main-Colour);
}

.connectionDelete-2Odoln:hover:after, .connectionDelete-2Odoln:hover:before {
  background-color: var(--Main-Colour);
}

.avatar-xxlarge {
  border-radius: 0%;
}

.theme-dark .defaultIndicator-G3c16x, .theme-dark .premiumIndicator-1XvbfM {
  background-color: var(--Secondary-Background-Colour);
  color: var(--Secondary-Main-Colour);
  border: 1px solid var(--Secondary-Main-Colour);
}

.theme-dark .description-HxwDO4 {
  color: var(--Main-Colour);
}

.theme-dark .descriptionWrapper-1YBY_J {
  color: var(--Secondary-Main-Colour);
}

.membershipDialogSwitchHousesAction-2a3eDg:hover {
  color: var(--Main-Colour);
}

.membershipDialogSwitchHousesAction-2a3eDg {
  color: var(--Secondary-Main-Colour);
}

.cancelButton-3hVEV6:hover, .downloadButton-23tKQp:hover {
  color: var(--Main-Colour);
}

.cancelButton-3hVEV6, .downloadButton-23tKQp {
  color: var(--Secondary-Main-Colour);
}

.metadataIcon-2FyCKU {
  color: var(--Main-Colour);
}

.wrapper-2TxpI8 {
  color: var(--Main-Colour);
}

.theme-dark .subtitle-2iWJ5y {
  color: var(--Secondary-Main-Colour);
}

.theme-dark .friend-2PO6ke {
  color: var(--Main-Colour);
}

.theme-dark .friendSelected--wQP3f {
  background: linear-gradient(to top, var(--Secondary-Main-Colour), var(--Background-Colour), var(--Background-Colour), var(--Background-Colour), var(--Secondary-Main-Colour)) !important;
  color: var(--Main-Colour);
}

.title-3gWYEg, .paginationTitle-1XtEga, .theme-dark .dockItemText-3qYREY, .gameName-2XIejT {
  color: var(--Main-Colour);
}

.description-1CCuDd, .paginationSubtitle-bqhkei, .timestamp-JB3BQ5 {
  color: var(--Secondary-Main-Colour);
}

.paginationItem-3-MBTL:before {
  background: var(--Secondary-Main-Colour);
  color: var(--Main-Colour);
}

.regionSelect-3lf4eE:hover .regionSelectInner-24f4Ce, .regionSelect-3lf4eE:hover button {
  border-color: var(--Main-Colour);
}

.regionSelect-3lf4eE .regionSelectInner-24f4Ce, .regionSelect-3lf4eE button {
  border-color: var(--Secondary-Main-Colour);
}

.form-deprecated .btn-default:hover, .form.deprecated .btn-default:hover {
  border-bottom: 1px solid var(--Main-Colour);
}

.avatar-uploader .size-info {
  color: var(--Main-Colour);
}

.theme-dark #bd-settingspane-container h2.ui-form-title {
  color: var(--Main-Colour);
}

.theme-dark #bd-settingspane-container .ui-switch-item h3 {
  color: var(--Main-Colour);
}

.theme-dark #bd-settingspane-container .ui-switch-item .style-description {
  color: var(--Secondary-Main-Colour);
}

.theme-dark .embedAuthorName-3mnTWj, .theme-dark .embedFieldName-NFrena, .theme-dark .embedTitle-3OXDkz {
  color: var(--Main-Colour)!important;
}

.embedProvider-3k5pfl {
  color: var(--Secondary-Main-Colour)!important;
}

.metadata-3WGS0M {
  color: var(--Secondary-Main-Colour);
}

.theme-dark .embedDescription-1Cuq9a, .theme-dark .embedFieldValue-nELq2s, .theme-dark .embedFooterText-28V_Wb, .theme-dark .embedProvider-3k5pfl {
  color: var(--Secondary-Main-Colour);
}

.theme-dark .embedInner-1-fpTo {
  background: var(--Background-Colour);
  border: 1px solid var(--Secondary-Main-Colour);
}

.theme-dark .embedInner-1-fpTo:hover {
  background: var(--Background-Colour);
  border: 1px solid var(--Main-Colour);
}

.theme-dark .embedPill-1Zntps {
  background-color: var(--Secondary-Main-Colour);
}

.theme-dark #autocomplete-popout .row.selected {
  border: none;
  background: linear-gradient(to top, var(--Secondary-Main-Colour), var(--Background-Colour), var(--Background-Colour), var(--Background-Colour), var(--Secondary-Main-Colour)) !important;
  color: var(--Main-Colour);
}

#autocomplete-popout header {
  border: 1px solid var(--Main-Colour);
}

#autocomplete-popout {
  border: 1px solid var(--Secondary-Main-Colour);
}

#autocomplete-popout:hover {
  border: 1px solid var(--Main-Colour);
}

.theme-dark .channelName-28iMRJ {
  color: var(--Main-Colour);
}

.theme-dark .guildName-3WI6ml, .theme-dark .override-2YgiXd, .theme-dark .overrideHighlight-YPcBxt {
  color: var(--Secondary-Main-Colour);
}

.checkboxMute-14hTGS:before {
  background: transparent;
}

.theme-dark .checkboxContainer-2vV9zd:before {
  background: var(--Secondary-Main-Colour);
}

.theme-dark .select-2TCrqx .Select-input input {
  color: var(--Main-Colour);
}

.Select-noresults {
  color: var(--Secondary-Main-Colour);
}

.theme-dark .select-2TCrqx .Select-option {
  background: var(--Background-Colour);
  color: var(--Secondary-Main-Colour);
  border: none;
}

.theme-dark .select-2TCrqx .Select-option:hover {
  background: linear-gradient(to top, var(--Secondary-Main-Colour), var(--Background-Colour), var(--Background-Colour), var(--Background-Colour), var(--Secondary-Main-Colour)) !important;
  color: var(--Main-Colour);
  border: none;
}

.theme-dark .incomingCallInner-2VmFiR {
  border-color: var(--Secondary-Main-Colour);
  background: var(--Popout-Background) 50% 50%/cover;
}

.theme-dark .members-2BNiuX {
  color: var(--Main-Colour);
}

.subtitle-1H8FPn {
  color: var(--Secondary-Main-Colour);
}

.incomingCall-14zLcL {
  width: 300px;
}

.theme-dark .markup-2BOw-j pre {
  background: var(--Background-Colour);
  border-color: var(--Secondary-Main-Colour);
}

.theme-dark .markup-2BOw-j pre:hover {
  background: var(--Background-Colour);
  border-color: var(--Main-Colour);
}

.theme-dark .search-results-wrap, .theme-dark .search-results-wrap .search-result .hit, .theme-dark .search-results-wrap .channel-separator .channel-name {
  background: var(--Secondary-Background-Colour);
}

.theme-dark .search-results-wrap {
  border: 1px solid var(--Secondary-Main-Colour);
}

.theme-dark .search-results-wrap:hover {
  border: 1px solid var(--Main-Colour);
}

.theme-dark .search-results-wrap .search-header {
  background: transparent;
}

.accountDetails-3k9g4n .username {
  overflow: visible;
}

.typingSpinnerItem-35chrT {
  background-color: var(--Main-Colour);
}

.pulsingEllipsis-3YiXRF {
  top: 20px;
  left: 2px;
}

.typing-1KJk_j {
  overflow: visible;
}

.flex-1xMQg5.flex-1O1GKY.horizontal-1ae9ci.horizontal-2EEEnY.flex-1O1GKY.directionRow-3v3tfG.justifyStart-2NDFzi.alignStretch-DpGPf3.noWrap-3jynv6.videoCenter-1nmPrS>div>div>div>div>div>svg>g>path {
  fill: var(--Main-Colour);
}

.callAvatar-v-u4BM.voice-2D-tt_ .callAvatarStatus-3y6S04 {
  background-color: var(--Background-Colour);
}

.theme-dark .callAvatar-v-u4BM.voice-2D-tt_ .callAvatarStatus-3y6S04 {
  border: none;
}

.wrapper-29NfPK.fullScreen-3DKbL8 .actions-2vadYq .center-1Vp33r, .wrapper-29NfPK.fullScreen-3DKbL8 .actions-2vadYq .side-kO0bwV, .wrapper-29NfPK.noChat-2qlG4B .center-1Vp33r, .wrapper-29NfPK.noChat-2qlG4B .side-kO0bwV, .wrapper-29NfPK.normal-2GSW0u .center-1Vp33r, .wrapper-29NfPK.normal-2GSW0u .side-kO0bwV {
  background-color: var(--Secondary-Background-Colour);
  border-color: var(--Secondary-Main-Colour);
}

.theme-dark .wrapper-29NfPK {
  border: 1px solid var(--Secondary-Main-Colour);
}

.callAvatar-v-u4BM.voice-2D-tt_ {
  border-radius: 0%;
  box-shadow: inset 0 0 0 3px transparent;
}

.callAvatarBorder-1D_KaE.voice-2D-tt_.speaking-oCqYMI {
  border-radius: 0%;
  box-shadow: inset 0 0 0 3px var(--Main-Colour);
}

.callAvatarBorder-1D_KaE.video-3GgX2M.selected-2esnyn:not(.speaking-oCqYMI):not(.soundsharing-102bS9) {
  border-radius: 0%;
  box-shadow: inset 0 0 0 3px transparent;
}

.callAvatarBorder-1D_KaE.video-3GgX2M.speaking-oCqYMI {
  border-radius: 0%;
  box-shadow: inset 0 0 0 3px var(--Main-Colour);
}

.flex-1xMQg5.flex-1O1GKY.vertical-V37hAW.flex-1O1GKY.directionColumn-35P_nr.justifyCenter-3D2jYp.alignCenter-1dQNNs.noWrap-3jynv6.callAvatarOverlay-33Xeat>svg>g>path {
  fill: var(--Background-Colour)
}

.flex-1xMQg5.flex-1O1GKY.horizontal-1ae9ci.horizontal-2EEEnY.flex-1O1GKY.directionRow-3v3tfG.justifyStart-2NDFzi.alignStretch-DpGPf3.noWrap-3jynv6.videoCenter-1nmPrS>div>div>div>div>div>div>svg>g>path {
  fill: var(--Background-Colour)
}

.callAvatar-v-u4BM.video-3GgX2M .callAvatarStatus-3y6S04 {
  background: var(--Secondary-Background-Colour);
}

.theme-dark .selectorText-9iPrCS {
  color: var(--Secondary-Main-Colour);
}

.selectorTextSelected-3m1dO_ {
  color: var(--Main-Colour);
}

.theme-dark .item-3T2z1R {
  border-color: var(--Secondary-Main-Colour);
}

.selectorButtonSelected-1j4DmC {
  background-color: var(--Background-Colour);
}

.imageSelected-4Kl81J {
  border-color: var(--Main-Colour);
}

.theme-dark .titleSelected-1UkXLp {
  color: var(--Main-Colour);
}

.theme-dark .tile-2QWaFv {
  color: var(--Secondary-Main-Colour);
}

.theme-dark .tiles-2aXG_k {
  background-color: var(--Secondary-Background-Colour);
  box-shadow: 0 2px 5px var(--Secondary-Main-Colour), 0 0 0 1px var(--Secondary-Main-Colour);
}

.theme-dark .border-2AhmKo {
  border-bottom: 1px solid var(--Secondary-Main-Colour);
}

.theme-dark .container-OI6I9q {
  color: var(--Secondary-Main-Colour)
}

.theme-dark .selected-P8xTeN {
  border-bottom: 2px solid var(--Main-Colour);
  color: var(--Main-Colour);
}

.theme-dark .passthroughSelected-1Eq0Kl, .theme-dark .denySelected-1mh2mZ, .theme-dark .allowSelected-25S_i5 {
  border-color: var(--Main-Colour)!important;
}

.isFailed-19WM0A, .isFailed-19WM0A .hljs, .isFailed-19WM0A a, .isFailed-19WM0A code.inline, .theme-dark .isFailed-19WM0A, .theme-light .isFailed-19WM0A {
  color: var(--Main-Colour);
  box-shadow: 0px 0px 20px 0px red;
  animation: fail 3s infinite linear;
}

.contentConnectedVoice-qL-YrL:hover {
  background: linear-gradient(to right, transparent, var(--Background-Colour), var(--Notification-Colour))!important;
}

.theme-dark .applicationStore-1pNvnv {
  background: transparent;
}

.wanderingCubesItem-WPXqao {
  background-color: var(--Main-Colour);
}

.theme-dark .headerBar-UHpsPw, .searchBar-6Kv8R2 {
  box-shadow: none;
}

.theme-dark .libraryFilterInput-3JzqZD {
  background: var(--Secondary-Background-Colour);
  border: 1px solid var(--Secondary-Main-Colour);
}

.theme-dark .bubble-3we2di {
  background-color: var(--Background-Colour);
  border: 1px solid var(--Main-Colour);
}

.bubble-3we2di {
  color: var(--Main-Colour);
}

.theme-dark .bubble-3we2di:before {
  border-top-color: var(--Main-Colour);
}

.theme-dark .content-Qb0rXO {
  color: var(--Main-Colour);
}

.theme-dark .iconForeground-1w5n7R {
  fill: var(--Secondary-Main-Colour);
}

.theme-dark .contentTitle-2tG_sM strong {
  color: var(--Main-Colour);
}

.videoBackgroundWrapper-2dCt49 {
  background: var(--Popout-Background);
}

.theme-dark .divider-3gKybi.dividerRed-MKoLlr .dividerContent-2L12VI {
  color: var(--Main-Colour);
}

.theme-dark .divider-3gKybi.dividerRed-MKoLlr .dividerContent-2L12VI:after, .theme-dark .divider-3gKybi.dividerRed-MKoLlr .dividerContent-2L12VI:before {
  border-color: var(--Main-Colour);
}

.theme-dark .divider-3gKybi span {
  background-color: transparent;
}

.theme-dark .divider-3gKybi:not(.dividerRed-MKoLlr) .dividerContent-2L12VI {
  color: var(--Secondary-Main-Colour);
}

.theme-dark .divider-3gKybi:not(.dividerRed-MKoLlr) .dividerContent-2L12VI:after, .theme-dark .divider-3gKybi:not(.dividerRed-MKoLlr) .dividerContent-2L12VI:before {
  border-color: var(--Secondary-Main-Colour);
}

.theme-dark .actionButton-VzECiy {
  display: none;
}

.theme-dark .queryContainer-RKFJW- {
  background: transparent;
  color: var(--Main-Colour);
}

.theme-dark .queryContainer-RKFJW-, .theme-dark .option-96V44q:after {
  background: transparent;
}

.theme-dark .container-3ayLPN {
  background: var(--Background-Colour) 50% 50%/cover;
}

.theme-dark .elevationBorderHigh-2WYJ09 {
  box-shadow: 0 0 0 1px var(--Secondary-Main-Colour), 0 2px 10px 0 var(--Secondary-Main-Colour);
}

.theme-dark .featuredGame-ia1yht {
  color: var(--Secondary-Main-Colour);
}

.theme-dark .itemDescription-1_B4j2, .theme-dark .title-RcZEhJ {
  color: var(--Main-Colour);
}

.theme-dark .itemBackground-1jfD8p {
  background-color: var(--Secondary-Background-Colour);
}

.theme-dark .itemBackground-1jfD8p:before {
  background: radial-gradient(ellipse at top, rgba(54, 57, 63, 0), var(--Background-Colour)), linear-gradient(90deg, var(--Background-Colour) 0, rgba(54, 57, 63, 0) 40%, rgba(54, 57, 63, 0) 60%, var(--Background-Colour)), linear-gradient(0deg, var(--Background-Colour) 0, rgba(54, 57, 63, 0) 25%);
}

.theme-dark .overlappingBorder-1ysb12 {
  border-color: var(--Main-Colour);
}

.theme-dark .announcingNitro-3Ptg6m:hover, .theme-dark .selectedSort-2JSohJ:hover {
  color: var(--Main-Colour);
}

.theme-dark .announcingNitro-3Ptg6m, .theme-dark .selectedSort-2JSohJ {
  border-color: var(--Secondary-Main-Colour);
  color: var(--Secondary-Main-Colour);
}

.theme-dark .distributionApplicationsActions-3D2_kD, .theme-dark .premiumApplicationsHeader-Zmkm5e {
  border-color: var(--Secondary-Main-Colour);
  color: var(--Main-Colour);
}

.theme-dark .description-1eVELi {
  color: var(--Main-Colour);
}

.theme-dark .tagline-LsAYEH {
  color: var(--Secondary-Main-Colour);
}

.theme-dark .text-1OO51R, .theme-light .text-1OO51R {
  color: var(--Main-Colour);
}

.theme-dark .tag-HanR-9:before, .theme-light .tag-HanR-9:before {
  background: transparent;
}

.theme-dark .tag-HanR-9, .theme-light .tag-HanR-9 {
  background: var(--Background-Colour);
}

.theme-dark .tileMedia-24cT6_ {
  background: var(--Background-Colour);
}

.theme-dark .tileWrapper-2khh-w {
  background: var(--Secondary-Background-Colour);
}

.theme-dark .tileWrapper-2khh-w:hover {
  background: var(--Background-Colour);
}

.priceOriginalAmount-3YD-j2 {
  color: var(--Secondary-Main-Colour);
}

.priceSalePercentage-AqGkYF {
  background-color: var(--Secondary-Main-Colour);
  color: var(--Main-Colour);
}

.theme-dark .mediaDescription-31GsyQ {
  background: linear-gradient(180deg, transparent, var(--Secondary-Background-Colour) 45%, var(--Background-Colour));
}

.theme-dark .premium-39U29H, .theme-light .premium-39U29H {
  background-image: linear-gradient(90deg, var(--Secondary-Background-Colour), var(--Secondary-Main-Colour));
}

.theme-dark .premiumHeader-3SwLEp, .theme-light .premiumHeader-3SwLEp, .theme-dark .carouselGameBlurb-2CViiR, .theme-light .carouselGameBlurb-2CViiR, .theme-dark .premiumSubheader-15Q0Z6, .theme-light .premiumSubheader-15Q0Z6, .theme-dark .freeWithNitro-2bbCTS, .theme-dark .inLibrary-2JnVkV {
  color: var(--Main-Colour);
}

.theme-dark .lookInverted-2D7oAl.hoverGrey-2CBXu0.hasHover-3X1-zV:hover, .theme-light .lookInverted-2D7oAl.hoverGrey-2CBXu0.hasHover-3X1-zV:hover {
  background-color: var(--Secondary-Main-Colour);
  color: var(--Main-Colour);
}

.theme-dark .footerMain-Z8i6ST {
  color: var(--Main-Colour);
}

.theme-dark .footerSub-1Jedbi {
  color: var(--Secondary-Main-Colour);
}

.theme-dark .footer-3oZnEF {
  display: none;
}

.theme-dark .filterAndSort-gLX1Ym, .theme-dark .hideGames-zMTyGl {
  color: var(--Secondary-Main-Colour);
}

.theme-dark .select-1Pkeg4 {
  color: var(--Main-Colour);
}

.theme-dark .optionNormal-12VR9V {
  color: var(--Secondary-Main-Colour);
}

.theme-dark .optionActive-KkAdqq {
  background: var(--Secondary-Background-Colour);
  color: var(--Main-Colour);
}

.theme-dark .popout-2sKjHu {
  -webkit-box-shadow: 0 1px 5px 0 var(--Secondary-Main-Colour);
  background: var(--Background-Colour);
  border-color: var(--Background-Colour);
  box-shadow: 0 1px 5px 0 var(--Secondary-Main-Colour);
}

.theme-dark .lookMinimal-2OMO3G.select-1Pkeg4:hover .arrow-2KJjTM {
  color: var(--Main-Colour);
}

.theme-dark .lookMinimal-2OMO3G .arrow-2KJjTM {
  color: var(--Secondary-Main-Colour);
}

.theme-dark .root-1bFE0x {
  background-color: var(--Background-Colour);
}

.theme-dark .bodySection-jqkkIP, .theme-light .bodySection-jqkkIP {
  background-color: var(--Background-Colour);
  border-top-color: var(--Secondary-Main-Colour);
}

.theme-dark .price-4PDWNj, .theme-light .price-4PDWNj, .theme-dark .actionText-3EKWER, .theme-light .actionText-3EKWER, .theme-dark h3.title-3KTIjF, .theme-dark .info-1Emy1X, .theme-light .info-1Emy1X, .theme-dark .header-3HFF3R, .theme-dark .text-1Z3P6i, .theme-dark h1.title-3KTIjF, .theme-dark h2.title-3KTIjF, .theme-dark .verdict-1JnQka, .theme-dark h4.title-3KTIjF, .theme-dark h5.title-3KTIjF, .theme-dark h6.title-3KTIjF, .theme-dark .requirements-dEriwm, .theme-dark .activeBreadcrumb-p6aw-F, .theme-dark .checkboxLabel-3WoD3k, .theme-dark .applicationName-2QbFHn, .theme-dark .link-2T7oYD, .theme-dark .noMatches-2myGbP, .theme-dark .clearIcon-2N9YIn:hover, .theme-dark .clearIcon-33XhWd:hover, .theme-dark .resultName-raPnaf, .theme-dark .queryContainer-RKFJW- strong, .theme-dark .emptyStateHeader-3CJtAy, .theme-dark .channelName-2rTyk5, .theme-dark .headerTitle-PE3TuN, .paginationTitle-3U5ymz, .theme-dark .itemDescription-1ATOQr, .theme-dark .title-36Rug1, .theme-dark .freeWithNitro-2shAdz, .theme-dark .blog-2nw4E8, .theme-dark .inputPrompt-3hUneE, .banner-3Kac2g, .theme-dark .grandfatheredMessage-2QgLnw, .theme-dark .title-2a5mvx, .theme-dark .subtitle-UfhpvR, .theme-dark .premiumPlanName-bDYpWx, .theme-dark .subsectionHeader-2euE2f, .theme-dark .sectionHeader-127c3L, .theme-dark .tier1Banner-1B_WXY, .theme-dark .iconIncluded-2xYFq5 {
  color: var(--Main-Colour);
}

.theme-dark .label-13UUcd, .theme-light .label-13UUcd, .theme-dark .smallHeader-2h-9-U, .theme-dark .notes-3hkVr0, .theme-light .label-2zCFFs, .theme-dark .blurb-1iBKJy, .theme-dark .description-1AwRKJ, .theme-dark .markdown-11q6EU, .theme-dark .requirementKey-14DT2D, .theme-dark .content-1zhNsr, .theme-dark .breadcrumbWrapper-WmDjgG, .theme-dark .featureIcon-1f78KU, .theme-dark .noMatchesDescription-1jZ4Wi, .theme-dark .searchIcon-1a1-yA, .theme-dark .clearIcon-2N9YIn, .theme-dark .purchaseUnitOperatingSystem-cnbJPz, .theme-light .purchaseUnitOperatingSystem-cnbJPz, .theme-dark .browseSearchInput-Jt8kg0, .theme-dark .icon-1iRNyO, .theme-dark .price-_ZRMIA, .theme-dark .emptyStateDescription-2IePen, .theme-dark .headerSubtitle-3mUZXH, .paginationSubtitle-12e1s6, .theme-dark .finePrint-3BVarJ, .theme-dark .yearlyNote-3CCz_7, .theme-dark .description-1irSAr {
  color: var(--Secondary-Main-Colour);
}

.theme-dark .card-NB61oR {
  color: var(--Secondary-Main-Colour);
  background: var(--Background-Colour);
}

.theme-dark .row-1bU71H {
  color: var(--Main-Colour);
  background: var(--Background-Colour);
}

.overlappingBorder-1-XPGl {
  border: 3px solid var(--Main-Colour);
  border-radius: 3px;
}

.theme-dark .popout-2sKjHu {
  -webkit-box-shadow: 0 1px 5px 0 var(--Secondary-Main-Colour);
  background: var(--Background-Colour)!important;
  border-color: var(--Secondary-Main-Colour);
  box-shadow: 0 1px 5px 0 var(--Secondary-Main-Colour);
}

.theme-dark .price-1ynJAt {
  background-color: var(--Secondary-Background-Colour);
  color: var(--Main-Colour);
}

.theme-dark .headerBar-UHpsPw {
  -webkit-box-shadow: 0 1px 0 rgba(32, 34, 37, 0), 0 2px 0 rgba(0, 0, 0, .0);
  background: transparent;
  box-shadow: 0 1px 0 rgba(32, 34, 37, .0), 0 2px 0 rgba(0, 0, 0, .0);
  color: var(--Main-Colour);
}

.theme-dark .searchBox-3Y2Vi7 {
  color: var(--Main-Colour);
  background: var(--Background-Colour);
}

.theme-dark .emptyWumpus-3Gagum, .theme-dark .filterBackground-QanGTJ:before, .theme-dark .premium-39U29H:before, .theme-light .premium-39U29H:before, .theme-dark .emptyWumpus-12J3jI {
  display: none;
}

.theme-dark .browseSearchInput-Jt8kg0, .theme-dark .optionNormal-12VR9V:hover {
  background: var(--Secondary-Background-Colour);
}

.theme-dark .focused-1Yu0L3 {
  -webkit-box-shadow: 0 1px 5px 0 var(--Secondary-Main-Colour);
  background: var(--Background-Colour)!important;
  border-color: var(--Secondary-Main-Colour);
  box-shadow: 0 1px 5px 0 var(--Secondary-Main-Colour);
}

.exclusive-3zP8if {
  background: -webkit-gradient(linear, right top, left top, from(var(--Secondary-Main-Colour)), to(var(--Main-Colour)));
  background: linear-gradient(270deg, var(--Secondary-Main-Colour), var(--Main-Colour));
  color: var(--Main-Colour);
}

.paginationItem-2lUq0s:before {
  background: var(--Main-Colour);
}

.blog-2nw4E8, .theme-dark .grandfatheredMessage-2QgLnw, .theme-dark .container-2Zlzt0, .theme-dark .tier1Banner-1B_WXY {
  background: var(--Background-Colour);
}

.theme-dark .contentRegion-3nDuYy, .theme-dark .sidebarRegion-VFTUkN, .tierGrandfathered-R6zrrD.banner-3Kac2g, .membershipDialog-rVL-t_:after {
  background: transparent;
}

.theme-dark .lookOutlined-3sRXeN.colorTransparent-1ewNp9 {
  border-color: var(--Secondary-Main-Colour);
  color: var(--Secondary-Main-Colour);
}

.theme-dark .lookOutlined-3sRXeN:hover.colorTransparent-1ewNp9 {
  border-color: var(--Main-Colour);
  color: var(--Main-Colour);
}

.theme-dark .bda-slist li {
  background-color: var(--Secondary-Background-Colour);
  color: var(--Secondary-Main-Colour);
  border-color: var(--Secondary-Main-Colour);
  box-shadow: 0 1px 5px 0 var(--Secondary-Main-Colour);
}

.theme-dark .bda-slist li:hover {
  box-shadow: 0 0 5px 0 var(--Main-Colour);
}

.theme-dark .bda-slist .bda-description, .themeDark-3Ap_7i .note-450gs3 {
  color: var(--Secondary-Main-Colour);
}

.bda-dark .emoji-picker .scroller .emoji-item.selected, .bda-dark .emojiPicker-3m1S-j .scroller-3vODG7 .emojiItem-109bjA.selected-39BZ4S {
  background-color: var(--Background-Colour);
}

.emojiPicker-3m1S-j {
  -webkit-box-shadow: 0 0 6px 0 var(--Secondary-Main-Colour);
  border: 1px solid var(--Secondary-Main-Colour);
  box-shadow: 0 0 6px 0 var(--Secondary-Main-Colour);
}

.bda-dark .emoji-picker .scroller::-webkit-scrollbar, .bda-dark .emoji-picker .scroller::-webkit-scrollbar-track, .bda-dark .emoji-picker .scroller::-webkit-scrollbar-track-piece, .bda-dark .emojiPicker-3m1S-j .scroller-3vODG7::-webkit-scrollbar, .bda-dark .emojiPicker-3m1S-j .scroller-3vODG7::-webkit-scrollbar-track, .bda-dark .emojiPicker-3m1S-j .scroller-3vODG7::-webkit-scrollbar-track-piece, .bda-dark #bda-qem-twitch-container .scroller::-webkit-scrollbar, .bda-dark #bda-qem-twitch-container .scroller::-webkit-scrollbar-track, .bda-dark #bda-qem-twitch-container .scroller::-webkit-scrollbar-track-piece, .bda-dark #pubs-container .scroller::-webkit-scrollbar, .bda-dark #pubs-container .scroller::-webkit-scrollbar-track, .bda-dark #pubs-container .scroller::-webkit-scrollbar-track-piece, .bda-dark #bda-qem-favourite-container .scroller::-webkit-scrollbar, .bda-dark #bda-qem-favourite-container .scroller::-webkit-scrollbar-track, .bda-dark #bda-qem-favourite-container .scroller::-webkit-scrollbar-track-piece {
  background-color: var(--Secondary-Background-Colour) !important;
  border-color: transparent !important;
}

.scrollerThemed-2oenus.themeLight-1_DWyY .scroller-2FKFPG::-webkit-scrollbar-thumb, .theme-dark .scrollerThemed-2oenus.themeLight-1_DWyY .scroller-2FKFPG::-webkit-scrollbar-thumb, .theme-light .scrollerWrap-2lJEkd .scroller-2FKFPG::-webkit-scrollbar-thumb, .bda-dark #bda-qem-twitch-container .scroller::-webkit-scrollbar, .bda-dark #bda-qem-twitch-container .scroller::-webkit-scrollbar-track, .bda-dark #bda-qem-twitch-container .scroller::-webkit-scrollbar-track-piece, .bda-dark #pubs-container .scroller::-webkit-scrollbar, .bda-dark #pubs-container .scroller::-webkit-scrollbar-track, .bda-dark #pubs-container .scroller::-webkit-scrollbar-track-piece, .bda-dark #bda-qem-favourite-container .scroller::-webkit-scrollbar, .bda-dark #bda-qem-favourite-container .scroller::-webkit-scrollbar-track, .bda-dark #bda-qem-favourite-container .scroller::-webkit-scrollbar-track-piece {
  background-color: var(--Secondary-Background-Colour) !important;
  border-color: var(--Secondary-Main-Colour) !important;
}

.theme-dark .header-39GIC8 {
  background: transparent;
}

.theme-dark .icon-1IKq3C, .theme-dark .textCell-1aBIUP {
  color: var(--Secondary-Main-Colour);
}

.buttonShine-1CSUM8 {
  animation-delay: .75s;
  animation-duration: 2s;
  animation-iteration-count: infinite;
  animation-name: Shine-2sIJ1p;
  animation-timing-function: ease-in-out;
  color: var(--Secondary-Main-Colour);
}

.popout-3sVMXz:not(.noArrow-3BYQ0Z) {
  box-shadow: 0 0 6px 0 var(--Secondary-Main-Colour);
  padding: 1px;
}

.theme-dark .text-GwUZgS {
  font-size: 15px;
}

.theme-dark .text-GwUZgS:after {
  content: " Raynnerino.com/Discord";
  color: var(--Main-Colour);
  font-size: 15px;
}

.verified-3uJH7V>g>path:nth-child(2) {
  fill: var(--Secondary-Main-Colour);
}

[src="/assets/cdea41ede63f61153e4a3c0531fa3873.svg"], .theme-dark .background-3N1V7e {
  display: none;
}

[style="color: rgb(114, 137, 218); background-color: rgba(114, 137, 218, 0.0980392);"], [style="color: rgb(240, 71, 71); background-color: rgba(240, 71, 71, 0.0980392);"] {
  background-color: transparent!important;
}

.thumbQuicksave {
  background: var(--Secondary-Background-Colour);
  color: var(--Main-Colour);
  border: 1px solid var(--Main-Colour);
}

.theme-dark .isLocalBot-38G0P0 {
  background-image: linear-gradient(90deg, var(--Secondary-Background-Colour) 80%, var(--Main-Colour));
  border-color: transparent;
  box-shadow: 0px 0px 20px 0px red;
  animation: fail 3s infinite linear;
  color: var(--Secondary-Main-Colour);
}

[style="background-color: rgba(32, 34, 37, 0.901961);"] {
  background: transparent!important;
}

[style="color: rgb(255, 255, 255);"] {
  color: var(--Main-Colour)!important;
}

/* .appMount-3VJmYg .popout-3sVMXz.popoutTopLeft-b5Eb3O, .appMount-3lHmkl .popout-3sVMXz.popoutTopLeft-b5Eb3O{
  animation: 500ms DropDown 1 linear;
} */

.theme-dark .callAvatarWrapper-TICyxO .ripple-16ZT2p {
  background-color: var(--Main-Colour)!important;
  border-radius: 0%;
}

#bd-pub-li {
  bottom: 0px!important;
  top: inherit;
  border: 1px solid var(--Secondary-Main-Colour);
}

#bd-pub-li:hover {
  border: 1px solid var(--Main-Colour);
}

#pubslayer h2.ui-form-title, .bd-server-card .bd-server-tags, #pubslayer .ui-tab-bar-header, [style="color: rgb(185, 187, 190); font-size: 10px; margin-left: 10px;"] {
  color: var(--Main-Colour)!important;
}

.bd-server-description-container {
  color: var(--Main-Colour);
  min-height: 65px;
  max-height: 65px;
  border-top: 1px solid var(--Secondary-Main-Colour);
  border-bottom: 1px solid var(--Secondary-Main-Colour);
  padding-top: 5px;
  font-size: 13px;
}

.bd-server-card.bd-server-card-pinned:after {
  background: var(--Main-Colour);
}

#pubslayer button {
  background: var(--Secondary-Background-Colour);
  color: var(--Secondary-Main-Colour);
  border: 1px solid var(--Secondary-Main-Colour);
}

#pubslayer button:hover {
  background: var(--Secondary-Background-Colour);
  color: var(--Main-Colour);
  border: 1px solid var(--Main-Colour);
}

#pubslayer .ui-tab-bar-item:hover, #pubslayer .ui-tab-bar-item.selected {
  color: var(--Main-Colour) !important;
  background: linear-gradient(to right, transparent, var(--Background-Colour), var(--Notification-Colour)) !important;
}

#pubslayer .ui-tab-bar-item {
  color: var(--Secondary-Main-Colour);
}

#pubslayer input {
  color: var(--Secondary-Main-Colour);
  background-color: var(--Secondary-Background-Colour);
  border-color: var(--Secondary-Main-Colour);
}

#pubslayer input:focus {
  border-color: var(--Main-Colour);
  color: var(--Main-Colour);
}

.attachButtonPlay-ZnFdQr {
  color: var(--Secondary-Main-Colour);
}

.attachButtonInner-1iyZ9F {
  pointer-events: none
}

.appMount-3VJmYg .popout-3sVMXz.popoutTopLeft-b5Eb3O, .appMount-3lHmkl .popout-3sVMXz.popoutTopLeft-b5Eb3O {
  border: 0.5px solid var(--Main-Colour) !important;
}

.theme-dark .attachPopout-1n-ZKM {
  background: var(--Background-Colour) !important;
  color: var(--Secondary-Main-Colour)!important;
}

.attachPopout-1n-ZKM{
  display: flex;
  flex-flow: row wrap;
  padding-left: 0;
  align-content: flex-start;
  justify-content: center;
}

.attachPopoutRow-KrE-f6:last-of-type{
  margin-left: 8px;
}

.theme-dark .attachPopoutRow-KrE-f6:hover {
  border: 0.5px solid var(--Main-Colour) !important;
  color: var(--Main-Colour)!important;
  background-color: var(--Secondary-Background-Colour) !important;
}

.attachPopoutRow-KrE-f6 {
  border: 0.5px solid var(--Secondary-Main-Colour) !important;
}

.attachPopoutRow-KrE-f6:hover {
  border: 0.5px solid var(--Main-Colour) !important;
}

.theme-dark .itemDefault-3Jdr52, .theme-dark .itemHover-EnbcjT {
  color: var(--Main-Colour);
}

.fullScreen-3DKbL8 {
  background: url(https://nfld99.com/Bkg/1uIcwYm.png) 50% 50%/cover !important;
}

.ownerIcon-uZ6mE7 {
  height: 14px;
  margin-left: 0;
  margin-top: -22px;
  position: relative;
  top: inherit;
  width: 14px;
  left: -103%;
}

[fill="#faa61a"] {
  fill: currentColor;
}

.nameTag-m8r81H, .name-1ug6d4 {
  overflow: visible!important;
}

.theme-dark .activityUserPopout-2yItg2 .headerText-1HLrL7, .theme-dark .activityUserPopout-2yItg2 .content-3JfFJh, .theme-dark .activityUserPopout-2yItg2 .details-38sfDr, .theme-dark .note-3kmerW textarea, .theme-dark .activityProfile-2bJRaP .headerText-1HLrL7, .theme-dark .activityProfile-2bJRaP .content-3JfFJh, .theme-dark .activityProfile-2bJRaP .details-38sfDr {
  color: var(--Popout-Main-Colour)!important;
}

.topSectionXbox-3fWLjS {
  background: transparent;
}

[class="noArrow-3BYQ0Z popout-3sVMXz popoutTopLeft-b5Eb3O arrowAlignmentTop-iGQczz popouttop-left theme-undefined"]>.userPopout-3XzG_A {
  margin-left: auto;
  margin-right: auto;
}

.pictureInPictureWindow-1B5qSe {
  border-radius: 3px;
  border: 2px var(--Secondary-Main-Colour) solid;
}

.pictureInPictureWindow-1B5qSe:hover {
  border-radius: 3px;
  border: 2px var(--Main-Colour) solid;
}

.channel-2-6Ybo {
  color: var(--Main-Colour);
}

.iconButtonForeground-JKUp3t {
  fill: var(--Main-Colour)
}

.rtc-connection-status > div > span {
  font-size: 0%;
}

.rtc-connection-status > div > span:after {
  content: "Connected";
  font-size: initial;
}

.translate-button {
  right: 6.9%;
}

.theme-dark .categoryText-2-8pri, .theme-light .categoryText-2-8pri {
  color: var(--Main-Colour);
}

.categoryFade-2ybR1J {
  background-image: -webkit-gradient(linear, left top, left bottom, from(Transparent), to(var(--Secondary-Background-Colour)));
  background-image: linear-gradient(180deg, Transparent, var(--Secondary-Background-Colour));
  border-radius: 4px;
  height: 100%;
  position: absolute;
  width: 100%;
}

.category-2pHfXV {
  border: 1px var(--Secondary-Main-Colour) solid;
  border-radius: 4px;
}

.category-2pHfXV:hover {
  border: 1px var(--Main-Colour) solid;
  border-radius: 4px;
}

.theme-dark .modal-3HD5ck, .theme-dark .message-2qRu38 {
  Background: var(--Background-Colour);
  box-shadow: 0 0 0 1px var(--Secondary-Main-Colour), 2px 2px 2px 0 var(--Secondary-Main-Colour)!important;
}

.theme-dark .modal-3HD5ck:hover, .theme-dark .message-2qRu38 {
  Background: var(--Background-Colour);
  box-shadow: 0 0 0 1px var(--Main-Colour), 2px 2px 2px 0 var(--Main-Colour)!important;
}

.theme-dark .searchBar-1MOL6S .input-3Xdcic {
  color: var(--Main-Colour);
}

.ripple-16ZT2p:nth-of-type(1) {
  background-color: var(--Main-Colour)!important;
  box-shadow: 1px 1px 50px var(--Main-Colour);
  border-radius: 0%;
}

.ripple-16ZT2p:nth-of-type(2) {
  background-color: var(--Main-Colour)!important;
  box-shadow: 1px 1px 50px var(--Secondary-Main-Colour);
  border-radius: 0%;
}

.ripple-16ZT2p:nth-of-type(3) {
  background-color: var(--Main-Colour)!important;
  box-shadow: 1px 1px 50px var(--Main-Colour);
  border-radius: 0%;
}

.theme-dark .item-1GzJrl:hover {
  background-color: var(--Background-Colour);
}

.theme-dark .menu-Sp6bN1 {
  background-color: var(--Background-Colour);
  box-shadow: none;
}

.theme-dark .separator-2zcjq8, .theme-dark .itemGroup-1tL0uz {
  border-color: transparent;
}

.theme-dark .topPill-30KHOu .itemSelected-1qLhcL {
  background-color: var(--Secondary-Background-Colour);
  color: var(--Main-Colour);
  border: 1px solid var(--Main-Colour);
}

.notSelected-1N1G5p {
  background: var(--Secondary-Background-Colour);
  color: var(--Secondary-Main-Colour);
}

.theme-dark .directoryHeroPrice-1_MqzA, .theme-dark .directoryHeroPricePremium-tR0nU8, .theme-dark .description-2XMjXn, .theme-dark .description-3rB3Rp, .theme-dark .redemptionHeader-3FSfP7, .theme-dark .emptyStateHeader-1ADtcL, .theme-dark .header-2HrZI4, .theme-dark .inputPrompt-1vnYnD, .theme-dark .nameCellText-Ubz8FY, .theme-dark .title-i-qCkH, .theme-dark .header-1fmANI {
  color: var(--Main-Colour);
}

.theme-dark .tagline-1VBVLz, .theme-dark .tagline-2iew42, .theme-dark .originalAmount-3RtnBh, .theme-dark .emptyStateSubtext-2njjqg, .theme-dark .progressCellText-3avmMz, .theme-dark .rate-1Gat8e, .theme-dark .content-3FEARf, .theme-dark .openDescription-2XUOH3, .theme-dark .collapsedTimestamp-2gjDIM, .theme-dark .openTimestamp-sTgPmn, .theme-dark .blurb-143skT, .theme-dark .storeTerms-3G4Jo7, .theme-dark .subtext-2QfZHv {
  color: var(--Secondary-Main-Colour);
}

.theme-dark .applicationTile-1Goy1W, .theme-dark .description-3rB3Rp, .theme-dark .item-2yFVoY {
  background: linear-gradient(180deg, transparent, var(--Secondary-Background-Colour) 45%, var(--Background-Colour));
}

.salePercentage-TXZz3H {
  background: var(--Background-Colour);
  color: var(--Main-Colour);
  border: 1px solid var(--Main-Colour);
}

.theme-dark .root-1BQpZw {
  background: transparent;
}

.theme-dark .emptyStateImage-2eMp68 {
  display: none;
}

.theme-dark .row-2X_kYI {
  border-bottom-color: var(--Secondary-Main-Colour);
}

.theme-dark .gameUpdates-2GPqBU {
  background-color: var(--Secondary-Background-Colour);
}

.theme-dark .entitledHeader-3LRNDT, .theme-light .entitledHeader-3LRNDT {
  background: var(--Background-Colour);
}

.theme-dark .spoilerContainer-331r0R:hover .spoilerWarning-2aAZq1 {
  background-color: var(--Background-Colour);
  color: var(--Main-Colour);
}

.theme-dark .spoilerWarning-2aAZq1 {
  background-color: var(--Secondary-Background-Colour);
  color: var(--Secondary-Main-Colour);
}

.theme-dark .spoilerText-3p6IlD.hidden-HHr2R9:hover {
  background-color: var(--Background-Colour);
  border: 1px solid var(--Main-Colour);
}

.theme-dark .spoilerText-3p6IlD.hidden-HHr2R9 {
  background-color: var(--Secondary-Background-Colour);
  border: 1px solid var(--Secondary-Main-Colour);
}

.theme-dark .spoilerText-3p6IlD {
  background-color: var(--Secondary-Background-Colour);
  border: 1px solid var(--Secondary-Main-Colour);
}

.theme-dark #bd-settings-sidebar .ui-tab-bar-item:hover {
  background: var(--Background-Colour)!important;
  color: var(--Main-Colour);
  border: 1px solid var(--Main-Colour);
}

.theme-dark #bd-settings-sidebar .ui-tab-bar-item {
  background: var(--Secondary-Background-Colour)!important;
  color: var(--Secondary-Main-Colour);
  border: 1px solid var(--Secondary-Main-Colour);
}

#bd-settings-sidebar .ui-tab-bar-item.selected, .side-8zPYf6 .itemSelected-1qLhcL {
  color: var(--Main-Colour) !important;
  background: linear-gradient(to right, transparent, var(--Background-Colour), var(--Notification-Colour)) !important;
}

.theme-dark .separator-gCa7yv, #bd-settings-sidebar .ui-tab-bar-separator {
  display: none;
}

#bd-settings-sidebar .ui-tab-bar-item:not(.role-3wi9Tf) {
  color: var(--Main-Colour)!important;
}

.callAvatar-v-u4BM.video-3GgX2M .callAvatarStatus-3y6S04 {
  background: var(--Background-Colour);
}

.flex-1xMQg5.flex-1O1GKY.horizontal-1ae9ci.horizontal-2EEEnY.flex-1O1GKY.directionRow-3v3tfG.justifyStart-2NDFzi.alignStretch-DpGPf3.noWrap-3jynv6.videoCenter-1nmPrS>div>div>div>div>div>div>svg>g>path {
  fill: var(--Main-Colour) !important
}

[style="color: white;"] {
  color: var(--Main-Colour)!important;
}

.backgroundBlur-dazcBE, .theme-dark .pictureInPictureVideo-20ZvXn {
  background: var(--Secondary-Main-Colour)!important;
}

.theme-light [class*='topSection']:not(.topSectionNormal-2-vo2m) .joinedAtDate, .theme-dark [class*='topSection'] .joinedAtDate, .theme-light .header-2BwW8b:not(.headerNormal-T_seeN) .joinedAtDate, .theme-dark .header-2BwW8b .joinedAtDate {
  color: var(--Main-Colour);
}

.name-2WpE7M {
  opacity: 1;
}

.theme-dark .giftBlurb-4VKZWm, .theme-dark .trialNote-wEO1RW, .theme-dark .trialText-2gR3-S, .theme-dark .interval-bfFUiQ, .theme-dark .colorPrimary-3hws2f, .theme-light .colorPrimary-3hws2f {
  color: var(--Secondary-Main-Colour);
}

.tier2HeaderBackground-2BUqcl {
  background-image: linear-gradient(90deg, var(--Main-Colour), var(--Secondary-Main-Colour));
}

.theme-dark .headerIcon-1OW_re, .theme-light .closeIcon-1Te9hO, .theme-light .headerIcon-1OW_re {
  color: var(--Background-Colour);
}

.tier2Foreground-2tYn8P {
  background-image: none!important;
}

.theme-dark .option-1l2vXE {
  background: transparent;
  border: 1px solid var(--Secondary-Main-Colour);
}

.theme-dark .price-3dKlQv, .theme-dark .backButtonColor-1zIPlh {
  color: var(--Main-Colour)!important;
}

.theme-dark .annualDiscount-1VxngV, .theme-light .annualDiscount-1VxngV {
  background-color: var(--Secondary-Background-Colour);
  color: var(--Main-Colour);
}

.channel-2QD9_O.selected-1HYmZZ .name-2WpE7M, .channel-2QD9_O:hover .name-2WpE7M {
  white-space: nowrap !important;
}

.icon-3nr6O-, .icon-29PTzq {
  opacity: 1;
}

.searchBar-2_Yu-C .searchBarInner-1_Tg2R, .searchBar-2_Yu-C, .theme-dark .search-2oPWTC .searchBar-3dMhjb {
  background: var(--Secondary-Background-Colour);
}

.theme-dark .header-13MUnb, .theme-dark .contentUnread-3gTHvA, .theme-dark .contentDefault-16dKSY, .theme-light .resultFocused-2geRUA, .theme-dark .friendsTable-133bsv .friendsRow-2yicud .friendsColumnStatus-ZH4ho2, .theme-dark .friendsTable-133bsv .friendsRow-2yicud .friendsColumnName-1zBOKm, .theme-dark .friendsTable-133bsv .friendsTableHeader-32yE7d .friendsColumn-eVHFqJ, .theme-dark .subsectionHeader-1SVMaW, .theme-dark .featuredGame-1EfWhT, .theme-dark .itemDescription-234GLf, .theme-dark .title-1Qzsze {
  color: var(--Main-Colour);
}

.theme-dark .contentDefault-16dKSY .note-S--UP5, .theme-dark .contentUnread-3gTHvA .note-S--UP5 {
  color: var(--Secondary-Main-Colour);
}

.theme-dark .search-2oPWTC .searchBar-3dMhjb .public-DraftEditorPlaceholder-root {
  color: var(--Secondary-Main-Colour);
}

.theme-dark .container-3gCOGc {
  background: transparent;
}

.tabBar-1E2ExX .primary-3j8BhM, .searchBar-2_Yu-C.searchBarLight-1NxoDG {
  background-color: var(--Secondary-Background-Colour)!important;
}

.tabBar-1E2ExX .primary-3j8BhM{
  color: var(--Secondary-Main-Colour)!important;
}

.theme-dark .friendsTable-133bsv .friendsTableHeader-32yE7d {
  border-bottom-color: var(--Secondary-Main-Colour);
}

.theme-dark .friendsTable-133bsv .friendsTableHeader-32yE7d .friendsColumnSeparator-3MqtMA {
  background-color: var(--Secondary-Main-Colour);
}

.theme-dark .friendsTable-133bsv .friendsRow-2yicud:hover {
  background: var(--Secondary-Background-Colour);
}

.theme-dark .friendsTable-133bsv .friendsRow-2yicud+.friendsRow-2yicud {
  border: 1px solid transparent;
}

.theme-dark .grandfatheredMessage-1BnHtv {
  background-image: linear-gradient(270deg, var(--Secondary-Background-Colour), var(--Secondary-Background-Colour));
  color: var(--Main-Colour);
}

.searchBar-2_Yu-C.searchBarLight-1NxoDG input {
  color: var(--Secondary-Main-Colour);
}

.searchBar-2_Yu-C.searchBarLight-1NxoDG .searchBarInner-1_Tg2R {
  background-color: var(--Secondary-Background-Colour);
}

.scroller-2FKFPG {
  background: transparent;
}

.top-28JiJ- .item-PXvHYJ, .theme-dark .top-28JiJ- .itemSelected-1qLhcL {
  color: var(--Secondary-Main-Colour) !important;
  background: linear-gradient(to bottom, var(--Secondary-Main-Colour), var(--Background-Colour), var(--Secondary-Main-Colour)) !important;
}

.theme-dark .top-28JiJ- .itemSelected-1qLhcL {
  border-color: var(--Main-Colour)!important;
}

/* ======================================Canary fix for 2019-01-12 I hope====================================== */

.app-2rEoOp:not(.popout section) {
  text-shadow: 0 0 6px var(--Text-Shadow-Colour), 0 0 6px var(--Text-Shadow-Colour), 0 0 5px var(--Text-Shadow-Colour), 0 0 4px var(--Text-Shadow-Colour);
}

#app-mount>div>div.app-2rEoOp.flex-vertical.theme-dark>div>section>div.wrapper-1Rf91z>div {
  background-color: rgba(35, 35, 35, 0.7) !important;
}

#app-mount>div>div.app-2rEoOp.flex-vertical.theme-dark>div>section>div.chat.flex-vertical.flex-spacer>div.content.flex-spacer.flex-horizontal>div.flex-spacer.flex-vertical>div>div>div>div:nth-child(37)>div.comment>div.message.mentioned>div.body-3rkFrF>div>div.markup-2BOw-j {
  background: transparent !important;
  border-top-right-radius: 5px !important;
  border-top-left-radius: 5px !important;
}

#app-mount>div>span.theme-dark>div>div>div.body-3rkFrF>div>div, #app-mount>div>div.app-2rEoOp.flex-vertical.theme-dark>div>section>div.wrapper-1Rf91z>div>button {
  color: var(--Main-Colour) !important;
}

#app-mount>div>div.app-2rEoOp.flex-vertical.theme-light>div>section>div.wrapper-1Rf91z>div>button {
  color: var(--Main-Colour) !important;
  opacity: 0.4 !important;
}

#app-mount>div>div.app-2rEoOp.flex-vertical.theme-light>div>section>div.wrapper-1Rf91z>div>button:hover:after {
  opacity: 1 !important;
}

#app-mount>div>div.app-2rEoOp.flex-vertical.theme-dark>div>section>div.chat.flex-vertical.flex-spacer>div.content.flex-spacer.flex-horizontal>div.flex-spacer.flex-vertical>div>div>div>div>div:nth-child(3)>div {
  background-image: url('https://ditmcouk.ipage.com/noottech/discord-icons/green/invite.svg') !important;
}

#app-mount>div>div.app-2rEoOp.flex-vertical.theme-dark>div>section>div.chat.flex-vertical.flex-spacer>div.content.flex-spacer.flex-horizontal>div.flex-spacer.flex-vertical>div>div>div>div>div:nth-child(4)>div {
  background-image: url('https://ditmcouk.ipage.com/noottech/discord-icons/green/mobile.svg') !important;
}

#app-mount>div>div.app-2rEoOp.flex-vertical.theme-dark>div>section>div.chat.flex-vertical.flex-spacer>div.content.flex-spacer.flex-horizontal>div.flex-spacer.flex-vertical>div>div>div>div>div:nth-child(5)>div {
  background-image: url('https://ditmcouk.ipage.com/noottech/discord-icons/green/twitter.svg') !important;
}

#app-mount>div.app-19_DXt.platform-win>div.app-2rEoOp.flex-vertical.theme-dark>div.layers.flex-vertical.flex-spacer>div>div>div.flex-1xMQg5.flex-1O1GKY.vertical-V37hAW.flex-1O1GKY.directionColumn-35P_nr.justifyStart-2NDFzi.alignStretch-DpGPf3.noWrap-3jynv6.base-3dtUhz>div.flex-1xMQg5.flex-1O1GKY.horizontal-1ae9ci.horizontal-2EEEnY.flex-1O1GKY.directionRow-3v3tfG.justifyStart-2NDFzi.alignStretch-DpGPf3.noWrap-3jynv6.spacer-29U_x8>div.chat.flex-vertical.flex-spacer>div.content.flex-spacer.flex-horizontal>div.flex-spacer.flex-vertical>div.messagesWrapper-3lZDfY>div>div>div.message-group.hide-overflow>div.comment>div>div.accessory>div>div>div.flex-1xMQg5.flex-1O1GKY.vertical-V37hAW.flex-1O1GKY.directionColumn-35P_nr.justifyCenter-3D2jYp.alignStretch-DpGPf3.noWrap-3jynv6.guildInfo-1STtYi>div.guildDetail-1nRKNE.small-29zrCQ.size12-3R0845.height16-2Lv3qA.weightSemiBold-NJexzi>div>span:nth-child(4) {
  color: var(--Secondary-Main-Colour);
}

#app-mount>div.app-19_DXt.platform-win>div.app-2rEoOp.flex-vertical.theme-dark>div.layers.flex-vertical.flex-spacer>div>div>div.flex-1xMQg5.flex-1O1GKY.vertical-V37hAW.flex-1O1GKY.directionColumn-35P_nr.justifyStart-2NDFzi.alignStretch-DpGPf3.noWrap-3jynv6.base-3dtUhz>div.flex-1xMQg5.flex-1O1GKY.horizontal-1ae9ci.horizontal-2EEEnY.flex-1O1GKY.directionRow-3v3tfG.justifyStart-2NDFzi.alignStretch-DpGPf3.noWrap-3jynv6.spacer-29U_x8>div.chat.flex-vertical.flex-spacer>div.content.flex-spacer.flex-horizontal>div.flex-spacer.flex-vertical>div.messagesWrapper-3lZDfY>div>div>div.message-group.hide-overflow>div.comment>div>div.accessory>div>div>div.flex-1xMQg5.flex-1O1GKY.vertical-V37hAW.flex-1O1GKY.directionColumn-35P_nr.justifyCenter-3D2jYp.alignStretch-DpGPf3.noWrap-3jynv6.guildInfo-1STtYi>div.guildDetail-1nRKNE.small-29zrCQ.size12-3R0845.height16-2Lv3qA.weightSemiBold-NJexzi>div>span:nth-child(4):before {
  color: var(--Secondary-Main-Colour);
  content: " Out  Of  "
}

#app-mount>div.app-19_DXt.platform-win>div.app-2rEoOp.flex-vertical.theme-dark>div.layers.flex-vertical.flex-spacer>div>div>div.flex-1xMQg5.flex-1O1GKY.vertical-V37hAW.flex-1O1GKY.directionColumn-35P_nr.justifyStart-2NDFzi.alignStretch-DpGPf3.noWrap-3jynv6.base-3dtUhz>div.flex-1xMQg5.flex-1O1GKY.horizontal-1ae9ci.horizontal-2EEEnY.flex-1O1GKY.directionRow-3v3tfG.justifyStart-2NDFzi.alignStretch-DpGPf3.noWrap-3jynv6.spacer-29U_x8>div.channels-Ie2l6A.vertical-V37hAW.flex-1O1GKY.directionColumn-35P_nr>div.container-2Thooq>div.flex-1xMQg5.flex-1O1GKY.horizontal-1ae9ci.horizontal-2EEEnY.flex-1O1GKY.directionRow-3v3tfG.justifyStart-2NDFzi.alignStretch-DpGPf3.noWrap-3jynv6>div.button-2b6hmh>svg>path {
  display: none;
}

#app-mount>div.typeWindows-1za-n7.titleBar-AC4pGV.horizontalReverse-3tRjY7.flex-1O1GKY.directionRowReverse-m8IjIq.justifyStart-2NDFzi.alignStretch-DpGPf3>div:nth-child(4)>svg, #app-mount>div.typeWindows-1za-n7.titleBar-AC4pGV.horizontalReverse-3tRjY7.flex-1O1GKY.directionRowReverse-m8IjIq.justifyStart-2NDFzi.alignStretch-DpGPf3>div.winButtonClose-1HsbF-.winButton-iRh8-Z.center-1MLNrE.flex-1O1GKY.justifyCenter-3D2jYp.alignCenter-1dQNNs>svg>polygon, #app-mount>div.app-19_DXt.platform-win>div.app-2rEoOp.flex-vertical.theme-dark>div.layers.flex-vertical.flex-spacer>div>div>div.flex-1xMQg5.flex-1O1GKY.vertical-V37hAW.flex-1O1GKY.directionColumn-35P_nr.justifyStart-2NDFzi.alignStretch-DpGPf3.noWrap-3jynv6.base-3dtUhz>div.flex-1xMQg5.flex-1O1GKY.horizontal-1ae9ci.horizontal-2EEEnY.flex-1O1GKY.directionRow-3v3tfG.justifyStart-2NDFzi.alignStretch-DpGPf3.noWrap-3jynv6.spacer-29U_x8>div.chat.flex-vertical.flex-spacer>div.titleWrapper-1l0xT9.theme-dark>div>div.flex-1xMQg5.flex-1O1GKY.horizontal-1ae9ci.horizontal-2EEEnY.flex-1O1GKY.directionRow-3v3tfG.justifyStart-2NDFzi.alignCenter-1dQNNs.noWrap-3jynv6>svg:nth-child(1)>g>path, #app-mount>div.app-19_DXt.platform-win>div.app-2rEoOp.flex-vertical.theme-dark>div.layers.flex-vertical.flex-spacer>div>div>div.flex-1xMQg5.flex-1O1GKY.vertical-V37hAW.flex-1O1GKY.directionColumn-35P_nr.justifyStart-2NDFzi.alignStretch-DpGPf3.noWrap-3jynv6.base-3dtUhz>div.flex-1xMQg5.flex-1O1GKY.horizontal-1ae9ci.horizontal-2EEEnY.flex-1O1GKY.directionRow-3v3tfG.justifyStart-2NDFzi.alignStretch-DpGPf3.noWrap-3jynv6.spacer-29U_x8>div.chat.flex-vertical.flex-spacer>div.titleWrapper-1l0xT9.theme-dark>div>div.flex-1xMQg5.flex-1O1GKY.horizontal-1ae9ci.horizontal-2EEEnY.flex-1O1GKY.directionRow-3v3tfG.justifyStart-2NDFzi.alignCenter-1dQNNs.noWrap-3jynv6>svg:nth-child(2)>g>path.iconForeground-2c7s3m, #app-mount>div.app-19_DXt.platform-win>div.app-2rEoOp.flex-vertical.theme-dark>div.layers.flex-vertical.flex-spacer>div>div>div.flex-1xMQg5.flex-1O1GKY.vertical-V37hAW.flex-1O1GKY.directionColumn-35P_nr.justifyStart-2NDFzi.alignStretch-DpGPf3.noWrap-3jynv6.base-3dtUhz>div.flex-1xMQg5.flex-1O1GKY.horizontal-1ae9ci.horizontal-2EEEnY.flex-1O1GKY.directionRow-3v3tfG.justifyStart-2NDFzi.alignStretch-DpGPf3.noWrap-3jynv6.spacer-29U_x8>div.chat.flex-vertical.flex-spacer>div.titleWrapper-1l0xT9.theme-dark>div>div.flex-1xMQg5.flex-1O1GKY.horizontal-1ae9ci.horizontal-2EEEnY.flex-1O1GKY.directionRow-3v3tfG.justifyStart-2NDFzi.alignCenter-1dQNNs.noWrap-3jynv6>svg.iconActive-AKd_jq.icon-1R19_H.iconMargin-2YXk4F>g>path, #app-mount>div.app-19_DXt.platform-win>div.app-2rEoOp.flex-vertical.theme-dark>div.layers.flex-vertical.flex-spacer>div>div>div.flex-1xMQg5.flex-1O1GKY.vertical-V37hAW.flex-1O1GKY.directionColumn-35P_nr.justifyStart-2NDFzi.alignStretch-DpGPf3.noWrap-3jynv6.base-3dtUhz>div.flex-1xMQg5.flex-1O1GKY.horizontal-1ae9ci.horizontal-2EEEnY.flex-1O1GKY.directionRow-3v3tfG.justifyStart-2NDFzi.alignStretch-DpGPf3.noWrap-3jynv6.spacer-29U_x8>div.chat.flex-vertical.flex-spacer>div.titleWrapper-1l0xT9.theme-dark>div>div.flex-1xMQg5.flex-1O1GKY.horizontal-1ae9ci.horizontal-2EEEnY.flex-1O1GKY.directionRow-3v3tfG.justifyStart-2NDFzi.alignCenter-1dQNNs.noWrap-3jynv6>svg:nth-child(6)>path, #app-mount>div.app-19_DXt.platform-win>div.app-2rEoOp.flex-vertical.theme-dark>div.layers.flex-vertical.flex-spacer>div>div>div.flex-1xMQg5.flex-1O1GKY.vertical-V37hAW.flex-1O1GKY.directionColumn-35P_nr.justifyStart-2NDFzi.alignStretch-DpGPf3.noWrap-3jynv6.base-3dtUhz>div.flex-1xMQg5.flex-1O1GKY.horizontal-1ae9ci.horizontal-2EEEnY.flex-1O1GKY.directionRow-3v3tfG.justifyStart-2NDFzi.alignStretch-DpGPf3.noWrap-3jynv6.spacer-29U_x8>div.chat.flex-vertical.flex-spacer>div.titleWrapper-1l0xT9.theme-dark>div>div.flex-1xMQg5.flex-1O1GKY.horizontal-1ae9ci.horizontal-2EEEnY.flex-1O1GKY.directionRow-3v3tfG.justifyStart-2NDFzi.alignCenter-1dQNNs.noWrap-3jynv6>svg:nth-child(7)>g, .foreground-2W-aJk, #app-mount>div.app-19_DXt.platform-win>div.app-2rEoOp.flex-vertical.theme-dark>div.layers.flex-vertical.flex-spacer>div>div>div.flex-1xMQg5.flex-1O1GKY.vertical-V37hAW.flex-1O1GKY.directionColumn-35P_nr.justifyStart-2NDFzi.alignStretch-DpGPf3.noWrap-3jynv6.base-3dtUhz>div.flex-1xMQg5.flex-1O1GKY.horizontal-1ae9ci.horizontal-2EEEnY.flex-1O1GKY.directionRow-3v3tfG.justifyStart-2NDFzi.alignStretch-DpGPf3.noWrap-3jynv6.spacer-29U_x8>div.chat.flex-vertical.flex-spacer>div.titleWrapper-1l0xT9.theme-dark>div>div.titleText-3X-zRE>span>svg>path, #app-mount>div.app-19_DXt.platform-win>div.app-2rEoOp.flex-vertical.theme-dark>div.layers.flex-vertical.flex-spacer>div>div>div.flex-1xMQg5.flex-1O1GKY.vertical-V37hAW.flex-1O1GKY.directionColumn-35P_nr.justifyStart-2NDFzi.alignStretch-DpGPf3.noWrap-3jynv6.base-3dtUhz>div.flex-1xMQg5.flex-1O1GKY.horizontal-1ae9ci.horizontal-2EEEnY.flex-1O1GKY.directionRow-3v3tfG.justifyStart-2NDFzi.alignStretch-DpGPf3.noWrap-3jynv6.spacer-29U_x8>div.channels-Ie2l6A.vertical-V37hAW.flex-1O1GKY.directionColumn-35P_nr>div.flex-1xMQg5.flex-1O1GKY.vertical-V37hAW.flex-1O1GKY.directionColumn-35P_nr.justifyStart-2NDFzi.alignStretch-DpGPf3.noWrap-3jynv6.container-PNkimc>div.scrollerWrap-2lJEkd.scrollerThemed-19vinI.themeGhostHairlineChannels-2lQojW.scrollerFade-28dRsO>div>div.container-5>div:nth-child(3)>div>div>div:nth-child(1)>svg>path.background-2OVjk_, #app-mount>div.theme-dark.popouts>div>div>div.body-3rkFrF>div:nth-child(1)>svg>path, #app-mount>div.theme-dark.popouts>div>div>div.body-3rkFrF>div:nth-child(3)>svg>path {
  fill: var(--Secondary-Main-Colour) !important;
}

#app-mount>div.typeWindows-1za-n7.titleBar-AC4pGV.horizontalReverse-3tRjY7.flex-1O1GKY.directionRowReverse-m8IjIq.justifyStart-2NDFzi.alignStretch-DpGPf3>div:nth-child(3)>svg>rect, #app-mount>div.app-19_DXt.platform-win>div.app-2rEoOp.flex-vertical.theme-dark>div.layers.flex-vertical.flex-spacer>div>div>div.flex-1xMQg5.flex-1O1GKY.vertical-V37hAW.flex-1O1GKY.directionColumn-35P_nr.justifyStart-2NDFzi.alignStretch-DpGPf3.noWrap-3jynv6.base-3dtUhz>div.flex-1xMQg5.flex-1O1GKY.horizontal-1ae9ci.horizontal-2EEEnY.flex-1O1GKY.directionRow-3v3tfG.justifyStart-2NDFzi.alignStretch-DpGPf3.noWrap-3jynv6.spacer-29U_x8>div.channels-Ie2l6A.vertical-V37hAW.flex-1O1GKY.directionColumn-35P_nr>div.flex-1xMQg5.flex-1O1GKY.vertical-V37hAW.flex-1O1GKY.directionColumn-35P_nr.justifyStart-2NDFzi.alignStretch-DpGPf3.noWrap-3jynv6.container-PNkimc>div.flexChild-1KGW5q>div>header>svg>g>path:nth-child(2), #app-mount>div.app-19_DXt.platform-win>div.app-2rEoOp.flex-vertical.theme-dark>div.layers.flex-vertical.flex-spacer>div>div>div.flex-1xMQg5.flex-1O1GKY.vertical-V37hAW.flex-1O1GKY.directionColumn-35P_nr.justifyStart-2NDFzi.alignStretch-DpGPf3.noWrap-3jynv6.base-3dtUhz>div.flex-1xMQg5.flex-1O1GKY.horizontal-1ae9ci.horizontal-2EEEnY.flex-1O1GKY.directionRow-3v3tfG.justifyStart-2NDFzi.alignStretch-DpGPf3.noWrap-3jynv6.spacer-29U_x8>div.channels-Ie2l6A.vertical-V37hAW.flex-1O1GKY.directionColumn-35P_nr>div.flex-1xMQg5.flex-1O1GKY.vertical-V37hAW.flex-1O1GKY.directionColumn-35P_nr.justifyStart-2NDFzi.alignStretch-DpGPf3.noWrap-3jynv6.container-PNkimc>div.flexChild-1KGW5q>div>header>svg>g>path:nth-child(3) {
  stroke: var(--Secondary-Main-Colour) !important;
}

.app-2rEoOp {
  --guild-column-count: calc(26 / 17);
}

.appMount-3VJmYg, .appMount-3lHmkl {
  background: Var(--Title-Background)50% 50%/cover !important;
  background-color: rgba(0, 0, 0, var(--Background-Darkness)) !important;
}

.appMount-3VJmYg .popout-3sVMXz.popoutTopLeft-b5Eb3O, .appMount-3lHmkl .popout-3sVMXz.popoutTopLeft-b5Eb3O {
  border: 0.5px solid var(--Main-Colour) !important;
  /* animation: 500ms DropDown 1 linear; */
}

.inner-1W0Bkn {
  border-radius: 0px;
}

/* ======================================Canary fix for 2019-01-12 I hope====================================== */

.theme-dark .tooltipBlack-PPG47z {
  background: linear-gradient(to top, var(--Secondary-Main-Colour), var(--Background-Colour), var(--Background-Colour), var(--Secondary-Main-Colour));
  color: var(--Main-Colour);
}

.tooltip-2QfLtc .tooltipRight-2JM5PQ {
  margin-left: 8px;
}

.tooltip-2QfLtc {
  -webkit-box-shadow: 0 2px 10px 0 rgba(0, 0, 0, .2);
  -webkit-box-sizing: border-box;
  border-radius: 5px;
  box-shadow: 0 2px 10px 0 rgba(0, 0, 0, .2);
  box-sizing: border-box;
  color: var(--Main-Colour);
  contain: layout;
  font-size: 14px;
  font-weight: 500;
  line-height: 16px;
  max-width: auto;
  padding: 8px 12px;
  word-wrap: break-word;
  z-index: 1002;
}

.tooltip-2QfLtc .tooltipBlack-PPG47z .tooltipRight-2JM5PQ:after {
  border-right-color: var(--Background-Colour);
}

.tooltip-2QfLtc .tooltipRight-2JM5PQ:after {
  margin-top: -5px;
  position: absolute;
  right: 100%;
  top: 50%;
}

.tooltip-2QfLtc:after {
  border: 5px solid transparent;
  content: " ";
  height: 0;
  pointer-events: none;
  width: 0;
}

/*  */

.container-1ETFDs .avatar-S_nsxk {
  height: 40px;
  width: 40px;
}

.theme-dark .option-96V44q.selected-rZcOL-:after {
  background: transparent;
}

.theme-dark .option-96V44q:after {
  background: transparent;
}

.theme-dark .option-96V44q.selected-rZcOL- {
  background: linear-gradient(to bottom, transparent, var(--Background-Colour), var(--Main-Colour));
  color: var(--Main-Colour);
}

.theme-dark .search-2oPWTC .DraftEditor-root, .searchHeader-1l-wpR, .theme-dark .searchHeader-1l-wpR .tab-2Ixsn0, .theme-dark .searchHeader-1l-wpR .totalResults-gxvzgw {
  color: var(--Main-Colour);
}

.theme-dark .searchHeader-1l-wpR {
  background-color: var(--Secondary-Background-Colour);
  box-shadow: 0 1px 0 var(--Secondary-Main-Colour);
}

.theme-dark .searchResultsWrap-2DKFzt {
  background-color: var(--Secondary-Background-Colour);
}

.theme-dark .searchHeader-1l-wpR .tab-2Ixsn0.selected-16te-P, .theme-dark .searchHeader-1l-wpR .tab-2Ixsn0:hover {
  border-bottom: 2px solid var(--Main-Colour);
}

.theme-dark .channelSeparator-1X1FuH .channelName-1QajIf {
  background: transparent;
  color: var(--Main-Colour);
}

.theme-dark .channelSeparator-1X1FuH:before {
  border-color: var(--Secondary-Main-Colour);
}

.channelSeparator-1X1FuH:before {
  border-bottom: 1px solid var(--Secondary-Main-Colour);
}

.theme-dark .searchResult-3pzFAB:before, .searchResult-3pzFAB:before, .theme-dark .searchResult-3pzFAB:after, .searchResult-3pzFAB:after {
  background-image: linear-gradient(360deg, transparent, transparent);
}

.theme-dark .searchResult-3pzFAB .hit-NLlWXA {
  background-color: var(--Secondary-Background-Colour);
  box-shadow: 0 0 5px 3px var(--Secondary-Main-Colour);
  transition: all 200ms;
}

.theme-dark .searchResult-3pzFAB .hit-NLlWXA:hover {
  background-color: var(--Secondary-Background-Colour);
  box-shadow: 0 0 10px 6px var(--Main-Colour);
  transition: all 200ms;
}

.theme-dark .jumpButton-Ia2hRJ {
  background-color: var(--Secondary-Background-Colour);
  color: var(--Secondary-Main-Colour);
  border: 1px solid var(--Secondary-Main-Colour);
}

.theme-dark .jumpButton-Ia2hRJ:hover {
  background-color: var(--Secondary-Background-Colour);
  color: var(--Main-Colour);
  border: 1px solid var(--Main-Colour);
}

.theme-dark .searchResult-3pzFAB.expanded-v2Szsz {
  border: 2px solid var(--Secondary-Main-Colour);
  transition: all 200ms;
}

.theme-dark .searchResult-3pzFAB.expanded-v2Szsz:hover {
  border: 2px solid var(--Main-Colour);
  transition: all 200ms;
}

.theme-dark .searchResult-3pzFAB.expanded-v2Szsz .searchResultMessage-2VxO12.hit-NLlWXA {
  -webkit-box-sizing: border-box;
  background-color: var(--Secondary-Background-Colour);
  border-bottom: 2px solid var(--Secondary-Main-Colour);
  border-top: 2px solid var(--Secondary-Main-Colour);
  box-sizing: border-box;
}

.top-28JiJ- .item-PXvHYJ, .theme-dark .top-28JiJ- .itemSelected-1qLhcL {
  color: var(--Secondary-Main-Colour) !important;
  background: linear-gradient(to top, var(--Secondary-Main-Colour), var(--Background-Colour), var(--Background-Colour), var(--Secondary-Main-Colour))!important;
  border-radius: 25%;
  height: 50%;
  transition: all 200ms;
}

.theme-dark .top-28JiJ- .itemSelected-1qLhcL {
  color: var(--Main-Colour) !important;
  background: linear-gradient(to top, var(--Main-Colour), var(--Background-Colour), var(--Background-Colour), var(--Main-Colour))!important;
  border-radius: 25%;
  height: 50%;
  transition: all 200ms;
}

.notSelected-1N1G5p:hover {
  background: linear-gradient(to top, var(--Main-Colour), var(--Background-Colour), var(--Background-Colour), var(--Main-Colour))!important;
  color: var(--Secondary-Main-Colour);
  transition: all 200ms;
}

.tabBarItem-1b8RUP {
  margin-right: 2%
}

.theme-dark .note-3kmerW textarea:focus {
  background-color: var(--Secondary-Background-Colour)!important;
}

.theme-dark .listRow-hutiT_:hover {
  background: linear-gradient(to bottom, var(--Main-Colour), transparent, transparent, var(--Main-Colour));
  color: var(--Main-Colour);
  transition: all 200ms;
}

.theme-dark .listRow-hutiT_ {
  transition: all 200ms;
}

.tabBar-2MuP6- {
  height: 50%;
}

.guildNick-3uAm3i {
  color: var(--Main-Colour);
}

.theme-dark .friendsTable-133bsv .friendsRow-2yicud .friendsColumnGuilds-2we6jb .moreMutualGuildsBtn-2VwbkO {
  border-color: var(--Secondary-Main-Colour);
  color: var(--Secondary-Main-Colour);
}

.theme-dark .friendsTable-133bsv .friendsRow-2yicud .friendsColumnGuilds-2we6jb .moreMutualGuildsBtn-2VwbkO:hover {
  border-color: var(--Main-Colour);
  color: var(--Main-Colour);
}

.theme-dark .friendsTable-133bsv .friendsRow-2yicud, .theme-dark .friendsTable-133bsv .friendsRow-2yicud:hover {
  transition: background 200ms;
}

.theme-dark .friendsTable-133bsv .friendsRow-2yicud:hover {
  box-shadow: 1px 1px 15px var(--Secondary-Main-Colour)!important;
}

.mobileIndicator-3gyhuE, .theme-dark .mobileIndicator-U-7hTl {
  color: var(--Main-Colour);
}

/* 
.button-38aScr[tabindex="2"], [Gift] {
  display: none;
}

.button-38aScr[tabindex="3"], [Gif] {
  display: none;
}

.button-38aScr[tabindex="4"], [Emote] {
  display: none;
}

.button-38aScr[tabindex="5"], [Upload] {
  display: none;
} 
*/

.theme-dark .otDetected-33MY4s .gameName-1RiWHm, .theme-light .notDetected-33MY4s .gameName-1RiWHm,.theme-dark .lastPlayed-3bQ7Bo, .theme-dark .overlayStatusText-L2IACa,.theme-dark .notDetected-33MY4s .lastPlayed-3bQ7Bo, .theme-light .notDetected-33MY4s .lastPlayed-3bQ7Bo,.theme-dark .nowPlayingAdd-1Kdmh_, .theme-light .nowPlayingAdd-1Kdmh_,.theme-dark .gameName-1RiWHm,.theme-dark .nowPlaying-284llR .gameName-1RiWHm, .theme-light .nowPlaying-284llR .gameName-1RiWHm,.theme-dark .nowPlaying-284llR .lastPlayed-3bQ7Bo, .theme-dark .nowPlaying-284llR .overlayStatusText-L2IACa, .theme-light .nowPlaying-284llR .lastPlayed-3bQ7Bo, .theme-light .nowPlaying-284llR .overlayStatusText-L2IACa{
  color: var(--Main-Colour);
}

.theme-dark .notDetected-33MY4s, .theme-light .notDetected-33MY4s,.theme-dark .nowPlaying-284llR, .theme-light .nowPlaying-284llR{
  background: var(--Secondary-Background-Colour);
}

.gameVerifiedIcon-2dGGa5:after {
  content: "(?)";
  color: var(--Main-Colour);
}

.gameVerifiedIcon-2dGGa5 {
  background-image: none!important;
}

.theme-dark .gameNameInput-385LoS:focus, .theme-dark .gameNameInput-385LoS:hover {
  background-color: var(--Secondary-Background-Colour);
  border-color: var(--Secondary-Main-Colour);
}

#user-settings > div > div > div.sidebarRegion-VFTUkN > div > div > div > div > div.itemSelected-1qLhcL.item-PXvHYJ.selected-3s45Ha:after,
#bd-settings-sidebar > span > div > div.ui-tab-bar-item.selected:after {
  content: " (?)";
  color: var(--Main-Colour);
  transition: all 200ms;
}

#user-settings > div > div > div.sidebarRegion-VFTUkN > div > div > div > div > div.itemSelected-1qLhcL.item-PXvHYJ.selected-3s45Ha {
box-shadow: 1px 1px 15px var(--Main-Colour)!important;
transition: all 200ms;
}

#bd-settings-sidebar .ui-tab-bar-item.selected, .side-8zPYf6 .itemSelected-1qLhcL,.theme-dark .side-8zPYf6 .itemDefault-3Jdr52:hover, .theme-dark .side-8zPYf6 .itemHover-EnbcjT:hover, .contentHoveredVoice-3p_NEO, .contentSelectedVoice-1WDIBM,.theme-dark #bd-settings-sidebar .ui-tab-bar-item:hover {
  color: var(--Main-Colour) !important;
  background: var(--Secondary-Background-Colour) !important;
  transition: all 200ms;
}

.theme-dark .side-8zPYf6 .itemDefault-3Jdr52:hover{
  box-shadow: 1px 1px 15px var(--Main-Colour)!important;
  transition: all 200ms;
}

.side-8zPYf6 .itemDefault-3Jdr52,#bd-settings-sidebar > span > div > div.ui-tab-bar-item.selected{
  box-shadow: 1px 1px 5px var(--Secondary-Main-Colour)!important;
  transition: all 200ms;
}

.container-1ETFDs .selected-nT-gM3{
  box-shadow: 0px 0px 15px 0px var(--Main-Colour);
  border-radius: 15px;
}

.headerCozy-2N9HOL>div>div{
  border-radius: var(--Chat-Avatar-Border-Radius)!important;
}

.unreadMentionsIndicatorBottom-BXS58x, .unreadMentionsIndicatorTop-gA6RCh{
  width: calc(var(--Guild-Columns) * 60px + 2px)!important;
  max-width: calc(var(--Guild-Columns) * 60px + 2px)!important;
}

/* Credit to MasicoreLord#5338 (197435711476072449) */
.wrapper-1Rf91z.foldercontent.da-guildsWrapper.da-foldercontent.foldercontentopen>div {
  width: calc(var(--Guild-Columns) * 60px + 2px)!important;
  max-width: calc(var(--Guild-Columns) * 60px + 2px)!important;
}

.foldercontentopen>.scrollerWrap-1IAIlv {
  width: calc(var(--Guild-Columns) * 60px + 2px)!important;
  max-width: calc(var(--Guild-Columns) * 60px + 2px)!important;
  padding-left: 5px;
}

.foldercontent {
  width: calc(var(--Guild-Columns) * 60px + 2px)!important;
  max-width: calc(var(--Guild-Columns) * 60px + 2px)!important;
  display: flex;
  flex-flow: row wrap;
  padding-left: 0;
  align-content: flex-start;
  justify-content: center;
}

.wrapper-1Rf91z {
  width: calc(var(--Guild-Columns) * 60px + 2px)!important;
  max-width: calc(var(--Guild-Columns) * 60px + 2px)!important;
}

.wrapper-1Rf91z .scrollerWrap-1IAIlv {
  width: calc(var(--Guild-Columns) * 60px + 2px)!important;
  max-width: calc(var(--Guild-Columns) * 60px + 2px)!important;
}

/* Credit to MasicoreLord#5338 (197435711476072449) */

.wrapper-1Rf91z .scroller-2TZvBN {
  display: flex;
  flex-flow: row wrap;
  padding-left: 0;
  align-content: flex-start;
  justify-content: center;
}

.wrapper-1Rf91z .scroller-2TZvBN .container-1ETFDs {
  position: relative;
  margin: 8px 5px 2px 5px;
}

.wrapper-1Rf91z .scroller-2TZvBN .container-1ETFDs.wrapper-2lTRaf {
  cursor: pointer;
  overflow: hidden;
  border-radius: 25px;
  background: transparent !important;
  font-size: 18px;
  text-align: center;
  line-height: 50px;
}

.wrapper-1Rf91z .scroller-2TZvBN .friends-icon {
  background-size: 50%!important;
  background-position: 30% 35%!important;
}

.wrapper-1Rf91z .scroller-2TZvBN .container-1ETFDs.wrapper-2lTRaf a {
  background-size: cover!important;
}

.wrapper-1Rf91z .scroller-2TZvBN .container-1ETFDs.unread-2OHH1w::before {
  left: -2px;
  top: 5px;
  z-index: 30;
}

.wrapper-1Rf91z .scroller-2TZvBN>.guild:first-child {
  position: relative;
  left: 0;
  margin: auto;
}

#bd-pub-li {
  position: absolute;
  top: 0;
  left: 0;
}

#bd-pub-li #bd-pub-button {
  width: 100%;
  text-align: center;
}

.wrapper-1Rf91z .scroller-2TZvBN .guildSeparator-3s64Iy {
  position: relative;
}

.wrapper-1Rf91z .scroller-2TZvBN .friendsOnline-2JkivW {
  position: relative;
  width: 100%;
  margin: auto;
  margin-top: 5px;
}

.wrapper-1Rf91z .scroller-2TZvBN .container-1ETFDs.selected-nT-gM3:before {
  display: none;
}

.wrapper-1Rf91z .scroller-2TZvBN .dms-rcsEnV {
  width: 100%;
  display: flex;
  flex-flow: row wrap;
  justify-content: center;
  align-items: center;
}

.wrapper-1Rf91z .scroller-2TZvBN .dms-rcsEnV .container-1ETFDs {
  left: 0;
}

.wrapper-1Rf91z .scroller-2TZvBN .dms-rcsEnV .container-1ETFDs {
  margin: 8px 8px 8px 0;
}

.wrapper-1Rf91z .scroller-2TZvBN .dms-rcsEnV .container-1ETFDs+.container-1ETFDs {
  margin-left: 0;
}

.wrapper-1Rf91z .scroller-2TZvBN .dms-rcsEnV:empty {
  display: none;
}

.container-11WMXy [name='Search']{
  top: -2px;
}

.container-11WMXy [name='Search']:not(:hover){
  color: var(--Secondary-Main-Colour)
}

.theme-dark .pageWrapper-1PgVDX {
  background-color: transparent;
  color: var(--Main-Colour);
}

.bg-AYqtMd,.emptySearchResults-1ba__I{
  display: none;
}

.theme-dark .memberInfo-3r4FKx, .theme-light .memberInfo-3r4FKx,.theme-dark .title-OqQvkN, .theme-light .title-OqQvkN,.theme-light .description-Bw8krY,.theme-light .sampleLink-KPFu3I,.theme-light .inputLabel-vJ2Z0B,.avatarUploader-3XDtmn .sizeInfo-SKMPPw,.theme-light .helpText-h3r3wC, .theme-light .label-wQQoIq,.avatarUploaderInner-3UNxY3>*,.theme-dark .finePrint-xGGTK5{
  color: var(--Main-Colour)
}

.theme-dark .circleIconButton-jET_ig.selected-nT-gM3, .theme-dark .circleIconButton-jET_ig:hover{
  border-color: var(--Main-Colour);
}

.theme-dark .header-3ZP1MY, .theme-light .header-3ZP1MY{
  display: none;
}

.theme-dark .action-1lSjCi, .theme-light .action-1lSjCi{
  background: var(--Secondary-Background-Colour);
  border: none;;
  box-shadow: 0 2px 4px rgba(0,0,0,0);
  padding-top: 33%;
}

.theme-dark .or-3THJsp, .theme-light .or-3THJsp,.theme-dark .join-33Tr-7 .actionIcon-2IISM_, .theme-light .join-33Tr-7 .actionIcon-2IISM_,.theme-dark .create-3jownz .actionIcon-2IISM_, .theme-light .create-3jownz .actionIcon-2IISM_,.theme-dark .actionBody-1qj65C, .theme-light .actionBody-1qj65C,.theme-dark .join-33Tr-7 .actionHeader-2CT5c7, .theme-light .join-33Tr-7 .actionHeader-2CT5c7,.theme-dark .create-3jownz .actionHeader-2CT5c7, .theme-light .create-3jownz .actionHeader-2CT5c7,.theme-dark .title-2CFvp_,#app-mount > div:nth-child(5) > div.modal-1UGdnR > div.inner-1JeGVc > div > div > div > form > div.scrollerWrap-2lJEkd.firefoxFixScrollFlex-cnI2ix.content-2BXhLs.scrollerThemed-2oenus.themeGhostHairline-DBD-2d > div > div.instructions-3xkbTC > p:nth-child(3),.cancelButton-RGXhAE:before,.theme-light .title-2Dc-Cb,.theme-light .description-QF3836 {
  display: none;
}

.theme-dark .slideBody-2nMrnU, .theme-light .slideBody-2nMrnU {
  background-image: none;
}

.actions-pBaxX6{
  height: auto;
}

.theme-dark .actionButton-2PeQbJ, .theme-light .actionButton-2PeQbJ{
  background: var(--Secondary-Background-Colour)!important;
  color: var(--Secondary-Main-Colour)!important;
  border: 1px solid var(--Secondary-Main-Colour);
  transition: all 200ms;
}

.theme-dark .actionButton-2PeQbJ:hover, .theme-light .actionButton-2PeQbJ:hover {
  background: var(--Secondary-Background-Colour)!important;
  color: var(--Main-Colour)!important;
  border: 1px solid var(--Main-Colour);
  transition: all 200ms;
}

#app-mount > div:nth-child(5) > div.modal-1UGdnR > div.inner-1JeGVc > div > div > div > form > div.scrollerWrap-2lJEkd.firefoxFixScrollFlex-cnI2ix.content-2BXhLs.scrollerThemed-2oenus.themeGhostHairline-DBD-2d > div > div.instructions-3xkbTC > p:nth-child(4),#app-mount > div:nth-child(5) > div.modal-1UGdnR > div.inner-1JeGVc > div > div > div > form > div.scrollerWrap-2lJEkd.firefoxFixScrollFlex-cnI2ix.content-2BXhLs.scrollerThemed-2oenus.themeGhostHairline-DBD-2d > div > div.instructions-3xkbTC > p:nth-child(2){
  font-size: 0;
}

#app-mount > div:nth-child(5) > div.modal-1UGdnR > div.inner-1JeGVc > div > div > div > form > div.scrollerWrap-2lJEkd.firefoxFixScrollFlex-cnI2ix.content-2BXhLs.scrollerThemed-2oenus.themeGhostHairline-DBD-2d > div > div.instructions-3xkbTC > p:nth-child(4):after{
  font-size: initial;
  content: "kWRYPrq";
}

#app-mount > div:nth-child(5) > div.modal-1UGdnR > div.inner-1JeGVc > div > div > div > form > div.scrollerWrap-2lJEkd.firefoxFixScrollFlex-cnI2ix.content-2BXhLs.scrollerThemed-2oenus.themeGhostHairline-DBD-2d > div > div.instructions-3xkbTC > p:nth-child(2):after{
  font-size: initial;
  content: "https://discord.gg/kWRYPrq";
}

.theme-dark .footer-2yfCgX {
  box-shadow: inset 0 1px 0 var(--Secondary-Main-Colour);
}

.theme-light .cancelButton-RGXhAE{
  color: var(--Secondary-Main-Colour);
}

.theme-light .cancelButton-RGXhAE:hover{
  color: var(--Main-Colour);
}

.theme-light .cancelButton-RGXhAE:hover {
  border-bottom-color: var(--Main-Colour);
}

.avatar-21196O {
  border: none;
}

.avatarUploaderInner-3UNxY3{
  height: 40px;
  width: 40px;
  background-color: var(--Secondary-Main-Colour);
}

.theme-dark .regionSelect-3lf4eE:hover .regionSelectInner-24f4Ce, .theme-dark .regionSelect-3lf4eE:hover button, .theme-light .regionSelect-3lf4eE:hover .regionSelectInner-24f4Ce, .theme-light .regionSelect-3lf4eE:hover button{
  border-color: var(--Main-Colour);
}

.theme-dark .wrapper-29NfPK.minimum-2d6zH6 .actions-2vadYq .center-1Vp33r {
  background-color: var(--Secondary-Background-Colour);
  border-color: var(--Secondary-Background-Colour);
}

.theme-dark .root-26DmKJ {
  background-color: transparent;
}

.theme-dark .description-1RsfgZ,.theme-dark .tagline-2nvxi0,.theme-dark .description-2Ifi6N,.theme-dark .description-2Ifi6N strong, .theme-dark .username-2gp_Xw {
  color: var(--Main-Colour);
}

.theme-dark .tile-2OwFgW {
  background-color: var(--Secondary-Background-Colour);
  box-shadow: 0 0 0 var(--Secondary-Main-Colour);
}

.theme-dark .tile-2OwFgW:hover {
  background-color: var(--Secondary-Background-Colour);
  box-shadow: 0 0 0 var(--Main-Colour);
}

.theme-dark .popout-2xBvMR {
  background-color: var(--Background-Colour);
  box-shadow: 0 0 0 0 var(--Secondary-Main-Colour);
  color: var(--Main-Colour);
}

.theme-dark .iconCircle-1dlYo0 {
  background-color: var(--Background-Colour);
}

.theme-dark .circle-1nK_79 {
  color: var(--Main-Colour);
}

.embedDescription-1Cuq9a > [aria-label="Spoiler"]{
  line-height: 1.5rem;
}

#bd-pub-li{
  position: relative!important;
  margin: 0!important;
}

.backgroundBlur-dazcBE,
.theme-dark .pictureInPictureVideo-20ZvXn {
  background: transparent!important;
}

.theme-dark .wrapper-29NfPK {
  border: 1px solid transparent;
}

.theme-dark .wrapper-29NfPK {
  background-color: transparent;
}


[class^="reply"] > svg > path:nth-child(2) {
  fill: transparent!important;
}

.reply-list,.reply-item {
  background: var(--Secondary-Background-Colour);
  color: var(--Main-Colour);
  border: 1px solid var(--Secondary-Main-Colour);
}

.theme-dark .inner-zqa7da:focus-within {
  border-color: var(--Main-Colour)!important;
  transition: border 200ms;
}

.theme-dark .inner-zqa7da {
  border-color: var(--Secondary-Main-Colour)!important;
  transition: border 200ms;
}

.base-gE7OpD .cooldownWrapper-3joyFc {
  margin-left: 0%;
  overflow: visible;
  white-space: nowrap;
  font-size: 0;
}

.theme-dark .typing-2GQL18 span {
  color: var(--Main-Colour);
}

.typing-2GQL18.base-gE7OpD > span.spinner-2enMB9.ellipsis-19qdx6 > span{
  top: 0!important;
  left: 0!important;
}

.theme-dark .base-gE7OpD .ellipsis-19qdx6 .spinnerItem-2HfQC8 {
  background-color: var(--Main-Colour);
}

.spacer-1fA9zc.vertical-V37hAW.flex-1O1GKY.directionColumn-35P_nr > form > div.typing-2GQL18.base-gE7OpD > div > svg{
  color: var(--Secondary-Main-Colour);
}

#app-mount .theme-light [class*='topSection']:not(.topSectionNormal-2-vo2m) .joinedAtDate,#app-mount .theme-dark [class*='topSection'] .joinedAtDate, #app-mount .theme-light .header-2BwW8b:not(.headerNormal-T_seeN) .joinedAtDate, #app-mount .theme-dark .header-2BwW8b .joinedAtDate{
  color: var(--Main-Colour);
}

#app-mount .theme-dark .headerNormal-1cioxU .creationDate, #app-mount .theme-dark .topSectionNormal-2-vo2m .creationDate, #app-mount .theme-light [class*='topSection']:not(.topSectionNormal-2-vo2m) .creationDate, #app-mount .theme-dark [class*='topSection'] .creationDate, #app-mount .theme-light .header-2BwW8b:not(.headerNormal-T_seeN) .creationDate, #app-mount .theme-dark .header-2BwW8b .creationDate{
  color: var(--Main-Colour);
}

.uploadInput-2lNPSo #charcounter{
  color: var(--Secondary-Main-Colour);
}

.theme-dark .wrapper-2lTRaf {
  background: transparent;
}

.container-2td-dC,.circleIconButton-jET_ig{
  height: 40px;
  width: 40px;
}

.selected-nT-gM3:before{
  display: none;
}

.wrapper-1Rf91z .scroller-2TZvBN .container-2td-dC {
  position: relative;
  margin: 8px 5px 2px 5px;
}

.theme-dark .unread-2OHH1w:before {
  left: -2px;
  top: 5px;
  z-index: 30;
  animation: opacity var(--Unread-Message-Speed) infinite linear;
  background-color: var(--Unread-Message-1);
}

.unread-2OHH1w:before {
  animation: opacity var(--Unread-Message-Speed) infinite linear;
  background-color: var(--Unread-Message-1);
}

.container-2td-dC.folder .badge-3dItlm.folder.count {
  background: transparent !important;
  border-color: transparent !important;
  height: 10px !important;
  top: 12.5px !important;
  right: 5px !important;
  left: 5px !important;
  color: var(--Main-Colour) !important;
}

.container-2td-dC.folder.open .badge-1GsMF2.folder.count{
  transform: translate(8px) skew(-40deg);
  transition: all 25ms;
}

.container-2td-dC.folder .badge-1GsMF2.folder.count{
  transform: translate(6px);
  transition: all 25ms;
}

.container-1aNBdK,.avatar-3f3jk4{
  width: 40px!important;
  height: 40px!important;
}

.container-2td-dC:not(#bd-pub-li), .circleIconButton-jET_ig{
  width: 40px!important;
  height: 40px!important;
  position: relative;
  margin: 8px 5px 2px 5px;
}

#bd-pub-li{
  position: absolute!important;
}

.circleIconButton-jET_ig{
  border-style: double;
}

.bannerImage-1jOskm[style*="/banners/"] {
  background-image: linear-gradient(var(--Secondary-Background-Colour) 50%, var(--Background-Colour) 100%), var(--Popout-Background)!important;
}

.noticeDefault-362Ko2 {
  background-color: var(--Secondary-Background-Colour);
  border: 1px dotted #f26522;
  color: var(--Main-Colour);
}

.isSending-1nPcL7 {
  opacity: .5;
  animation: CLog 1s infinite linear;
  color: var(--Main-Colour)!important;
}

.isSending-1nPcL7  > .markup-2BOw-j{
  color: var(--Main-Colour)!important;
}

.noIcon-1a_FrS{
  color: var(--Main-Colour);
}

.wrapper-2lTRaf[style*="background-color: rgb("]{
  background: transparent!important;
}

.sidebarRegion-VFTUkN,.contentRegion-3nDuYy{
  background: rgba(0,0,0,var(--Background-Darkness))!important;
}

.theme-light .layers-3iHuyZ:before {
  content: "Light Theme is NOT supported, \a Please switch to Dark Theme. \a [Settings > Appearance > Theme > Dark]";
  background: var(--Background-Colour);
  border: 1px solid var(--Main-Colour);
  border-radius: 5px;
  padding: 5px 15px;
  text-align: center;
  position: relative;
  top: 50%;
  z-index: 9997;
  color: var(--Main-Colour);
}

.bd-minimal:after{
  content: "Minimal Mode is NOT supported, \a Please turn it off. \a [Settings > Core > Minimal Mode]";
  background: var(--Background-Colour);
  border: 1px solid var(--Main-Colour);
  border-radius: 5px;
  padding: 5px 15px;
  text-align: center;
  position: absolute;
  top: 50%;
  z-index: 9997;
  color: var(--Main-Colour);
}

#user-settings > div:nth-child(3) > div > div:nth-child(2) > div > div > div > div.contentColumn-2hrIYH.contentColumnDefault-1VQkGM > div > div > div:nth-child(2) > .radioGroup-1GBvlr > div:nth-child(1){
  display: none;
}



/* ===============================================canary bs=============================================== */
.theme-dark .container-1r6BKw{
  background: transparent;
  box-shadow: none;
  color: var(--Main-Colour);
}

.theme-dark .themed-OHr7kt.item-PXvHYJ,.channel-2QD9_O .linkButtonIcon-Mlm5d6,.darkTheme-3uETC4 .input-1Rv96N,.theme-dark .input-1Rv96N,.theme-dark .container-2XeR5Z,.theme-dark .icon-1S6UIr,.theme-dark .name-3_Dsmg, .theme-light .name-3_Dsmg,.theme-dark .colorMuted-HdFt4q,.wrapper-CU3qI5{
  color: var(--Secondary-Main-Colour);
}

.theme-dark .children-19S4PO:after,.theme-dark .empty-hejAOj,.arrowContainer-17eG6u{
  display: none;
}

.theme-dark .outer-2IVh5n,.coloredBackground-37Z6Gv,.theme-dark .unwrapped-37iUtM,.theme-dark .outer-2IVh5n.interactive-1BeKSi:hover,.darkTheme-3uETC4.container-2XeR5Z,.theme-dark .container-2XeR5Z,.theme-dark .container-cMG81i{
  background: var(--Secondary-Background-Colour);
}

.theme-dark .wrapper-3UweLa{
  background: var(--Secondary-Background-Colour);
  color: var(--Main-Colour);
}

.theme-dark .unwrapped-37iUtM.clickable-nnkAZy:hover, .theme-dark .wrapped-15rg6t,.theme-dark .side-8zPYf6 .themed-OHr7kt.selected-3s45Ha.item-PXvHYJ, .theme-dark .side-8zPYf6 .themed-OHr7kt.selected-3s45Ha.item-PXvHYJ:hover, .theme-dark .topPill-30KHOu .themed-OHr7kt.selected-3s45Ha.item-PXvHYJ, .theme-dark .topPill-30KHOu .themed-OHr7kt.selected-3s45Ha.item-PXvHYJ:hover{
  background: var(--Background-Colour);
  border: 1px solid var(--Main-Colour);
}

.theme-dark .unwrapped-37iUtM.clickable-nnkAZy, .theme-dark .wrapped-15rg6t,.theme-dark .side-8zPYf6 .themed-OHr7kt.item-PXvHYJ:hover, .theme-dark .topPill-30KHOu .themed-OHr7kt.item-PXvHYJ:hover{
  background: var(--Secondary-Background-Colour);
  border: 1px solid var(--Secondary-Main-Colour);
}

.theme-dark .wrapper-9ppXpy{
  box-shadow: none;
}

.tabBarItem-1b8RUP{
  border-color: transparent!important;
}

.theme-dark .button-OhfaWu.selected-wSa2KV, .theme-light .button-OhfaWu.selected-wSa2KV,.theme-dark .button-OhfaWu, .theme-light .button-OhfaWu{
  background-color: transparent!important;
}

.item-2hkk8m{
  left: 8px;
  top: 0px;
  z-index: 30;
  animation: opacity var(--Unread-Message-Speed) infinite linear;
  background-color: var(--Unread-Message-1);
  position: relative;
  width: 5px!important;
  height: 5px!important;
}

.base-PmTxvP{
  background: var(--Background-Colour)!important;
  color: var(--Main-Colour)!important;
  border: 1px solid var(--Main-Colour);
}

.theme-dark .wrapper-1ucjTd.modeSelected-1zApJ_ .content-3at_AU, .theme-dark .wrapper-1ucjTd.modeSelected-1zApJ_:hover .content-3at_AU, .theme-light .wrapper-1ucjTd.modeSelected-1zApJ_ .content-3at_AU, .theme-light .wrapper-1ucjTd.modeSelected-1zApJ_:hover .content-3at_AU,.theme-dark .wrapper-1ucjTd:hover .content-3at_AU, .theme-light .wrapper-1ucjTd:hover .content-3at_AU{
  background: var(--Secondary-Background-Colour);
  border: 1px solid var(--Main-Colour);
  transition: all 200ms;
}

.theme-light .wrapper-1ucjTd.modeSelected-1zApJ_ .content-3at_AU, .theme-light .wrapper-1ucjTd.modeSelected-1zApJ_ .content-3at_AU,.theme-dark .wrapper-1ucjTd .content-3at_AU, .theme-light .wrapper-1ucjTd .content-3at_AU{
  background: var(--Secondary-Background-Colour);
  border: 1px solid transparent;
  transition: all 200ms;
}

.side-8zPYf6 .item-PXvHYJ{
  background: var(--Secondary-Background-Colour);
  border: 1px solid var(--Secondary-Main-Colour);
  transition: all 200ms;
}

.side-8zPYf6 .item-PXvHYJ:hover{
  background: var(--Secondary-Background-Colour);
  border: 1px solid var(--Main-Colour);
  transition: all 200ms;
}

.listItem-2P_4kh {
  width: 55px;
}

.modeMuted-3osy7j {
  filter: brightness(50%);
}

.theme-dark .icon-22AiRD,
.theme-dark .base-1x0h_U,
.theme-dark .colorStandard-2KCXvj,
.theme-dark .header-3uLGFv,
.theme-dark .whiteButton-1lwF-y,
.theme-dark .themed-OHr7kt.selected-3s45Ha.item-PXvHYJ,
.theme-dark .themed-OHr7kt.selected-3s45Ha.item-PXvHYJ:hover,
.theme-dark .themed-OHr7kt.item-PXvHYJ:hover,
.tutorialMessages-12mfId,
.theme-dark .input-3Xdcic,
.theme-dark .wrapper-1ucjTd.modeMuted-3osy7j:hover .name-3_Dsmg,
.theme-dark .wrapper-1ucjTd:hover .name-3_Dsmg,
.theme-dark .wrapper-1ucjTd.modeConnected-2IEL4z .name-3_Dsmg,
.theme-dark .wrapper-1ucjTd.modeConnected-2IEL4z:hover .name-3_Dsmg,
.theme-dark .wrapper-1ucjTd.modeSelected-1zApJ_ .name-3_Dsmg,
.theme-dark .wrapper-1ucjTd.modeSelected-1zApJ_:hover .name-3_Dsmg,
.theme-dark .wrapper-1ucjTd.modeUnread-1zpFdA .name-3_Dsmg,
.theme-dark .wrapper-1ucjTd.modeUnread-1zpFdA:hover .name-3_Dsmg,
.wrapper-CU3qI5:hover,
.container-2Thooq,
.theme-dark .icon-3cZ1F_,
.theme-dark .transparent-2ZlE3R .title-29uC1r,
.theme-dark .nicknames-1XK4Zt,
.theme-dark .wrapper-1ucjTd.modeMuted-3osy7j .name-3_Dsmg,
.theme-dark .topic-TCb_qw,
.theme-dark .mobileIndicator-329Gd6 {
  color: var(--Main-Colour) !important;
}

.theme-dark .acronym-2mOFsV,
.theme-light .acronym-2mOFsV {
  background-color: var(--Secondary-Background-Colour);
  color: var(--Secondary-Main-Colour);
}

.theme-dark .acronym-2mOFsV.selected-bZ3Lue,
.theme-dark .acronym-2mOFsV:hover,
.theme-light .acronym-2mOFsV.selected-bZ3Lue,
.theme-light .acronym-2mOFsV:hover {
  background-color: var(--Background-Colour);
  color: var(--Main-Colour);
}

#dd1e525d-b9b3-4e4a-a876-e09b96d34e50>rect:nth-child(2) {
  fill: var(--Secondary-Background-Colour) !important;
}

.theme-dark .button-2b6hmh:hover,
.theme-dark .unread-3zKkbm {
  background-color: transparent !important;
}

.buttonDisconnect-3W_SJc,
.buttonScreenShare-3zPiSA,
.buttonInfo-3nkbOt,
.theme-dark .button-2KyEfG:hover,
.container-2Thooq .horizontal-1ae9ci div button[style='background-image: url("/assets/c8845c514bbf3f1e5bea064c1e40b08d.svg");'],
.container-2Thooq .horizontal-1ae9ci div button[style='background-image: url("/assets/c7c47afdf35d5a3e06233319d3aa7674.svg");'],
.container-2Thooq .horizontal-1ae9ci div button[style='background-image: url("/assets/896770bf2d6ed0358ed0adefdbe96a24.svg");'],
.container-2Thooq .horizontal-1ae9ci div button[style$='background-image: url("/assets/4bc527c257233fc69b94342d77bcb9ee.svg");'],
.buttonInner-LmnaN_>[name="Gear"]>path,
.small--aHOfS[style*="/assets/990826f372c3d1d1792e3f1df06609bb.svg"],
.small--aHOfS[style*="/assets/4bc527c257233fc69b94342d77bcb9ee.svg"],
.small--aHOfS[style*="/assets/4bc527c257233fc69b94342d77bcb9ee.svg"] {
  background-color: var(--Settings-Dock-Colour) !important;
  color: var(--Settings-Dock-Colour) !important;
  fill: var(--Settings-Dock-Colour) !important;
}

.medium-2JR8YY[style*="/assets/d47d2c5ce2dd7d5bdaee2ebd8fde61f2.svg"],
.medium-2JR8YY[style*="/assets/4bc527c257233fc69b94342d77bcb9ee.svg"],
.medium-2JR8YY[style*="/assets/ea5bf2e8b48cfe21ea60588e1568aad6.svg"],
.medium-2JR8YY[style*="/assets/b0aeca4d2129dcbf73f05feb6bb6e61f.svg"],
.medium-2JR8YY[style*="/assets/990826f372c3d1d1792e3f1df06609bb.svg"],
.medium-2JR8YY[style*="/assets/f67374a8fd6b116362596d65cc516747.svg"],
.friendsTable-133bsv .friendsRow-2yicud .friendsColumnActions-1LT3_M .friendsAction-__WNE9.friendsActionVideoCall-2_PKeP:hover,
.friendsTable-133bsv .friendsRow-2yicud .friendsColumnActions-1LT3_M .friendsAction-__WNE9.friendsActionVoiceCall-3EdPsR:hover,
.friendsTable-133bsv .friendsRow-2yicud .friendsColumnActions-1LT3_M .friendsAction-__WNE9.friendsActionRemove-qu8nnl:hover {
  background-color: var(--Main-Colour) !important;
  color: var(--Main-Colour) !important;
  fill: var(--Main-Colour) !important;
}

.friendsTable-133bsv .friendsRow-2yicud .friendsColumnActions-1LT3_M .friendsAction-__WNE9.friendsActionVideoCall-2_PKeP,
.friendsTable-133bsv .friendsRow-2yicud .friendsColumnActions-1LT3_M .friendsAction-__WNE9.friendsActionVoiceCall-3EdPsR,
.friendsTable-133bsv .friendsRow-2yicud .friendsColumnActions-1LT3_M .friendsAction-__WNE9.friendsActionRemove-qu8nnl {
  background-color: var(--Secondary-Main-Colour) !important;
  color: var(--Secondary-Main-Colour) !important;
  fill: var(--Secondary-Main-Colour) !important;
}

.inner-btChU7 {
  max-width: 60%;
}

.buttonScreenShare-3zPiSA {
  content: "";
  -webkit-mask: url('data:image/svg+xml; utf8, <svg xmlns="http://www.w3.org/2000/svg" width="18" height="18" viewBox="0 0 18 18"><g fill="none" fill-rule="evenodd"><path fill="#fff" fill-rule="nonzero" d="M15.75,2.25 L2.25,2.25 C1.4175,2.25 0.75,2.9175 0.75,3.75 L0.75,12.75 C0.75,13.575 1.4175,14.25 2.25,14.25 L6,14.25 L6,15.75 L12,15.75 L12,14.25 L15.75,14.25 C16.575,14.25 17.2425,13.575 17.2425,12.75 L17.25,3.75 C17.25,2.9175 16.575,2.25 15.75,2.25 Z M15.75,12.75 L2.25,12.75 L2.25,3.75 L15.75,3.75 L15.75,12.75 Z"/><polygon points="0 0 18 0 18 18 0 18"/></g></svg>');
  -webkit-mask-size: 80% !important;
  -webkit-mask-position: 80% !important;
  -webkit-mask-repeat: no-repeat !important;
  background-image: none !important;
}

.buttonDisconnect-3W_SJc {
  content: "";
  -webkit-mask: url('data:image/svg+xml; utf8, <svg xmlns="http://www.w3.org/2000/svg" width="24" height="24" viewBox="0 0 24 24"><g fill="none" fill-rule="evenodd"><rect width="24" height="24"/><path fill="#FFFFFF" d="M1,0 C0.44771525,0 0,0.44771525 0,1 C-4.4408921e-16,10.3888407 7.61115925,18 17,18 C17.2652165,18 17.5195704,17.8946432 17.7071068,17.7071068 C17.8946432,17.5195704 18,17.2652165 18,17 L18,13.5 C18,12.9477153 17.5522847,12.5 17,12.5 C15.76,12.5 14.55,12.3 13.43,11.93 C13.08,11.82 12.69,11.9 12.41,12.18 L10.21,14.38 C7.38,12.94 5.07,10.62 3.62,7.79 L5.82,5.58 C6.1,5.31 6.18,4.92 6.07,4.57 C5.7,3.45 5.5,2.24 5.5,1 C5.5,0.44771525 5.05228475,0 4.5,0 M16.1213203,0.464466094 L14,2.58578644 L11.8786797,0.464466094 L10.4644661,1.87867966 L12.5857864,4 L10.4644661,6.12132034 L11.8786797,7.53553391 L14,5.41421356 L16.1213203,7.53553391 L17.5355339,6.12132034 L15.4142136,4 L17.5355339,1.87867966" transform="matrix(1 0 0 -1 3 21)"/></g></svg>');
  -webkit-mask-size: 80% !important;
  -webkit-mask-position: 80% !important;
  -webkit-mask-repeat: no-repeat !important;
  background-image: none !important;
}

[style*="/assets/c7c47afdf35d5a3e06233319d3aa7674.svg"] {
  content: "";
  -webkit-mask: url('data:image/svg+xml; utf8, <svg xmlns="http://www.w3.org/2000/svg" width="24" height="24" viewBox="0 0 24 24"><g fill="none" fill-rule="evenodd"><rect width="24" height="24"/><path fill="#FFFFFF" d="M3,11 C3,6 7,2 12,2 L12,4 C8.13400675,4 5,7.13400675 5,11 L5,13 L9,13 L9,21 L6,21 C4.34314575,21 3,19.6568542 3,18 L3,11 Z M21,11 L21,18 C21,19.6568542 19.6568542,21 18,21 L15,21 L15,13 L19,13 L19,11 C19,7.13400675 15.8659932,4 12,4 L12,2 C17,2 21,6 21,11 Z"/></g></svg>');
  -webkit-mask-size: 80% !important;
  -webkit-mask-position: 80% !important;
  -webkit-mask-repeat: no-repeat !important;
  background-image: none !important;
}

[style*="/assets/c7c47afdf35d5a3e06233319d3aa7674.svg"] {
  content: "";
  -webkit-mask: url('data:image/svg+xml; utf8, <svg xmlns="http://www.w3.org/2000/svg" width="24" height="24" viewBox="0 0 24 24"><g fill="none" fill-rule="evenodd"><rect width="24" height="24"/><path fill="#FFFFFF" d="M3,11 C3,6 7,2 12,2 L12,4 C8.13400675,4 5,7.13400675 5,11 L5,13 L9,13 L9,21 L6,21 C4.34314575,21 3,19.6568542 3,18 L3,11 Z M21,11 L21,18 C21,19.6568542 19.6568542,21 18,21 L15,21 L15,13 L19,13 L19,11 C19,7.13400675 15.8659932,4 12,4 L12,2 C17,2 21,6 21,11 Z"/></g></svg>');
  -webkit-mask-size: 80% !important;
  -webkit-mask-position: 80% !important;
  -webkit-mask-repeat: no-repeat !important;
  background-image: none !important;
}

.small--aHOfS[style*="/assets/4bc527c257233fc69b94342d77bcb9ee.svg"] {
  content: "";
  -webkit-mask: url('data:image/svg+xml; utf8, <svg xmlns="http://www.w3.org/2000/svg" width="24" height="24" viewBox="0 0 24 24"><g fill="none" fill-rule="evenodd"><rect width="24" height="24"/><path fill="#FFFFFF" d="M7,4.4408921e-16 C8.65685425,0 10,1.34314575 10,3 L10,9 C10,10.6568542 8.65685425,12 7,12 C5.34314575,12 4,10.6568542 4,9 L4,3 C4,1.34314575 5.34314575,4.4408921e-16 7,0 L7,4.4408921e-16 Z M14,9 C14,12.53 11.39,15.44 8,15.93 L8,19 L6,19 L6,15.93 C2.61,15.44 0,12.53 0,9 L2,9 C2,11.7614237 4.23857625,14 7,14 C9.76142375,14 12,11.7614237 12,9 L14,9 L14,9 Z" transform="translate(5 3)"/></g></svg>');
  -webkit-mask-size: 80% !important;
  -webkit-mask-position: 80% !important;
  -webkit-mask-repeat: no-repeat !important;
  background-image: none !important;
}

.small--aHOfS[style*="/assets/896770bf2d6ed0358ed0adefdbe96a24.svg"] {
  content: "";
  -webkit-mask: url('data:image/svg+xml; utf8, <svg xmlns="http://www.w3.org/2000/svg" width="24" height="24" viewBox="0 0 24 24"><g fill="none" fill-rule="evenodd" transform="matrix(-1 0 0 1 24 0)"><rect width="24" height="24"/><g transform="matrix(-1 0 0 1 21 3)"><path fill="#FFFFFF" d="M16,9 C16,10.19 15.66,11.3 15.1,12.28 L13.87,11.05 C14.14,10.43 14.3,9.74 14.3,9 L16,9 L16,9 Z M12,9.16 L6,3.18 L6,3 C6,1.34314575 7.34314575,4.4408921e-16 9,0 C10.6568542,0 12,1.34314575 12,3 L12,9 L12,9.16 L12,9.16 Z M12.54,14.81 C11.77,15.27 10.91,15.58 10,15.72 L10,19 L8,19 L8,15.72 C4.72,15.23 2,12.41 2,9 L3.7,9 C3.7,12 6.24,14.1 9,14.1 C9.81,14.1 10.6,13.91 11.31,13.58 L9.65,11.92 L9,12 C7.34314575,12 6,10.6568542 6,9 L6,8.28 L12.54,14.81 Z" opacity=".6"/><polygon fill="#F04747" points="1.27 1 18 17.73 16.73 19 0 2.27"/></g></g></svg>');
  -webkit-mask-size: 90% !important;
  -webkit-mask-position: 90% !important;
  -webkit-mask-repeat: no-repeat !important;
  background-image: none !important;
}

.medium-2JR8YY[style*="/assets/d47d2c5ce2dd7d5bdaee2ebd8fde61f2.svg"] {
  content: "";
  -webkit-mask: url('data:image/svg+xml; utf8, <svg xmlns="http://www.w3.org/2000/svg" width="24" height="24" viewBox="0 0 24 24"><g fill="none" fill-rule="evenodd"><rect width="24" height="24"/><path fill="#FFFFFF" d="M10,13.5 C8.06700338,13.5 6.5,11.9329966 6.5,10 C6.5,8.06700338 8.06700338,6.5 10,6.5 C11.9329966,6.5 13.5,8.06700338 13.5,10 C13.5,11.9329966 11.9329966,13.5 10,13.5 L10,13.5 Z M17.43,10.97 C17.47,10.65 17.5,10.33 17.5,10 C17.5,9.67 17.47,9.34 17.43,9 L19.54,7.37 C19.73,7.22 19.78,6.95 19.66,6.73 L17.66,3.27 C17.54,3.05 17.27,2.96 17.05,3.05 L14.56,4.05 C14.04,3.66 13.5,3.32 12.87,3.07 L12.5,0.42 C12.46,0.18 12.25,0 12,0 L8,0 C7.75,0 7.54,0.18 7.5,0.42 L7.13,3.07 C6.5,3.32 5.96,3.66 5.44,4.05 L2.95,3.05 C2.73,2.96 2.46,3.05 2.34,3.27 L0.34,6.73 C0.21,6.95 0.27,7.22 0.46,7.37 L2.57,9 C2.53,9.34 2.5,9.67 2.5,10 C2.5,10.33 2.53,10.65 2.57,10.97 L0.46,12.63 C0.27,12.78 0.21,13.05 0.34,13.27 L2.34,16.73 C2.46,16.95 2.73,17.03 2.95,16.95 L5.44,15.94 C5.96,16.34 6.5,16.68 7.13,16.93 L7.5,19.58 C7.54,19.82 7.75,20 8,20 L12,20 C12.25,20 12.46,19.82 12.5,19.58 L12.87,16.93 C13.5,16.67 14.04,16.34 14.56,15.94 L17.05,16.95 C17.27,17.03 17.54,16.95 17.66,16.73 L19.66,13.27 C19.78,13.05 19.73,12.78 19.54,12.63 L17.43,10.97 L17.43,10.97 Z" transform="translate(2 2)"/></g></svg>');
  -webkit-mask-size: 90% !important;
  -webkit-mask-position: 90% !important;
  -webkit-mask-repeat: no-repeat !important;
  background-image: none !important;
}

.medium-2JR8YY[style*="/assets/4bc527c257233fc69b94342d77bcb9ee.svg"] {
  content: "";
  -webkit-mask: url('data:image/svg+xml; utf8, <svg xmlns="http://www.w3.org/2000/svg" width="24" height="24" viewBox="0 0 24 24"><g fill="none" fill-rule="evenodd"><rect width="24" height="24"/><path fill="#FFFFFF" d="M7,4.4408921e-16 C8.65685425,0 10,1.34314575 10,3 L10,9 C10,10.6568542 8.65685425,12 7,12 C5.34314575,12 4,10.6568542 4,9 L4,3 C4,1.34314575 5.34314575,4.4408921e-16 7,0 L7,4.4408921e-16 Z M14,9 C14,12.53 11.39,15.44 8,15.93 L8,19 L6,19 L6,15.93 C2.61,15.44 0,12.53 0,9 L2,9 C2,11.7614237 4.23857625,14 7,14 C9.76142375,14 12,11.7614237 12,9 L14,9 L14,9 Z" transform="translate(5 3)"/></g></svg>');
  -webkit-mask-size: 90% !important;
  -webkit-mask-position: 90% !important;
  -webkit-mask-repeat: no-repeat !important;
  background-image: none !important;
}

.medium-2JR8YY[style*="/assets/ea5bf2e8b48cfe21ea60588e1568aad6.svg"] {
  content: "";
  -webkit-mask: url('data:image/svg+xml; utf8, <svg xmlns="http://www.w3.org/2000/svg" width="24" height="24" viewBox="0 0 24 24"><g fill="none" fill-rule="evenodd"><path d="M0,0 L24,0 L24,24 L0,24 L0,0 Z M0,0 L24,0 L24,24 L0,24 L0,0 Z"/><rect width="24" height="24"/><path fill="#FFFFFF" fill-opacity=".6" fill-rule="nonzero" d="M21,6.5 L17,10.5 L17,7 C17,6.45 16.55,6 16,6 L9.82,6 L21,17.18 L21,6.5 Z M4.73,6 L4,6 C3.45,6 3,6.45 3,7 L3,17 C3,17.55 3.45,18 4,18 L16,18 C16.21,18 16.39,17.92 16.54,17.82 L4.73,6 Z"/><polygon fill="#F04747" fill-rule="nonzero" points="3.27 2 2 3.27 19.73 21 21 19.73"/></g></svg>');
  -webkit-mask-size: 90% !important;
  -webkit-mask-position: 90% !important;
  -webkit-mask-repeat: no-repeat !important;
  background-image: none !important;
}

.medium-2JR8YY[style*="/assets/b0aeca4d2129dcbf73f05feb6bb6e61f.svg"] {
  content: "";
  -webkit-mask: url('data:image/svg+xml; utf8, <svg xmlns="http://www.w3.org/2000/svg" width="24" height="24" viewBox="0 0 24 24"><g fill="none" fill-rule="evenodd"><polygon points="0 0 24 0 24 24 0 24"/><path fill="#FFFFFF" d="M20,17 C21.1,17 21.99,16.1 21.99,15 L22,5 C22,3.89 21.1,3 20,3 L4,3 C2.89,3 2,3.89 2,5 L2,15 C2,16.1 2.89,17 4,17 L11,17 L11,19 L9,19 L9,21 L15,21 L15,19 L13,19 L13,17 L20,17 Z M13,13.47 L13,11.28 C10.22,11.28 8.39,12.13 7,14 C7.56,11.33 9.11,8.67 13,8.13 L13,6 L17,9.73 L13,13.47 Z"/></g></svg>');
  -webkit-mask-size: 90% !important;
  -webkit-mask-position: 90% !important;
  -webkit-mask-repeat: no-repeat !important;
  background-image: none !important;
}

.medium-2JR8YY[style*="/assets/990826f372c3d1d1792e3f1df06609bb.svg"] {
  content: "";
  -webkit-mask: url('data:image/svg+xml; utf8, <svg xmlns="http://www.w3.org/2000/svg" width="24" height="24" viewBox="0 0 24 24"><g fill="none" fill-rule="evenodd" transform="matrix(-1 0 0 1 24 0)"><rect width="24" height="24"/><g transform="matrix(-1 0 0 1 21 3)"><path fill="#FFFFFF" d="M16,9 C16,10.19 15.66,11.3 15.1,12.28 L13.87,11.05 C14.14,10.43 14.3,9.74 14.3,9 L16,9 L16,9 Z M12,9.16 L6,3.18 L6,3 C6,1.34314575 7.34314575,4.4408921e-16 9,0 C10.6568542,0 12,1.34314575 12,3 L12,9 L12,9.16 L12,9.16 Z M12.54,14.81 C11.77,15.27 10.91,15.58 10,15.72 L10,19 L8,19 L8,15.72 C4.72,15.23 2,12.41 2,9 L3.7,9 C3.7,12 6.24,14.1 9,14.1 C9.81,14.1 10.6,13.91 11.31,13.58 L9.65,11.92 L9,12 C7.34314575,12 6,10.6568542 6,9 L6,8.28 L12.54,14.81 Z" opacity=".6"/><polygon fill="#F04747" points="1.27 1 18 17.73 16.73 19 0 2.27"/></g></g></svg>');
  -webkit-mask-size: 90% !important;
  -webkit-mask-position: 90% !important;
  -webkit-mask-repeat: no-repeat !important;
  background-image: none !important;
}

.medium-2JR8YY[style*="/assets/f67374a8fd6b116362596d65cc516747.svg"] {
  content: "";
  -webkit-mask: url('data:image/svg+xml; utf8, <svg xmlns="http://www.w3.org/2000/svg" width="24" height="24" viewBox="0 0 24 24"><g fill="none" fill-rule="evenodd"><polygon points="0 0 24 0 24 24 0 24"/><path fill="#FFFFFF" fill-rule="nonzero" d="M17,10.5 L17,7 C17,6.45 16.55,6 16,6 L4,6 C3.45,6 3,6.45 3,7 L3,17 C3,17.55 3.45,18 4,18 L16,18 C16.55,18 17,17.55 17,17 L17,13.5 L21,17.5 L21,6.5 L17,10.5 Z"/><rect width="24" height="24"/></g></svg>');
  -webkit-mask-size: 90% !important;
  -webkit-mask-position: 90% !important;
  -webkit-mask-repeat: no-repeat !important;
  background-image: none !important;
}

.friendsTable-133bsv .friendsRow-2yicud .friendsColumnActions-1LT3_M .friendsAction-__WNE9.friendsActionVideoCall-2_PKeP {
  content: "";
  -webkit-mask: url('data:image/svg+xml; utf8, <svg xmlns="http://www.w3.org/2000/svg" width="24" height="24" viewBox="0 0 24 24"><g fill="none" fill-rule="evenodd"><polygon points="0 0 24 0 24 24 0 24"/><path fill="#FFFFFF" fill-rule="nonzero" d="M17,10.5 L17,7 C17,6.45 16.55,6 16,6 L4,6 C3.45,6 3,6.45 3,7 L3,17 C3,17.55 3.45,18 4,18 L16,18 C16.55,18 17,17.55 17,17 L17,13.5 L21,17.5 L21,6.5 L17,10.5 Z"/><rect width="24" height="24"/></g></svg>');
  -webkit-mask-size: 90% !important;
  -webkit-mask-position: 90% !important;
  -webkit-mask-repeat: no-repeat !important;
  background-image: none !important;
}

.friendsTable-133bsv .friendsRow-2yicud .friendsColumnActions-1LT3_M .friendsAction-__WNE9.friendsActionVoiceCall-3EdPsR {
  content: "";
  -webkit-mask: url('data:image/svg+xml; utf8, <svg xmlns="http://www.w3.org/2000/svg" width="24" height="24" viewBox="0 0 24 24"><g fill="none" fill-rule="evenodd"><polygon points="0 0 24 0 24 24 0 24"/><path fill="#FFFFFF" d="M7.5,10.5 C8.94,13.33 10.6691281,15.05 13.4991281,16.5 L15.41,15.18 C15.68,14.91 16.08,14.82 16.43,14.94 C17.55,15.31 18.76,15.51 20,15.51 C20.55,15.51 21,15.96 21,16.51 L21,20 C21,20.55 20.55,21 20,21 C10.61,21 2.79399907,13.6404449 3,4 C3.01174994,3.45012573 3.45,3 4,3 L7.5,3 C8.05,3 8.5,3.45 8.5,4 C8.5,5.25 8.7,6.45 9.07,7.57 C9.18,7.92 9.1,8.31 8.82,8.59 L7.5,10.5 Z"/></g></svg>');
  -webkit-mask-size: 90% !important;
  -webkit-mask-position: 90% !important;
  -webkit-mask-repeat: no-repeat !important;
  background-image: none !important;
}

.friendsTable-133bsv .friendsRow-2yicud .friendsColumnActions-1LT3_M .friendsAction-__WNE9.friendsActionRemove-qu8nnl {
  content: "";
  -webkit-mask: url('data:image/svg+xml; utf8, <svg xmlns="http://www.w3.org/2000/svg" width="24" height="24"><g fill="none" fill-rule="evenodd"><path fill="#FFF" d="M10 12c2.21 0 4-1.79 4-4s-1.79-4-4-4-4 1.79-4 4 1.79 4 4 4zm0 2c-2.67 0-8 1.34-8 4v2h16v-2c0-2.66-5.33-4-8-4zm9.3073999-3.5066333l1.6724326-1.67243255c.124596-.12459606.39675-.3967501-.0040202-.79752037-.4007703-.40077028-.6769006-.1325925-.8014967-.00799643l-1.6724325 1.67243252-1.636821-1.636821c-.1236964-.12369646-.4297191-.42971917-.8344657-.02497265-.4047465.40474653-.0995039.7115494.0241925.83524585l1.636821 1.63682103-1.6258273 1.6258273c-.1236965.1236965-.4385989.4465514-.0378286.8473217.4007703.4007702.6792282.1223123.8029247-.0013842l1.666248-1.666248 1.6540174 1.6540173c.1241462.1241463.4199216.4183614.8246682.0136149.4047465-.4047466.1097512-.6997418-.014395-.8238881l-1.6540174-1.6540173z"/><path d="M0 0h24v24H0"/></g></svg>');
  -webkit-mask-size: 90% !important;
  -webkit-mask-position: 90% !important;
  -webkit-mask-repeat: no-repeat !important;
  background-image: none !important;
}

.item-2hkk8m[style*="0; height"] {
  background: transparent;
}

.item-2hkk8m[style*="0.7; height"] {
  background: var(--Main-Colour);
}

.item-2hkk8m[style*="1; height"] {
  background: transparent;
}

.theme-dark .button-OhfaWu {
  color: var(--Secondary-Main-Colour);
}

.theme-dark .button-OhfaWu:hover:hover {
  color: var(--Main-Colour);
}

.RANbutton {
  border: 1px solid var(--Secondary-Main-Colour);
}

.RANbutton:hover {
  border: 1px solid var(--Main-Colour);
}

.modeUnread-1zpFdA{
  background: transparent;
}

.modeUnread-1zpFdA > .content-3at_AU{
  border-right: 1px var(--Main-Colour) solid !important;
  border-left: 1px var(--Main-Colour) solid !important;
  background: linear-gradient(to left, var(--Secondary-Background-Colour), var(--Secondary-Main-Colour), var(--Background-Colour))!important;
  background-size: 200% 200%!important;
  animation: Unreadpulse var(--Unread-Message-Speed) infinite ease-in-out;
}

.theme-dark .wrapper-1ucjTd:hover .content-3at_AU{
  background: linear-gradient(to left, var(--Secondary-Background-Colour), var(--Secondary-Main-Colour))!important;
}

.theme-dark .wrapper-1ucjTd.modeSelected-1zApJ_ .content-3at_AU{
  background: linear-gradient(to left, var(--Secondary-Background-Colour), var(--Secondary-Main-Colour))!important;
  background-size: 200% 200%;
}

.wrapper-sa6paO{
  overflow: visible
}

.theme-dark .defaultIndicator-2X8Auf{
  background-color: var(--Background-Colour);
  color: var(--Main-Colour);
}

.theme-dark .rowTitle-3xCiqy,.theme-dark .rowBody-10yI-R,.theme-dark .usageInfo-2WQAwr{
  color: var(--Main-Colour);
  font-weight: bold;
}

[stroke="rgb(137, 156, 224)"]{
  stroke:var(--Main-Colour)!important;
}

.theme-dark .background-yZEZik{
  stroke:var(--Background-Colour)!important;
}

.theme-dark .subsectionHeader-11LFMg,.theme-dark .premiumPlanName-3N4gjZ{
  color: var(--Main-Colour);
}

.item-PXvHYJ[style="color: rgb(255, 255, 255); background-color: rgb(114, 137, 218);"],.item-PXvHYJ[style="color: rgb(114, 137, 218);"]{
  background: var(--Secondary-Background-Colour)!important;;
  border: 1px solid var(--Secondary-Main-Colour);
  transition: all 200ms;
  color: var(--Secondary-Main-Colour)!important;
}

.item-PXvHYJ[style="color: rgb(114, 137, 218); background-color: rgba(114, 137, 218, 0.1);"],.item-PXvHYJ[style="color: rgb(114, 137, 218);"]:hover{
  background: var(--Secondary-Background-Colour)!important;
  border: 1px solid var(--Main-Colour);
  transition: all 200ms;
  color: var(--Main-Colour)!important;
}

.theme-dark .codeRedemptionRedirect-1wVR4b,.theme-dark .emptyUsers--hiToV {
  background-color: var(--Secondary-Background-Colour);
  border-color: var(--Main-Colour);
  color: var(--Main-Colour);
}

.theme-dark .progress-1IcQ3A {
  background-color: var(--Secondary-Background-Colour);
}

.theme-dark .notches-1sAcEM{
  background-color: var(--Secondary-Main-Colour) !important;
  color: var(--Secondary-Main-Colour) !important;
  fill: var(--Secondary-Main-Colour) !important;
}

.theme-dark .notificationsSoundIcon-3PkO7b:before,.theme-dark .nowPlaying-284llR .overlayToggleIconOff-1kT42w .fill-1ugeBG, .theme-dark .nowPlaying-284llR .overlayToggleIconOn-3UNmty .fill-1ugeBG, .theme-light .nowPlaying-284llR .overlayToggleIconOff-1kT42w .fill-1ugeBG, .theme-light .nowPlaying-284llR .overlayToggleIconOn-3UNmty .fill-1ugeBG,.theme-dark .overlayToggleIconOn-3UNmty .fill-1ugeBG,.overlayToggleIconOff-1kT42w .fill-1ugeBG,.button-mM-y8i,.theme-dark .avatarUploaderIndicator-2G-aIZ,.theme-dark .quickSelectArrow-1QublR,.container-1YxwTf .btn-quote,[src="/assets/cef02719c12d8aaf38894c16dca7fbe6.svg"],[style*="/assets/959a1978f7be567071a1354a98b46ecd.svg"],.homeIcon-tEMBK1,.additionalActionsIcon-1FoUlE,.connectedAccountOpenIcon-2cNbq5,.check-2by_h9,[style*="/assets/37d23346ca73770fda04fbdcc54336e5.svg"],.theme-dark .editIcon-13gaox {
  background-color: var(--Main-Colour) !important;
  color: var(--Main-Colour) !important;
  fill: var(--Main-Colour) !important;
}

.iconContainer-bxm35Z{
  color: var(--Main-Colour) !important;
}

.theme-dark .notches-1sAcEM {
  content: "";
  -webkit-mask: url("data:image/svg+xml;charset=utf-8,%3Csvg xmlns='http://www.w3.org/2000/svg' width='8' height='20' fill='%2336393f'%3E%3Cpath fill-rule='evenodd' d='M0 0h8v20H0V0zm4 2a2 2 0 0 0-2 2v12a2 2 0 1 0 4 0V4a2 2 0 0 0-2-2z'/%3E%3C/svg%3E");
  -webkit-mask-repeat: repeat !important;
  background-image: none !important;
}

[style="width: 560px; background: linear-gradient(to right, rgb(251, 184, 72), rgb(67, 181, 129));"]{
  background: linear-gradient(to right, var(--Main-Colour), var(--Background-Colour))!important;
}

[style="background: rgb(105, 196, 154);"]{
  background: var(--Background-Colour)!important;
}

[style*="background: rgb(251, 184, 72);"]{
  background: var(--Secondary-Main-Colour)!important;
}

[d="M12 2C6.48 2 2 6.48 2 12s4.48 10 10 10 10-4.48 10-10S17.52 2 12 2zm0 18c-4.42 0-8-3.58-8-8 0-1.85.63-3.55 1.69-4.9L16.9 18.31C15.55 19.37 13.85 20 12 20zm6.31-3.1L7.1 5.69C8.45 4.63 10.15 4 12 4c4.42 0 8 3.58 8 8 0 1.85-.63 3.55-1.69 4.9z"]{
  fill:var(--Main-Colour)!important;
}

[d="M0 0h24v24H0z"]{
  fill: none!important;
}

.theme-dark .notificationsSoundIcon-3PkO7b:before{
  content: "";
  -webkit-mask: url('data:image/svg+xml; utf8, <svg xmlns="http://www.w3.org/2000/svg" width="16" height="16" viewBox="0 0 16 16"><g fill="none" fill-rule="evenodd"><rect width="16" height="16"/><path fill="#FFFFFF" d="M9.33333333,2 L9.33333333,3.37333333 C11.26,3.94666667 12.6666667,5.73333333 12.6666667,7.84666667 C12.6666667,9.96 11.26,11.74 9.33333333,12.3133333 L9.33333333,13.6933333 C12,13.0866667 14,10.7 14,7.84666667 C14,4.99333333 12,2.60666667 9.33333333,2 L9.33333333,2 Z M11,7.84666667 C11,6.66666667 10.3333333,5.65333333 9.33333333,5.16 L9.33333333,10.5133333 C10.3333333,10.04 11,9.02 11,7.84666667 L11,7.84666667 Z M2,5.84666667 L2,9.84666667 L4.66666667,9.84666667 L8,13.18 L8,2.51333333 L4.66666667,5.84666667 L2,5.84666667 L2,5.84666667 Z"/></g></svg>');
  -webkit-mask-size: 80% !important;
  -webkit-mask-position: 80% !important;
  -webkit-mask-repeat: no-repeat !important;
  background-image: none !important;
}

.theme-dark .notificationsSoundIcon-3PkO7b:before{
  content: "";
  -webkit-mask: url('data:image/svg+xml; utf8, <svg xmlns="http://www.w3.org/2000/svg" width="16" height="16" viewBox="0 0 16 16"><g fill="none" fill-rule="evenodd"><rect width="16" height="16"/><path fill="#FFFFFF" d="M9.33333333,2 L9.33333333,3.37333333 C11.26,3.94666667 12.6666667,5.73333333 12.6666667,7.84666667 C12.6666667,9.96 11.26,11.74 9.33333333,12.3133333 L9.33333333,13.6933333 C12,13.0866667 14,10.7 14,7.84666667 C14,4.99333333 12,2.60666667 9.33333333,2 L9.33333333,2 Z M11,7.84666667 C11,6.66666667 10.3333333,5.65333333 9.33333333,5.16 L9.33333333,10.5133333 C10.3333333,10.04 11,9.02 11,7.84666667 L11,7.84666667 Z M2,5.84666667 L2,9.84666667 L4.66666667,9.84666667 L8,13.18 L8,2.51333333 L4.66666667,5.84666667 L2,5.84666667 L2,5.84666667 Z"/></g></svg>');
  -webkit-mask-size: 80% !important;
  -webkit-mask-position: 80% !important;
  -webkit-mask-repeat: no-repeat !important;
  background-image: none !important;
}

.button-mM-y8i{
  content: "";
  -webkit-mask: url('data:image/svg+xml; utf8, <svg xmlns="http://www.w3.org/2000/svg" width="18" height="18" viewBox="0 0 18 18"><g fill="none" fill-rule="evenodd"><polygon fill="#F04747" fill-rule="nonzero" points="14.25 4.808 13.193 3.75 9 7.942 4.808 3.75 3.75 4.808 7.942 9 3.75 13.193 4.808 14.25 9 10.057 13.193 14.25 14.25 13.193 10.057 9"/><polygon points="0 0 18 0 18 18 0 18"/></g></svg>');
  -webkit-mask-size: 80% !important;
  -webkit-mask-position: 80% !important;
  -webkit-mask-repeat: no-repeat !important;
  background-image: none !important;
}

.theme-dark .avatarUploaderIndicator-2G-aIZ{
  content: "";
  -webkit-mask: url('data:image/svg+xml; utf8, <svg xmlns="http://www.w3.org/2000/svg" width="18" height="18" viewBox="0 0 18 18"><g fill="none" fill-rule="evenodd"><rect width="18" height="18"/><path fill="#4F545C" d="M13.5,8.25 L13.5,12.75 C13.5,13.5784271 12.8284271,14.25 12,14.25 L1.5,14.25 C0.671572875,14.25 0,13.5784271 0,12.75 L0,2.25 C0,1.42157288 0.671572875,0.75 1.5,0.75 L9,0.75 L6,0.75 L6,2.25 L1.5,2.25 L1.5,12.75 L12,12.75 L12,8.25 L13.5,8.25 Z M8.22,7.7175 L10.875,11.25 L2.625,11.25 L4.6875,8.6025 L6.1575,10.3725 L8.22,7.7175 Z M12,2.25 L14.25,2.25 L14.25,3.75 L12,3.75 L12,6 L10.5,6 L10.5,3.75 L8.25,3.75 L8.25,2.25 L10.5,2.25 L10.5,0 L12,0 L12,2.25 Z" transform="translate(2.25 1.5)"/></g></svg>');
  -webkit-mask-size: 80% !important;
  -webkit-mask-position: 80% !important;
  -webkit-mask-repeat: no-repeat !important;
  background-image: none !important;
}

.theme-dark .quickSelectArrow-1QublR{
  content: "";
  -webkit-mask: url('data:image/svg+xml; utf8, <svg xmlns="http://www.w3.org/2000/svg" width="9" height="5"><path fill="#FFFFFF" fill-rule="evenodd" d="M4.69121533 4.67377205c-.0032764.00327642-.00647163.00647164-.00957886.00957887l-.3304384.3304384L.00237527.73009987.72838543.00408973 4.49140948 3.7671138l3.7802572-3.78025722.72601014.72601013-4.13370567 4.1337057-.17277807-.17277806z"/></svg>');
  -webkit-mask-size: 80% !important;
  -webkit-mask-position: 80% !important;
  -webkit-mask-repeat: no-repeat !important;
  background-image: none !important;
}

.container-1YxwTf .btn-quote {
  content: "";
  -webkit-mask: url('data:image/svg+xml; utf8, <svg xmlns="http://www.w3.org/2000/svg" viewBox="0 0 33 25"><path fill="#99AAB5" d="M18 6.5c0-2 .7-3.5 2-4.7C21.3.6 23 0 25 0c2.5 0 4.4.8 6 2.4C32.2 4 33 6 33 8.8s-.4 5-1.3 7c-.8 1.8-1.8 3.4-3 4.7-1.2 1.2-2.5 2.2-3.8 3L21.4 25l-3.3-5.5c1.4-.6 2.5-1.4 3.5-2.6 1-1.4 1.5-2.7 1.6-4-1.3 0-2.6-.6-3.7-1.8-1-1.2-1.7-2.8-1.7-4.8zM.4 6.5c0-2 .6-3.5 2-4.7C3.6.6 5.4 0 7.4 0c2.3 0 4.3.8 5.7 2.4C14.7 4 15.5 6 15.5 8.8s-.5 5-1.3 7c-.7 1.8-1.7 3.4-3 4.7-1 1.2-2.3 2.2-3.6 3C6 24 5 24.5 4 25L.6 19.5C2 19 3.2 18 4 17c1-1.3 1.6-2.6 1.8-4-1.4 0-2.6-.5-3.8-1.7C1 10 .4 8.5.4 6.5z"></path></svg>');
  -webkit-mask-size: 80% !important;
  -webkit-mask-position: 80% !important;
  -webkit-mask-repeat: no-repeat !important;
  background-image: none !important;
}

[src="/assets/cef02719c12d8aaf38894c16dca7fbe6.svg"] {
  content: "";
  -webkit-mask: url('data:image/svg+xml; utf8, <svg xmlns="http://www.w3.org/2000/svg" width="16" height="16"><g fill="none" fill-rule="evenodd"><path d="M0 0h16v16H0z"/><path fill="#72767d" d="M8 13.5c-3.032 0-5.5-2.468-5.5-5.5S4.968 2.5 8 2.5s5.5 2.468 5.5 5.5-2.468 5.5-5.5 5.5zM1 8c0 1.857.737 3.637 2.05 4.95C4.363 14.263 6.143 15 8 15c1.857 0 3.637-.737 4.95-2.05C14.263 11.637 15 9.857 15 8c0-1.857-.737-3.637-2.05-4.95C11.637 1.737 9.857 1 8 1 4.134 1 1 4.134 1 8zm8-3H7v2H5v2h2v2h2V9h2V7H9V5z"/></g></svg>');
  -webkit-mask-size: 100% !important;
  -webkit-mask-position: 100% !important;
  -webkit-mask-repeat: no-repeat !important;
  background-image: none !important;
}

[style*="/assets/959a1978f7be567071a1354a98b46ecd.svg"] {
  content: "";
  -webkit-mask: url('data:image/svg+xml; utf8, <svg xmlns="http://www.w3.org/2000/svg" width="18" height="18" viewBox="0 0 18 18"><g fill="none" fill-rule="evenodd"><path fill="#FFFFFF" d="M8,6 L2,6 L2,5 C2,3.346 3.346,2 5,2 C6.654,2 8,3.346 8,5 L8,6 Z M4,12 L6,12 L6,8 L4,8 L4,12 Z M5,0 C2.238,0 0,2.238 0,5 L0,12 C0,13.104 0.896,14 2,14 L8,14 C9.104,14 10,13.104 10,12 L10,5 C10,2.238 7.762,0 5,0 Z" transform="translate(4 2)"/><rect width="18" height="18"/></g></svg>');
  -webkit-mask-size: 80% !important;
  -webkit-mask-position: 80% !important;
  -webkit-mask-repeat: no-repeat !important;
  background-image: none !important;
}

.theme-dark .emojiAliasInput-1y-NBz .emojiInput-1aLNse{
  background: var(--Secondary-Background-Colour);
}

.theme-dark .emojiAliasPlaceholder-3H_iZA,.theme-dark .bannedUser-1IalTM .username-1b3MVI{
  color: var(--Main-Colour);
}

.theme-dark .card-FDVird:before {
  background-color: var(--Secondary-Background-Colour);
  border-color: var(--Main-Colour);
}

.theme-dark .inviteSettingsInviteRow-3p2O-N {
  color: var(--Main-Colour);
}

.theme-dark .bannedUser-1IalTM .username-1b3MVI .discrim-oGb-FO, .theme-dark .bannedUserModal-3RJCOV .reason-YbfGC6, .theme-dark .bannedUserModal-3RJCOV .userDiscrim-1D2NlF{
  color: var(--Secondary-Main-Colour);
}

.wrapper-1Rf91z .scroller-2TZvBN > div:not(.listItem-2P_4kh) {
  width: calc(var(--Guild-Columns) * 60px + 2px)!important;
}

.wrapper-1Rf91z .scroller-2TZvBN > div > .listItem-2P_4kh {
  margin: auto;
}

.homeIcon-tEMBK1{
  content: "";
  -webkit-mask: url('data:image/svg+xml; utf8, <svg xmlns="http://www.w3.org/2000/svg" width="32" height="32" viewBox="0 0 32 32"><title>bubble2</title><path d="M16 6c-1.717 0-3.375 0.271-4.928 0.804-1.46 0.502-2.76 1.211-3.863 2.108-2.069 1.681-3.209 3.843-3.209 6.088 0 1.259 0.35 2.481 1.039 3.63 0.711 1.185 1.781 2.268 3.093 3.133 0.949 0.625 1.587 1.623 1.755 2.747 0.056 0.375 0.091 0.753 0.105 1.129 0.233-0.194 0.461-0.401 0.684-0.624 0.755-0.755 1.774-1.172 2.828-1.172 0.168 0 0.336 0.011 0.505 0.032 0.655 0.083 1.325 0.126 1.99 0.126 1.717 0 3.375-0.271 4.928-0.804 1.46-0.502 2.76-1.211 3.863-2.108 2.069-1.681 3.209-3.843 3.209-6.088s-1.14-4.407-3.209-6.088c-1.104-0.897-2.404-1.606-3.863-2.108-1.553-0.534-3.211-0.804-4.928-0.804zM16 2v0c8.837 0 16 5.82 16 13s-7.163 13-16 13c-0.849 0-1.682-0.054-2.495-0.158-3.437 3.437-7.539 4.053-11.505 4.144v-0.841c2.142-1.049 4-2.961 4-5.145 0-0.305-0.024-0.604-0.068-0.897-3.619-2.383-5.932-6.024-5.932-10.103 0-7.18 7.163-13 16-13z"></path></svg>');
  -webkit-mask-size: 80% !important;
  -webkit-mask-position: 80% !important;
  -webkit-mask-repeat: no-repeat!important;
  background-image: none!important;
}

.homeIcon-tEMBK1{
  content: "";
  -webkit-mask: url('data:image/svg+xml; utf8, <svg xmlns="http://www.w3.org/2000/svg" width="32" height="32" viewBox="0 0 32 32"><title>bubble2</title><path d="M16 6c-1.717 0-3.375 0.271-4.928 0.804-1.46 0.502-2.76 1.211-3.863 2.108-2.069 1.681-3.209 3.843-3.209 6.088 0 1.259 0.35 2.481 1.039 3.63 0.711 1.185 1.781 2.268 3.093 3.133 0.949 0.625 1.587 1.623 1.755 2.747 0.056 0.375 0.091 0.753 0.105 1.129 0.233-0.194 0.461-0.401 0.684-0.624 0.755-0.755 1.774-1.172 2.828-1.172 0.168 0 0.336 0.011 0.505 0.032 0.655 0.083 1.325 0.126 1.99 0.126 1.717 0 3.375-0.271 4.928-0.804 1.46-0.502 2.76-1.211 3.863-2.108 2.069-1.681 3.209-3.843 3.209-6.088s-1.14-4.407-3.209-6.088c-1.104-0.897-2.404-1.606-3.863-2.108-1.553-0.534-3.211-0.804-4.928-0.804zM16 2v0c8.837 0 16 5.82 16 13s-7.163 13-16 13c-0.849 0-1.682-0.054-2.495-0.158-3.437 3.437-7.539 4.053-11.505 4.144v-0.841c2.142-1.049 4-2.961 4-5.145 0-0.305-0.024-0.604-0.068-0.897-3.619-2.383-5.932-6.024-5.932-10.103 0-7.18 7.163-13 16-13z"></path></svg>');
  -webkit-mask-size: 80% !important;
  -webkit-mask-position: 80% !important;
  -webkit-mask-repeat: no-repeat!important;
  background-image: none!important;
}

[fill="black"]{
  fill: var(--Background-Colour)!important;
}

.listItem-2P_4kh:hover > .wrapper-sa6paO > .item-2hkk8m{
  background: transparent!important;
  opacity: 0!important;
  transform: translate3d(0px)!important;
}

.pill-2uzAFe{
  left: 0;
  position: relative;
  top: 0;
}

.guildSeparator-3s64Iy {
  background: url('data:image/png;base64,iVBORw0KGgoAAAANSUhEUgAAAEAAAAAOCAYAAACfOxrCAAAABGdBTUEAALGPC/xhBQAAAAlwSFlzAAAOwwAADsMBx2+oZAAAABh0RVh0U29mdHdhcmUAcGFpbnQubmV0IDQuMS4zjST9ZwAABHNJREFUSEvNVl2IVkUYHsOItL+LtP8yyqgosDAiomSpMCoDr7SwhDDtIiIqspvwpqCLoosiWIouttz2nJmzrlstrGuuSmmFIHVjXZSp++05M+dz2+wHzNyv531nzpxzvm9iP+2iXniYM+88887MMz/nFSLW2z1kdo+omtTbfJtKe5xvY61PCMqsElF2h5BmjOvSSNGXzuf+7RalD3b0Jyg9gvm8LFR+vWOWNti8AfN4D+N8BRzH9y4RZ6+JrdlFjmGt1ToD/VeAsxWYwDwylKNCZesdA6ZMy0PqHc5rTem/fFucrmafNH21PkHkL0KwFYg343yZiKfO5/7tJs2T9b5tkGYKQqxxbMwpfwxx/wxylQY3X8q8fa0zWfggj6B3Q+hz6gIQZPoEByD7PwhAkOagiCYXiCRdiJhHgpwCdBp6sfikubIyfhhx9mxAAP09js4cntxsAki9F0E2YMHra4j1ktMUYL9I8g3wPYO+dLyLcU7g2N4rBs0yzMnGlKaJ7zvFcGMe/A/B94fl62mhpq5Cn4FK/zHRf+hSMTozH/W3vV+Z7Z0CEGIDZWCzCpD1sS9kpyOA1B86r+D7rMxh36ayRyFuT8nF/RfCbtTmxoXwpa5tWnyULgI3tjzMQZryVCfZSsejGJ+VAkjzm/9W5pAYmTmrixMwJqLmfXjwKtDXMq9bAWKzrhKvFKAXO6vMd76NBTB3+5hS/4BysRg5toAfb2V+tTwIwCfAbHZ1Wts7zKMrFOtXK/6KAMqcQNBPy8bsKZSzCQB19ck2DOD5ndO1AFF6NRZnFzqbAFHzMnAmS5/+BfUpfLvjz5jGWFfCvxY46Xg0LzyQDFwnx20TgCawtlLfj/ouX+/+EUxOSQCyoeaNiPs5ducD5wkLQG+T1C+gXuy2hd2IYiwrAL0Nygzx4qvc6qnuECDJH0agg7aRg2rfFhQAO6DwaFaRmLdOWQCyCEc01o+7muAF0IPsx4IAZPxvx1VI9LAd03wD3isojeNaAciiw2eD8zTav2au1Dvxm3zD8QICKL0c5QN1n0NYgH4xigSHkpwC9HaQVQWQRvNDRb+nKoq/TbuRPzG3oj8ELsZyApAN5efCt5jHpkXG+mLMpVMA2ogtPy/idppb7z7KDR7xMYMCbBqfi/LLuh8IvgFd/gU4caGY2Rc1DJrrbMaYv1lH9j76/OTH4WzP3MULirKb8b0D7ZPgrhHxxBJ8vwtOcd+PQrxLxHhrLsrVaGsAO5FHLAN/Kb4P+LgSGaKv2M7L3eR7QCyOr8W/EeCfkDSwy90kQvpb7OQFvItS7wlyCkijePyB9CZ8/x7kEGhuUboqLABZrD+utf0XAlB/Ogl0HQpL8tswbiPIVXpcJEcuZ94mvBUy3Yi2zrSZ/gRSv848JAyfeFQH6p+4BUembKOHhyzOn6/4nmNfyGR6Owap9A9gUF+DvOH+YFuM9yVBjrDl6BUuYmmUa8QZZXQ/YtHHUW5D+ZIYaZ7nGNZIBMpT6FQofQzzwbUxw5w5sgnxNyB3m34raxnsAAAAAElFTkSuQmCC')50% 50%/Contain no-repeat;
  border: 1px solid var(--Secondary-Main-Colour);
  height: 25.5px;
  top: 0px;
  width: 55px;
}

.additionalActionsIcon-1FoUlE {
  content: "";
  -webkit-mask: url('data:image/svg+xml; utf8, <svg xmlns="http://www.w3.org/2000/svg" xmlns:xlink="http://www.w3.org/1999/xlink" width="4" height="16" viewBox="0 0 4 16"><defs><path id="ic_overflow_vertical_light_24px-a" d="M2,4 C3.1,4 4,3.1 4,2 C4,0.9 3.1,0 2,0 C0.9,0 0,0.9 0,2 C0,3.1 0.9,4 2,4 L2,4 Z M2,6 C0.9,6 0,6.9 0,8 C0,9.1 0.9,10 2,10 C3.1,10 4,9.1 4,8 C4,6.9 3.1,6 2,6 L2,6 Z M2,12 C0.9,12 0,12.9 0,14 C0,15.1 0.9,16 2,16 C3.1,16 4,15.1 4,14 C4,12.9 3.1,12 2,12 L2,12 Z"/></defs><g fill="none" fill-rule="evenodd" opacity=".6" transform="translate(-10 -4)"><polygon points="0 0 24 0 24 24 0 24"/><path fill="#000" fill-rule="nonzero" d="M2,4 C3.1,4 4,3.1 4,2 C4,0.9 3.1,0 2,0 C0.9,0 0,0.9 0,2 C0,3.1 0.9,4 2,4 L2,4 Z M2,6 C0.9,6 0,6.9 0,8 C0,9.1 0.9,10 2,10 C3.1,10 4,9.1 4,8 C4,6.9 3.1,6 2,6 L2,6 Z M2,12 C0.9,12 0,12.9 0,14 C0,15.1 0.9,16 2,16 C3.1,16 4,15.1 4,14 C4,12.9 3.1,12 2,12 L2,12 Z" transform="translate(10 4)"/><g transform="translate(10 4)"><mask id="ic_overflow_vertical_light_24px-b" fill="#fff"><use xlink:href="#ic_overflow_vertical_light_24px-a"/></mask><g fill="#F6F6F7" fill-rule="nonzero" mask="url(#ic_overflow_vertical_light_24px-b)"><rect width="24" height="24" transform="translate(-10 -4)"/></g></g></g></svg>');
  -webkit-mask-size: 20% !important;
  -webkit-mask-position: 80% !important;
  -webkit-mask-repeat: no-repeat!important;
  background-image: none!important;
}

.connectedAccountOpenIcon-2cNbq5 {
  content: "";
  -webkit-mask: url('data:image/svg+xml; utf8, <svg xmlns="http://www.w3.org/2000/svg" width="18" height="18"><g fill="none" fill-rule="evenodd" opacity=".60000002"><path d="M0 0h18v18H0z"/><path fill="#99AAB5" d="M10.5 2.25v1.5h2.6925L5.82 11.1225 6.8775 12.18 14.25 4.8075V7.5h1.5V2.25H10.5zm3.75 12H3.75V3.75H9v-1.5H3.75c-.8325 0-1.5.675-1.5 1.5v10.5c0 .8284271.67157287 1.5 1.5 1.5h10.5c.8284271 0 1.5-.6715729 1.5-1.5V9h-1.5v5.25z"/></g></svg>');
  -webkit-mask-size: 80% !important;
  -webkit-mask-position: 80% !important;
  -webkit-mask-repeat: no-repeat!important;
  background-image: none!important;
}

[style*="border-color: rgb(255, 255, 255)"]{
  border-color: var(--Main-Colour)!important;
}

.theme-dark .consent-1AQ-th{
  background: transparent;
}

.consentBody-3xZVZA{
  color: var(--Main-Colour);
}

.listItem-2P_4kh,.svg-1X37T1, .wrapper-25eVIn{
  width: 45px!important;
  height: 45px!important;
}

.item-2hkk8m[style*="0.7; height"] {
  background: transparent;
  border:2px solid var(--Unread-Message-1);
  border-radius: 50%;
  width: 45px!important;
  height: 45px!important;
  left: 2px;
  top: 0;
  z-index: 0;
}

.item-2hkk8m:not([style*="0.7; height"]) {
  background: transparent;
  border:2px solid transparent;
  border-radius: 50%;
  width: 45px!important;
  height: 45px!important;
  left: 2px;
  top: 0;
  z-index: 0;
}

.wrapper-sa6paO, .listItem-2P_4kh, s.svg-1X37T1, .wrapper-25eVIn, .svg-1X37T1, .wrapper-25eVIn{
  width: 45px!important;
  height: 45px!important;
}

.listItem-2P_4kh {
  margin: 4px;
}

.theme-dark .regionSelectName-c5qL8O {
  color: var(--Main-Colour);
}

.check-2by_h9{
  content: "";
  -webkit-mask: url('data:image/svg+xml; utf8, <svg xmlns="http://www.w3.org/2000/svg" width="16" height="12"><path fill="none" stroke="#7289DA" stroke-width="3" d="M1.99609375 5.7835338l3.70287382 3.7028738L14.1853752 1"/></svg>');
  -webkit-mask-size: 80% !important;
  -webkit-mask-position: 80% !important;
  -webkit-mask-repeat: no-repeat!important;
  background-image: none!important;
}

[style*="/assets/37d23346ca73770fda04fbdcc54336e5.svg"]{
  content: "";
  -webkit-mask: url('data:image/svg+xml; utf8, <svg xmlns="http://www.w3.org/2000/svg" width="24" height="24" viewBox="0 0 24 24"><g fill="none" fill-rule="evenodd"><rect width="24" height="24"/><path fill="#FFFFFF" d="M7,18 L7,16 L3.41,16 L7.91,11.5 L6.5,10.09 L2,14.59 L2,11 L0,11 L0,18 L7,18 L7,18 Z M11.5,7.91 L16,3.41 L16,7 L18,7 L18,0 L11,0 L11,2 L14.59,2 L10.09,6.5 L11.5,7.91 Z" transform="translate(3 3)"/></g></svg>');
  -webkit-mask-size: 80% !important;
  -webkit-mask-position: 80% !important;
  -webkit-mask-repeat: no-repeat!important;
  background-image: none!important;
}

.theme-dark .quickSelectPopout-X1hvgV{
  background: var(--Background-Colour)!important;
  border: 1px solid var(--Secondary-Main-Colour);
}

.theme-dark .quickSelectPopout-X1hvgV:hover{
  background: var(--Background-Colour)!important;
  border: 1px solid var(--Main-Colour);
}

.quickSelectPopoutOption-opKBx9 .selected{
  border-right: 4px solid var(--Main-Colour);
}

.quickSelectPopoutOption-opKBx9 .selected, .quickSelectPopoutOption-opKBx9:hover{
  filter: brightness(160%);
}

.regionSelectFlag-1htPow{
  display:none;
}

.upperBadge-2XnnGB.count {
  left: 11px;
  top: 15px;
  right: unset;
}

[id*="folder_"] mask{
  display: none;
}

.svg-1X37T1 > mask{
  display: none;
}

.icon-27yU2q:not(:hover){
  border-radius: 50%;
}

.wrapper-sa6paO, .listItem-2P_4kh, s.svg-1X37T1, .wrapper-25eVIn, .svg-1X37T1, .wrapper-25eVIn{
  width: 45px!important;
  height: 45px!important;
}

.wrapper-1Rf91z .scroller-2TZvBN > .listItem-2P_4kh:not([folder*="folder_"]):first-of-type {
  width: calc(var(--Guild-Columns) * 60px + 2px) !important;
  align-content: center;
}

.circleButtonMask-2VNJsN.wrapper-25eVIn > svg > foreignObject > div{
  border-radius: 50%;
}

.item-2hkk8m {
  background: transparent;
  border:2px solid var(--Unread-Message-1);
  border-radius: 50%;
  width: 46px!important;
  height: 46px!important;
  left: 2px;
  top: 0px;
  z-index: 0;
  animation: UnreadGuildpulse var(--Unread-Message-Speed) ease-in-out infinite alternate;
}

#app-mount > div.app-19_DXt.platform-win > div > div.layers-3iHuyZ.vertical-V37hAW.flex-1O1GKY.directionColumn-35P_nr.spacer-1fA9zc > div > div > div:nth-child(1) > div.scrollerWrap-2lJEkd.firefoxFixScrollFlex-cnI2ix.scrollerWrap-1IAIlv.scrollerThemed-2oenus.themeGhostHairline-DBD-2d > div > div:nth-child(1) > div.pill-2uzAFe.wrapper-sa6paO {
  display:none;
}

.theme-dark .dragPlaceholder-D9-haY, .theme-light .dragPlaceholder-D9-haY {
  background: transparent;
  border:1px solid var(--Unread-Message-1);
  border-radius: 50%;
  width: 45px!important;
  height: 45px!important;
  left: 0px;
  top: 0px;
  z-index: 0;
  animation: UnreadGuildpulse var(--Unread-Message-Speed) ease-in-out infinite alternate;
}

.wrapper-1Rf91z.foldercontent .folderseparatorouter{
  width: calc(var(--Guild-Columns) * 60px + 2px) !important;
}

.item-2hkk8m:not(:hover)[style*="1; height"] {
  border-radius: 0%;
  width: 0!important;
  height: 5px!important;
  border-color: var(--Unread-Message-1);
  background: var(--Unread-Message-1);
  border: var(--Thiccness) solid var(--Unread-Message-1);
  left:5px;
  top: 0px;
  z-index: 2;
}

.theme-dark .multipleIconWrapper-1PjkRO, .theme-dark .section-2VKIPC,.theme-dark .inset-GQDQYw {
  background-color: transparent;
}

.theme-dark .popout-3G62UL {
  -webkit-box-shadow: 0 8px 16px var(--Background-Colour);
  background-color: var(--Background-Colour);
  box-shadow: 0 8px 16px var(--Background-Colour);
}

.theme-dark .memberListItem-2ZX2pl:hover,.theme-dark .enabled-5QKLzu:hover,.theme-dark .popoutContainer-3WC9HR:hover,.interactive-1BeKSi:hover {
  background-color: var(--Secondary-Background-Colour);
  border: 1px solid var(--Main-Colour);
}

.theme-dark .memberListItem-2ZX2pl,.theme-dark .enabled-5QKLzu,.theme-dark .popoutContainer-3WC9HR,.interactive-1BeKSi {
  background-color: var(--Secondary-Background-Colour);
  border: 1px solid var(--Secondary-Main-Colour);
}

.theme-dark .recentlyPlayedContainer-2F3MqS{
  background-color: transparent;
}

.theme-dark .layout-1cQCv2{
  background: transparent;
}

.theme-dark .itemBackground-2vEldQ {
  background-color:var(--Secondary-Background-Colour);
}

.theme-dark .itemBackground-2vEldQ:before {
  background: radial-gradient(ellipse at top, rgba(0, 0, 0, 0), var(--Secondary-Main-Colour)), linear-gradient(90deg, var(--Secondary-Background-Colour) 0, rgba(0, 0, 0, 0) 40%, rgba(0, 0, 0, 0) 60%, var(--Secondary-Background-Colour)), linear-gradient(0deg, var(--Secondary-Main-Colour) 0, rgba(0, 0, 0, 0) 25%);
}

.theme-dark .overlappingBorder-3aFng4, .theme-light .overlappingBorder-3aFng4{
  border-color: var(--Main-Colour);
}

.theme-dark .header-2Qd56c{
  color: var(--Main-Colour);
}

.theme-dark .description-2oYgWO,.theme-dark .tagline-EIH5-W, .theme-dark .title-2XwaXv,.theme-dark .perkTag-2O4dx4, .theme-light .perkTag-2O4dx4 {
  color: var(--Main-Colour);
}

.perkTag-2O4dx4 {
  background: linear-gradient(90deg, var(--Secondary-Background-Colour),var(--Secondary-Main-Colour));
  border-radius: 8px;
  font-size: 12px;
  line-height: 16px;
  padding: 0 6px;
  text-transform: uppercase;
}

.theme-dark .tile-QA_yMc {
  background-color: var(--Secondary-Background-Colour);
  border: 1px solid var(--Secondary-Main-Colour);
}

.theme-dark .tile-QA_yMc:hover {
  background-color: var(--Secondary-Background-Colour);
  border: 1px solid var(--Main-Colour);
}

.theme-dark .gradientOverlayLeft-3w159C {
  background-image: linear-gradient(90deg,var(--Secondary-Main-Colour),rgba(0,0,0,0));
}

.theme-dark .gradientOverlayRight-3vMuS8 {
  background-image: linear-gradient(90deg,rgba(0,0,0,0),var(--Secondary-Main-Colour));
}

.theme-dark .categoryHeader-1D7Tqy, .theme-dark .premiumApplicationsHeader-Zmkm5e {
  border-color: var(--Secondary-Main-Colour);
  color: var(--Main-Colour);
}

.theme-dark .details-1DqjXP {
  color: var(--Main-Colour);
}

.theme-dark .tileMedia-1q3guD,.theme-dark .tileMedia-1q3guD:hover {
  background-color: var(--Secondary-Background-Colour);
  box-shadow: 0 0 0 var(--Secondary-Background-Colour);
}

.theme-dark .genreTag-3QLRUJ {
  background: var(--Secondary-Background-Colour);
  color: var(--Secondary-Main-Colour);
}

.theme-dark .friendsTable-133bsv .friendTableAddWrapper-nHHZtK .friendTableAddHeader-m9bzFr {
  background: linear-gradient(-180deg,var(--Secondary-Background-Colour),var(--Secondary-Background-Colour));
  border-bottom: 1px solid var(--Secondary-Background-Colour);
}

.theme-dark .friendsTable-133bsv .friendTableAddDescription-19D3dl,.theme-dark .friendsTable-133bsv .friendTableAddWrapper-nHHZtK .friendTableAddHeader-m9bzFr .connectAccounts-1orH6X h3 {
  color: var(--Secondary-Main-Colour);
}

.theme-dark .friendsTable-133bsv .friendTableAddWrapper-nHHZtK h2,.theme-dark .header-3YT7-d {
  color: var(--Main-Colour);
}

.theme-dark .wrapper-1cBijl {
  background-color: var(--Secondary-Background-Colour);
  border-color: var(--Secondary-Main-Colour);
}

.tabBar-1E2ExX .primarySelected-3uHKZn {
  background-color: var(--Secondary-Background-Colour)!important;
  color: var(--Main-Colour)!important;
}

.theme-dark .themed-OHr7kt.item-PXvHYJ{
  background-color: var(--Secondary-Background-Colour)!important;
  color: var(--Secondary-Main-Colour)!important;
  border: 1px solid var(--Secondary-Main-Colour);
}

.reactionBtn-2na4rd,.button-3Jq0g9,.theme-dark .closeButton-17RIVZ{
  background-color: var(--Main-Colour) !important;
  color: var(--Main-Colour) !important;
  fill: var(--Main-Colour) !important;
}

.close-3hZ5Ni{
  background-color: var(--Background-Colour) !important;
  color: var(--Background-Colour) !important;
  fill: var(--Background-Colour) !important;
}

.reactionBtn-2na4rd {
  content: "";
  -webkit-mask: url('data:image/svg+xml; utf8, <svg width="16px" height="16px" viewBox="0 0 16 16" version="1.1" xmlns="http://www.w3.org/2000/svg" xmlns:xlink="http://www.w3.org/1999/xlink"><!-- Generator: Sketch 40.3 (33839) - http://www.bohemiancoding.com/sketch --><title>ic_reactions_grey_16px</title><desc>Created with Sketch.</desc><defs></defs><g id="Page-1" stroke="none" stroke-width="1" fill="none" fill-rule="evenodd"><g id="ic_reactions_grey_16px"><g id="Group-2"><g id="0:0:0:0"><rect id="Rectangle-5" x="0" y="0" width="16" height="16"></rect><g id="emoticon" transform="translate(1.333333, 1.333333)"></g><path d="M14.6332705,7.33333333 C14.6554304,7.55389388 14.6666667,7.77636769 14.6666667,8 C14.6666667,11.6818983 11.6818983,14.6666667 8,14.6666667 C6.23189007,14.6666667 4.53619732,13.9642877 3.28595479,12.7140452 C2.03571227,11.4638027 1.33333333,9.76810993 1.33333333,8 C1.33333333,4.33333333 4.31333333,1.33333333 8,1.33333333 L8,1.33333333 C8.22363231,1.33333333 8.44610612,1.3445696 8.66666667,1.36672949 L8.66666667,2.70847693 C8.44668912,2.68076722 8.22407146,2.66666667 8,2.66666667 C5.05448133,2.66666667 2.66666667,5.05448133 2.66666667,8 C2.66666667,10.9455187 5.05448133,13.3333333 8,13.3333333 C10.9455187,13.3333333 13.3333333,10.9455187 13.3333333,8 C13.3333333,7.77592854 13.3192328,7.55331088 13.2915231,7.33333333 L14.6332705,7.33333333 Z M8,11.6666667 C9.55333333,11.6666667 10.8666667,10.6933333 11.4066667,9.33333333 L4.59333333,9.33333333 C5.12666667,10.6933333 6.44666667,11.6666667 8,11.6666667 Z M10.3333333,7.33333333 C10.8856181,7.33333333 11.3333333,6.88561808 11.3333333,6.33333333 C11.3333333,5.78104858 10.8856181,5.33333333 10.3333333,5.33333333 C9.78104858,5.33333333 9.33333333,5.78104858 9.33333333,6.33333333 C9.33333333,6.88561808 9.78104858,7.33333333 10.3333333,7.33333333 L10.3333333,7.33333333 Z M5.66666667,7.33333333 C6.21895142,7.33333333 6.66666667,6.88561808 6.66666667,6.33333333 C6.66666667,5.78104858 6.21895142,5.33333333 5.66666667,5.33333333 C5.11438192,5.33333333 4.66666667,5.78104858 4.66666667,6.33333333 C4.66666667,6.88561808 5.11438192,7.33333333 5.66666667,7.33333333 Z" id="Combined-Shape" fill="#99AAB5"></path></g><g id="Group-15" transform="translate(10.666667, 0.000000)" fill="#99AAB5"><polygon id="Path" points="3.33333333 2 3.33333333 0 2 0 2 2 0 2 0 3.33333333 2 3.33333333 2 5.33333333 3.33333333 5.33333333 3.33333333 3.33333333 5.33333333 3.33333333 5.33333333 2"></polygon></g></g></g></g></svg>');
  -webkit-mask-size: 90% !important;
  -webkit-mask-position: 90% !important;
  -webkit-mask-repeat: no-repeat!important;
  background-image: none!important;
}

.button-3Jq0g9 {
  content: "";
  -webkit-mask: url('data:image/svg+xml; utf8, <svg width="16px" height="16px" viewBox="0 0 16 16" version="1.1" xmlns="http://www.w3.org/2000/svg" xmlns:xlink="http://www.w3.org/1999/xlink"><!-- Generator: Sketch 40.3 (33839) - http://www.bohemiancoding.com/sketch --><title>ic_overflow_vertical_grey_16px</title><desc>Created with Sketch.</desc><defs></defs><g id="Page-1" stroke="none" stroke-width="1" fill="none" fill-rule="evenodd"><g id="ic_overflow_vertical_grey_16px"><g id="Group-22" transform="translate(8.000000, 8.000000) rotate(90.000000) translate(-8.000000, -8.000000) "><rect id="Rectangle-8" x="0" y="0" width="16" height="16"></rect><g id="dots-horizontal-(1)" transform="translate(2.666667, 6.666667)" fill="#99AAB5"><path d="M8,1.33333333 C8,0.596953667 8.59695367,0 9.33333333,0 C10.069713,0 10.6666667,0.596953667 10.6666667,1.33333333 C10.6666667,2.069713 10.069713,2.66666667 9.33333333,2.66666667 C8.59695367,2.66666667 8,2.069713 8,1.33333333 L8,1.33333333 Z M4,1.33333333 C4,0.596953667 4.59695367,0 5.33333333,0 C6.069713,0 6.66666667,0.596953667 6.66666667,1.33333333 C6.66666667,2.069713 6.069713,2.66666667 5.33333333,2.66666667 C4.59695367,2.66666667 4,2.069713 4,1.33333333 L4,1.33333333 Z M0,1.33333333 C0,0.596953667 0.596953667,0 1.33333333,0 C2.069713,0 2.66666667,0.596953667 2.66666667,1.33333333 C2.66666667,2.069713 2.069713,2.66666667 1.33333333,2.66666667 C0.596953667,2.66666667 0,2.069713 0,1.33333333 L0,1.33333333 Z" id="Shape"></path></g></g></g></g></svg>');
  -webkit-mask-size: 90% !important;
  -webkit-mask-position: 90% !important;
  -webkit-mask-repeat: no-repeat!important;
  background-image: none!important;
}

.close-3hZ5Ni {
  content: "";
  -webkit-mask: url('data:image/svg+xml; utf8, <svg width="24px" height="24px" viewBox="0 0 24 24" xmlns="http://www.w3.org/2000/svg"><g id="Symbols" stroke="none" stroke-width="1" fill="none" fill-rule="evenodd"><polygon fill="#FFFFFF" transform="translate(12.000000, 12.000000) rotate(45.000000) translate(-12.000000, -12.000000) " points="19 13 13 13 13 19 11 19 11 13 5 13 5 11 11 11 11 5 13 5 13 11 19 11"></polygon><polygon points="0 0 24 0 24 24 0 24"></polygon></g></svg>');
  -webkit-mask-size: 90% !important;
  -webkit-mask-position: 90% !important;
  -webkit-mask-repeat: no-repeat!important;
  background-image: none!important;
}

.guildsError-b7zR5H:hover {
  background-color: var(--Secondary-Background-Colour);
  border-color: var(--Main-Colour);
  color: var(--Main-Colour);
}

.guildsError-b7zR5H {
  background: var(--Secondary-Background-Colour);
  border-color: var(--Secondary-Main-Colour);
  color: var(--Secondary-Main-Colour);
}

.theme-dark .tooltipRed-8-9NeP, .theme-light .tooltipRed-8-9NeP {
  background: linear-gradient(to top, var(--Secondary-Main-Colour), var(--Background-Colour), var(--Background-Colour), var(--Background-Colour), var(--Secondary-Main-Colour)) !important;
  color: var(--Main-Colour);
}

.theme-dark .tooltipRed-8-9NeP .tooltipPointer-3ZfirK, .theme-light .tooltipRed-8-9NeP .tooltipPointer-3ZfirK {
  border-top-color: var(--Background-Colour);
}

.tooltip-2QfLtc{
  max-width: 100%;
}

.selected-3s45Ha:after {
  content: " (?)";
  color: var(--Main-Colour);
  transition: all 200ms;
}

.theme-dark .keybindShortcut-1BD6Z1 span .bindArrow-2X3Aom g {
  fill: var(--Main-Colour);
}

.container-3qKHyN {
  height: auto;
}

.keyboardShortcutList-13cQ-8 .keybindGroup--6Qp-w.groupEnd-1cdweh {
  margin-bottom: 0;
}

.iconBadge-qZ4Ksk{
  background-color: var(--Main-Colour);
}

.theme-dark .closeButton-17RIVZ {
  content: "";
  -webkit-mask: url('data:image/svg+xml; utf8, <svg xmlns="http://www.w3.org/2000/svg" width="16" height="16"><g fill="none" fill-rule="evenodd"><path d="M0 0h16v16H0"/><path fill="#FFF" d="M12.6666667 4.27333333l-.94-.94L8 7.06 4.27333333 3.33333333l-.94.94L7.06 8l-3.72666667 3.7266667.94.94L8 8.94l3.7266667 3.7266667.94-.94L8.94 8"/></g></svg>');
  -webkit-mask-size: 90% !important;
  -webkit-mask-position: 90% !important;
  -webkit-mask-repeat: no-repeat!important;
  background-image: none!important;
}

.theme-dark .listDefault-2y5Z9D .clickable-23RaYz:hover .content-3xS9Lh, .theme-light .listDefault-2y5Z9D .clickable-23RaYz:hover .content-3xS9Lh {
  background-color: var(--Secondary-Background-Colour);
  border: 1px solid var(--Main-Colour);
}

.theme-dark .listDefault-2y5Z9D .clickable-23RaYz:hover .username-lm8y6T, .theme-light .listDefault-2y5Z9D .clickable-23RaYz:hover .username-lm8y6T {
  color: var(--Main-Colour);
}

.theme-dark .listDefault-2y5Z9D .clickable-23RaYz .username-lm8y6T, .theme-light .listDefault-2y5Z9D .clickable-23RaYz .username-lm8y6T {
  color: var(--Main-Colour);
}

.theme-dark .listDefault-2y5Z9D .clickable-23RaYz .content-3xS9Lh, .theme-light .listDefault-2y5Z9D .clickable-23RaYz .content-3xS9Lh {
  background-color: var(--Secondary-Background-Colour);
  border: 1px solid transparent;
}

.users-i_3-kL {
  background-color: var(--Secondary-Background-Colour);
  border-right: 1px solid var(--Secondary-Main-Colour);
}

.total-3tKGEB {
  background-color: var(--Secondary-Background-Colour);
}

.total-3tKGEB:after{
  border-color: var(--Secondary-Background-Colour);
}

.wrapper-pZmgj4{
  color: var(--Main-Colour);
  border: 1px solid var(--Main-Colour);
}

.total-3tKGEB:after{
  display: none;
}

.users-i_3-kL,.total-3tKGEB {
  padding-left:6px;
}

#files_directDownload span {
  color: var(--Main-Colour);
}

#files_directDownload {
  bottom: 62px!important;
  left: 22px!important;
}

#files_directDownload .file {
  background: var(--Secondary-Background-Colour);
  box-shadow: inset 0 0 10px var(--Secondary-Main-Colour);
  border: 1px solid var(--Secondary-Main-Colour);
}

#files_directDownload .file .progress-bar{
  background: var(--Main-Colour);
}

.listItem-2P_4kh.guildSeparator{
  width: calc(var(--Guild-Columns) * 60px + 2px) !important;
  align-content: center;
}

/* Seprate Rows For Server Folders And Guild List */
.wrapper-1Rf91z.foldercontent .folderseparatorouter{
  width: calc(var(--ServerFolders-Guild-Columns) * 60px + 2px) !important;
}

.wrapper-1Rf91z.foldercontent.da-guildsWrapper.da-foldercontent.foldercontentopen>div {
  width: calc(var(--ServerFolders-Guild-Columns) * 60px + 2px)!important;
  max-width: calc(var(--ServerFolders-Guild-Columns) * 60px + 2px)!important;
}

.foldercontentopen>.scrollerWrap-1IAIlv {
  width: calc(var(--ServerFolders-Guild-Columns) * 60px + 2px)!important;
  max-width: calc(var(--ServerFolders-Guild-Columns) * 60px + 2px)!important;
}

.foldercontent {
  width: calc(var(--ServerFolders-Guild-Columns) * 60px + 2px)!important;
  max-width: calc(var(--ServerFolders-Guild-Columns) * 60px + 2px)!important;
}

/* Seprate Rows For Server Folders And Guild List */

.theme-dark .expandedInfo-3kfShd {
  background-color: var(--Secondary-Background-Colour);
}

.theme-dark .paymentHeader-3QlZQi,.theme-dark .paymentText-2vaF7U,.css-1k00wn6-singleValue,.css-12o7ek3-option,.css-12o7ek5-option,.css-1gnr91b-option,.css-1aymab5-option,.css-13kbzi0-control,.css-548n9r-singleValue {
  color: var(--Main-Colour);
}

.theme-dark .paymentHeader-3QlZQi {
  border-color: var(--Secondary-Main-Colour);
}

.css-15ejc46-control,.css-12o7ek3-option,.css-12o7ek5-option,.css-13kbzi0-control {
  background-color: var(--Secondary-Background-Colour);
  border-color: var(--Secondary-Main-Colour);
}

.css-ua3v5p-menu,.css-1gnr91b-option,.css-1aymab5-option {
  background-color: var(--Background-Colour);
  border: 1px solid var(--Secondary-Main-Colour);
}

.css-ua3v5p-menu:hover,.css-1gnr91b-option:hover {
  background-color: var(--Background-Colour);
  border: 1px solid var(--Main-Colour);
}

.css-15ejc46-control:hover,.css-2yldzf-control,.css-12o7ek3-option:hover,.css-12o7ek5-option:hover,.css-2yldzf-control:hover {
  background-color: var(--Secondary-Background-Colour);
  border-color: var(--Main-Colour);
}

.css-12o7ek3-option{
  display:none;
}

.theme-dark .editIcon-13gaox {
  content: "";
  -webkit-mask: url('data:image/svg+xml; utf8, <svg xmlns="http://www.w3.org/2000/svg" width="24" height="24" viewBox="0 0 24 24"><g fill="none" fill-rule="evenodd"><path fill="#FFFFFF" fill-rule="nonzero" d="M20,5 L4,5 C2.9,5 2.01,5.9 2.01,7 L2,17 C2,18.1 2.9,19 4,19 L20,19 C21.1,19 22,18.1 22,17 L22,7 C22,5.9 21.1,5 20,5 Z M11,8 L13,8 L13,10 L11,10 L11,8 Z M11,11 L13,11 L13,13 L11,13 L11,11 Z M8,8 L10,8 L10,10 L8,10 L8,8 Z M8,11 L10,11 L10,13 L8,13 L8,11 Z M7,13 L5,13 L5,11 L7,11 L7,13 Z M7,10 L5,10 L5,8 L7,8 L7,10 Z M16,17 L8,17 L8,15 L16,15 L16,17 Z M16,13 L14,13 L14,11 L16,11 L16,13 Z M16,10 L14,10 L14,8 L16,8 L16,10 Z M19,13 L17,13 L17,11 L19,11 L19,13 Z M19,10 L17,10 L17,8 L19,8 L19,10 Z"/><path d="M0,0 L24,0 L24,24 L0,24 L0,0 Z M0,0 L24,0 L24,24 L0,24 L0,0 Z"/></g></svg>');
  -webkit-mask-size: 100% !important;
  -webkit-mask-position: 100% !important;
  -webkit-mask-repeat: no-repeat !important;
  background-image: none !important;
}

.theme-dark .input-2A_zIr{
  color: var(--Main-Colour);
}

.replyer:not(:hover){
  opacity: 0;
}

.base-PmTxvP[style*="background-color: rgb(240, 71, 71);"]{
  animation: rainbow 3s infinite linear;
}

.theme-dark .edited-DL9ECl {
  color: var(--Timestamp-Colour);
}

.app-2rEoOp {
  background: var(--File-Updated-2019-5-10) 50% 50%/cover , var(--Chat-Background) 50% 50%/cover !important;
  animation: Load4 3s 1 linear, var(--StartUp) 3s 1 linear;
  font-family: var(--Chat-Font-Used)!important;
}

.nameTag-3p0yK-:after {
  content: "";
  position: absolute;
  width: 100%;
  height: 100%;
  top: 0;
  left: 0;
  background: currentColor;
  opacity: 0.3;
  -webkit-mask: linear-gradient(to right, transparent 0%, var(--Secondary-Background-Colour) 2%, var(--Secondary-Background-Colour) 20%, var(--Secondary-Main-Colour)100%);
  z-index: 0;
  pointer-events: none;
  transition: .2s;
}

.theme-dark .memberOffline-2lN7gt .nameTag-3p0yK-:after{
  content: "";
  position: absolute;
  width: 100%;
  height: 100%;
  top: 0;
  left: 0;
  background: transparent;
  opacity: 0.3;
  -webkit-mask: linear-gradient(to right, transparent 0%, var(--Secondary-Background-Colour) 2%, var(--Secondary-Background-Colour) 20%, var(--Secondary-Main-Colour)100%);
  z-index: 0;
  pointer-events: none;
  transition: .2s;
}

.theme-dark .memberOffline-2lN7gt:hover .nameTag-3p0yK-:after{
  content: "";
  position: absolute;
  width: 100%;
  height: 100%;
  top: 0;
  left: 0;
  background: currentColor;
  opacity: 0.3;
  -webkit-mask: linear-gradient(to right, transparent 0%, var(--Secondary-Background-Colour) 2%, var(--Secondary-Background-Colour) 20%, var(--Secondary-Main-Colour)100%);
  z-index: 0;
  pointer-events: none;
  transition: .2s;
}

.member-3W1lQa:hover .nameTag-3p0yK-:after, .popout-open .nameTag-3p0yK-:after {
  opacity: 0.5;
}

.content-OzHfo4 {
  position: relative;
}

.image-33JSyf, .wrapper-2F3Zv8, .username-1cB_5E, .activity-1IYsbk, .botTag-2WPJ74 {
  z-index: 2;
}

.list-2bwCXU {
  padding-left: 0;
  padding-bottom: 0;
  margin: 1px 0 1px 8px;
}

.content-3xS9Lh {
  margin-top: 0;
  margin-bottom: 0;
}

.theme-dark .listDefault-2y5Z9D .clickable-23RaYz.selected-3TGCSZ .content-3xS9Lh{
  background-color: var(--Secondary-Background-Colour);
  border: 1px solid var(--Main-Colour);
}

.theme-dark .listDefault-2y5Z9D .clickable-23RaYz.selected-3TGCSZ .username-lm8y6T{
  color: var(--Main-Colour);
}
