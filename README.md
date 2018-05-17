# 0.安裝虛擬機

這裡是我個人的一個小筆記

記錄我一些在學習程式的過程

我會在虛擬機的環境中做練習

並在主機中開發

這裡我們虛擬機軟體選擇的是VirtualBox

先進到官網

{% embed data="{\"url\":\"https://www.virtualbox.org/\",\"type\":\"link\",\"title\":\"\n      Oracle VM VirtualBox\n    \",\"icon\":{\"type\":\"icon\",\"url\":\"https://www.virtualbox.org/graphics/VirtualBox.ico\",\"aspectRatio\":0}}" %}



![](.gitbook/assets/1.png)

把那個大大的 Download 給他點下去

再來找到紅框這個按下去就能下載啦

![](.gitbook/assets/2.png)

開始安裝

之後就是一直下一步下一步

不用特別設定什麼

![](.gitbook/assets/3.png)

安裝完成

![](.gitbook/assets/4.png)

好的~

目前VirtualBox已經安裝完成了

接下來是要裝我虛擬機要用的 Linux Mint Sylvia 64-bit

先到他的官網

然後進到這個畫面

並選擇Download

這裡我選擇的是紅框那個

{% embed data="{\"url\":\"https://linuxmint.com/\",\"type\":\"link\",\"title\":\"Main Page - Linux Mint\",\"description\":\"Linux Mint is an elegant, easy to use, up to date and comfortable GNU/Linux desktop distribution.\",\"icon\":{\"type\":\"icon\",\"url\":\"https://linuxmint.com/favicon.ico\",\"aspectRatio\":0}}" %}

![](.gitbook/assets/5.png)

進到下載的畫面

往下拉找台服的會下載比較快哦~

![](.gitbook/assets/6.png)

下載完成

這是一個光碟映像檔

![](.gitbook/assets/7.png)

接下來回到VirtualBox

選擇新增

![](.gitbook/assets/8.png)

然後設定一下名稱和作業系統

這裡我稍微爬了個文

發現原來 Mint 是基於 Ubuntu 而開發出來的

那我在這邊就選擇 Ubuntu 64-bit

![](.gitbook/assets/9.png)

接下來就是一連串的下一步

全部都用預設值

除了 RAM

我發現 1024MB 好像有點卡

就把它設定到 2048MB 了

![](.gitbook/assets/10.png)

完成之後

現在要來改它的設定值

點選設定

![](.gitbook/assets/18.png)

找到存放位置 -&gt; IDE

右邊有個光碟的小圖示

點進去 -&gt; 選擇虛擬光碟檔案

![](.gitbook/assets/15.png)

找到剛剛存放iso檔的位置並選取

![](.gitbook/assets/16.png)

接下來到網路這邊

把附加到這個選項

改為橋接介面卡

以便使用現有網路環境

![](.gitbook/assets/17.png)

接下來就設定完成啦~

在紅框處點兩下開啟虛擬機

![](.gitbook/assets/19.png)

接著再安裝

就結束啦~

![](.gitbook/assets/0.png)

---更新---

我發現原先用的 Cinnamon 很吃顯卡

於是我換了 Mate

安裝方法一樣

![](.gitbook/assets/20.png)

