@font-face {
    font-family: 'Circular Std';
    src: url("../fonts/CircularStd-Book.eot");
    src: url("../fonts/CircularStd-Book.eot?#iefix") format("embedded-opentype"), url("../fonts/CircularStd-Book.woff") format("woff"), url("../fonts/CircularStd-Book.ttf") format("truetype");
    font-weight: normal;
    font-style: normal;
}

@font-face {
    font-family: 'Circular Std';
    src: url("../fonts/CircularStd-Bold.eot");
    src: url("../fonts/CircularStd-Bold.eot?#iefix") format("embedded-opentype"), url("../fonts/CircularStd-Bold.woff") format("woff"), url("../fonts/CircularStd-Bold.ttf") format("truetype");
    font-weight: bold;
    font-style: normal;
}

@font-face {
    font-family: 'Circular Std';
    src: url("../fonts/CircularStd-Black.eot");
    src: url("../fonts/CircularStd-Black.eot?#iefix") format("embedded-opentype"), url("../fonts/CircularStd-Black.woff") format("woff"), url("../fonts/CircularStd-Black.ttf") format("truetype");
    font-weight: 900;
    font-style: normal;
}

@font-face {
    font-family: 'Circular Std';
    src: url("../fonts/CircularStd-Medium.eot");
    src: url("../fonts/CircularStd-Medium.eot?#iefix") format("embedded-opentype"), url("../fonts/CircularStd-Medium.woff") format("woff"), url("../fonts/CircularStd-Medium.ttf") format("truetype");
    font-weight: 500;
    font-style: normal;
}

@font-face {
    font-family: 'uni_sansheavy_caps';
    src: url("../fonts/uni_sans_heavy-webfont.woff2") format("woff2"), url("../fonts/uni_sans_heavy-webfont.woff") format("woff");
    font-weight: normal;
    font-style: normal;
}

body {
    font-family: "Circular Std", sans-serif;
    font-size: 14px;
    background: #0f0f0f;
    color: #ffffff;
}

.current-server img {
    width: 100%;
    height: 100%;
    border-radius: 50%;
}

#bg {
    position: fixed;
    top: 0;
    left: 0;
    right: 0;
    bottom: 0;
    background-image: url("../img/background.jpg");
}

#bg:before {
    content: "";
    position: absolute;
    left: 50%;
    top: 50%;
    -webkit-transform: translateY(-50%) translateX(-25%);
    transform: translateY(-50%) translateX(-25%);
    width: 200%;
    height: 100%;
    background-image: url("../img/background.jpg");
    /* background-position: center; */
    background-repeat: no-repeat;
    background-size: contain;
    background-attachment: fixed;
    /* background: linear-gradient(to bottom, #000803 14%, #000836 100%); */
}

html,
body {
    height: 100%;
}

h1 {
    font-size: 4.4em;
}

h2 {
    font-size: 3.6em;
}

h3 {
    font-size: 2.6em;
}

h4 {
    font-size: 2.2em;
}

h5 {
    font-size: 1.8em;
}

h6 {
    font-size: 1.4em;
}

h1,
h2,
h3,
h4,
h5,
h6 {
    margin: 0;
}

p {
    line-height: 1.67;
}

a {
    color: #ffffff;
    -webkit-transition: all .3s ease;
    transition: all .3s ease;
}

a:hover,
a:active {
    color: rgba(255, 255, 255, 0.6);
    text-decoration: none;
}

a:focus {
    color: inherit;
    outline: 0;
    text-decoration: none;
}


/*** Typography ***/

.text-semibold {
    font-weight: 600;
}

.text-bold {
    font-weight: 700;
}

.text-extrabold {
    font-weight: 900;
}

.text-underline {
    display: inline-block;
    border-bottom: 2px solid;
    padding-bottom: 2px;
}

.text-light {
    font-weight: 300;
}

.text-regular {
    font-weight: normal;
}

.heading1 {
    font-size: 4.8em;
}

.heading2 {
    font-size: 3.9em;
}

.heading3 {
    font-size: 3em;
}

.heading4 {
    font-size: 2.4em;
}

.heading-xxl {
    font-size: 5.4em;
}

.sub1 {
    font-size: 2em;
}

.sub2 {
    font-size: 1.6em;
}

.sub3 {
    font-size: 1.2em;
}

