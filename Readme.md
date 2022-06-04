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

* register heroku account
![](static/step3-1.png)
* go to dashboard, and add new an app
![](static/step3-2.png)
* go to resource and add-on an Heroku postgredb
![](static/step3-3.png)

### step 4: login to heroku pstgredb using HeidiSQL


```sql
myserver ="<fill-in-Heroku-Postgredb-DB-sever>"
myuser="<fill-in-Heroku-Postgredb-DB-user>"
mypassword="<fill-in-Heroku-Postgredb-DB-pwd>"
mydb="<fill-in-Heroku-Postgredb-DB-db>"

```
### step 5: import postgredb (in db/postgre.db)


### step 6: setting db in app.py


```sql
myserver ="<fill-in-Heroku-Postgredb-DB-sever>"
myuser="<fill-in-Heroku-Postgredb-DB-user>"
mypassword="<fill-in-Heroku-Postgredb-DB-pwd>"
mydb="<fill-in-Heroku-Postgredb-DB-db>"

```
### step 7: testing locally by running python app.py

### step 8: deploy to github (new private github repositoy)

delete .git and git remote add origin master github.com/xxxxx


### step 9: Heroku deploy from github

### step 10: Complete

Sample link 1:
https://awinlab-aiot.herokuapp.com/

Sample link 2: 
https://aiot0529.herokuapp.com/





