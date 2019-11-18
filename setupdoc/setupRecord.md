setUpRecord
===========

### 設定例外網站清單
![IEsetting](https://coolteng.github.io/myPage/gif/JavaSafedUrlSetting.PNG "")

- [設定例外網站清單說明](https://www.java.com/zh_TW/download/faq/exception_sitelist.xml)
- 從 Java 7 Update 11 版開始，Java 已經預設在高安全性設定中封鎖自行簽署和未簽署的 Applet 應用程式
- 從 Java 7 Update 51 版本開始導入了例外網站清單功能
- 由於Java不允許調降安全規格(Java不允許使用者執行未經簽署 (未簽署)、自行簽署 (不是由信任授權單位簽署) 或是遺漏權限屬性的應用程式)，將網站加入例外網站是唯一解法
* 2.1.[啟動 Java 控制面板]
  * 2.1.1.啟動 Java 控制面板之法一：控制台 > 程式集 > Java(32位元)
  * 2.1.2.啟動 Java 控制面板之法二：開始 > Java > 設定 Java

* 2.2.[編輯網站清單]例外網站清單會在 Java 控制面板的"安全"頁籤中管理。清單會顯示在該頁籤中。若要新增、編輯或移除清單中的 URL，請按一下【編輯網站清單】按鈕。
* 2.3.接著按一下「例外網站清單」視窗中的【新增】按鈕。
* 2.4.按一下「位置」欄位下空白的欄位，分別新增輸入下列兩個 URL：
  * 2.4.1.URL：https://coolteng.github.io/
  * 2.4.2.URL：http://robotics.ee.uwa.edu.au
* 2.5.按一下【確定】按鈕以儲存您輸入的 URL，如下圖所示。如果按一下【取消】按鈕，則不會儲存 URL。
![ghSetting](https://coolteng.github.io/myPage/setupdoc/擷取git01Fork.PNG "")
* 2.6.按一下前述「安全性警告」對話方塊中的【繼續】按鈕。