.m-0 {
    margin: 0 !important;
}

.mt-0 {
    margin-top: 0 !important;
}

.mt-10 {
    margin-top: 10px !important;
}

.mt-20 {
    margin-top: 20px !important;
}

.mt-25 {
    margin-top: 25px !important;
}

.mt-50 {
    margin-top: 50px !important;
}

.mt-100 {
    margin-top: 100px !important;
}

.mt-200 {
    margin-top: 200px !important;
}

.mb-10 {
    margin-bottom: 10px !important;
}

.mb-20 {
    margin-bottom: 20px !important;
}

.mb-25 {
    margin-bottom: 25px !important;
}

.mb-50 {
    margin-bottom: 50px !important;
}

.mb-100 {
    margin-bottom: 100px !important;
}

.p-0 {
    padding: 0 !important;
}

.pt-0 {
    padding-top: 0 !important;
}

.pt-10 {
    padding-top: 10px !important;
}

.pt-20 {
    padding-top: 20px !important;
}

.pt-25 {
    padding-top: 25px !important;
}

.pt-50 {
    padding-top: 50px !important;
}

.pt-100 {
    padding-top: 100px !important;
}

.pb-0 {
    padding-bottom: 0 !important;
}

.pb-10 {
    padding-bottom: 10px !important;
}

.pb-20 {
    padding-bottom: 20px !important;
}

.pb-25 {
    padding-bottom: 25px !important;
}

.pb-50 {
    padding-bottom: 50px !important;
}

.pb-100 {
    padding-bottom: 100px !important;
}

.text-big {
    font-size: 1.125em;
}

.text-big-xl {
    font-size: 1.275em;
}

.text-small {
    font-size: 0.875em;
}

.clr-primary {
    color: #35ecd3;
}

.clr-secondary {
    color: #5135ec;
}

.clr-gray {
    color: #11111a;
}

.clr-white {
    color: #fff !important;
}

.clr-fade {
    opacity: 0.6;
}


/*** Typography End ***/


/*** Header Start ***/

.navbar {
    position: fixed;
    left: 0;
    top: 0;
    width: 100%;
    border: 0;
    border-radius: 0;
    margin: 0;
    z-index: 1051;
    padding: 5px 0;
}

.navbar a {
    color: #fff;
}

.navbar-brand {
    font-family: "uni_sansheavy_caps", sans-serif;
    font-weight: 700;
    color: rgb(167, 5, 5);
}

.navbar-header {
    float: none !important;
}

.navbar-menu {
    margin-left: auto;
}

.navbar-menu .btn {
    font-size: 0.875em;
    padding: 8px 24px;
}

.navbar-brand-center {
    float: none !important;
    display: inline-block;
    margin-left: 0 !important;
    padding: 30px 0;
    font-size: 2em;
}

.justify-center {
    -webkit-box-pack: center;
    -ms-flex-pack: center;
    justify-content: center;
}

.navbar-nav>li>a:hover {
    background-color: transparent;
}

.navbar-nav>li>a:focus {
    background-color: transparent;
}

.steam-info {
    display: table;
}

.steam-avatar,
.steam-login {
    display: table-cell;
    vertical-align: middle;
}

.steam-login {
    padding-left: 15px;
}

.steam-avatar {
    display: none;
}

.user-logged-in .steam-avatar {
    display: table-cell;
}

.user-logged-in .steam-login {
    display: none;
}

.steam-avatar-holder {
    position: relative;
    overflow: hidden;
    width: 32px;
    height: 32px;
    border-radius: 4px;
    z-index: 1;
    display: block;
}

.steam-avatar-holder img {
    position: absolute;
    top: 50%;
    left: 50%;
    -webkit-transform: translateY(-50%) translateX(-50%);
    transform: translateY(-50%) translateX(-50%);
    max-width: 115%;
    min-height: 100%;
    min-width: 100%;
    height: auto;
}

.navbar>* {
    display: -webkit-box;
    display: -ms-flexbox;
    display: flex;
    -webkit-box-align: center;
    -ms-flex-align: center;
    align-items: center;
}

.navbar-nav {
    margin-left: auto;
}


/*** Header End ***/


/*** Hero Start ***/

.hero {
    position: relative;
    background-size: cover;
    background-position: center center;
    background-repeat: no-repeat;
}

