## Book Flight

### Request URL
https://jipiao.jd.com/search/queryFlight.action

### Method
get

### Request body

```json
{
    depCity: "北京",
    arrCity: "天津",
    depDate: "2017-08-20",
    arrDate: "",
    lineType: "OW",
    queryType: "jipiaoindexquery",
    queryModule: "1"
}
```

### Response 

```json
{
  "code": 200,
  "data": {
    "captchaInfo": null,
    "desc": "",
    "flights": [
    {
        "activityUserType": "0",
        "addDay": "0",
        "airTime": "2小时15分",
        "airways": "MU",
        "airwaysCn": "东方航空",
        "arrAirdrome": "虹桥机场",
        "arrCity": "SHA",
        "arrDate": "2017-07-06",
        "arrTerminal": "T2",
        "arrTime": "2345",
        "arrTimeType": "3",
        "bingoClassInfoList": [
        {
          "activityId": 0,
          "activityUserType": null,
          "airCompanyFlag": 1,
          "childLuggage": "20",
          "childOilTax": 0,
          "childSalePrice": 620,
          "childSeatCode": "R",
          "classLevel": "1",
          "classLimit": null,
          "classLimitInfo": "",
          "classNo": "R",
          "classNoCn": "经济舱",
          "classText": null,
          "deliveryType": null,
          "discount": "∞",
          "exsitsActivity": false,
          "fareItemId": "AIR_CABIN_PROVISION_616066_MU5158_R_20170706_780",
          "fastIssueSwitch": "false",
          "fastIssueTime": "5",
          "fastRefundSwitch": "false",
          "flightSaleRuleId": 0,
          "flightSaleSign": 0,
          "hasVenderCouponFlag": null,
          "isFastTicket": null,
          "isSpecialClass": null,
          "isfirstShow": "1",
          "leastClassInfoFlag": null,
          "limitAgeBegin": null,
          "limitAgeEnd": null,
          "limitAgeText": "",
          "limitCert": null,
          "limitCertText": "",
          "luggage": "20",
          "luggageText": "免费托运20KG",
          "mile": 0.5,
          "mobileMileVal": "0.5",
          "oilTax": 0,
          "originalPrice": 780,
          "pcCodesVal": "",
          "policyComment": null,
          "policyId": "",
          "policySourceType": null,
          "price": 780,
          "productCode": "",
          "reducePrice": 0,
          "refundFeeFormulaId": 0,
          "refundRemark": {
            "text": null,
            "type": 1,
            "value": "156"
          },
          "sale": null,
          "seatNum": "A",
          "seatType": "1",
          "shortClassNoCn": null,
          "sourceId": "616066",
          "specialClassLevel": "1",
          "uniqueKey": "616066_PEK_SHA_170706_5158_R",
          "venderPrice": 780,
          "workTime": null
        }],
        "bingoLeastClassInfo": {
          "activityId": 0,
          "activityUserType": null,
          "airCompanyFlag": 1,
          "childLuggage": "20",
          "childOilTax": 0,
          "childSalePrice": 620,
          "childSeatCode": "R",
          "classLevel": "1",
          "classLimit": null,
          "classLimitInfo": "",
          "classNo": "R",
          "classNoCn": "经济舱",
          "classText": null,
          "deliveryType": null,
          "discount": "∞",
          "exsitsActivity": false,
          "fareItemId": "AIR_CABIN_PROVISION_616066_MU5158_R_20170706_780",
          "fastIssueSwitch": "false",
          "fastIssueTime": "5",
          "fastRefundSwitch": "false",
          "flightSaleRuleId": 0,
          "flightSaleSign": 0,
          "hasVenderCouponFlag": null,
          "isFastTicket": null,
          "isSpecialClass": null,
          "isfirstShow": "1",
          "leastClassInfoFlag": null,
          "limitAgeBegin": null,
          "limitAgeEnd": null,
          "limitAgeText": "",
          "limitCert": null,
          "limitCertText": "",
          "luggage": "20",
          "luggageText": "免费托运20KG",
          "mile": 0.5,
          "mobileMileVal": "0.5",
          "oilTax": 0,
          "originalPrice": 780,
          "pcCodesVal": "",
          "policyComment": null,
          "policyId": "",
          "policySourceType": null,
          "price": 780,
          "productCode": "",
          "reducePrice": 0,
          "refundFeeFormulaId": 0,
          "refundRemark": {
            "text": null,
            "type": 1,
            "value": "156"
          },
          "sale": null,
          "seatNum": "A",
          "seatType": "1",
          "shortClassNoCn": null,
          "sourceId": "616066",
          "specialClassLevel": "1",
          "uniqueKey": "616066_PEK_SHA_170706_5158_R",
          "venderPrice": 780,
          "workTime": null
        },
        "depAirdrome": "首都机场",
        "depCity": "PEK",
        "depDate": "2017-07-06",
        "depTerminal": "T2",
        "depTime": "2130",
        "depTimeType": "3",
        "exsitsActivity": false,
        "flightNo": "MU5158",
        "flightSaleSign": 0,
        "hasVenderCouponFlag": null,
        "isCodeShare": 0,
        "isStop": "0",
        "islimit2HoursFlight": 0,
        "meal": "",
        "milage": null,
        "optimalReducePrice": 0,
        "planeStyle": "325",
        "planeStyleCN": "",
        "planeStyleType": "4",
        "sale": null,
        "shareFlightNo": "",
        "tax": 50,
        "ticketMap": null,
        "vipLoungeFlag": 0,
        "yseatPrice": 0
    }]
  }
   "interval": "1000",
   "isFinished": 0,
   "queryDate": "2017-07-06",
   "queryuuid": "9281e17f73564e2e90fd40efad73ed171241272071781499271728154",
   "resultCode": 0
}
```


