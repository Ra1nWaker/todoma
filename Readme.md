# Todolist
<div>
    這個專案的目的是提供使用者能夠建立自己的代辦清單。由於專案本身並不複雜，所以使用者就算不看使用說明，也能夠很直覺地使用網站上提供的功能，但我仍然會在下面提供使用說明
</div>
<br>
<br>

## 預覽
![screenshot](/imgs/Website_preview.png)

## 網站
http://timalen-001-site1.itempurl.com/
<br>
<br>
<br>


<h2 style="color:red">備註</h2>
<h3>2022/3/23 Bug Fixed</h3>
關於日期選擇器的瀏覽器相容性問題已經修復了
<br>
<br>

<h3>2022/3/14 Bug Issue</h3>
如果你的電腦環境是使用 <span style="color:red">Apple 系列的作業系統(MacOS、iOS)、瀏覽器(Safari)</span>，那麼再創建任務時，日期選項有可能會沒辦法選，或者按下 Create 按鈕沒辦法建立任務。<br>
<span style="color:blue">建議在Windows 作業系統、chrome 瀏覽器的條件下使用網站服務</span>
<br>
<br>





## 特色
  <ul>
    <li>
        <h4>建立任務</h4>
    </li>
    <li>
        <h4>任務期限</h4>
        <div>
            在創建任務的時候，可以選擇這項任務的期限是幾月幾號
        </div>
    </li>
    <li>
        <h4>狀態</h4>
        <div>
            代辦任務分成 3 個狀態，並且每個狀態有各自的顏色<br>
            1. <span style="color:blue">In-progress (進行中、藍色)</span> <br>
            2. <span style="color:red">Failed (失敗、紅色)</span><br>
            3. <span style="color:rgb(238, 221, 29)">Finished(完成、黃色)</span><br>
        </div>
    </li>
    <li>
        <h4>正反面</h4>
        <div>- 正面 </div>
        <div>
            顯示任務標題、內容、任務期限和功能列(檢視、編輯、刪除)
        </div>
        <br>
        <div>- 反面 </div>
        <div>
            顯示任務狀態、距離期限還剩多少時間
        </div>
    </li>
  </ul>
<br>
<br>
<br>



## 如何使用
首先進入網站後，會看到首頁
<br>
![screenshot](/imgs/home.png)
<br>
<br>
<br>

接著按右上角的 Register 進入註冊頁面
<br>
![screenshot](/imgs/Register_page.png)
<br>
<br>
<br>

註冊完帳號後，會跳轉到任務清單管理介面
<br>
![screenshot](/imgs/Todolist_page-1.png)
<br>
<br>
<br>

接著將滑鼠移到藍色按鈕<img src="imgs/create_button.png" width="30px">，並點下去，就會進入到創建任務的介面
<br>
![screenshot](/imgs/CreateMission-1.png)
<br>
<br>
<br>

把該填的項目都填好，按下 Create 按鈕，就能創建任務了
<br>
<br>
![screenshot](/imgs/CreateMission-2.png)
<br>
<br>
<br>

創建好任務後，頁面會跳到任務管理介面，最新建立的任務會出現在左上角
<br>
![screenshot](/imgs/Todolist_page-2.png)
<br>
<br>
<br>

任務的顏色是藍色的，代表還在進行中。移動滑鼠到任務上，按下左鍵，就會翻到背面去了
<br>
任務的背面能夠告訴你距離期限還剩多少時間。
<br>
![screenshot](/imgs/Todolist_page-3.png)
<br>
<br>
<br>

要翻回正面有兩個方法
1. 再按一次左鍵
2. 將滑鼠移動到任務框框外
<br>
<img src="/imgs/Todolist_page-2.png">
<br>
<br>
<br>

任務正面有 3 個按鈕<img src="/imgs/button_bar.png" width="30%">

這三個按鈕左到右的功能分別是：
檢視、編輯、刪除。
<br>
<br>
<br>

檢視
![screenshot](/imgs/Mission_Details.png)
<br>
<br>
<br>

編輯
![screenshot](/imgs/Mission_Edit.png)
<br>
<br>
<br>

刪除
![screenshot](/imgs/Mission_Delete.png)
<br>
<br>
<br>

現在回到管理介面，再新增兩個任務
<br>
![screenshot](/imgs/Todolist_page-4.png)
<br>
<br>
<br>

從這裡開始，要示範如何改變任務狀態。首先要示範的是將狀態改成 "完成" 。隨便選擇一個任務，按下編輯按鈕，接著就會進入編輯畫面，按下 Finished 選項，並按下 save
<br>
![screenshot](/imgs/English_Mission_Edit.png)
<br>
<br>
<br>

任務顏色變黃色，代表此任務已經完成了
<br>
![screenshot](/imgs/Todolist_page-5.png)
<br>
<br>
<br>

接著要示範的是將狀態改成 "失敗" 。也是一樣，隨便選一個任務，按下編輯按鈕，接著就會進入編輯畫面，按下 Failed 選項，並按下 save
<br>
![screenshot](/imgs/Chinese_Mission_Edit.png)
<br>
<br>
<br>

任務顏色變紅色，代表此任務失敗了
[備註:如果期限到了，任務也沒有完成，則狀態也會變成失敗的]
<br>
![screenshot](/imgs/Todolist_page-6.png)
<br>
<br>
<br>

接著要介紹的是在管理頁面右邊的分類欄。分類欄提供了選項，讓使用者根據任務狀態和任務期限來檢視任務。
<ul>
    <span style="font-weight:bold;
                text-decoration: underline;">狀態
    </span>
    <li>
        All
        <div>
            顯示所有的任務
            <img src="/imgs/Category-All.png">
        </div>
    </li>
    <br>
    <li>
        Finished
        <div>
            只顯示完成的任務
            <img src="/imgs/Category-Finished.png">
        </div>
    </li>
    <br>
    <li>
        In-progress
        <div>
            只顯示進行中的任務
            <img src="/imgs/Category-In_progress.png">
        </div>
    </li>
    <br>
    <li>
        Failed
        <div>
            只顯示失敗的任務
            <img src="/imgs/Category-Failed.png">
        </div>
    </li>
</ul>
<br>
<ul>
    <span style="font-weight:bold;
                text-decoration: underline;">日期
    </span>
    <li>
        Nearest
        <div>
            日期由最近到最遠來排序
            <img src="/imgs/Category-Nearest.png">
        </div>
    </li>
    <br>
    <li>
        Farthest
        <div>
            日期由最遠到最進排序
            <img src="/imgs/Category-Farthest.png">
        </div>
    </li>
</ul>
<br>
<br>
<br>
<br>
<br>
最後如果你想將任務由最新建立的開始排序，可以按導覽列的
<img src="/imgs/Todolist-button.png" width="25%">
<br>
<br>
<br>
<img src="/imgs/Category-Newest.png">
<br>
<br>
<br>

感謝你的閱讀~