#home {
    background-size: cover;
    background-position: center center;
    background-repeat: no-repeat;
    height: 75vh;
}


/*** Hero End ***/


/*** Main Start ***/

#page {
    padding-left: 60px;
}

#sidebar {
    position: fixed;
    top: 60px;
    left: 0;
    height: calc(100% - 60px);
    z-index: 2;
}

.sidebar-menu {
    list-style: none;
    padding: 0;
    margin: 0;
}

.sidebar-menu li+li {
    margin-top: 10px;
}

.sidebar-menu li a {
    background: rgba(255, 255, 255, 0.05);
    color: #fff;
    display: block;
    width: 40px;
    height: 40px;
    line-height: 40px;
    margin: 0 6px 0;
    font-weight: 700;
    text-align: center;
    border-radius: 60%;
    font-size: 18px;
    -webkit-transition: all 0.3s cubic-bezier(0.68, -0.55, 0.265, 1.55);
    transition: all 0.3s cubic-bezier(0.68, -0.55, 0.265, 1.55);
}

.sidebar-menu li a:hover {
    background: rgba(255, 255, 255, 0.07);
    border-radius: 10px;
}

.sidebar-menu li a:active {
    background: rgba(255, 255, 255, 0.04);
    color: rgba(255, 255, 255, 0.6);
}

.sidebar-menu .current-server {
    background-color: #12c2aa;
    font-family: "uni_sansheavy_caps", sans-serif;
    font-size: 24px;
}

.sidebar-menu .current-server:hover {
    background-color: #10ab96;
}

.sidebar-menu .join-server {
    background: transparent;
    border: 1px dashed rgba(255, 255, 255, 0.4);
    color: rgba(255, 255, 255, 0.4);
}

.sidebar-menu .join-server:hover {
    border-color: #fff;
    color: #fff;
    background: transparent;
}

.ui-settings {
    list-style: none;
    padding: 0;
    margin: 0;
    float: left;
}

.ui-settings li {
    display: inline-block;
    margin: 0 10px;
}

.ui-settings li a:active {
    opacity: 0.6;
}

.page {
    position: fixed;
    top: 60px;
    left: 52px;
    width: calc(100% - 52px);
    height: calc(100% - 60px);
    -webkit-transition: left 0.7s cubic-bezier(0.86, 0, 0.07, 1), -webkit-filter 0.3s ease;
    transition: left 0.7s cubic-bezier(0.86, 0, 0.07, 1), -webkit-filter 0.3s ease;
    transition: filter 0.3s ease, left 0.7s cubic-bezier(0.86, 0, 0.07, 1);
    transition: filter 0.3s ease, left 0.7s cubic-bezier(0.86, 0, 0.07, 1), -webkit-filter 0.3s ease;
}

.page-single {
    padding-left: 52px;
    padding-top: 60px;
}

#chat-list {
    position: fixed;
    left: 52px;
    top: 60px;
    width: 240px;
    background: #006dff0f;
    height: calc(100% - 60px);
    -webkit-transform: translateX(calc(-100% - 52px));
    transform: translateX(calc(-100% - 52px));
    -webkit-transition: box-shadow 0.3s ease 0s, -webkit-transform 0.7s cubic-bezier(0.86, 0, 0.07, 1);
    transition: box-shadow 0.3s ease 0s, -webkit-transform 0.7s cubic-bezier(0.86, 0, 0.07, 1);
    transition: transform 0.7s cubic-bezier(0.86, 0, 0.07, 1), box-shadow 0.3s ease 0s;
    transition: transform 0.7s cubic-bezier(0.86, 0, 0.07, 1), box-shadow 0.3s ease 0s, -webkit-transform 0.7s cubic-bezier(0.86, 0, 0.07, 1);
    z-index: 2;
}

.sidebar-expanded #chat-list {
    -webkit-transform: none;
    transform: none;
    box-shadow: 16px 0 64px rgba(17, 17, 26, 0.3);
    -webkit-transition: box-shadow 0.3s ease 0.7s, -webkit-transform 0.7s cubic-bezier(0.86, 0, 0.07, 1);
    transition: box-shadow 0.3s ease 0.7s, -webkit-transform 0.7s cubic-bezier(0.86, 0, 0.07, 1);
    transition: transform 0.7s cubic-bezier(0.86, 0, 0.07, 1), box-shadow 0.3s ease 0.7s;
    transition: transform 0.7s cubic-bezier(0.86, 0, 0.07, 1), box-shadow 0.3s ease 0.7s, -webkit-transform 0.7s cubic-bezier(0.86, 0, 0.07, 1);
}

