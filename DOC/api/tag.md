### Tag API

#### Add tag
* path: `/api/tag/add`
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

#### Update tag
* path: `/api/tag/update`
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

#### Remove tag
* path: `/api/tag/remove`
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

#### Get all tags data
* path: `/api/tag/all`
* method: `GET`
* return:
```javascript
[
  {
    "_id": "548ee2ce4ab7379536f56358",
    "activity": 0,
    "locale": {},
    "name": "1080p",
    "syn_lowercase": [
      "1080p",
      "1920x1080",
      "1920*1080",
      "1920×1080",
      "1080",
      "fullhd"
    ],
    "synonyms": [
      "1080p",
      "1920x1080",
      "1920*1080",
      "1920×1080",
      "1080",
      "FullHD"
    ],
    "type": "resolution"
  },
  {
    "_id": "548f0004f892774b140ac618",
    "activity": 0,
    "locale": {
      "ja": "アカメが斬る!",
      "zh_cn": "斩·赤红之瞳！",
      "en": "Akame Ga Kill",
      "zh_tw": "斬！赤紅之瞳"
    },
    "name": "アカメが斬る!",
    "syn_lowercase": [
      "アカメが斬る!",
      "斩·赤红之瞳！",
      "akame ga kill",
      "akame ga kiru",
      "斬！赤紅之瞳"
    ],
    "synonyms": [
      "アカメが斬る!",
      "斩·赤红之瞳！",
      "Akame Ga Kill",
      "Akame Ga Kiru",
      "斬！赤紅之瞳"
    ],
    "type": "bangumi"
  },
  {
    "_id": "548f0434f892774b140ac64c",
    "activity": 0,
    "locale": {
      "ja": "天体のメソッド",
      "zh_cn": "天体的方式",
      "zh_tw": "天體運行式",
      "en": "Sora no Method"
    },
    "name": "天体のメソッド",
    "syn_lowercase": [
      "天体のメソッド",
      "天体的秩序",
      "天体运行式",
      "天体的方式",
      "天體運行式",
      "sora no method"
    ],
    "synonyms": [
      "天体のメソッド",
      "天体的秩序",
      "天体运行式",
      "天体的方式",
      "天體運行式",
      "Sora no Method"
    ],
    "type": "bangumi"
  },
  {
    "_id": "548edffb4ab7379536f56352",
    "activity": 0,
    "locale": {},
    "name": "MP4",
    "syn_lowercase": [
      "mpeg4",
      "mp4"
    ],
    "synonyms": [
      "MPEG4",
      "MP4"
    ],
    "type": "format"
  },
  {
    "_id": "548ee0ea4ab7379536f56354",
    "activity": 0,
    "locale": {
      "en": "chs"
    },
    "name": "简体中文",
    "syn_lowercase": [
      "简体中文",
      "简体",
      "chs",
      "gb"
    ],
    "synonyms": [
      "简体中文",
      "简体",
      "chs",
      "GB"
    ],
    "type": "lang"
  },
  {
    "_id": "5492dda32a934ba5288acb1b",
    "activity": 7,
    "locale": {},
    "name": "ANK-Raws",
    "syn_lowercase": [
      "ank-raws"
    ],
    "synonyms": [
      "ANK-Raws"
    ],
    "type": "team"
  },
  {
    "_id": "549306ae5c4651317663a274",
    "activity": 139064,
    "locale": {
      "en": "KNA",
      "zh_cn": "KNA",
      "zh_tw": "KNA"
    },
    "name": "KNA",
    "syn_lowercase": [
      "kna",
      "kna字幕组",
      "kna字幕組",
      "kna-subs"
    ],
    "synonyms": [
      "KNA",
      "KNA字幕组",
      "KNA字幕組",
      "KNA-Subs"
    ],
    "type": "team"
  },
  {
    "_id": "54967e14ff43b99e284d0bf7",
    "activity": 0,
    "locale": {
      "zh_cn": "合集",
      "zh_tw": "合集",
      "en": "[Collection]"
    },
    "name": "Collection",
    "syn_lowercase": [
      "合集",
      "合集版本",
      "1-12end",
      "完结合集",
      "完結合集",
      "[collection]"
    ],
    "synonyms": [
      "合集",
      "合集版本",
      "1-12END",
      "完结合集",
      "完結合集",
      "[Collection]"
    ],
    "type": "misc"
  }
]
```
* note:
  * types could be:
    * `lang` - languages
    * `resolution` - video resolution
    * `format` - file format
    * `bangumi` - bangumi tags
    * `team` - team tags
    * `misc` - others

