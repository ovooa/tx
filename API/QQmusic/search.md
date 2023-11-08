
---
- [搜索音乐](#搜索音乐)
---

## 搜索音乐

> https://u.y.qq.com/cgi-bin/musicu.fcg

*请求方式：POST*

<details>
<summary>提交数据：</summary>

```json
{
        "comm": {
            "ct": "19",
            "cv": "1910"
        },
        "music": {
            "method": "DoSearchForQQMusicDesktop",
            "module": "music.search.SearchCgiService",
            "param": {
                "grp": 1, //多版本
                "num_per_page": 1, //搜索页数
                "page_num": 1, //数据返回条数
                "query": "" //搜索的歌名
            }
        }
    }
```

</details>