.sidebar-expanded [data-toggle="sidebar"] i:before {
    content: "\f00d";
}

.sidebar-menu [data-toggle="sidebar"]:hover {
    border-radius: 60%;
}

.chat-list {
    list-style: none;
    padding: 0;
    margin: 12px 5px 0;
    max-height: 100%;
}

.chat-list li {
    position: relative;
}

.chat-list li>a {
    display: block;
    padding: 8px 15px;
    border-radius: 6px;
    color: rgba(255, 255, 255, 0.4);
    font-size: 0.875em;
}

.chat-list li>a .avatar {
    position: relative;
    top: -1px;
    width: 20px;
    height: 20px;
    display: inline-block;
    vertical-align: middle;
    margin-right: 10px;
}

.chat-list li>a:hover {
    background-color: rgba(255, 255, 255, 0.05);
}

.chat-list li a:active {
    background-color: rgba(255, 255, 255, 0.025);
}

.chat-list li+li {
    margin-top: 4px;
}

.list {
    list-style: none;
    padding: 0;
    margin: 12px 5px 0;
    max-height: 100%;
}

.list li a {
    display: block;
    padding: 8px 15px;
    border-radius: 6px;
    color: rgba(255, 255, 255, 0.4);
    font-size: 0.875em;
}

.list li a .avatar {
    position: relative;
    top: -1px;
    width: 20px;
    height: 20px;
    display: inline-block;
    vertical-align: middle;
    margin-right: 10px;
}

.list li a:hover {
    background-color: rgba(255, 255, 255, 0.05);
}

.list li a:active {
    background-color: rgba(255, 255, 255, 0.025);
}

.list li+li {
    margin-top: 4px;
}

.friend-list {
    background-color: #172c48;
    border-radius: 6px;
    padding: 5px;
    min-height: 120px;
    max-height: calc(50vh - 240px);
    overflow: hidden;
}

.friend-list .list {
    margin: 0;
}

.groups-list {
    background-color: #172c48;
    border-radius: 6px;
    padding: 5px;
    min-height: 120px;
    max-height: calc(50vh - 240px);
    overflow: hidden;
}

.groups-list .list {
    margin: 0;
}

.user {
    display: -webkit-box;
    display: -ms-flexbox;
    display: flex;
    -webkit-box-align: center;
    -ms-flex-align: center;
    align-items: center;
    padding: 5px 20px;
    font-weight: 700;
    color: #fff;
    background-color: rgba(255, 255, 255, 0.1);
}

.user .avatar {
    position: relative;
    margin-right: 10px;
}

.user .avatar img {
    border-radius: 100%;
    height: 15px;
}

.user .avatar:before {
    content: "";
    position: absolute;
    bottom: -3.5px;
    right: -3.5px;
    background-color: #22c287;
    border: 3px solid #2F425B;
    border-radius: 100%;
    width: 14px;
    height: 14px;
    z-index: 2;
}

.page-header {
    padding: 10px 15px;
    background-color: hwb(0 100% 0% / 0.103);
    margin: 0;
    border: 0;
}

.page-header ul {
    float: right;
    margin-bottom: 0;
    padding: 0;
    list-style: none;
}

.page-header ul li {
    display: inline-block;
    margin-left: 10px;
}

.page-header ul li a {
    font-size: 0.75em;
    font-weight: 700;
    color: #fff;
    text-transform: uppercase;
}

.page-header ul li a:hover {
    color: #fff;
}

.page-header ul li:last-of-type a:hover {
    color: #35ecd3;
}

.page-header>span {
    color: #ffffff;
    font-weight: 700;
}

.chat-body {
    height: calc(100% - 175px);
    margin: 15px;
    overflow: hidden;
}

.chat-message {
    padding: 20px 0;
    margin: 0;
}

.chat-message+.chat-message {
    border-top: 1px solid rgba(255, 255, 255, 0.05);
}

.chat-message .avatar {
    width: 40px;
    height: 40px;
    margin-right: 20px;
    float: left;
}

