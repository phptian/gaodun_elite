Wap\Controller\IndexController
===============

Class IndexController




* Class name: IndexController
* Namespace: Wap\Controller
* Parent class: Common\Controller\CommonController







Methods
-------


### index

    mixed Wap\Controller\IndexController::index()

### 首页
GET /Wap/Index/
  ```
     {
         //已经解锁的数据
         "courses": [
         {
             "id": "535",
             "student_id": "0",
             "course_id": "1521",
             "type_id": "17",
             "project_id": "37",
             "regdate": "1458641687",
             "big_id": "1528",
             "status": "1",
             "isdel": "0",
             "sort": "127"
             },
             ],
             "sign": 1, //sign 签到 1 已经签到0
             "hasPermission": 2, //是否有测试权限
             "pop": 1,//首次是否要弹出
             "eliteNum": {
             "total_num": "10" //菁英币
         },
         "prevRecord":: {
              "id": "86591",
              "project_id": "00000000001",
              "subject_id": null,
              "course_id": "0",
              "courseware_id": "16778",
              "name": "阶段测试类型",
              "partpath3": "",
              "partpath": "3331",
              "partpath_new": "",
              "series_id": "0",
              "type": "9",
              "exercise_id": null,
              "sortid": "0",
              "timekey": "0",
              "desc": "",
              "listentest": "0",
              "isanswer": "0",
              "itemoption": "a:0:{}",
              "is_complete": "1",
              "is_enable": "0",
              "status": "0",
              "info": "",
              "upload_username": "admin",
              "check_username": null,
              "upload_admin_id": null,
              "check_admin_id": null,
              "regdate": "1459333590",
              "checktime": null,
              "modifydate": "1464256138",
              "isdel": "0",
              "duration": "1",
              "gl_live_id": "",
              "kid": "",
              "explain": null
            }
     }
 ```



* Visibility: **public**



