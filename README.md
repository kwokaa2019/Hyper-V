
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
<p><img src="https://i0.wp.com/image.walker-a.com/2021/07/homehy/hy-18.jpg?w=1200&#038;ssl=1" alt="Hyper-V" data-recalc-dims="1" /><div class='code-block code-block-5' style='margin: 8px 0; clear: both;'>
<script async src="https://pagead2.googlesyndication.com/pagead/js/adsbygoogle.js?client=ca-pub-1178754458536026"
     crossorigin="anonymous"></script>
<ins class="adsbygoogle"
     style="display:block; text-align:center;"
     data-ad-layout="in-article"
     data-ad-format="fluid"
     data-ad-client="ca-pub-1178754458536026"
     data-ad-slot="5876192061"></ins>
<script>
     (adsbygoogle = window.adsbygoogle || []).push({});
</script></div>
</p>
<p>&nbsp;</p>
<p>手動安裝完後想要移除怎麼辦？不用緊張，當然也是要手動移除，一樣在桌面上建立一個文件檔，自訂名稱後注意附檔名也是要cmd。</p>
<p><img src="https://i0.wp.com/image.walker-a.com/2021/07/homehy/hy-20.jpg?w=1200&#038;ssl=1" alt="Hyper-V" data-recalc-dims="1" /></p>
<p>&nbsp;</p>

<p>執行一樣要使用「以系統管理員身分執行」。</p>
<p><img src="https://i0.wp.com/image.walker-a.com/2021/07/homehy/hy-22.jpg?w=1200&#038;ssl=1" alt="Hyper-V" data-recalc-dims="1" /></p>
<p>&nbsp;</p>
<p>移除後會詢問是否要重新開機，按「Y」來重新開機，重新開機後就找不到「Hyper-V 管理員」了。</p>
<p><img src="https://i0.wp.com/image.walker-a.com/2021/07/homehy/hy-23.jpg?w=1200&#038;ssl=1" alt="Hyper-V" data-recalc-dims="1" /></p>
<p>&nbsp;</p>
<p>不過移除後要注意實體網路卡的內容，假如你有建立「Hyper-V的虛擬交換器」，實體的網卡可能已經被指定成交換器，所以要將「Hyper-V可擴充式虛擬交換器」取消，將「網際網路通訊協定地4版TCP/IPv4」勾選還來，這樣網際網路才會通。</p>
<p><img src="https://i0.wp.com/image.walker-a.com/2021/07/homehy/hy-24.jpg?w=1200&#038;ssl=1" alt="Hyper-V" data-recalc-dims="1" /><div class='code-block code-block-6' style='margin: 8px 0; clear: both;'>
<script async src="https://pagead2.googlesyndication.com/pagead/js/adsbygoogle.js?client=ca-pub-1178754458536026"
     crossorigin="anonymous"></script>
<ins class="adsbygoogle"
     style="display:block; text-align:center;"
     data-ad-layout="in-article"
     data-ad-format="fluid"
     data-ad-client="ca-pub-1178754458536026"
     data-ad-slot="5876192061"></ins>
<script>
     (adsbygoogle = window.adsbygoogle || []).push({});
</script></div>
</p>
<p>&nbsp;</p>
<h3>延伸閱讀：</h3>
<ul>
<li><a title="Permalink to 檢查你的PC是否可以安裝 Windows 11" href="https://walker-a.com/archives/6808" target="_blank" rel="bookmark noopener">檢查你的PC是否可以安裝 Windows 11</a></li>
<li><a title="Permalink to 如何關閉 Windows 10 工具列上右邊的 天氣資訊" href="https://walker-a.com/archives/6779" target="_blank" rel="bookmark noopener">如何關閉 Windows 10 工具列上右邊的 天氣資訊</a></li>
<li><a title="Permalink to 無法升級 Windows 11 ,山不轉路轉,玩虛擬機總可以吧！" href="https://walker-a.com/archives/6810" target="_blank" rel="bookmark noopener">無法升級 Windows 11 ,山不轉路轉,玩虛擬機總可以吧！</a></li>
</ul>
<p>&nbsp;</p>
<div class="walke-after-content" id="walke-761304964"><div class="fb-page" data-href="https://www.facebook.com/itwalker/" data-tabs="timeline" data-width="" data-height="70" data-small-header="false" data-adapt-container-width="true" data-hide-cover="false" data-show-facepile="false"><blockquote cite="https://www.facebook.com/itwalker/" class="fb-xfbml-parse-ignore"><a href="https://www.facebook.com/itwalker/">挨踢路人甲</a></blockquote></div>

<!-- <span aling=center id="BloggerAds2">Bloggerads載入中~</span> -->


<script async src="https://pagead2.googlesyndication.com/pagead/js/adsbygoogle.js"></script>
<ins class="adsbygoogle"
     style="display:block; text-align:center;"
     data-ad-layout="in-article"
     data-ad-format="fluid"
     data-ad-client="ca-pub-1178754458536026"
     data-ad-slot="1445779508"></ins>
<script>
     (adsbygoogle = window.adsbygoogle || []).push({});
</script>