.chat-message-content {
    line-height: 1.44;
    overflow: hidden;
    color: rgba(255, 255, 255, 0.4);
}

.chat-message-author {
    color: #fff;
    font-weight: 700;
    display: inline-block;
    margin-right: 4px;
}

.chat-message-date {
    font-size: 0.875em;
}

.chat-message-author:hover {
    color: #35ecd3;
}

.chat-message .chat-message-message {
    color: rgba(255, 255, 255, 0.8);
}

.avatar {
    position: relative;
    height: 30px;
    width: 30px;
    border-radius: 100%;
    z-index: 2;
}

.avatar img {
    position: absolute;
    top: 50%;
    left: 50%;
    -webkit-transform: translateY(-50%) translateX(-50%);
    transform: translateY(-50%) translateX(-50%);
    -o-object-fit: cover;
    object-fit: cover;
    max-width: 100%;
    min-height: 100%;
    height: 40px;
    min-width: 100%;
    border-radius: 100%;
}

.avatar .little_avatar {
    height: 20px;
}

.chat-footer {
    padding: 30px;
    background-color: #10243E;
}

.chat-footer input {
    background: rgba(255, 255, 255, 0.05);
    border: 0;
    width: 100%;
    height: 50px;
    border-radius: 6px;
    padding: 6px 20px;
}

.chat-footer input:focus {
    background: rgba(255, 255, 255, 0.06);
}

.chat-footer input::-webkit-input-placeholder {
    color: rgba(255, 255, 255, 0.4);
}

.chat-footer input::-moz-placeholder {
    color: rgba(255, 255, 255, 0.4);
}

.chat-footer input:-ms-input-placeholder {
    color: rgba(255, 255, 255, 0.4);
}

.chat-footer input::placeholder {
    color: rgba(255, 255, 255, 0.4);
}

.tooltip-inner {
    min-width: 120px;
    font-weight: 700;
    font-family: "Circular Std", sans-serif;
    padding: 6px 10px;
}

.invitation {
    position: absolute;
    top: 50%;
    left: 50%;
    -webkit-transform: translateY(-50%) translateX(-50%) scale(0.5);
    transform: translateY(-50%) translateX(-50%) scale(0.5);
    opacity: 0;
    width: 100%;
    max-width: 600px;
    -webkit-animation: bounce-invitation 0.3s cubic-bezier(0.175, 0.885, 0.32, 1.275) forwards 0.6s;
    animation: bounce-invitation 0.3s cubic-bezier(0.175, 0.885, 0.32, 1.275) forwards 0.6s;
}

.invitation-header {
    background-color: #0d1d31;
    padding: 15px 15px;
    text-align: center;
    font-family: "uni_sansheavy_caps", sans-serif;
    font-size: 1.25em;
    border-radius: 10px 10px 0 0;
}

.invitation-info {
    background-color: #0f2239;
    display: -webkit-box;
    display: -ms-flexbox;
    display: flex;
}

.invitation-info .col {
    -webkit-box-flex: 1;
    -ms-flex: 1;
    flex: 1;
    padding: 30px;
    text-align: center;
    display: -webkit-box;
    display: -ms-flexbox;
    display: flex;
    -webkit-box-align: center;
    -ms-flex-align: center;
    align-items: center;
    -webkit-box-pack: center;
    -ms-flex-pack: center;
    justify-content: center;
    -webkit-box-orient: vertical;
    -webkit-box-direction: normal;
    -ms-flex-direction: column;
    flex-direction: column;
}

.invitation-info .col:last-of-type {
    background-color: #0d1d31;
}

.invitation-info .col:last-of-type h6 {
    font-family: "uni_sansheavy_caps", sans-serif;
    font-size: 1.25em;
}

.invitation .group-avatar {
    position: relative;
    width: 100px;
    height: 100px;
    margin: 0 auto;
}

.invitation .group-avatar img {
    position: absolute;
    top: 50%;
    left: 50%;
    -webkit-transform: translateX(-50%) translateY(-50%);
    transform: translateX(-50%) translateY(-50%);
    max-width: 100%;
    min-width: 100%;
    min-height: 100%;
    border-radius: 100%;
}

.invitation .group-stats {
    list-style: none;
    padding: 0;
    margin: 0 0 25px;
}