#### Get popular bangumi tags
* path: `/api/tag/popbangumi`
* method: `GET`
* return:
```javascript
[
  {
    "_id": "549983cec8b118cf40b274db",
    "activity": 13991,
    "locale": {
      "ja": "アブソリュート・デュオ",
      "zh_cn": "绝对双刃",
      "zh_tw": "絕對雙刃",
      "en": "Absolute Duo"
    },
    "name": "アブソリュート・デュオ",
    "syn_lowercase": [
      "アブソリュート・デュオ",
      "绝对双刃",
      "絕對雙刃",
      "absolute duo"
    ],
    "synonyms": [
      "アブソリュート・デュオ",
      "绝对双刃",
      "絕對雙刃",
      "Absolute Duo"
    ],
    "type": "bangumi"
  },
  {
    "_id": "54a0b72660cda70b18a38948",
    "activity": 4380,
    "locale": {
      "ja": "冴えない彼女の育てかた",
      "zh_cn": "路人女主的养成方法",
      "zh_tw": "不起眼女主角培育法",
      "en": "Saekano: How to Raise a Boring Girlfriend"
    },
    "name": "冴えない彼女の育てかた",
    "syn_lowercase": [
      "冴えない彼女の育てかた",
      "路人女主的养成方法",
      "不起眼女主角培育法",
      "saekano: how to raise a boring girlfriend"
    ],
    "synonyms": [
      "冴えない彼女の育てかた",
      "路人女主的养成方法",
      "不起眼女主角培育法",
      "Saekano: How to Raise a Boring Girlfriend"
    ],
    "type": "bangumi"
  },
  {
    "_id": "548f02abf892774b140ac638",
    "activity": 3987,
    "locale": {
      "ja": "四月は君の嘘",
      "zh_cn": "四月是你的谎言",
      "en": "Shigatsu wa Kimi no Uso",
      "zh_tw": "四月是你的謊言"
    },
    "name": "四月は君の嘘",
    "syn_lowercase": [
      "四月は君の嘘",
      "四月是你的谎言",
      "shigatsu wa kimi no uso",
      "四月是你的謊言"
    ],
    "synonyms": [
      "四月は君の嘘",
      "四月是你的谎言",
      "Shigatsu wa Kimi no Uso",
      "四月是你的謊言"
    ],
    "type": "bangumi"
  },
  {
    "_id": "54b1552dc0a4985d2c95d489",
    "activity": 2845,
    "locale": {
      "ja": "DOG DAYS''",
      "en": "DOG DAYS''",
      "zh_tw": "DOG DAYS''",
      "zh_cn": "DOG DAYS''"
    },
    "name": "DOG DAYS''",
    "syn_lowercase": [
      "dog days''",
      "dog days\"",
      "dog days′′",
      "dog days"
    ],
    "synonyms": [
      "DOG DAYS''",
      "DOG DAYS\"",
      "DOG DAYS′′",
      "DOG DAYS"
    ],
    "type": "bangumi"
  }
]
```
* note:
  * return 30 bangumi **TAG** data sort by activity

#### Get common tags
* path: `/api/tag/common`
* method: `GET`
* return:
```javascript
[
  {
    "_id": "548ee00b4ab7379536f56353",
    "activity": 0,
    "locale": {},
    "name": "MKV",
    "syn_lowercase": [
      "mkv"
    ],
    "synonyms": [
      "MKV"
    ],
    "type": "format"
  },
  {
    "_id": "548ee0ea4ab7379536f56354",
    "activity": 0,
    "locale": {
      "en": "chs"
    },
    "name": "简体中文",
    "syn_lowercase": [
      "简体中文",
      "简体",
      "chs",
      "gb"
    ],
    "synonyms": [
      "简体中文",
      "简体",
      "chs",
      "GB"
    ],
    "type": "lang"
  },
  {
    "_id": "549cc9369310bc7d04cddf9f",
    "activity": 0,
    "locale": {
      "zh_cn": "剧场版",
      "zh_tw": "劇場版",
      "ja": "劇場版",
      "en": "Movie"
    },
    "name": "Movie",
    "syn_lowercase": [
      "剧场版",
      "劇場版",
      "movie"
    ],
    "synonyms": [
      "剧场版",
      "劇場版",
      "Movie"
    ],
    "type": "misc"
  },
  {
    "_id": "549eef6ffe682f7549f1ea8b",
    "activity": 0,
    "locale": {
      "zh_cn": "音乐",
      "zh_tw": "音樂",
      "en": "Music"
    },
    "name": "Music",
    "syn_lowercase": [
      "音乐",
      "音樂",
      "music"
    ],
    "synonyms": [
      "音乐",
      "音樂",
      "Music"
    ],
    "type": "misc"
  }
]
```
* note:
  * return some common tags used by resources.

