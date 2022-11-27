/* Made by zombie.#0987 */

@import url('https://fonts.googleapis.com/css2?family=Titillium+Web:wght@700&display=swap');

/* Home */
:root {
    --asscentColor: #5cb7bf;
    --textColor: #5cb7bf;
    --right-border: 2px solid var(--asscentColor);
    --corners: linear-gradient(to right, var(--asscentColor) 2px, transparent 2px) 0
      100%,
        linear-gradient(to left, var(--asscentColor) 2px, transparent 2px) 100% 100%,
        linear-gradient(to top, var(--asscentColor) 2px, transparent 2px) 0 100%,
        linear-gradient(to top, var(--asscentColor) 2px, transparent 2px) 100% 100%,
        linear-gradient(to right, var(--asscentColor) 2px, transparent 2px) 0 0,
        linear-gradient(to left, var(--asscentColor) 2px, transparent 2px) 100% 0,
        linear-gradient(to bottom, var(--asscentColor) 2px, transparent 2px) 0 0,
        linear-gradient(to bottom, var(--asscentColor) 2px, transparent 2px) 100% 0;
    --right-corners: linear-gradient(to right, var(--asscentColor) 0px, transparent 0px) 0
      100%,
      linear-gradient(to left, var(--asscentColor) 2px, transparent 2px) 100% 100%,
      linear-gradient(to top, var(--asscentColor) 0px, transparent 0px) 0 100%,
      linear-gradient(to top, var(--asscentColor) 2px, transparent 2px) 100% 100%,
      linear-gradient(to right, var(--asscentColor) 0px, transparent 0px) 0 0,
      linear-gradient(to left, var(--asscentColor) 2px, transparent 2px) 100% 0,
      linear-gradient(to bottom, var(--asscentColor) 0px, transparent 0px) 0 0,
      linear-gradient(to bottom, var(--asscentColor) 2px, transparent 2px) 100% 0;
}

::-webkit-scrollbar-thumb {
    background-color: var(--asscentColor);
}
::-webkit-scrollbar:horizontal {
    background-color: transparent !important;
}
::-webkit-scrollbar-thumb:horizontal{
        background: transparent !important;
        border-radius: 10px;
}

#app > div.interface.text-2 > div.team-section > div.player > div > div.levels,
#app > div.game-interface > div.esc-interface > div.left-container > div.player-list > div > div.player-right > div,
#b4861794-0f92-45b6-bc4e-292a6e0ddc52 > div.time-left > button {
  border-radius: 0px;
  background-color: var(--background) !important;
  background: var(--corners);
  background-size: 10px 10px;
  background-repeat: no-repeat;
}

/* Fonts */
* {
    font-family: 'Titillium Web', sans-serif;
}

/* Glows Clan Name */
.heads .clan-tag {
    -webkit-animation: glow 2s ease-in-out infinite alternate;
    -moz-animation: glow 2s ease-in-out infinite alternate;
    animation: glow 2s ease-in-out infinite alternate;
}

/* play section */
#play {
    position: absolute;
    left: 35% !important;
    top: 7% !important;
    z-index: 1 !important;
    transform-origin: top left;
}

/* Removes Logo  */
.interface .logo {
    display: none !important;
}

.promo-link-btn {
    display: none !important;
}
.soc-group[data-v-3c44abf2] {
    display: none;
}

/* Transparent */
.box,
.input,
.settings,
.quests,
.quest,
.tip,
.amount,
.reward,
.progress-line,
.card-cont,
.container-card,
.progress[data-v-49c6809c],
.background,
.container button .border-top,
.container button .border-bottom,
.messages.messages-cont.small,
.title,
.card-list,
.head,
.changelog-item,
.card,
.live-streams,
.left,
.cont,
.bg {
    background: transparent !important;
    border: none !important;
}

.progress[data-v-2bdf2bcd] {
    background: transparent !important;
    border: none !important;
    box-shadow: none !important;
}

.progress[data-v-0f7a25c2] {
    background: transparent !important;
    box-shadow: none !important;
    border-bottom: none !important;
    
}

.active {
    border-bottom: var(--asscentColor) solid 0.125rem !important; 
}