.invitation .group-stats li {
    color: rgba(255, 255, 255, 0.6);
}

.invitation-join .btn {
    padding: 10px 32px;
    font-size: 1.5em;
    border-radius: 0 0 10px 10px;
}

@-webkit-keyframes bounce-invitation {
    100% {
        -webkit-transform: translateY(-50%) translateX(-50%) scale(1);
        transform: translateY(-50%) translateX(-50%) scale(1);
        opacity: 1;
    }
}

@keyframes bounce-invitation {
    100% {
        -webkit-transform: translateY(-50%) translateX(-50%) scale(1);
        transform: translateY(-50%) translateX(-50%) scale(1);
        opacity: 1;
    }
}

.decline {
    font-weight: 700;
    font-size: 0.875em;
    color: #ff355a;
}

.decline:hover {
    color: #ff355a;
    text-decoration: underline;
}

.decline.link-underline:before {
    background-color: #ff355a;
}

.link-underline {
    text-underline: none;
    position: relative;
    -webkit-transition: color 0.4s cubic-bezier(0.7, 0, 0.3, 1);
    transition: color 0.4s cubic-bezier(0.7, 0, 0.3, 1);
}

.link-underline:hover {
    color: #fff !important;
    text-decoration: none !important;
}

.link-underline:before {
    content: "";
    position: absolute;
    bottom: -2px;
    right: 0;
    width: 0;
    height: 1px;
    background-color: #35ecd3;
    -webkit-transition: width 0.4s cubic-bezier(0.7, 0, 0.3, 1), background-color 0.3s ease;
    transition: width 0.4s cubic-bezier(0.7, 0, 0.3, 1), background-color 0.3s ease;
}

.link-underline:hover:before {
    left: 0;
    right: auto;
    width: 100%;
    background-color: #fff;
}

.caret-right {
    position: relative;
    left: -1px;
    width: 6px;
    height: 6px;
    display: block;
    border-right: 2px solid #fff;
    border-bottom: 2px solid #fff;
    -webkit-transform: rotate(-45deg);
    transform: rotate(-45deg);
}

.post-button {
    position: absolute;
    right: 45px;
    top: 50%;
    -webkit-transform: translateY(-50%) scale(0.5);
    transform: translateY(-50%) scale(0.5);
    background: #12c2aa;
    border-radius: 60%;
    width: 24px;
    height: 24px;
    display: -webkit-box;
    display: -ms-flexbox;
    display: flex;
    -webkit-box-align: center;
    -ms-flex-align: center;
    align-items: center;
    -webkit-box-pack: center;
    -ms-flex-pack: center;
    justify-content: center;
    border: 0;
    color: #fff;
    opacity: 0;
    -webkit-transition: all 0.3s cubic-bezier(0.68, -0.55, 0.265, 1.55);
    transition: all 0.3s cubic-bezier(0.68, -0.55, 0.265, 1.55);
}

.post-input:focus+.post-button {
    opacity: 1;
    -webkit-transform: translateY(-50%) scale(1);
    transform: translateY(-50%) scale(1);
}

.modal-block-wrap {
    position: fixed;
    top: 0;
    left: 0;
    right: 0;
    bottom: 0;
    display: none;
    z-index: 101;
    pointer-events: auto;
}

.modal-block {
    overflow: hidden;
    border-radius: 10px;
    position: absolute;
    left: 50%;
    top: 50%;
    -webkit-transform: translateX(-50%) translateY(-50%) scale(0.7);
    transform: translateX(-50%) translateY(-50%) scale(0.7);
    opacity: 0;
    visibility: hidden;
    -webkit-transition: opacity 0.3s ease, visibility 0.3s ease, -webkit-transform 0.3s cubic-bezier(0.175, 0.885, 0.32, 1.275);
    transition: opacity 0.3s ease, visibility 0.3s ease, -webkit-transform 0.3s cubic-bezier(0.175, 0.885, 0.32, 1.275);
    transition: opacity 0.3s ease, visibility 0.3s ease, transform 0.3s cubic-bezier(0.175, 0.885, 0.32, 1.275);
    transition: opacity 0.3s ease, visibility 0.3s ease, transform 0.3s cubic-bezier(0.175, 0.885, 0.32, 1.275), -webkit-transform 0.3s cubic-bezier(0.175, 0.885, 0.32, 1.275);
    width: 100%;
    max-width: 660px;
    background-color: #1c2f48;
    box-shadow: 0 0 24px rgba(17, 17, 26, 0.4);
    display: -webkit-box;
    display: -ms-flexbox;
    display: flex;
    z-index: 101;
}