#### Get popular team tags
* path: `/api/tag/team`
* method: `GET`
* return:
```javascript
[
  {
    "_id": "54992d1cc8b118cf40b274b3",
    "activity": 434119,
    "locale": {
      "zh_tw": "DHR動研字幕組",
      "zh_cn": "DHR动研字幕组",
      "en": "DHR"
    },
    "name": "DHR動研字幕組",
    "syn_lowercase": [
      "dhr動研字幕組",
      "dhr动研字幕组",
      "dhr",
      "dhr肉片小组"
    ],
    "synonyms": [
      "DHR動研字幕組",
      "DHR动研字幕组",
      "DHR",
      "DHR肉片小组"
    ],
    "type": "team"
  },
  {
    "_id": "549306ae5c4651317663a274",
    "activity": 139064,
    "locale": {
      "en": "KNA",
      "zh_cn": "KNA",
      "zh_tw": "KNA"
    },
    "name": "KNA",
    "syn_lowercase": [
      "kna",
      "kna字幕组",
      "kna字幕組",
      "kna-subs"
    ],
    "synonyms": [
      "KNA",
      "KNA字幕组",
      "KNA字幕組",
      "KNA-Subs"
    ],
    "type": "team"
  },
  {
    "_id": "5492ecbc2a934ba5288acb20",
    "activity": 80060,
    "locale": {
      "zh_cn": "囧夏发布组",
      "zh_tw": "囧夏發佈組",
      "en": "J.X"
    },
    "name": "囧夏发布组",
    "syn_lowercase": [
      "囧夏发布组",
      "囧夏發佈組",
      "j.x",
      "囧夏字幕组",
      "囧夏字幕組"
    ],
    "synonyms": [
      "囧夏发布组",
      "囧夏發佈組",
      "J.X",
      "囧夏字幕组",
      "囧夏字幕組"
    ],
    "type": "team"
  }
]
```

#### Get misc tags
* path: `/api/tag/misc`
* method: `GET`
* return:
```javascript
[
  {
    "_id": "549ef250fe682f7549f1ea91",
    "activity": 0,
    "locale": {
      "zh_tw": "其他",
      "zh_cn": "其他",
      "en": "Other"
    },
    "name": "Other",
    "syn_lowercase": [
      "其他",
      "other"
    ],
    "synonyms": [
      "其他",
      "Other"
    ],
    "type": "misc"
  },
  {
    "_id": "549ef015fe682f7549f1ea8d",
    "activity": 0,
    "locale": {
      "zh_tw": "遊戲",
      "zh_cn": "游戏",
      "en": "Game"
    },
    "name": "Game",
    "syn_lowercase": [
      "遊戲",
      "游戏",
      "game"
    ],
    "synonyms": [
      "遊戲",
      "游戏",
      "Game"
    ],
    "type": "misc"
  },
  {
    "_id": "549ef207fe682f7549f1ea90",
    "activity": 0,
    "locale": {
      "zh_tw": "動畫",
      "zh_cn": "动画",
      "en": "Donga"
    },
    "name": "Donga",
    "syn_lowercase": [
      "動畫",
      "动画",
      "donga"
    ],
    "synonyms": [
      "動畫",
      "动画",
      "Donga"
    ],
    "type": "misc"
  },
  {
    "_id": "549eefebfe682f7549f1ea8c",
    "activity": 0,
    "locale": {
      "zh_tw": "漫畫",
      "zh_cn": "漫画",
      "en": "Comic"
    },
    "name": "Comic",
    "syn_lowercase": [
      "漫畫",
      "漫画",
      "comic"
    ],
    "synonyms": [
      "漫畫",
      "漫画",
      "Comic"
    ],
    "type": "misc"
  },
  {
    "_id": "549eef6ffe682f7549f1ea8b",
    "activity": 0,
    "locale": {
      "zh_cn": "音乐",
      "zh_tw": "音樂",
      "en": "Music"
    },
    "name": "Music",
    "syn_lowercase": [
      "音乐",
      "音樂",
      "music"
    ],
    "synonyms": [
      "音乐",
      "音樂",
      "Music"
    ],
    "type": "misc"
  }
]
```
* note:
  * return all tags with type `misc`.

