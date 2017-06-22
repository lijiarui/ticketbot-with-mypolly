## Book Flight

* Request URL
http://101.201.150.169:9000/bookFlight

* Method
get

* Request body

	* one-way ticket sample
```json
{
		"isround": "false",
		"toCity": "上海",
		"fromDate": "2017-08-20",
		"fromCity": "北京",
		"toDate": "" 
   }
```

	* round-trip ticket sample
```json
	{ 
		 "isround": "true",
		 "toCity": "上海",
		 "fromDate": "2017-08-20",
		 "fromCity": "北京",
		 "toDate": "2017-08-25" 
   }
```

* Response 

	* without error 
```json
{
    "data": [
        {
            "company": "南方航空 CZ6412 空中客车 A321(中型)",
            "endtime": "08:40",
            "fromPlace": "首都国际机场T2",
            "price": "¥840起",
            "startime": "06:25",
            "toPlace": "虹桥国际机场T2",
            "unDelayRate": "准点率 87%"
        }
    ],
    "status": 200
}
```

	* error
```json
{
    "error": info,
    "status": 200
}
```

## Book Train


* Request URL
http://101.201.150.169:9000/bookTrain 

* Method
get

* Request body
```json
{
		"toCity": "上海",
		"fromDate": "2017-08-20",
		"fromCity": "北京",
   }
```

* Response 

	* without error 
```json
{
    "data": [
        {
            "endtime": "11:12+1",
            "fromPlace": "过 北京西",
            "startime": "05:14",
            "tickets": [
                {
                    "num": "    仅11张",
                    "price": "¥251",
                    "type": "硬座"
                },
                {
                    "num": "100张",
                    "price": "¥426",
                    "type": "硬卧"
                }
            ],
            "timelong": "29小时58分",
            "toPlace": "终 广州",
            "train": "K599"
        }
    ],
    "status": 200
}
```

	* error
```json
{
    "error": info,
    "status": 200
}
```


## Book Hotel

* Request URL
http://101.201.150.169:9000/bookHotel

* Method
get

* Request body
```json
{
		"city": "北京",
		"fromDate": "2017-08-20",
		"fromCity": "五道口",
		"toDate": "2017-08-22" 
   }
```

* Response 

	* without error 
```json
{
    "data": [
        {
            "locate": "位于安贞，北京东城区和平里兴化路，靠近和平里北街地铁站A2口",
            "name": "北京和平里宾馆",
            "price": "¥361起"
        }
    ],
    "status": 200
}
```

	* error
```json
{
    "error": info,
    "status": 200
}
```