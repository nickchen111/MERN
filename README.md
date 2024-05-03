# MERN
# 專案說明
* 網站功能: 建立了一個可供註冊登入的網站, 使用者可以註冊成為該網站的會員並提供兩種身份做選擇: 老師或者學生, 選擇老師可以在平台上發布、更改、刪除自己的課程。如果是學生的話可以選擇註冊課程
* 網站版面與功能說明:
  * 網站首頁: ![image](https://github.com/nickchen111/MERN/blob/main/img/%E7%B6%B2%E7%AB%99%E9%A6%96%E9%A0%81.png)
  * 註冊會員功能:  ![image](https://github.com/nickchen111/MERN/blob/main/img/%E8%A8%BB%E5%86%8A%E6%9C%83%E5%93%A1.png)
    * 註冊成功畫面 並且註冊為講師: ![image](https://github.com/nickchen111/MERN/blob/main/img/%E8%A8%BB%E5%86%8A%E6%88%90%E5%8A%9F.png)
  * 會員登入: ![image](https://github.com/nickchen111/MERN/blob/main/img/%E6%9C%83%E5%93%A1%E7%99%BB%E5%85%A5.png)
    * 會員註冊失敗(信箱錯誤): ![image](https://github.com/nickchen111/MERN/blob/main/img/%E6%9C%83%E5%93%A1%E7%99%BB%E5%85%A5%E5%A4%B1%E6%95%97%E5%B8%B3%E8%99%9F.png)
    * 會員註冊失敗(密碼錯誤): ![image](https://github.com/nickchen111/MERN/blob/main/img/%E6%9C%83%E5%93%A1%E7%99%BB%E5%85%A5%E5%A4%B1%E6%95%97%E5%AF%86%E7%A2%BC.png)
  * 登入後的講師profile: ![image](https://github.com/nickchen111/MERN/blob/main/img/%E7%99%BB%E5%85%A5%E6%88%90%E5%8A%9F%E8%AC%9B%E5%B8%ABprofile.png)
  * 講師的課程: ![image](https://github.com/nickchen111/MERN/blob/main/img/%E8%AC%9B%E5%B8%AB%E8%AA%B2%E7%A8%8B%E9%A0%81%E9%9D%A2.png)
              可以看到自己有哪些課程、課程學生人數、價格與課程介紹
    * 講師新增課程功能與成功新增: ![image](https://github.com/nickchen111/MERN/blob/main/img/%E6%96%B0%E5%A2%9E%E8%AA%B2%E7%A8%8B.png)
    * 講師更新課程功能與成功更新: ![image](https://github.com/nickchen111/MERN/blob/main/img/%E6%9B%B4%E6%96%B0%E6%88%90%E5%8A%9F%E9%80%9A%E7%9F%A5.png)
    * 講師刪除課程功能與成功刪除: ![image](https://github.com/nickchen111/MERN/blob/main/img/%E5%88%AA%E9%99%A4%E6%88%90%E5%8A%9F%E9%80%9A%E7%9F%A5.png)
                              遇到兩個一樣的課名,只能刪除自己的,點選其他人的課程刪除會沒反應
 * 登入後的學生profile: ![image](https://github.com/nickchen111/MERN/blob/main/img/%E5%AD%B8%E7%94%9F%E7%AB%AF%E7%99%BB%E5%85%A5profile.png)
   * 學生註冊課程與成功註冊: ![image](https://github.com/nickchen111/MERN/blob/main/img/%E5%AD%B8%E7%94%9F%E8%A8%BB%E5%86%8A%E8%AA%B2%E7%A8%8B.png)
* 學生註冊的課程頁面: ![image](https://github.com/nickchen111/MERN/blob/main/img/%E5%AD%B8%E7%94%9F%E8%A8%BB%E5%86%8A%E8%AA%B2%E7%A8%8B%E9%A0%81%E9%9D%A2.png)
                   可以看到自己註冊了哪些課程、課程學生人數、價格與課程介紹

  
* 技術細節:
  * MERN專案技術 -> node.js 建構server-side 、 react建構client-side 、 mongodb做為資料庫管理系統 儲存用戶以及課程資料
  * React框架設計route以及網頁版並且用state lifting 技術去讓程式碼更簡潔好維護
  * 在每個特定功能選單頁面都會進行邏輯判斷使用者才會顯示或者可以使用特定的功能選單
  * 做身份認證與授權並且每個用戶都可以決定是要選擇註冊或者登入為instructor 或者 student
    


# English Version
* **Website Functionality:** Created a website with registration and login capabilities. Users can register as members of the website and choose between two identities: teacher or student. Teachers can publish, edit, and delete their courses on the platform, while students can register for courses.

* **Website Layout and Functionality Overview:**
  * **Homepage:** ![image](https://github.com/nickchen111/MERN/blob/main/img/%E7%B6%B2%E7%AB%99%E9%A6%96%E9%A0%81.png)
  * **Member Registration:** ![image](https://github.com/nickchen111/MERN/blob/main/img/%E8%A8%BB%E5%86%8A%E6%9C%83%E5%93%A1.png)
    * **Registration Success as Instructor:** ![image](https://github.com/nickchen111/MERN/blob/main/img/%E8%A8%BB%E5%86%8A%E6%88%90%E5%8A%9F.png)
  * **Member Login:** ![image](https://github.com/nickchen111/MERN/blob/main/img/%E6%9C%83%E5%93%A1%E7%99%BB%E5%85%A5.png)
    * **Member Registration Failed (Incorrect Email):** ![image](https://github.com/nickchen111/MERN/blob/main/img/%E6%9C%83%E5%93%A1%E7%99%BB%E5%85%A5%E5%A4%B1%E6%95%97%E5%B8%B3%E8%99%9F.png)
    * **Member Registration Failed (Incorrect Password):** ![image](https://github.com/nickchen111/MERN/blob/main/img/%E6%9C%83%E5%93%A1%E7%99%BB%E5%85%A5%E5%A4%B1%E6%95%97%E5%AF%86%E7%A2%BC.png)
  * **Instructor Profile after Login:** ![image](https://github.com/nickchen111/MERN/blob/main/img/%E7%99%BB%E5%85%A5%E6%88%90%E5%8A%9F%E8%AC%9B%E5%B8%ABprofile.png)
  * **Teacher's Courses:** ![image](https://github.com/nickchen111/MERN/blob/main/img/%E8%AC%9B%E5%B8%AB%E8%AA%B2%E7%A8%8B%E9%A0%81%E9%9D%A2.png)
    * **Add Course Functionality and Success:** ![image](https://github.com/nickchen111/MERN/blob/main/img/%E6%96%B0%E5%A2%9E%E8%AA%B2%E7%A8%8B.png)
    * **Update Course Functionality and Success:** ![image](https://github.com/nickchen111/MERN/blob/main/img/%E6%9B%B4%E6%96%B0%E6%88%90%E5%8A%9F%E9%80%9A%E7%9F%A5.png)
    * **Delete Course Functionality and Success:** ![image](https://github.com/nickchen111/MERN/blob/main/img/%E5%88%AA%E9%99%A4%E6%88%90%E5%8A%9F%E9%80%9A%E7%9F%A5.png)
      Encounters with duplicate course names will only allow deletion of the user's own courses; attempting to delete others' courses will have no effect.
  * **Student Profile after Login:** ![image](https://github.com/nickchen111/MERN/blob/main/img/%E5%AD%B8%E7%94%9F%E7%AB%AF%E7%99%BB%E5%85%A5profile.png)
    * **Student Course Registration and Success:** ![image](https://github.com/nickchen111/MERN/blob/main/img/%E5%AD%B8%E7%94%9F%E8%A8%BB%E5%86%8A%E8%AA%B2%E7%A8%8B.png)

* **Technical Details:**
  * **MERN Project Technologies:** Node.js for server-side development, React for client-side development, MongoDB as the database management system for storing user and course data.
  * **Route and Web Page Design:** Designed routes and web pages using the React framework and employed state lifting techniques to simplify code and maintenance.
  * **User Role-Based Functionality:** Implemented logic checks on specific feature menu pages to display or enable specific features based on user roles.
  * **Authentication and Authorization:** Implemented authentication and authorization, allowing users to choose between registering or logging in as instructors or students.