#### Search tags
* path: `/api/tag/search`
* method: `POST`
* post:
```javascript
{
	"name": "akame ga kill",
  "type"?: "bangumi",
	"keywords": true,
	"multi": true
}
```

  - `type`: Get the specified type of tag(s). If not set, it will return all kind of tags.
  - `keywords`: Search tag(s) by matching part of tag's name.
  - `multi`: Return the collection of tags or not.

* return:
```javascript
{
  "success": true,
  "found": true,
  "tag": [
    {
      "_id": "548f0004f892774b140ac618",
      "activity": 0,
      "locale": {
        "ja": "アカメが斬る!",
        "zh_cn": "斩·赤红之瞳！",
        "en": "Akame Ga Kill",
        "zh_tw": "斬！赤紅之瞳"
      },
      "name": "アカメが斬る!",
      "syn_lowercase": [
        "アカメが斬る!",
        "斩·赤红之瞳！",
        "akame ga kill",
        "akame ga kiru",
        "斬！赤紅之瞳"
      ],
      "synonyms": [
        "アカメが斬る!",
        "斩·赤红之瞳！",
        "Akame Ga Kill",
        "Akame Ga Kiru",
        "斬！赤紅之瞳"
      ],
      "type": "bangumi"
    }
  ]
}
```
or (multi=false):
```javascript
{
  "success": true,
  "found": true,
  "tag": {
    "_id": "548f0004f892774b140ac618",
    "activity": 0,
    "locale": {
      "ja": "アカメが斬る!",
      "zh_cn": "斩·赤红之瞳！",
      "en": "Akame Ga Kill",
      "zh_tw": "斬！赤紅之瞳"
    },
    "name": "アカメが斬る!",
    "syn_lowercase": [
      "アカメが斬る!",
      "斩·赤红之瞳！",
      "akame ga kill",
      "akame ga kiru",
      "斬！赤紅之瞳"
    ],
    "synonyms": [
      "アカメが斬る!",
      "斩·赤红之瞳！",
      "Akame Ga Kill",
      "Akame Ga Kiru",
      "斬！赤紅之瞳"
    ],
    "type": "bangumi"
  }
}
```
or (not found):
```javascript
{
  "success": true,
  "found": false
}
```
* note:
  * name should exactly the same in synonyms, case insensitive.

#### Get tag suggestions
* path: `/api/tag/suggest`
* method: `POST`
* post:
```javascript
{
	"query": "【DHR動研字幕組】[不起眼女主角培育法 / 路人女主的養成方法_Saenai Hiroin no Sodatekata / Saekano][10][繁體][720P][MP4]"
}
```
* return:
```javascript
[
  {
    "_id": "548edfb54ab7379536f56351",
    "activity": 0,
    "locale": {},
    "name": "720p",
    "syn_lowercase": [
      "720p",
      "1280x720",
      "1280*720",
      "1280×720",
      "1280",
      "720"
    ],
    "synonyms": [
      "720p",
      "1280x720",
      "1280*720",
      "1280×720",
      "1280",
      "720"
    ],
    "type": "resolution"
  },
  {
    "_id": "54992d1cc8b118cf40b274b3",
    "activity": 434119,
    "locale": {
      "zh_tw": "DHR動研字幕組",
      "zh_cn": "DHR动研字幕组",
      "en": "DHR"
    },
    "name": "DHR動研字幕組",
    "syn_lowercase": [
      "dhr動研字幕組",
      "dhr动研字幕组",
      "dhr",
      "dhr肉片小组"
    ],
    "synonyms": [
      "DHR動研字幕組",
      "DHR动研字幕组",
      "DHR",
      "DHR肉片小组"
    ],
    "type": "team"
  },
  {
    "_id": "548edffb4ab7379536f56352",
    "activity": 0,
    "locale": {},
    "name": "MP4",
    "syn_lowercase": [
      "mpeg4",
      "mp4"
    ],
    "synonyms": [
      "MPEG4",
      "MP4"
    ],
    "type": "format"
  },
  {
    "_id": "54a0b72660cda70b18a38948",
    "activity": 4380,
    "locale": {
      "ja": "冴えない彼女の育てかた",
      "zh_cn": "路人女主的养成方法",
      "zh_tw": "不起眼女主角培育法",
      "en": "Saekano: How to Raise a Boring Girlfriend"
    },
    "name": "冴えない彼女の育てかた",
    "syn_lowercase": [
      "冴えない彼女の育てかた",
      "路人女主的养成方法",
      "不起眼女主角培育法",
      "saekano: how to raise a boring girlfriend"
    ],
    "synonyms": [
      "冴えない彼女の育てかた",
      "路人女主的养成方法",
      "不起眼女主角培育法",
      "Saekano: How to Raise a Boring Girlfriend"
    ],
    "type": "bangumi"
  },
  {
    "_id": "548ee1204ab7379536f56357",
    "activity": 0,
    "locale": {
      "en": "cht",
      "zh_cn": "繁体中文",
      "zh_tw": "正體中文"
    },
    "name": "繁體中文",
    "syn_lowercase": [
      "繁體中文",
      "繁體",
      "cht",
      "big5",
      "繁体中文",
      "正體中文",
      "繁體外掛"
    ],
    "synonyms": [
      "繁體中文",
      "繁體",
      "cht",
      "BIG5",
      "繁体中文",
      "正體中文",
      "繁體外掛"
    ],
    "type": "lang"
  }
]
```
* note:
  * `query` mostly to be a title.

