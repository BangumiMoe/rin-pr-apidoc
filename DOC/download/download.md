### Download

#### Download torrent file
* path: `/download/torrent/:tid/:filename`
* method: `GET`
* params:
  * `tid`: torrent id
  * `filename`: torrent file name - could be any valid filename, this option is only for browsers to save file with a readable name.
* returns: `[ArrayBuffer]`
* example: `GET /download/torrent/550b329e6b21765755f4962a/kancolle.11.torrent`