## Book Train


### Request URL
http://jisutrain.market.alicloudapi.com/train/ticket

### Method
get

### Request body
```json
{
    start: "北京",
    end: "上海",
    date: "2017-07-06",
}
```

### Response 

```json
{
    "status": "0",
      "msg": "ok",
      "result": [
      {
           "trainno": "G5",
           "type": "高铁",
           "departstation": "北京南",
           "terminalstation": "上海虹桥",
           "station": "北京南",
           "endstation": "上海虹桥",
           "starttime": "07:00",
           "endtime": "11:55",
           "costtime": "04:55",
           "day": "1",
           "gr": "--",
           "qt": "--",
           "rw": "--",
           "rz": "--",
           "td": "--",
           "wz": "--",
           "yw": "--",
           "yz": "--",
           "ed": "无",
           "yd": "2",
           "sw": "无"
      }]
}
```

## Book Hotel

### Request URL
https://ali-hotel.showapi.com/hotelList

### Method
get

### Request body
```json
{
	cityId: 53,
    comeDate: "20170706",
    leaveDate: "20170707",
}
```

### Response 

```json
{
  "showapi_res_code": 0,
  "showapi_res_error": "",
  "showapi_res_body": {
    "ret_code": 0,
    "totalCount": "9519",
    "page": "1",
    "pageSize": "100",
    "list": [
    {
        "commentTotal": "224",
        "streetAddr": "51号",
        "highestPrice": "150.0",
        "cityId": "53",
        "starRatedName": "四星级",
        "street": "复兴门内大街",
        "img": "http://pic2.40017.cn/hotel/2015/7/24/14/32/L/3e118de71c1c42099581204bb3b9b9e2_240x180_01.jpg",
        "sectionName": "西城区",
        "nearBy": "近民族文化宫",
        "hotelId": "216",
        "hotelName": "北京民族饭店",
        "longitude": "116.35586776914236",
        "groupBuy": "0",
        "starRatedId": "2",
        "recmdLevel": "40",
        "commentGood": "215",
        "imgSize": [
          "400x300",
          "240x180",
          "100x75"
        ],
        "intro": "北京民族饭店是一家国际  商务酒店，傲居于西长安街，紧邻西单繁华商业中心以及金融街区。饭店已于2005年换上了豪华的新装，外观雄伟高大，华贵典雅，汇聚中西合璧式风格，豪华但不奢华。商务客房舒适典雅、特色餐厅誉满京城，同时还具有多个现代化的大型会议厅，配合极臻完善。北京民族饭店悉心的贴身服务，满足您的一切愿望。",
        "sectionId": "641",
        "roomType": "行政间;商务套间;商务迷你套间;商务双床房;商务大床房(10元度周末);商务大床房(半价专享);商务双床房(春节预售);【包楼度周末】商务双床房;家庭套间;商务大床间;商务双床间",
        "address": "复兴门内大街51号",
        "oneWord": "北京民族饭店是一家国际  商务酒店，傲居于西长安街，紧邻西单繁华商业中心以及金融街区。",
        "latitude": "39.906809482895845",
        "viewCount": "56",
        "lowestPrice": "798.0"
    }],
    "totalPage": "96"
  }
}
```