#### Fetch tag data
* path: `/api/tag/fetch`
* method: `POST`
* post/type-object:
```javascript
{
	"_id": "548f0434f892774b140ac64c"
}
```
* return/type-object:
```javascript
{
  "_id": "548f0434f892774b140ac64c",
  "activity": 0,
  "locale": {
    "ja": "天体のメソッド",
    "zh_cn": "天体的方式",
    "zh_tw": "天體運行式",
    "en": "Sora no Method"
  },
  "name": "天体のメソッド",
  "syn_lowercase": [
    "天体のメソッド",
    "天体的秩序",
    "天体运行式",
    "天体的方式",
    "天體運行式",
    "sora no method"
  ],
  "synonyms": [
    "天体のメソッド",
    "天体的秩序",
    "天体运行式",
    "天体的方式",
    "天體運行式",
    "Sora no Method"
  ],
  "type": "bangumi"
}
```
* post/type-array:
```javascript
{
	"_ids": [
		"548f0434f892774b140ac64c",
		"54900139ab830e195bf7cb40"
	]
}
```
* return/type-array:
```javascript
[
  {
    "_id": "548f0434f892774b140ac64c",
    "activity": 0,
    "locale": {
      "ja": "天体のメソッド",
      "zh_cn": "天体的方式",
      "zh_tw": "天體運行式",
      "en": "Sora no Method"
    },
    "name": "天体のメソッド",
    "syn_lowercase": [
      "天体のメソッド",
      "天体的秩序",
      "天体运行式",
      "天体的方式",
      "天體運行式",
      "sora no method"
    ],
    "synonyms": [
      "天体のメソッド",
      "天体的秩序",
      "天体运行式",
      "天体的方式",
      "天體運行式",
      "Sora no Method"
    ],
    "type": "bangumi"
  },
  {
    "_id": "54900139ab830e195bf7cb40",
    "activity": 0,
    "locale": {
      "ja": "トリニティセブン 7人の魔書使い",
      "zh_cn": "TRINITY SEVEN 魔道书7使者",
      "zh_tw": "TRINITY SEVEN 魔道書7使者",
      "en": "TRINITY SEVEN"
    },
    "name": "トリニティセブン 7人の魔書使い",
    "syn_lowercase": [
      "トリニティセブン 7人の魔書使い",
      "trinity seven 魔道书7使者",
      "trinity seven 魔道書7使者",
      "trinity seven",
      "七人魔法使",
      "魔道書7使者"
    ],
    "synonyms": [
      "トリニティセブン 7人の魔書使い",
      "TRINITY SEVEN 魔道书7使者",
      "TRINITY SEVEN 魔道書7使者",
      "TRINITY SEVEN",
      "七人魔法使",
      "魔道書7使者"
    ],
    "type": "bangumi"
  }
]
```
