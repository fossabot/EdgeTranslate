# 側邊翻譯

[![Version](https://img.shields.io/github/release/nickyc975/EdgeTranslate.svg?label=version)](https://github.com/nickyc975/EdgeTranslate/release)
[![Build Status](https://travis-ci.org/nickyc975/EdgeTranslate.svg?branch=master)](https://travis-ci.org/nickyc975/EdgeTranslate)
[![codebeat badge](https://codebeat.co/badges/7f28bc52-26ec-4dbc-815d-343220100c72)](https://codebeat.co/projects/github-com-nickyc975-edgetranslate-master)
[![License](https://img.shields.io/github/license/nickyc975/EdgeTranslate.svg?colorB=44cc11?maxAge=2592000)](https://github.com/nickyc975/EdgeTranslate/blob/master/LICENSE)

[![Chrome users](https://img.shields.io/chrome-web-store/users/bocbaocobfecmglnmeaeppambideimao.svg?label=Chrome%20users)](https://chrome.google.com/webstore/detail/bocbaocobfecmglnmeaeppambideimao)
[![Chrome stars](https://img.shields.io/chrome-web-store/stars/bocbaocobfecmglnmeaeppambideimao.svg?label=Chrome%20stars)](https://chrome.google.com/webstore/detail/bocbaocobfecmglnmeaeppambideimao)
[![Firefox users](https://img.shields.io/amo/users/edge_translate.svg?label=Firefox%20users)](https://addons.mozilla.org/firefox/addon/edge_translate/)
[![Firefox stars](https://img.shields.io/amo/stars/edge_translate.svg?label=Firefox%20stars)](https://addons.mozilla.org/firefox/addon/edge_translate/)

## 下載

[Chrome應用商店](https://chrome.google.com/webstore/detail/bocbaocobfecmglnmeaeppambideimao)
/ [Firefox附加組件商店](https://addons.mozilla.org/firefox/addon/edge_translate/)
/ [GitHub Release頁面](https://github.com/nickyc975/EdgeTranslate/releases)

## 構建擴展

構建本擴展需要安裝[Node.js](https://nodejs.org/)。

克隆倉庫：

    git clone https://github.com/nickyc975/EdgeTranslate.git

安裝依賴：

    npm install

構建Chrome擴展：

    npm run build:chrome

構建Firefox擴展：

    npm run build:firefox

構建完成之後在    ./build/chrome/    和    ./build/firefox/    文件夾下可分別找到Chrome擴展和Firefox擴展。

## 在瀏覽器中加載已解壓的擴展

### Chrome

* 在瀏覽器中訪問：    chrome://extensions    ；

* 開啓右上角的開發者模式；

* 點擊左上角的“加載已解壓的擴展程序”；

* 找到剛才克隆下來的倉庫，打開    build    文件夾，選擇其中的    chrome    文件夾；

* 現在你就可以在Chrome中體驗本擴展了。

### Firefox

* 在瀏覽器中訪問：    about:debugging    ；

* 選中該頁面上的“啓用附加組件調試”；

* 點擊“臨時載入附加組件”；

* 找到剛才克隆下來的倉庫，打開    build/firefox    , 選擇其中的任意一個文件；

* 現在你就可以在Firefox中體驗本擴展了。

## 瞭解更多

[Wiki](https://github.com/nickyc975/EdgeTranslate/wiki)

## 聯係我們

電子郵件: [chenjinlong2016@outlook.com](mailto:chenjinlong2016@outlook.com), [f18846188605@gmail.com](mailto:f18846188605@gmail.com)