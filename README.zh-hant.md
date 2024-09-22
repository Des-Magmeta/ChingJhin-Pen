# ChingJhin Pen | 青衿楷  
An open source CJK font devired from Fontworks' Klee One.

## Introduction / 專案簡介
> 青青子衿，悠悠我心。縱我不往，子寧不嗣音？——《詩經》

2020 年 12 月，日本著名字體廠商 FONTWORKS 在 GitHub 上釋出了 [7 款開源日文字體](https://github.com/fontworks-fonts)，其中 [Klee One](https://github.com/fontworks-fonts/Klee) 字元數最多，兼有仿宋和楷體的特點，具有優雅的外觀及較高的可讀性，非常適合內文排版。與一般的教科書體相比，Klee One 保留了傳統印刷體的一些特徵。2021 年，[LXGW](https://github.com/lxgw) 在其基礎上增補和修改字形，製成[「霞鶩文楷」/ LXGW WenKai](https://github.com/lxgw/LxgwWenKai) 字體，受到廣泛歡迎。除此之外，一些字體設計師/愛好者也製作了其他的衍生版本，如[「芫荽」/ Iansui](https://github.com/ButTaiwan/iansui)、[「芫茜雅楷」/ JyunsaiKaai](https://github.com/ItMarki/jyunsaikaai) 等。在字體設計師/愛好者的努力下，一系列基於 Klee One 衍生的字體支持的字元數遠大於原有的字元數。
然而，不同字形之間的統合是一個問題。有的和原字型 Klee One 或其他衍生專案共用同一字形，有的卻做出了修改。對於 Klee One 不包含的字，新補的字之間的設計比例、設計間架具有一定的差異。這些新補字在不同字型對照時較為明顯。在大字符集和標準規範之間，字形統合成了亟待解決的問題。

我們希望能夠製作出一個類似於思源黑體、思源宋體那樣的大字符集和字形整合兼備的字體，為此本項目誕生了。

青衿楷是一套 TrueType 泛中日韓字體，支持四種不同的東亞語言（簡體中文、繁體中文、日文和韓文），其中，繁體中文又分為臺灣繁體和香港繁體。5 種粗細類型中的每一種都有約 5 萬個字形，可共同呈現一致的視覺美感。該字體還包含多個西文字形，支持拉丁語、希臘語和西裏爾文文本，這些字形一部分來源於 Klee One，一部分來源於霞鶩文楷以及其他的衍生字體。

在有些情況下，基於同一個原始表意文字的字可能有多達五個區域差異化的字形設計。該專案涵蓋所有這些字形變體並且精心地設計了這些區域化字形。在網頁／軟體支持字形變體的情況下，您只需選擇相應語言特定的字體或相應的語言標籤，正確的字形變體即可設置成功。

## Authorization / 授權資訊

本字體是基於 SIL Open Font License 1.1 改造的 FONTWORKS 開發併發布的 [Klee](https://github.com/fontworks-fonts/Klee) 開源專案。Klee 是 FONTWORKS 的商標。

### License / 許可  

- 這款字體無論是個人還是企業都可以自由商用，無需付費，也無需知會或者標明原作者。 *（但如果告知，我會很感激。）*
- 這款字體可以自由傳播、分享，或者將字體安裝於系統、軟體或 APP 中也是允許的，可以與任何軟體捆綁再分發以及／或一併銷售。
- 這款字體可以自由修改、改造，製作衍生字體。修改或改造後的字體也必須同樣以 [SIL OFL 1.1](https://scripts.sil.org/OFL) 公開。

### Limit / 限制  

- 在製作衍生字型時，其名稱不可使用原有字型的「保留名稱」。此字型保留名稱
<span lang="zh-cn">「青衿楷」</span>
<span lang="zh-tw">「青衿楷」</span>
<span lang="ja-jp">「セイキン楷書」</span>「Ching Jhin Pen」，基於此字型二次衍生的專案，名稱中不可出現保留名稱
<span lang="zh-cn">「青衿楷」</span>
<span lang="zh-tw">「青衿楷」</span>
<span lang="ja-jp">「セイキン楷書」</span>
或「Ching Jhin Pen」；而在沒有對字型源代碼進行修改的情況下，重新編譯出來的字型，可以繼續使用此字型的保留名稱。
- 根據 [SIL Open Font License 1.1](https://scripts.sil.org/OFL) 許可與條件中第一條的規定， **禁止單獨出售字型檔(OTF/TTF 檔)的行為。**
- 該字體不可在 [SIL Open Font License 1.1](https://scripts.sil.org/OFL) 以外的授權許可下發行。

## Acknowledgement / 鳴謝

- [FONTWORKS 株式會社](http://fontworks.co.jp) 提供原版開源字型（見[開發者 GitHub 主頁](https://github.com/fontworks-fonts/)）；  
- [白易](https://github.com/yi-bai)開發的網站[字統網](https://zi.tools)提供各地區標準字形參考；  
- [Shs-cid](https://github.com/NightFurySL2001/shs-cid) 提供思源黑體、思源宋體映射參考；  
- [LXGW](https://github.com/lxgw) 提供中國大陸標準字型、韓文部分字型；  
- [ButTaiwan](https://github.com/ButTaiwan) 提供臺灣標準字型；  
- [ItMarki](https://github.com/ItMarki) 提供香港標準字型；  
- [Steve-Yuu](https://github.com/Steve-Yuu/YshiPen-Shuti) 提供相關字型。
