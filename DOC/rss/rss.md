### RSS API

#### Get latest RSS feed
* path: `/rss/latest`
* method: `GET`
* return: <RSS Object>

#### Get RSS feed with tags filter
* path: `/rss/tags/<tag_ids>`
* method: `GET`
* return: <RSS Object>
* notes:
  * `tag_ids` can be one tag id or many tag ids concatenate with `+`. E.g., `/rss/tags/550fd9df1fe5c31a190a068d` or `/rss/tags/550fd9df1fe5c31a190a068d+548edfb54ab7379536f56351`.

#### Get user RSS feed
* path: `/rss/user/user_id`
* method: `GET`
* return <RSS Object>
* notes:
  * This method returns RSS object under the user's specific tag filters. User could define one or multiple tags for a filter, and the feed contains all search results meet these filter rules.

#### Common queries

##### Item limits
* param: `limit`
* desc: This parameter specifies the amount of items included in the RSS object. There is a default item amount and a hard-limited amount defined per site configuration.
* example: `GET` `/rss/latest?limit=150`

#### Use torrent ID instead of title
* param: `useid`
* desc: In some system that does not have CJK support may encounter error while downloading torrent files via default RSS enclosure. Set `useid` to `true` to use torrent ID as filename to avoid these errors.
* example: `GET` `/rss/latest?useid=true`
