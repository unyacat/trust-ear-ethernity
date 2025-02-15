# Trust Ear Ethernity
水瀬いのりさんのクリップ

## リンク
[https://trust-ear-ethernity.vercel.app/](https://trust-ear-ethernity.vercel.app/)


## フォーマット
```
{
  "title": "水瀬いのり"  # 利用していない
  "clips": [
    ...
    {
      "display_name": ""   # クリップの内容を短く示す
      "trasncription": ""  # クリップの完全な書き起こし
      "youtube_link": ""   # YouTubeのリンク先
      "source_name": ""    # 元ネタ名
      "start_time": ""     # 動画においてクリップが始まる時間(秒)
      "duration": ""       # クリップの長さ
    }
    ...
  ]
}
```

`start_time`、`duration`は、
`ffmpeg -i "source.mp3" -ss ${start_time} -t ${duration} output.mp3`
で確かめることができます。




