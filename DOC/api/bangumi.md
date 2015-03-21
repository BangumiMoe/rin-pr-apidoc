### Bangumi API

#### Get timelinejs data
* path: `/api/bangumi/timeline`
* method: `GET`
* return:
```javascript
{
  "timeline": {
    "type": "default",
    "date": [
      {
        "startDate": "2015-03-21T10:30:00.000Z",
        "endDate": "2015-03-21T11:00:00.000Z",
        "headline": "<a href=\"/tag/548fd6d0f892774b140ac6d4\">記錄的地平線 第二季</a>",
        "text": "スタジオディーン",
        "asset": {
          "media": "data/images/2014/12/7h21ipw246mrf67bh8o.jpg",
          "thumbnail": "data/images/2014/12/3bzpwq7wiz4ybgpexf6.jpg"
        }
      },
      {
        "startDate": "2015-03-18T18:30:00.000Z",
        "endDate": "2015-03-18T19:00:00.000Z",
        "headline": "<a href=\"/tag/548f12e0f892774b140ac684\">寄生獸 生命的準則</a>",
        "text": "マッドハウス",
        "asset": {
          "media": "data/images/2014/12/663e9myabv052m5gj26.jpg",
          "thumbnail": "data/images/2014/12/3njeqjnm6n7brobqngy.jpg"
        }
      },
      {
        "startDate": "2015-03-20T14:30:00.000Z",
        "endDate": "2015-03-20T15:00:00.000Z",
        "headline": "<a href=\"/tag/548f04e3f892774b140ac654\">白箱</a>",
        "text": "P.A.WORKS",
        "asset": {
          "media": "data/images/2014/12/0jjygtzj4qsz58o487d.jpg",
          "thumbnail": "data/images/2014/12/2hghnn73yw83049kdur.jpg"
        }
      }
    ]
  }
}
```

#### Get current season on-showing bangumi data
* path: `/api/bangumi/current`
* method: `GET`
* return:
```javascript
[
  {
    "name": "アイカツ! -アイドルカツドウ!",
    "credit": "SUNRISE",
    "startDate": 1349690400000,
    "endDate": 1538994600000,
    "showOn": 1,
    "tag_id": "548f0f4cf892774b140ac678",
    "icon": "data/images/2014/12/65rqcovela1kddxj81t.jpg",
    "cover": "data/images/2014/12/6dv8ukxc0odnwade3pi.jpg",
    "_id": "548f0f4cf892774b140ac67b"
  },
  {
    "name": "ダイヤのA",
    "credit": "MADHOUSE×Production I.G",
    "startDate": 1381015800000,
    "endDate": 1426980600000,
    "showOn": 0,
    "tag_id": "548efbc280f39e1639da243e",
    "icon": "data/images/2014/12/6vlhuq982abhhhu54sy.jpg",
    "cover": "data/images/2014/12/0iizc2l67npv4ufiyws.jpg",
    "_id": "548efbc280f39e1639da2441"
  },
  {
    "name": "ディスク・ウォーズ:アベンジャーズ",
    "credit": "東映アニメーション",
    "startDate": 1396377000000,
    "endDate": 1430247600000,
    "showOn": 3,
    "tag_id": "548f0f93f892774b140ac67c",
    "icon": "data/images/2014/12/08j68mic47jiujq7gsh.jpg",
    "cover": "data/images/2014/12/2rrcld2dfgnod1vk3ni.jpg",
    "_id": "548f0f93f892774b140ac67f"
  }
]
```
* note:
  * include bangumi data that starts in 3 days.
  * include bangumi data that ended in the past 7 days.

#### Get recent on-air bangumi data
* path: `/api/bangumi/recent`
* method: `GET`
* return:
```javascript
[
  {
    "name": "ダイヤのA",
    "credit": "MADHOUSE×Production I.G",
    "startDate": 1381015800000,
    "endDate": 1426980600000,
    "showOn": 0,
    "tag_id": "548efbc280f39e1639da243e",
    "icon": "data/images/2014/12/6vlhuq982abhhhu54sy.jpg",
    "cover": "data/images/2014/12/0iizc2l67npv4ufiyws.jpg",
    "_id": "548efbc280f39e1639da2441"
  },
  {
    "name": "妖怪ウォッチ",
    "credit": "オー・エル・エム",
    "startDate": 1396611000000,
    "endDate": 1432900800000,
    "showOn": 5,
    "tag_id": "548f0dbdf892774b140ac670",
    "icon": "data/images/2014/12/5m3nu7m8y5e9vq28ur2.jpg",
    "cover": "data/images/2014/12/5sc1wnqc5oerybqe50n.jpg",
    "_id": "548f0dbdf892774b140ac673"
  },
  {
    "name": "レディ ジュエルペット",
    "credit": "ZEXCS、スタジオコメット",
    "startDate": 1396663200000,
    "endDate": 1426905000000,
    "showOn": 6,
    "tag_id": "548fcfc1f892774b140ac6cc",
    "icon": "data/images/2014/12/7ciu1nkr7kdvlmu30jx.jpg",
    "cover": "data/images/2014/12/7a41j5oz6f2qc5cfmg1.jpg",
    "_id": "548fcfc1f892774b140ac6cf"
  },
  {
    "name": "FAIRY TAIL",
    "credit": "A-1Pictures/ブリッジ",
    "startDate": 1396665000000,
    "endDate": 1798732800000,
    "showOn": 6,
    "tag_id": "548f0f2df892774b140ac674",
    "icon": "data/images/2014/12/38zjyburvh2om7o8a37.jpg",
    "cover": "data/images/2014/12/6dznn2rykghikpgav2k.jpg",
    "_id": "548f0f2df892774b140ac677"
  }
]
```
* note:
  * include bangumi data from the day before yesterday to tomorrow.