.modal-block-content {
    background-color: inherit;
    padding: 50px 30px 50px 42px;
    -webkit-box-flex: 1;
    -ms-flex: 1;
    flex: 1;
}

.modal-block h3 {
    font-family: "uni_sansheavy_caps", sans-serif;
    font-size: 1.25em;
}

.modal-close {
    position: absolute;
    top: 15px;
    right: 15px;
    cursor: pointer;
}

.modal-close:hover {
    opacity: 0.7;
}

.modal-close:active:focus {
    opacity: 0.3;
}

.modal-visible {
    opacity: 1;
    visibility: visible;
    -webkit-transform: translateX(-50%) translateY(-50%) scale(1);
    transform: translateX(-50%) translateY(-50%) scale(1);
}

.modal-is-open {
    pointer-events: none;
}

.modal-is-open .page {
    -webkit-filter: blur(5px);
    filter: blur(5px);
}

.modal-is-open .modal-visible {
    opacity: 0;
    visibility: hidden;
}

.modal-open {
    display: block;
}

.modal-block-open {
    -webkit-transform: translateX(-50%) translateY(-50%) scale(1);
    transform: translateX(-50%) translateY(-50%) scale(1);
    opacity: 1;
    visibility: visible;
    pointer-events: auto;
}

.modal-brand {
    position: relative;
    min-width: 150px;
    background-color: #12c2aa;
}

.modal-brand:before {
    content: "";
    position: absolute;
    top: 0;
    right: 1px;
    height: 100%;
    width: 16px;
    background: url("../img/border.svg") no-repeat center left;
    -webkit-transform: translateX(100%);
    transform: translateX(100%);
    background-size: 100%;
}

.modal-brand-caption {
    position: absolute;
    left: 50%;
    top: 50%;
    -webkit-transform: translateX(-50%) translateY(-50%);
    transform: translateX(-50%) translateY(-50%);
    width: 100%;
    text-align: center;
    padding: 30px 15px 30px 27px;
}

.modal-brand-caption .logo {
    font-size: 2.5em;
    line-height: 1;
    font-family: "uni_sansheavy_caps", sans-serif;
    pointer-events: none;
    -webkit-user-select: none;
    -moz-user-select: none;
    -ms-user-select: none;
    user-select: none;
}

.modal-brand-caption .logo>span {
    margin-top: -6px;
    display: block;
    font-size: 1.25em;
}

.help-block {
    font-family: "uni_sansheavy_caps", sans-serif;
    font-size: 0.75em;
    letter-spacing: 0.05em;
    margin-bottom: 5px;
}

.help-block a {
    color: #ffffff;
}

.help-block .link-underline:before {
    background-color: #fff;
}

.help-block2 {
    color: #687A92;
    font-size: 0.875em;
    font-weight: 700;
}

.help-block2 a.clr-primary:hover {
    color: #35ecd3;
}

.form-horizontal {
    margin-top: 30px;
}

.form-horizontal .form-group {
    position: relative;
    margin-left: 0;
    margin-right: 0;
}

.form-horizontal .form-group:before {
    content: "";
    position: absolute;
    right: 0;
    bottom: 0;
    width: 0;
    height: 2px;
    background-color: #35ecd3;
    -webkit-transition: width 0.7s cubic-bezier(0.19, 1, 0.22, 1);
    transition: width 0.7s cubic-bezier(0.19, 1, 0.22, 1);
}

.form-group.is-focus:before {
    width: 100%;
    left: 0;
}

label,
.label {
    display: inline-block;
    font-family: "uni_sansheavy_caps", sans-serif;
    font-size: 0.75em;
    letter-spacing: 0.075em;
    color: #687A92;
    padding: 0;
}

.form-control {
    border: 0;
    background: transparent;
    border-radius: 0;
    border-bottom: 2px solid #324052;
    color: #fff;
    height: 46px;
    padding: 10px 0;
}

.form-control:focus {
    box-shadow: none;
    border-color: #324052;
}

