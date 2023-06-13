# AI-Farmer

學生資料建立教學：
1. 使用自己的Google帳號新增google試算表  
  a.建立一個空的試算表
![image](https://github.com/SunSyueWei/AI-Farmer/assets/95061333/8fff2250-d58e-46c1-b1e2-034c17dc9a58)
  b.開啟共用-知道連結的任何人-編輯者  
![image](https://github.com/SunSyueWei/AI-Farmer/assets/95061333/03ed8522-c457-4d1d-a6ab-14149764b1a9)

2. 建立學生資料  
  a.到以下Google試算表網址的Student工作表複製學生資料(僅作為格式參考，校名、班級、學號、姓名等參數皆可自行修改)
    https://docs.google.com/spreadsheets/d/19b40jAz1aOl-OFUPNcIeTlh-rxIF6qTpp-EAiB_f2Kg/edit?usp=sharing  
  b.注意！工作表名稱需修改為'**Student**'，且S大寫
  ![image](https://github.com/SunSyueWei/AI-Farmer/assets/95061333/985176e2-aeb0-435a-a867-8e40022a081c)

3. 新建GAS  
  a.選擇擴充功能-Apps Script  
  ![image](https://github.com/SunSyueWei/AI-Farmer/assets/95061333/1eb444d3-d8a9-4a55-839d-15051994338b)  

4. 更改GAS程式碼並發布  
  a.到此Github上的GAS程式碼中複製程式碼  
  https://github.com/SunSyueWei/AI-Farmer/blob/main/GAS%E7%A8%8B%E5%BC%8F%E7%A2%BC.txt  
  b.選擇copy raw file  
  ![image](https://github.com/SunSyueWei/AI-Farmer/assets/95061333/d04f7ed8-f8cc-48d2-a156-3218e9113aac)  
  c.貼上並儲存  
  ![image](https://github.com/SunSyueWei/AI-Farmer/assets/95061333/5c4a2b63-c603-469d-9bde-49b79f5b3212)  
  d.選擇部署-新增部署作業  
  ![image](https://github.com/SunSyueWei/AI-Farmer/assets/95061333/5bc1af12-5bfe-484d-a0ed-d2a18dbd662f)  
  e.點選選取類型旁邊的齒輪-網頁應用程式  
  ![image](https://github.com/SunSyueWei/AI-Farmer/assets/95061333/a1f636c5-a5dc-4cb9-99aa-e9a264d10384)  
  f.執行身分(我)-誰可以存取(所有人)-最後選擇部署  
  ![image](https://github.com/SunSyueWei/AI-Farmer/assets/95061333/e0437ef7-b49f-47ba-9384-d8ec62b61ace)  
  g.選擇授予存取權  
  ![image](https://github.com/SunSyueWei/AI-Farmer/assets/95061333/d1e2fb6f-a401-4b84-ad79-b92bba0f47e0)  
  h.選擇Go to 'GAS名稱' (unsafe)  
  ![image](https://github.com/SunSyueWei/AI-Farmer/assets/95061333/5ffb444b-ac14-4ee2-8573-bef93391a6ec)  
  i.選擇Allow  
  ![image](https://github.com/SunSyueWei/AI-Farmer/assets/95061333/b6353114-3b8d-4a4d-a729-62856f4a941e)  
  j.複製下方網頁應用程式網址  
  ![image](https://github.com/SunSyueWei/AI-Farmer/assets/95061333/f9e4b04b-890f-4fa8-9ee9-689b9e707b42)  
  
5. Github 操作  
  a.到此Github上複製網址  
  ![image](https://github.com/SunSyueWei/AI-Farmer/assets/95061333/d5d97b69-6751-459b-a7c5-dbef7190e31f)  
  b.到自己的Github上選擇import  
  ![image](https://github.com/SunSyueWei/AI-Farmer/assets/95061333/77112bfa-eb3c-4f64-ad1d-21952772b5d4)  
  c.貼上連結-輸入Repository name-選擇public-Begin import  
  ![image](https://github.com/SunSyueWei/AI-Farmer/assets/95061333/375d0d29-d7a1-4c10-be5a-b8ef2268d8a8)  
  d.複製到自己的Github後，下載html檔  
  ![image](https://github.com/SunSyueWei/AI-Farmer/assets/95061333/5fa637a0-7f58-40e7-8bc6-58c1f95e3efe)  
  
7. 修改html檔  
  a.將步驟四複製下來的網址替換到value="原先的網址"中  
  ![image](https://github.com/SunSyueWei/AI-Farmer/assets/95061333/90765cc5-ff44-48cd-98e2-06cc836dbb52)  
  b.到Github上選擇Upload files  
  ![image](https://github.com/SunSyueWei/AI-Farmer/assets/95061333/4b2665aa-3d0d-4fe4-a7af-2b395c484f0e)  
  c.上傳修改過後的index檔  
  ![image](https://github.com/SunSyueWei/AI-Farmer/assets/95061333/62d92a95-b53e-4b03-bb87-f05f1b1c4276)  
  d.輸入commit(類似給這次上傳做一個標注)-選擇Commit changes  
  ![image](https://github.com/SunSyueWei/AI-Farmer/assets/95061333/5f109734-5b59-4a3c-81be-0c9d4a952dac)  

8. 使用Github pages作為伺服器發佈到網路上  
  a.選擇Settings  
  ![image](https://github.com/SunSyueWei/AI-Farmer/assets/95061333/3291a5a5-22f8-4300-8e69-17116e1d9a37)  
  b.選擇Pages  
  ![image](https://github.com/SunSyueWei/AI-Farmer/assets/95061333/8671e73d-2494-4980-8517-2676f122623a)  
  c.None改為Main-點選Save  
  ![image](https://github.com/SunSyueWei/AI-Farmer/assets/95061333/ce2aeb97-2cbe-4fdd-b7af-077eb73d74ef)
  d.回到Code頁面  
  ![image](https://github.com/SunSyueWei/AI-Farmer/assets/95061333/8a440757-b3e7-4b59-bcdf-6bff52ed049c)  
  e.點選Github-pages  
  ![image](https://github.com/SunSyueWei/AI-Farmer/assets/95061333/128c5de9-20e2-481f-aac3-0e59b81b38db)  
  f.選擇View deployment  
  ![image](https://github.com/SunSyueWei/AI-Farmer/assets/95061333/b97cc5f1-fd0c-418f-ba88-e044c70ab54e)  

9. 成功進到遊戲畫面！  
  ![image](https://github.com/SunSyueWei/AI-Farmer/assets/95061333/6c69c245-cb26-4a30-8879-3a256c693abd)
