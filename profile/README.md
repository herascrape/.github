# herascrape

Instagram private API for developers. 37 real-time `GET` endpoints for profiles,
followers and following, posts, reels, stories, highlights, comments, likers,
hashtags, locations, audio and search, returned as Instagram's own JSON.
$0.0004 per successful call, flat. Failed calls are not billed.

| Repository | What it is |
| --- | --- |
| [herascrape](https://github.com/herascrape/herascrape) | Python and TypeScript client: `pip install herascrape` · `npm i herascrape` |
| [herascrape-mcp](https://github.com/herascrape/herascrape-mcp) | Instagram MCP server for Claude, Cursor, VS Code and other AI agents |
| [hikerapi-to-herascrape](https://github.com/herascrape/hikerapi-to-herascrape) | Migrate from HikerAPI with one coding-agent prompt |
| [instagram-video-downloader](https://github.com/herascrape/instagram-video-downloader) | Free Instagram downloader for reels, videos, photos and stories |

```python
from herascrape import Client

client = Client(api_key="hs_live_xxxxxxxx")
user = client.user_by_username(username="instagram")
print(user["username"], user["follower_count"])
```

[Website](https://herascrape.com) · [Docs](https://herascrape.com/docs) ·
[API reference](https://api.herascrape.com/docs) · [Pricing](https://herascrape.com/pricing)
