# AIoT Homework 5 2022
[Link](https://github.com/Forcer0625/2022-AIoT-HW5)
### step 1 : Clone My github repository
* 複製存放庫
![](static/step1-1.png)
* 選擇在遠端的存放庫進行複製
![](static/step1-2.png)
* 選擇存放庫資料夾
![](static/step1-3.png)

### step 2 : install package
```python
pip install -r requirements.txt
```
![](static/step2.png)

### step 3: add an heroku postgredb

* 註冊Heroku帳號
![](static/step3-1.png)
* go to dashboard, and add new an app
![](static/step3-2.png)
* go to resource and add-on an Heroku postgredb
![](static/step3-3.png)

### step 4: login to heroku postgredb using HeidiSQL
* 到postgredb查看資料庫屬性
![](static/step4-1.png)
* 在HeidiSQL新增資料庫
![](static/step4-2.png)

### step 5: import postgredb (in db/postgre.sql)
* 匯入並執行postgredb.sql
![](static/step5-1.png)

### step 6: setting db in app.py
* 在`app.py`填入postgredb相關資訊
![](static/step6.png)

### step 7: testing locally by running python app.py
* 本地端執行Flask
![](static/step7-1.png)
* 檢查運行情況
![](static/step7-2.png)

### step 8: deploy to github (new private github repositoy)

delete .git and git remote add origin master github.com/xxxxx


### step 9: Heroku deploy from github

### step 10: Complete

Sample link 1:
https://awinlab-aiot.herokuapp.com/

Sample link 2: 
https://aiot0529.herokuapp.com/