#### Get all bangumi data
* path: `/api/bangumi/all`
* method: `GET`
* return:
```javascript
[
  {
    "name": "グリザイアの果実",
    "credit": "エイトビット",
    "startDate": 1412530200000,
    "endDate": 1419789600000,
    "showOn": 1,
    "tag_id": "548ef9d980f39e1639da2438",
    "icon": "data/images/2014/12/4iegoy7k8194ogpgwzt.jpg",
    "cover": "data/images/2014/12/4wih83ee75qpa1n74ut.jpg",
    "_id": "548ef9d980f39e1639da243b"
  },
  {
    "name": "ダイヤのA",
    "credit": "MADHOUSE×Production I.G",
    "startDate": 1381015800000,
    "endDate": 1426980600000,
    "showOn": 0,
    "tag_id": "548efbc280f39e1639da243e",
    "icon": "data/images/2014/12/6vlhuq982abhhhu54sy.jpg",
    "cover": "data/images/2014/12/0iizc2l67npv4ufiyws.jpg",
    "_id": "548efbc280f39e1639da2441"
  },
  {
    "_id": "548efccd80f39e1639da244d",
    "cover": "data/images/2014/12/28beewuqckag8ilahv6.jpg",
    "credit": "ぴえろ",
    "endDate": 1426600800000,
    "icon": "data/images/2014/12/2ycfvte23wqu4je5hd2.jpg",
    "name": "暁のヨナ",
    "showOn": 3,
    "startDate": 1412690400000,
    "tag_id": "548efccd80f39e1639da244a"
  }
]
```

#### Add bangumi data
* path: `/api/bangumi/add`
* method: `POST`
* post:
```javascript
(TODO)
```
* return:
```javascript
(TODO)
```
* note:
  * user(staff or above) session required.

#### Update bangumi data
* path: `/api/bangumi/update`
* method: `POST`
* post:
```javascript
(TODO)
```
* return:
```javascript
(TODO)
```
* note:
  * user(staff or above) session required.

#### Remove bangumi data
* path: `/api/bangumi/remove`
* method: `POST`
* post:
```javascript
(TODO)
```
* return:
```javascript
(TODO)
```
* note:
  * user(staff or above) session required.

#### Search bangumi data
* path: `/api/bangumi/search`
* method: `POST`
* post
```javascript
{
	"name": "結城友奈は勇者である"
}
```
* return:
```javascript
{
  "success": true,
  "found": true,
  "bangumi": {
    "_id": "548f047ff892774b140ac653",
    "cover": "data/images/2014/12/7oco5rpb1ubcvmg8lbh.jpg",
    "credit": "Studio五組",
    "endDate": 1419529800000,
    "icon": "data/images/2014/12/7ige8c9xyl2qvtby6f6.jpg",
    "name": "結城友奈は勇者である",
    "showOn": 5,
    "startDate": 1413480000000,
    "tag_id": "548f047ff892774b140ac650"
  }
}
```
* note:
  * `name` must be exactly the same, case insesitive.

#### Fetch bangumi data
* path: `/api/bangumi/fetch`
* method: `POST`
* post/type-object:
```javascript
{
	"_id": "548f047ff892774b140ac653"
}
```
* return/type-object:
```javascript
{
  "_id": "548f047ff892774b140ac653",
  "cover": "data/images/2014/12/7oco5rpb1ubcvmg8lbh.jpg",
  "credit": "Studio五組",
  "endDate": 1419529800000,
  "icon": "data/images/2014/12/7ige8c9xyl2qvtby6f6.jpg",
  "name": "結城友奈は勇者である",
  "showOn": 5,
  "startDate": 1413480000000,
  "tag_id": "548f047ff892774b140ac650"
}
```
* post/type-array:
```javascript
{
	"_ids": [
		"548f024df892774b140ac633",
		"548f047ff892774b140ac653"
	]
}
```
* return/type-array:
```javascript
[
  {
    "_id": "548f024df892774b140ac633",
    "cover": "data/images/2014/12/5amux6k3yt6qr98v29f.jpg",
    "credit": "京都アニメーション",
    "endDate": 1419526200000,
    "icon": "data/images/2014/12/4wwbso2q8tybiw0lbd2.jpg",
    "name": "甘城ブリリアントパーク",
    "showOn": 5,
    "startDate": 1412612400000,
    "tag_id": "548f024df892774b140ac630"
  },
  {
    "_id": "548f047ff892774b140ac653",
    "cover": "data/images/2014/12/7oco5rpb1ubcvmg8lbh.jpg",
    "credit": "Studio五組",
    "endDate": 1419529800000,
    "icon": "data/images/2014/12/7ige8c9xyl2qvtby6f6.jpg",
    "name": "結城友奈は勇者である",
    "showOn": 5,
    "startDate": 1413480000000,
    "tag_id": "548f047ff892774b140ac650"
  }
]
```
