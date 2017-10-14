---
layout: post
title:  "LevelUp 中文網站上線！10/07更新"
date:   2017-10-07 08:32:25 +0800
categories: levelup update
---

去年最花時間投入的二個在地化翻譯專案，到頭來回顧，都是蠻好的失敗教訓，畢竟失敗這回事佔滿了人生的十之八九。
但還是稍心有不甘地想繼續賭氣，於是回過頭來整理去年譯成的初稿，算是把它們告一段落終結。

除了 Umbrella-app 之外，另一個就是[LevelUp](https://level-up.cc)（請見去年所留下的記錄[數位安全訓練員教材中文化初稿](http://self.jxtsai.info/2016/08/level-up.html)）。

最近整理完 [Umbrella-app](https://github.com/twngo/Umbrella_content) 之後，以為自己對於 Jekyll 這個靜態網頁產生器更熟悉了，可以再來替 Level-Up 「撿骨」一下。不過這個檢骨工程不太順利，原來整套放在 transifex 上的原文，大約只佔了20%(純「感覺」的推估)，更何況因為 LevelUp 強調自身為一份與時俱進的文件，所以....(雖然網站內容一年多沒更新了)，許多文件必須重頭做起。

level up 的網站內容架構是以：1)身為安全訓練員 you-the-trainer　2)活動之前　before-an-event 3)活動之後　after-an-event 4)上課內容　curriculum 5)支援社群　community ，這五大單元為主，五大單元底下再分枝出：

**1. you the trainer**
- be a better trainer 
- first 3 sessions of your event
  -  developing-a-shared-brain
  -  developing-shared-agreements
  -  sharing-your-story
- golden rules of effective training　（Ｏ）
- how to handle surprises during training　
- ice breakers and energizers
- roles and responsibilities of a digital security trainer　 （Ｏ）
- setting expectations for participants organizers and yourself （V）

**2. before an event （Ｏ）** 


**3. curriculum**
- malware protection
  - safer software updating (ADIDS)
  - using antivirus tools (ADIDS)
- mobile safety
  - how mobile networks work (ADIDS)
- protecting data
  - creating and managing strong passwords (ADIDS)
  - data backup basics (ADIDS) 
- safer browsing
  - anonymity and circumvention (ADIDS)
  - https ssl (ADIDS) 
  - identity protection privacy (ADIDS)
- safer communication
  - pgp gpg email encryption (ADIDS)
- safer workspaces
  - Tails (ADIDS)
- social media safety （V）
 - social media safety awareness (ADIDS)

**4. after an event （Ｏ）**

**5. community （Ｏ）**

畫（Ｏ）的部份完成中文初稿。至於剩下，暫時沒什麼心情或急迫性想弄它，就先放著吧....

### jekyll 問題

levelup.cc 使用　jekyll　建置，所以我下載了原始文檔後（或 fork 原資源庫），只須把解壓過的檔案全部複製到本地電腦上新建、空白的 jekyll 專案上即可快速順利克隆出同樣外觀模版的網站。不過一直查不出為何在自動把 MarkDown 轉成 html 時，(/communiyt/community.md) 卻傳回無法找到其對應的鍵：

    Error reading file 
     ..../levelup/community/community.md: (<unknown>): 
    did not find expected key while parsing a block mapping ...
    
所以無法順利讓 community 及其底下的文章成功地出現上方選單位置（雖然有轉成 html）。於是乎就賭氣地用了手動貼上的笨方法，以紙糊的方式把這個中文網站做了出來　Σ(￣□￣；

### 瀏覽器呈現
不曉得是否因為原模版設計者未考慮不同瀏覽器底下的呈現效果，有些網頁在 FireFox 底下會「被擠出來」，用 Chrome 就順眼許多。就連這篇文章（post）在 Chrome 底下也是亂七八糟(╯-_-)╯ ~╩╩　，若不是....還蠻想另換個主題。（說說碎念而已，別怕。）


