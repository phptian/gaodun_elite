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
             "sign": 1, //如果首次进入弹出欢迎页面
             "hasPermission": 2, //是否有测试权限
             "pop": 1,//是否要弹出
             "eliteNum": {
             "total_num": "10" //菁英币
         },
         "prevRecord": false  //上一次学习的记录
     }
 ```



* Visibility: **public**



