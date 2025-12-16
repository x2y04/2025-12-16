初始專案
1.會需要把檔案放進去建立好的github儲存庫裡面
2.要打標題說明
【前綴：說明】
init:初始化專案會使用到
feat:新增功能/畫面等等
fix:修改檔案內容
style:樣式
docs:說明文件相關的
3.說明內容(可寫或不寫)
4.commit -> 上傳到暫存的空間
5.publish branch -> 把東西推到github上面
6.fetch origin -> 東西已經上傳成功

更新專案
1.會先確認儲存庫有沒有檔案要先同步(fetch origin)
(如果有要更新檔案的話)
1-2.要把檔案拉下來 -> pull origin
1-3.如果兩個人都改到同一支檔案會有衝突需要解衝突
1-4.解衝突流程
stash changes and contine -> 先把自己寫的東西放到一個獨立的空間
1-5.多點幾次fetch 確保沒有人再上傳
把自己撰寫的內容放回去 -> stash changes ->restore
只要有綠色勾勾的情況下，一定要上傳

2.要先打標題說明(描述可打可不打)
3.commit ->上傳到暫存空間
4.push origin ->上傳到github的儲存庫裡面