.profile-body {
    height: calc(100% - 40px);
    padding: 30px 15px;
    background-color: rgba(44, 44, 44, 0.5);
}

.avatar-placeholder {
    width: 100%;
    height: 100%;
}

.avatar-placeholder img {
    max-width: 100%;
    width: 100%;
    margin: 0 auto;
}

.profile-photo[type="file"],
.profile-photo {
    display: none;
}

.profile-photo-placeholder {
    position: relative;
    overflow: hidden;
    width: 48px;
    height: 48px;
    border-radius: 100%;
    background: #DCDCDD;
    margin-top: 0;
    cursor: pointer;
    display: block;
}

.group-photo[type="file"],
.group-photo {
    display: none;
}

.group-photo-placeholder {
    position: relative;
    overflow: hidden;
    width: 48px;
    height: 48px;
    border-radius: 100%;
    background: #DCDCDD;
    margin-top: 0;
    cursor: pointer;
    display: block;
}

.menu {
    position: absolute;
    left: 0;
    top: 100%;
    background-color: #0A1C35;
    padding: 4px;
    border-radius: 6px;
    min-width: 100%;
    z-index: 101;
    margin-top: 10px;
    opacity: 0;
    -webkit-transition: opacity .3s ease;
    transition: opacity .3s ease;
}

.menu:before {
    content: "";
    position: absolute;
    left: 20px;
    top: -6px;
    width: 12px;
    height: 12px;
    border-top-left-radius: 6px;
    -webkit-transform: rotate(45deg);
    transform: rotate(45deg);
    background-color: inherit;
}

.menu li a {
    padding: 4px 12px;
    color: #fff;
}

.menu li a:hover {
    background: transparent;
    color: rgba(255, 255, 255, 0.75);
}

.menu li a:active {
    background: transparent;
    color: rgba(255, 255, 255, 0.5);
}

.menu-open {
    opacity: 1;
}


/*** Main End ***/


/*** Buttons Start ***/

.btn {
    font-family: "uni_sansheavy_caps", sans-serif;
    font-weight: 700;
    padding: 10px 24px;
    -webkit-transition: background-color .3s ease, color .3s ease;
    transition: background-color .3s ease, color .3s ease;
}

.btn-radius {
    -webkit-transition: border-radius 0.4s cubic-bezier(1, 0.885, 0.32, 1.275);
    transition: border-radius 0.4s cubic-bezier(1, 0.885, 0.32, 1.275);
}

.btn-radius:hover {
    border-radius: 60px;
}

.btn-primary,
.btn-primary:focus {
    background-color: #12c2aa;
    border: 0;
    color: #fff;
}

.btn-primary:hover,
.btn-primary:active:focus {
    background-color: #10ab96;
    color: #fff;
}


/*** Buttons End ***/


/*** Misc Start ***/

.container-fluid {
    width: 100%;
}

.front {
    z-index: 4;
}

.page-content {
    padding: 100px 0;
}

.page-content-sm {
    padding: 75px 0;
}

.overflow-h {
    overflow: hidden;
}

.relative {
    position: relative;
}

.valign {
    display: -webkit-box;
    display: -ms-flexbox;
    display: flex;
    -webkit-box-align: center;
    -ms-flex-align: center;
    align-items: center;
    -ms-flex-wrap: wrap;
    flex-wrap: wrap;
}

.valign>div {
    float: none;
}

.valign {
    display: -webkit-flex;
    -webkit-flex-wrap: wrap !important;
}

.valign:before,
.valign:after {
    width: 0;
}

.vh-100 {
    min-height: 100vh;
    height: 100vh;
}

.vh-75 {
    min-height: 75vh;
    height: 75vh;
}

.vh-50 {
    min-height: 50vh;
    height: 50vh;
}

.vh-25 {
    min-height: 25vh;
    height: 25vh;
}

div[class].vh-100,
div[class].vh-75,
div[class].vh-50,
div[class].vh-25 {
    height: auto;
}

section[class].vh-100,
section[class].vh-75,
section[class].vh-50,
section[class].vh-25 {
    height: auto;
}

.bg-white {
    background-color: #ffffff;
}

.inline-block {
    display: inline-block;
}

*:focus {
    outline: 0 !important;
}


/*** Misc End ***/


/*** Footer Start ***/


/*** Footer End ***/