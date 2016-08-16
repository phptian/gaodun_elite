#简历接口
###接口地址
```
[
	method:GET
	/wap/Resume/
]
```
###接口参数

```
{
    "status":0,
    "info":"",
    "result":{
    		  //用户基本信息
            "baseInfo":{
                "name":"诸剑飞",
                "birth_date":"2009-04-06",
                "gender":"1",
                "graduate_school":"36",
                "graduate_year":"2015",
                "education":"2",
                "politics_status":"2",
                "detail_major":"会计",
                "living_city":"上海",
                "contact_email":"64894546@qq.com",
                "contact_mobile":"13295287850",
                "dear_hr":"发反反复复111111111方法反反复复",
                "graduate_school_id":"36",
                "gender_text":"男",
                "current_grade_text":"2015年",
                "education_text":"本科",
                "politics_status_text":"其他",
                "headimgurl":false
            },
            //教育背景
            "education":[
                {
                    "pkid":"280",
                    "start_time":" 2016-04 ",
                    "finish_time":" 2017-04 ",
                    "school_name":"上海财经",
                    "major_title":"财会",
                    "degree":"博士"
                }
            ],
            //荣誉证书
            "prize":{
            		//荣誉
                "prize":[
                    {
                        "pkid":"5",
                        "period":" 2016-08 ",
                        "description":"灌灌灌灌"
                    }
                ],
                //证书
                "certificate":{
                    "mir_cert":[
                        {
                            "cname":"互联网金融方向",
                            "ware_id":"16777",
                            "student_id":"246916"
                        }
                    ],
                    "signtime":"2016-05",
                    "cert":[
                        {
                            "pkid":"263",
                            "finish_time":" 2016-08 ",
                            "score":"22",
                            "certificate_org":"点点点",
                            "status":"通过",
                            "certificate_name":"1",
                            "certificate":"1"
                        }
                    ]
                }
            },
            //实习经历 --list
            "practice":[
                {
                    "pkid":"192",
                    "period":" 2016-09 ",
                    "description":"现在，",
                    "period_end":" 2016-09 ",
                    "type":"2"
                }
            ],
            //实践活动
            "activity":[
                {
                    "pkid":"192",
                    "period":" 2016-09 ",
                    "description":"现在，",
                    "period_end":" 2016-09 ",
                    "type":"2"
                }
            ],
            //技能水平
            "skill": [
			      {
			        "display_name": "数据检索实操",
			        "is_illume": 100
			      },
			      {
			        "display_name": "Wind数据库使用实训",
			        "is_illume": 100
			      },
			      {
			        "display_name": "金融数量分析workshop",
			        "is_illume": 100
			      },
			      {
			        "display_name": "行业研究与公司分析",
			        "is_illume": 100
			      }
		    ]
        },
        //头信息
        "headerSet":{
        	  "title":null,
            "keywords":null,
            "description":null,
            "SITE_TITLE":null
        }
    }
```
