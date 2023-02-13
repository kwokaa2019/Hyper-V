
</div>

<h3><a id="top1"></a>Windows 10 Home版沒有內建Hyper-V</h3>
<p>Windows 10專業版預設的情形下是沒有自動安裝Hyper-V，所以進入「設定應用程式」畫面，選擇應用程式（紅色框）。</p>
<p><img src="https://i0.wp.com/image.walker-a.com/2021/06/hyperv/hv-02.jpg?w=1200&#038;ssl=1" alt="Hyper-V" data-recalc-dims="1" /></p>
<p>&nbsp;</p>
<p>在「應用程式與功能」頁面上捲動「相關設定」下方，點選「程式和功能」。</p>
<p><img src="https://i0.wp.com/image.walker-a.com/2021/06/hyperv/hv-03.jpg?w=1200&#038;ssl=1" alt="Hyper-V" data-recalc-dims="1" /></p>
<p>&nbsp;</p>
<p>預設的情形下是沒有自動安裝Hyper-V，所以進入「程式和功能」畫面上，點選「開啟或關閉Windows功能」，在出現的視窗上找到「Hyper-V」服務程式，請勾選後按下〔確定〕來安裝。</p>
<p><img src="https://i0.wp.com/image.walker-a.com/2021/06/hyperv/hv-04.jpg?w=1200&#038;ssl=1" alt="Hyper-V" data-recalc-dims="1" /><div class="walke-content-1" 
<p>&nbsp;</p>
<p>&nbsp;</p>

<p>Windows 10 Home內建找遍了整個應用程式，似乎看不到Hyper-V的蹤影，那到底Windows 10 Home家用版是有否支援呢？</p>
<p><img src="https://i0.wp.com/image.walker-a.com/2021/07/homehy/hy-06.jpg?w=1200&#038;ssl=1" alt="Hyper-V" data-recalc-dims="1" /></p>
<p>&nbsp;</p>
<h3><a id="top2"></a>檢查Hyper-V環境</h3>
<p>為了確認Windows 10的系統是否可運行Hyper-V，所以先來查看Windows系統資訊內容，首先【Windows key + R】後輸入「cmd」。</p>
<p><img src="https://i0.wp.com/image.walker-a.com/2021/07/homehy/hy-02.jpg?w=1200&#038;ssl=1" alt="Hyper-V" data-recalc-dims="1" /></p>
<p>&nbsp;</p>
<p>這時「命令提示字元」輸入指令 SystemInfo 輕鬆列出各種資訊。</p>
<p><img src="https://i0.wp.com/image.walker-a.com/2021/07/homehy/hy-03.jpg?w=1200&#038;ssl=1" alt="Hyper-V" data-recalc-dims="1" /></p>
<p>&nbsp;</p>
<p>看到一直捲動的資訊不用理會，哪不是重點，在底端看到「Hyper-V需求」項目中，的四個條件都要顯示為「是」，表示即使是Windows 10 Home版也具有Hyper-V的環境。</p>
<p><img src="https://i0.wp.com/image.walker-a.com/2021/07/homehy/hy-04.jpg?w=1200&#038;ssl=1" alt="Hyper-V" data-recalc-dims="1" /></p>
<p>&nbsp;</p>
<h3><a id="top3"></a>手動安裝與移除Hyper-V</h3>
<p>確定有了Hyper-V的環境，接下來就是如何安裝，Windows 10 Pro有安裝項目可選，Windows 10 Home被隱藏起來了，山不轉路轉，只要點選<a href="https://mega.nz/file/fh4whaQJ#_dxxztEJyhrbEhxL3kBU5KtEnt5xDvN-cEzlt-Juq5o" target="_blank" rel="noopener">這裡</a>來下載install_hyper-v
.cmd (副檔名記得一定要是.cmd哦）</p>

<p>執行時須注意，必須要有較高的權限來執行，所以在檔案圖示上按下滑鼠右鍵使用「以系統管理員身分執行」。</p>
<p><img src="https://i0.wp.com/image.walker-a.com/2021/07/homehy/hy-11.jpg?w=1200&#038;ssl=1" alt="Hyper-V" data-recalc-dims="1" /></p>
<p>&nbsp;</p>
<p>執行中會一直看到指令一直跑（若沒有開始執行請按下一下〔Enter〕鍵），請看心等待安裝。</p>
<p><img src="https://i0.wp.com/image.walker-a.com/2021/07/homehy/hy-13.jpg?w=1200&#038;ssl=1" alt="Hyper-V" data-recalc-dims="1" /></p>
<p>&nbsp;</p>
<p>安裝完後會詢問是否要重新開機，按「Y」來重新開機。</p>
<p><img src="https://i0.wp.com/image.walker-a.com/2021/07/homehy/hy-16.jpg?w=1200&#038;ssl=1" alt="Hyper-V" data-recalc-dims="1" /></p>
<p>&nbsp;</p>
<p>重新開機後，使用搜尋欄上即可找到「Hyper-V 管理員」，表示手動安裝成功。</p>
<p><img src="https://i0.wp.com/image.walker-a.com/2021/07/homehy/hy-17.jpg?w=1200&#038;ssl=1" alt="Hyper-V" data-recalc-dims="1" /></p>
<p>&nbsp;</p>
<p>來執行看看，果然可以運作正常。</p>
<p><img src="https://i0.wp.com/image.walker-a.com/2021/07/homehy/hy-18.jpg?w=1200&#038;ssl=1" alt="Hyper-V" data-recalc-dims="1" /><div class='code-block code-
