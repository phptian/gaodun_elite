Wap\Controller\LiveController
===============






* Class name: LiveController
* Namespace: Wap\Controller
* Parent class: Common\Controller\CommonController







Methods
-------


### index

    mixed Wap\Controller\LiveController::index()

###导师预约首页
method: GET
```
[
     'type'=>2, //默认2:一对一 1:一对多
     'times' => 'all', //时间段 默认all:全部 week:本周 next:下周 other: 其他
     'p' => 1 //分页参数
]
```
```
{
     "title": "梦想导师_CFA投行菁英计划", //title
     "list": {
         //预约列表数据
         "data": [
         {
             "id": "3251",
             "title": "ACCA小班课 5月11",
             "project_id": "4",
             "subject_id": "75",
             "course_id": null,
             "teacher_id": "102",
             "teachername": "1111",
             "teacher_pic": "Teacher/2016/05/09/5730386e8ecec.jpg",
             "teacher_identity": "444444",
             "regdate": "1462933357",
             "pic": null,
             "type": "1",
             "oneStarttime": "1464105600",
             "capacity": "2",
             "nownum": "0",
             "count": "5"
         },
         .

...
     ],
     "info": "",
     "status": 105
     },
     "permission": 2, //权限
     "times": "all",  //授课时间
     "now": 1468567761, //时间错
     "type": 2   //授课方式
 }
```

* Visibility: **public**




### accountLive

    mixed Wap\Controller\LiveController::accountLive()

###我的预约页面
method:Get
```
[
     'p'=>1,//页数
]
```
```
{
     "page": 1, //页数
     "list": {
         "data": [
             {
                 "id": "3256",
                 "title": "一对一",
                 "starttime": "1463481600",
                 "endtime": "1468839000",
                 "project_id": "4",
                 "subject_id": "0",
                 "course_id": null,
                 "teacher_id": "103",
                 "teachername": "222",
                 "teacher_pic": "Teacher/2016/05/25/574535d47bc47.jpg",
                 "teacher_identity": "sdcscs",
                 "regdate": "1463472985",
                 "pic": "Liveppt/2016/05/17/573ad3a20a448.jpg",
                 "type": "1",
                 "oneStarttime": "1463475060",
                 "oneEndtime": "1463475600",
                 "oneid": "22",
                 "capacity": null,
                 "nownum": null,
                 "count": null
             }
         ],
         "info": "",
         "status": 105
     },
     "title": "我的预约_CFA投行菁英计划",
     "now": 1468568785
 }
```



* Visibility: **public**




### teacher

    mixed Wap\Controller\LiveController::teacher()

###获取导师详情页面
```
{
     "tags": [
     ""
     ],
     "title": "梦想导师_CFA投行菁英计划",
     "teacher": {
         "data": {
             "id": "102",
             "name": "1111",
             "titles": "444444",
             "tag": "90后,2222",
             "desc": "fsdvsdvsdvsvbsdvs",
             "photo": "Teacher/2016/06/23/576b91bb80241.jpg"
         },
         "info": "",
         "status": 105
     }
 }
```



* Visibility: **public**




### toAddLive

    mixed Wap\Controller\LiveController::toAddLive()

###添加预约
method:POST
```
[
     'type'=>1,//预约类型
]

```
return
```
{
     'error':0,
     'msg':''
}
```

* Visibility: **public**




### toCancelLive

    mixed Wap\Controller\LiveController::toCancelLive()

###取消预约
method:POST
```
[
     'id' => 12,
     'type'=>1,//预约类型
]

```
return
```
{
     'error':0,
     'msg':''
}
```

* Visibility: **public**




### getTimes

    mixed Wap\Controller\LiveController::getTimes()

###获取时间段
method:POST
```
[
     'id'=>1,
]

```
return
```
{
     'error':0,
     'msg':''
}
```

* Visibility: **public**



