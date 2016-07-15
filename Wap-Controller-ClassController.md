Wap\Controller\ClassController
===============






* Class name: ClassController
* Namespace: Wap\Controller
* Parent class: Common\Controller\CommonController







Methods
-------


### getlession

    mixed Wap\Controller\ClassController::getlession()

###获取课程列表页面
请求
```
 Method:GET
 [
    'cid'=>123; //课程id
 ]
```
数据
```
{
     "records":{
         "86555":"86555",
         "86556":"86556",
         "86557":"86557",
         "86558":"86558",
         "86559":"86559",
         "86560":"86560",
         "86561":"86561",
         "86562":"8656",
             .

...
     },
     "detail":{
         ....//课程详情
     },
     "assignData":"0",
     "progress":{
         "status":2,
         "point":100,
         "count":40,
         "finish":40
     },
     "list":[
         {
             "id":"18",
             "course_id_bak":"10",
             "series_id_bak":"0",
             "name":"A1",
             "summary":"etwetewtewtewt",
             "ppt":"讲义.zip",
             "ppturl":"Courseppt/2016/04/25/571d791ed7fd9.zip",
             "ppt2":"",
             "ppt2url":"",
             "paper":"0",
             "uploadtime":"1335418502",
             "keypoint_ids":"",
             "sortid_bak":"11",
             "task_id":null,
             "status":"0",
             "type":"0",
             "difficulty":"1",
             "major":"1",
             "duration":"1",
             "listentest":"0",
             "modifydate":"1461549342",
             "study_time":"0",
             "coursemodule_id_bak":"0",
             "project_id":"8",
             "subject_id":"0",
             "partlist":{
                 "86500":{
                     "id":"86500",
                     "project_id":"00000000004",
                     "subject_id":null,
                     "course_id":"0",
                     "courseware_id":"16751",
                     "name":"课后练习",
                     "partpath3":"",
                     "partpath":"5024",
                    "partpath_new":"",
                     "series_id":"0",
                     "type":"2",
                     "exercise_id":null,
                     "sortid":"0",
                     "timekey":"0",
                     "desc":"",
                     "listentest":"0",
                     "isanswer":"0",
                     "itemoption":"a:0:{}",
                     "is_complete":"1",
                     "is_enable":"0",
                     "status":"0",
                     "info":"",
                     "upload_username":"admin",
                     "check_username":"admin",
                     "upload_admin_id":null,
                     "check_admin_id":null,
                     "regdate":"1454487754",
                    "checktime":"1454488384",
                     "modifydate":"1463556624",
                     "isdel":"0",
                     "duration":"1",
                     "gl_live_id":"",
                     "kid":"",
                     "explain":null
                 },
             }
         }
     ]
 }
```

* Visibility: **public**



