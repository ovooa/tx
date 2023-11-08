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
                "num_per_page": 1,
                "page_num": 1,
                "query": ""
            }
        }
    }
```

| 字段   | 类型 | 内容     | 备注         |
| ------ | ---- | -------- | ------------ |
| query | strin  | 搜索的歌曲名  | 必填      |
| page_num | num | 搜索的页数  | 必填 0也可以 |
| num_per_page     | num  | 返回的数据条数 | 必填 最小值为1       |

</details>