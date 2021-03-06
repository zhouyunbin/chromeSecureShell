# chromeSecureShell

I want to use chrome secure shell on Windows and Mac, but it doesn't satisfy my usual operatic habits.
So I improved it by adding more options.

1. Automatically login to SSH server: I add a new feature that can save the password in the local storage. It will automatically login in a server without typing the password.

2. Chinese characters typing. (You can use any input methods it depends on your system.)


# Demo Video
<a href="http://www.youtube.com/watch?v=6wygEEF8mDc" target="_blank">
  <img src="http://img.youtube.com/vi/6wygEEF8mDc/2.jpg">
</a>


# New Options

The following are the new options that I added for chrome SSH extension.

* meta-as-ctrl : Map the key command+v to ctrl+v on Mac.
* ctrl-v-paste-hacky : Force the key ctrl+v to paste content from the clipboard.
* meta-plus-arrow-switch-tab :
* ctrl-plus-arrow-switch-tab :
* enable-input-method: Enable the ime-mode for entering chinese characters. (使用方式為: 先勾選 enable-input-metod，然後就可以在 Terminal 輸入中文，各種輸入法都能使用。)

# How to install

* git clone git@github.com:puritys/chromeSecureShell.git
* Open the browser chrome and keyin the value "chrome://extensions/" into URL bar.
* Click the checkbox of developer mode to enable developer mode.
* Click the button "Load unpacked extension" and choose the directory "chromeSecureShell"
 

# 安裝方式

本來想建一個新的  SSH Client V2 到 Google Chrome Extension ，但是 SSH Client 有用到一個 Native Plugin 叫 Terminal Private ，這個 Plugin 並不是 public ，所以目前只能用開發者模式來安裝，安裝方式如下。

* git clone git@github.com:puritys/chromeSecureShell.git
* 打開瀏覽器，輸入 "chrome://extensions/"。
* 在右上角，打開開發者模式。
* 點擊 "載入未封裝程式" ，再選擇資料夾 "chromeSecureShell"。

# 基本設定

安裝成功後，請打開 option，我有新加了一些設定，你可以自行決定哪些功能要打開：

* meta-as-ctrl : 將 Mac 的 command 變成 ctrl ，我習慣將 Mac 的 command 與 ctrl 對調，變成 ctrl+c 中斷功能失效，所以這個功能就是不管 command 還是 ctrl ，都當是成 ctrl。
* ctrl-v-paste-hacky : 我習慣將 Mac 的 command 與 ctrl 對調，所以新增這個功能，強迫 Ctrl + v 為貼上，剛好負負得正，原 Mac command + v 也會保留貼上功能。
* meta-plus-arrow-switch-tab : [command + 左右方向鍵]，切換 tab
* ctrl-plus-arrow-switch-tab : [ctrl + 左右方向鍵]，切換 tab
* enable-input-method: 啟用這個功能，就可以在 Terminal 輸入中文，各種輸入法都能使用。





