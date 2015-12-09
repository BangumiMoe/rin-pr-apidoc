### Torrent API

#### Get torrent page per page
* path: `/api/torrent/page/:pagenum`
* method: `GET`
* params:
  * pagenum: <number>
* return:
```javascript
{
	page_count: 100,
	"torrent": <Array>
}
```

#### Get torrents published by self
* path: `/api/torrent/my`
* method: `GET`
* return:
```javascript
{
	"page_count": <number>,
	"torrents": <Array>
}
```
* note:
  * user session required.

#### Get torrents published by team
* path: `/api/torrent/team`
* method: `GET`
* return:
```javascript
(TODO)
```

#### Search torrent by tag_id
* path: `/api/torrent/search`
* methid: `POST`
* post:
```javascript
{
	tag_id: <string>|<Array>,
  p: <number (optional)>
}
```
* return (with count & page_count only when page is 1):
```javascript
{
  "count": <number>,
  "page_count": <number>,
  "torrents": <Array>
}
```

#### Search torrent by title
* path: `/api/torrent/search/title`
* methid: `POST`
* post:
```javascript
{
  title: <string>,
  p: <number (optional)>
}
```
* return (with count & page_count only when page is 1):
```javascript
{
  "count": <number>,
  "page_count": <number>,
  "torrents": <Array>
}
```