/* Text Color */
.level-value,
.levels,
.clan-tag,
.top-name,
.list-labels,
.active,
.level,
.header,
.lvl-leader,
.label-primary,
.awards-span,
.champions-league,
.champions-scores,
.all-scores-label,
.stat-name,
.progress-level-value,
.amount,
.head {
    color: var(--textColor) !important;
}
.tab:hover,
.nav:hover {
    color: var(--textColor) !important;
}

/* Custom Backgorund */
#app > div.interface.text-2 > div.background {
    background-image: url(https://cdn.discordapp.com/attachments/1046359085391552623/1046360629470052432/unknown.png) !important;
    background-size: cover !important;
}
#app > div.interface.text-2 > div.background > div.pattern-bg,
#app > div.interface.text-2 > div.background > div.bg-radial {
    display: none !important
}

/*End Screen Background*/
.end-modal {
    background: url(https://cdn.discordapp.com/attachments/1046359085391552623/1046360905438470205/unknown.png) no-repeat !important;
    background-size: cover;
    z-index: -1;
}

.end-modal .team-list-players .list .player {
    background: transparent !important;
    border: none !important;
    border-bottom: none !important;
    box-shadow: none !important;
}

.end-modal .team-list-players .card-cont:nth-child(1),
.end-modal .team-list-players .card-cont:nth-child(2),
.end-modal .items {
    background: transparent !important;
    box-shadow: none !important;
}

.end-modal .team-list-players .label {
    background: transparent;
    color: var(--asscentColor);
}

/* Login/Signup*/
.auth-form {
    margin-left: 0 !important;
    background: transparent !important;
    border: none !important;
    border-radius: 0 !important;
}

.auth-form .btns button {
    transform: none !important;
    padding: 0px;
}

.auth-user .loading {
    background: transparent !important;
	border: none;
	border-bottom: none !important;
	border-radius: 0;
}

.auth-user .loader-container {
	margin-right: 95% !important;
}

.auth-form .btns button:hover {
    background-color: transparent !important;
    box-shadow: none !important;
}

.auth-form button,
.auth-form button .border-top,
.auth-form button .border-bottom{
    background: transparent !important;
    box-shadow: none !important;
}

.auth-form button .triangle {
    display: none;
}

.button[data-v-02c36fca]:after {
    border: none;
}



/* Money */
.moneys {
    flex-direction: absolute;
    position: absolute;
    left: -40%;
    top: 10%;
}

.moneys[data-v-2484b84e] {
    display: flex;
    flex-direction: row;
    margin-left: -50px;
    margin-top: 80px;
}

/* Right Interface */
.right-interface {
	padding-top: 20px;
}

.soc-group:nth-child(1),
.soc-group:nth-child(2) {
	background: transparent !important;
	border: none;
    visibility: hidden;
}

.soc-group:nth-child(1):hover,
.soc-group:nth-child(2):hover {
	background: none !important;
	transform: scale(1.5);
    visibility: hidden;
}

.right-interface .settings {
	position: absolute;
    left: -260% !important;
    top: 35% !important;
    z-index: 1 !important;
    transform-origin: top left;
} 

.right-interface {
    z-index: 999 !important;
}

.quests {
    position: relative;
    top: 7rem !important;
    transform: scale(.9)
}

#settings-and-socicons > div.card-cont.settings.card-1{
    background: url(https://media.discordapp.net/attachments/1020437466550894682/1020505847476015224/settings.png?width=598&height=598) !important;
    background-size: 60px !important;
    background-repeat: no-repeat !important;
    margin-top: 0;
    transition: 0.3s;
    height: 80px !important;
    width: 90px !important;
}

.coin-icon {
    background: url(https://cdn.discordapp.com/attachments/1046359085391552623/1046362777809321984/coin_icon.png) !important;
    background-size: 30px !important;
    background-repeat: no-repeat !important;
    margin-top: 0;
    transition: 0.3s;
}

.svg-icon--diamond {
    background: url(https://cdn.discordapp.com/attachments/1046359085391552623/1046362778186817566/gem.icon.png) !important;
    background-size: 30px !important;
    background-repeat: no-repeat !important;
    margin-top: 0;
    transition: 0.3s;
}

#settings-and-socicons > div.card-cont.settings.card-1 > svg,
#left-interface > div.moneys > div:nth-child(1) > svg > use,
#left-interface > div.moneys > div.card-cont.money.diamonds > svg > use {
    display: none !important;
}
/* Left Menu */
.left-icons .icon-btn:nth-child(1) {
    background: url(https://cdn.discordapp.com/attachments/1046359085391552623/1046362974274715690/home-icon.png);
    background-size: 60px !important;
    background-repeat: no-repeat;
    margin-top: 0;
    background-position-x: 2rem !important;
    background-position-y: 1rem !important;
    transition: 0.3s;
    height: 100px !important;
}

.left-icons .icon-btn:nth-child(2) {
    background: url(https://cdn.discordapp.com/attachments/1046359085391552623/1046364212693323796/market.png);
    background-size: 60px !important;
    background-repeat: no-repeat;
    margin-top: 0;
    background-position-x: 2rem !important;
    background-position-y: 1rem !important;
    transition: 0.3s;
    height: 100px !important;
}

.left-icons .icon-btn:nth-child(3) {
    background: url(https://cdn.discordapp.com/attachments/1046359085391552623/1046363909461901442/generator.png);
    background-size: 60px !important;
    background-repeat: no-repeat;
    margin-top: 0;
    background-position-x: 2rem !important;
    background-position-y: 1rem !important;
    transition: 0.3s;
    height: 100px !important;
}

.left-icons .icon-btn:nth-child(4) {
    background: url(https://cdn.discordapp.com/attachments/1046359085391552623/1046364607993880656/quests.png);
    background-size: 60px !important;
    background-repeat: no-repeat;
    margin-top: 0;
    background-position-x: 2rem !important;
    background-position-y: 1rem !important;
    transition: 0.3s;
    height: 100px !important;
}

.left-icons .icon-btn:nth-child(5) {
    background: url(https://cdn.discordapp.com/attachments/1046359085391552623/1046365197515903027/friends.png);
    background-size: 60px !important;
    background-repeat: no-repeat;
    margin-top: 0;
    background-position-x: 2rem !important;
    background-position-y: 1rem !important;
    transition: 0.3s;
    height: 100px !important;
}

.left-icons .icon-btn:nth-child(6) {
    background: url(https://cdn.discordapp.com/attachments/1046359085391552623/1046365768213856296/inv.png);
    background-size: 60px !important;
    background-repeat: no-repeat;
    margin-top: 0;
    background-position-x: 2rem !important;
    background-position-y: 1rem !important;
    transition: 0.3s;
    height: 100px !important;
}

.left-icons .icon-btn:nth-child(7) {
    background: url(https://cdn.discordapp.com/attachments/1046359085391552623/1046366047726473246/map.png);
    background-size: 60px !important;
    background-repeat: no-repeat;
    margin-top: 0;
    background-position-x: 2rem !important;
    background-position-y: 1rem !important;
    transition: 0.3s;
    height: 100px !important;
}

.left-icons .icon-btn:nth-child(1):hover {
    background: url(https://cdn.discordapp.com/attachments/1046359085391552623/1046362974274715690/home-icon.png);
    background-repeat: no-repeat;
    transform: scale(1.2)
}

.left-icons .icon-btn:nth-child(2):hover {
    background: url(https://cdn.discordapp.com/attachments/1046359085391552623/1046363581840642048/market.png);
    background-repeat: no-repeat;
    transform: scale(1.2)
}

.left-icons .icon-btn:nth-child(3):hover {
    background: url(https://cdn.discordapp.com/attachments/1046359085391552623/1046363909461901442/generator.png);
    background-repeat: no-repeat;
    transform: scale(1.2)
}

.left-icons .icon-btn:nth-child(4):hover {
    background: url(https://cdn.discordapp.com/attachments/1046359085391552623/1046364212693323796/market.png);
    background-repeat: no-repeat;
    transform: scale(1.2)
}

.left-icons .icon-btn:nth-child(5):hover {
     background: url(https://cdn.discordapp.com/attachments/1046359085391552623/1046364607993880656/quests.png);
    background-repeat: no-repeat;
    transform: scale(1.2)
}

.left-icons .icon-btn:nth-child(6):hover {
    background: url(https://cdn.discordapp.com/attachments/1046359085391552623/1046365197515903027/friends.png);
    background-repeat: no-repeat;
    transform: scale(1.2)
}

.left-icons .icon-btn:nth-child(7):hover {
     background: url(https://cdn.discordapp.com/attachments/1046359085391552623/1046365768213856296/inv.png);
    background-repeat: no-repeat;
    transform: scale(1.2)
}
.left-icons {
    background: transparent !important;
}

#left-icons {
    flex-direction: row-reverse;
}

.left-icons .icon-btn {
    background: transparent;
    border: none;
    width: 107px;
    border-radius: 0;
}

#left-icons {
    display: flex;
    flex-direction: row;
    align-items: flex-start;
    position: absolute;
    left:50% !important;
    top: 3% !important;
    z-index: 100 !important;
    transform-origin: top left;
}

.right-interface {
    z-index: 1 !important;
}

.text-icon,
.left-icons .icon-btn svg {
    display: none !important;
}

/* Removed Profile Card */
.avatar-info,
.progress-label {
    display: none !important;
}

.user-info {
    padding-left: 3vw !important; 
}

.progress {
    background: var(--asscentColor) !important;
    display: block !important;
}

.progress {
    box-shadow: 0px 0px 10px 6px var(--asscentColor);
}

.left-interface[data-v-6ef47e92] {
    position: absolute;
    left: 42%;
    top: 3%;
    z-index: 9;
    transform-origin: top left;
}

/* Profile */
div.card-cont.avatar-info,
div.card-cont.user-info,
.money {
    background: transparent !important;
    border-bottom: transparent !important;
    border: none !important;
}
.settings[data-v-e0ea0f78] {
    background: transparent !important;
    border-bottom: transparent !important;
}

.card-cont[data-v-1cbd79ff] {
    background: transparent !important;
    border-bottom: transparent !important;
    border: none !important;
}
.card-cont[data-v-1cbd79ff]:hover {
    background: transparent !important;
}


/* Inv & Friends */
#right-icons [data-v-ae524044] {
    height: 3.2rem;
}
#right-icons > div.icon-btn.text-1 {
    width: 139px;
    font-size: 18px;
    height: 65px;
}
#right-icons [data-v-1cbd79ff] {
    width: 139px;
    font-size: 18px;
    height: 65px;
}
#right-icons [data-v-b8de1e14] {
    display: none;
}
.right-icons .gun-img {
    display: none;
}
.right-icons .icon-btn {
    background: transparent !important;
    border-bottom: transparent !important;
    border: none !important;
}

/* Server & Play */
.select-mod,
.select-region {
    background: transparent !important;
    border-right: none !important;
    border-left: none !important;
    border-top: none !important;
    border-bottom: none !important;
}
.select-regions-cont[data-v-6ef47e92] {
    background: transparent !important;
    border-right: none !important;
    border-left: none !important;
    border-top: none !important;
    border-bottom: none !important;
}
.container button {
    background: transparent !important;
    border-right: none !important;
    border-left: none !important;
    border-top: none !important;
    border-bottom: none !important;
    border-radius: 0 !important;
}
.container button {
    background: transparent !important;
    border-radius: 0 !important;
    transform: none !important;
    border-radius: 0 !important;
}
.container button .border-top,
.container button .border-bottom {
    display: none;
}
/* Join URL Button (For client only) */
.join-using-link {
    background: transparent !important;
    border-right: none !important;
    border-left: none !important;
    border-top: none !important;
    border-bottom: none !important;
}

.join-using-link:active {
    background: transparent !important;
    border-right: none !important;
    border-left: none !important;
    border-top: none !important;
    border-bottom: none !important;
}

#clientJoinButton {
    background: transparent !important;
    border-right: none !important;
    border-left: none !important;
    border-top: none !important;
    border-bottom: none !important;
}

#clientJoinButton:active {
    background: transparent !important;
    border-right: none !important;
    border-left: none !important;
    border-top: none !important;
    border-bottom: none !important;
}

#play-btn {
    background: rgba(68, 68, 68, 0) !important;
    box-shadow: 4px 4px 10px #0000 !important;
}

#play-btn .border-top,
#play-btn .border-bottom {
    background: none;
}

.button[data-v-02c36fca] {
    -webkit-text-stroke: 0px !important;
}

.button[data-v-02c36fca]:after {
    border: none;
    background: transparent !important;
}

.triangle[data-v-02c36fca] {
    display: none !important;
    background: transparent;
}


/*	Ad Removal */
.ad-bottom,
.ad-left {
    display: none !important;
    visibility: hidden !important;
}
.className {
    display: none !important;
}
/* Mode Selection */
.select-mods-cont,
.select-mods-cont > hr {
    background: transparent!important;
    border: none !important;
    margin-right: 500px;
    border: 1px solid var(--asscentColor);
}
.custom-checkbox > input:checked + span[data-v-47e1b746]:before {
    background-color: var(--asscentColor);
    border-color: var(--asscentColor);
}
.soc-group[data-v-f6928a74],
.text-soc[data-v-26102dd2] {
    display: none !important;
}

/* Check Box */
.private-btn > span[data-v-47e1b746] {
    content: url(https://cdn.discordapp.com/attachments/1046359085391552623/1046367012563189761/open.png);
    position: fixed;
    left: 25px;
    width: 40px;
}

.private-btn > input:checked + span[data-v-47e1b746] {
    content: url(https://cdn.discordapp.com/attachments/1046359085391552623/1046367298316935178/locked.png);
}

.custom-checkbox > span[data-v-47e1b746]:before {
    border-radius: 50px;
    background-color: white;
    border: none;
}

.custom-checkbox > input:checked + span[data-v-47e1b746]:before {
    background-color: var(--asscentColor);
}

.input .items[data-v-4f6bb432] {
    background: transparent !important;
    backdrop-filter: blur(15px);
}

/* chat */
.desktop-game-interface #WMNn {
    transform: scale(0);
    transition-duration: 0.25s !important;
}

.desktop-game-interface #WMNn:focus {
    transform: scale(1);
}
.clans,
.hub-container,
.mobile-fullscreen,
.add-friends,
.tab-bar,
.top-items,
.subject,
.inventory .avatar,
.inventory .bottom {
    background: transparent !important;
}

.head-text,
.reset-time,
.info-awards,
.news,
.list-cont,
.card-profile,
.profile .k-d,
.profile .statistics,
.profile-cont .progress[data-v-d2be3bc6] {
    background: transparent !important;
    box-shadow: none !important;
    border-bottom: none;
}

.tabs {
    background: transparent !important;
    border-bottom: none !important;
    box-shadow: none !important;
    border-right: none !important;
}

.active-tab,
.tab {
    background: transparent !important;
    border-right: none !important;
    border-left: none !important;
}

.tab:hover {
    background: transparent !important;
    border-right: none !important;
    border-left: none !important;
}

.limit {
    border-left: none !important;
}

.top-bar,
.home,
.name-page {
    display: none !important;
}

.container {
    background: transparent !important;
    backdrop-filter: blur(15px);
    box-shadow: none !important;
}

.champions-list {
    box-shadow: none !important;
}

.subjects,
.gun {
    background: transparent !important;
    border: none !important;
}

.profile .you {
    visibility: hidden;
}
.top[data-v-319b95e8] {
    background: transparent !important;
    border-right: none !important;
    border-left: none !important;
}
.item[data-v-319b95e8] {
    background: transparent !important;
    border-right: none !important;
    border-left: none !important;
}
.champions-list[data-v-3ade8f70] {
    background: transparent !important;
    border-right: none !important;
    border-left: none !important;
}
.items .item[data-v-3ade8f70] {
    background: transparent !important;
    border-right: none !important;
    border-left: none !important;
}
.card-head[data-v-5b2dc87c] {
    background: transparent !important;
    border-right: none !important;
    border-left: none !important;
}
.list-container[data-v-3bcb580a] {
    background: transparent !important;
    border-right: none !important;
    border-left: none !important;
}
.card-cont[data-v-040b7087] {
    background: transparent !important;
    border-right: none !important;
    border-left: none !important;
}
.description[data-v-040b7087] {
    background: transparent !important;
    border-right: none !important;
    border-left: none !important;
}
.all-scores[data-v-040b7087] {
    background: transparent !important;
    border-right: none !important;
    border-left: none !important;
}
.champions-stat[data-v-040b7087] {
    background: transparent !important;
    border-right: none !important;
    border-left: none !important;
}
.item-content[data-v-3bcb580a] {
    background: transparent !important;
    border-right: none !important;
    border-left: none !important;
}
.server[data-v-679cb6a8] {
    background: transparent !important;
    border-bottom: transparent !important;
    border: none !important;
}  
.player[data-v-68ad001e] {
    background: transparent !important;
    border-bottom: transparent !important;
    border: none !important;
}
.right-container[data-v-68ad001e] {
    background: transparent !important;
    border-bottom: transparent !important;
    border: none !important;
}
.messages[data-v-76a3fe0a] {
    background: transparent !important;
    border-bottom: transparent !important;
    border: none !important;
}
.input[data-v-29d4a917] {
    background: transparent !important;
    border-bottom: transparent !important;
    border: none !important;
}
.timer[data-v-1d4749de] {
    background: transparent !important;
    border-bottom: transparent !important;
    border: none !important;
}
.bg[data-v-1d4749de] {
    background: transparent !important;
    border-bottom: transparent !important;
    border: none !important;
}
.head[data-v-a204db68] {
    background: transparent !important;
    border-bottom: transparent !important;
    border: none !important;
}
.list[data-v-a204db68] {
    background: transparent !important;
    border-bottom: transparent !important;
    border: none !important;
}
.name[data-v-2bbf437a] {
    padding-top: 20px;    
}
.time-left[data-v-556f2c42] {
    background: transparent !important;
    border: none !important;
}
.rewards[data-v-556f2c42] {
    background: transparent !important;
    border: none !important;
}
.level-cont[data-v-197190ba] {
    background: transparent !important;
    border-bottom: transparent !important;
    border: none !important;
}
.level-label[data-v-197190ba] {
    color: #ffffff;
    background: transparent !important;
    border-bottom: transparent !important;
    border: none !important;
}
.card[data-v-49c6809c] {
    background: transparent !important;
    border-bottom: transparent !important;
    border: none !important;
}
.friend[data-v-197190ba] {
    background: transparent !important;
}
.add[data-v-197190ba], .delete[data-v-197190ba] {
    background: transparent !important;
    border-bottom: transparent !important;
    border: none !important;
}
.info-key-cont,
.list-weapons,
.mWwn,
.instruction {
    display: none !important;
}

.hp {
    margin-right: 20%;
    border: #ffffff;
}

.hp-progress {
    background-color: #ffffff !important;
}

.state {
    position: fixed;
    width: 300px;
    top: 93%;
    left: 37% !important;
}

/* HUD */
.mini-map-cont .name,
.desktop-game-interface .info-key-cont,
.list-weapons,
.hp-title,
.mWwn,
.instruction {
    display: none !important;
}

.end-modal .clan-tag {
    -webkit-animation: glow 2s ease-in-out infinite alternate;
    -moz-animation: glow 2s ease-in-out infinite alternate;
    animation: glow 2s ease-in-out infinite alternate;
}

/* Leaderboard */
.leaders .clan-tag {
    -webkit-animation: glow 2s ease-in-out infinite alternate;
    -moz-animation: glow 2s ease-in-out infinite alternate;
    animation: glow 2s ease-in-out infinite alternate;
}

/* In Game Leaderboard */
.tab-info,
.container-card {
    background: transparent !important;
	box-shadow: none !important;
	border-radius: 0 !important;
	border: none !important;
    backdrop-filter: blur(5px);
}

.tab-info .head {
	display: none;
}

.tab-info .player {
	background: transparent !important;	
}

.tab-info .primary {
	color: white !important;
}

.tab-info .nickname,
.tab-info .player-right {
	color: var(--asscentColor) !important;
}

.tab-info .list {
	color: white;
	margin: 0 !important;
}

.tab-info .list .list-value:nth-child(1),
.tab-info .list .list-value:nth-child(2),
.tab-info .list .list-value:nth-child(3) {
	visibility: hidden;
}

.tab-info .list .list-value:nth-child(1):after {
	visibility: visible;
	content: "K";
	margin-left: -29px;
}

.tab-info .list .list-value:nth-child(2):after {
	visibility: visible;
	content: "D";
	margin-left: -28px;
}

.tab-info .list .list-value:nth-child(3):after {
	visibility: visible;
	content: "S";
	margin-left: -5px;
}

.tab-info .player-right svg {
	display: none;
}

.cont-hp {
    background: transparent !important;
}

.hp {
    margin-right: 20%;
}

.hp-progress {
    background: #ffffff !important;
}

.desktop-game-interface .state {
    position: fixed;
    width: 500px !important;
    top: 93%;
    left: 37% !important;
}

.cont-endurance {
    margin-left: 1.5%;
    background: transparent !important;
    border: var(--asscentColor) !important;
}

.endurance-progress {
    background: linear-gradient(to right, var(--asscentColor), var(--asscentColor)) !important;
}

.ammunition {
   background: transparent !important;
    display: inline-block;
    position: fixed;
    left: calc(52% + 188px);
    top: calc(91%)
}

.bg[data-v-14e97ff8] {
    background: transparent !important;
    border-bottom: transparent !important;
    border: none !important;
}

.player[data-v-3a61646a] {
    background: transparent !important;
    border-bottom: transparent !important;
    border: none !important;
}
.timer[data-v-14e97ff8] {
    background: transparent !important;
    border-bottom: transparent !important;
    border: none !important;
}
.interface .nickname:after {
    display: none;
}
.top-items[data-v-319b95e8] {
    box-shadow: none !important;
    border-bottom: none !important;
    border: none !important;
}
/* Esc Interface*/
.esc-interface {
    backdrop-filter: blur(5px);
}

.esc-interface .head-right button,
.esc-interface .head-right button .border-top,
.esc-interface .head-right button .border-bottom {
    background: transparent !important;
    box-shadow: none;
    border-radius: 0;
}

.esc-interface .head-right button:hover {
    background: transparent !important;
    border-bottom: 5px solid white;
}

.esc-interface .left-container .player {
    background: transparent !important;
}

.esc-interface .right-container {
    background: transparent !important;
}

.esc-interface .player .label {
    color: var(--asscentColor);
    -webkit-animation: glow 2s ease-in-out infinite alternate;
    -moz-animation: glow 2s ease-in-out infinite alternate;
    animation: glow 2s ease-in-out infinite alternate;
}

.esc-interface .primary {
	color: #ffffff !important;
}

.esc-interface .level{
	color: white;
}

.continue {
	background: rgb(68, 68, 68) !important;
	box-shadow: none !important;
}

.continue:hover {
	background: var(--asscentColor) !important;
	box-shadow: none !important;
}

.continue .border-top,
.continue .border-bottom {
	background: transparent !important;
	box-shadow: none !important;
}

#dailyQuests {
    position: fixed;
    top: 30px;
    border: none;
	border-radius: 0;
	z-index: -1 !important;
	overflow: auto;
}

/*  Player Position  */
#team-section > div.player {
margin-right: 90rem;
margin-top: 27rem;
}

/* / Button Locations (Thank you cvivic ily) */
.moneys {
position: absolute;
top: 90px;
}

#left-interface {
position: absolute;
left: -1.9%;
top: -30px;
}

/* Transparent Containers */
.clans,
.hub-container,
.mobile-fullscreen,
.add-friends,
.tab-bar,
.top-items,
.subject,
.inventory .avatar,
.player-right,
.ach-cont,
.inventory .bottom,
.button.create-btn.rectangle,
.border-top.border,
.border-bottom.border,
.background {
background: transparent !important;
}

.head-text,
.reset-time,
.info-awards,
.news,
.list-cont,
.card-profile,
.profile .k-d,
.profile .statistics,
.profile-cont .progress[data-v-d2be3bc6] {
background: transparent !important;
box-shadow: none !important;
}

.tabs {
background: transparent !important;
border-bottom: none !important;
box-shadow: none !important;
border-right: none !important;
}

.active-tab,
.tab {
background: transparent !important;
border-right: none !important;
border-left: none !important;
}

.limit {
border-left: none !important;
}

.top-bar,
.home,
.name-page {
display: none !important;
}

.container {
background: transparent !important;
backdrop-filter: blur(5px);
box-shadow: none !important;
}

.champions-list {
box-shadow: none !important;
}

.profile .you {
visibility: hidden;
}
.button.create-btn.rectangle {
	background: transparent !important;
	box-shadow: none !important;
}
.card.progress {
	background: transparent !important;
	box-shadow: none !important;
}
.items {
	background: transparent !important;
	box-shadow: none !important;
}

.achive-cont {
  	content: url(https://cdn.discordapp.com/attachments/1046359085391552623/1046369082435448862/killicon.png) !important;
  	position: fixed;
  	right: 45%;
    width: 160px !important;
    height: 160px !important;
}
