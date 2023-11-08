
---

- [搜索音乐](#搜索音乐)

---

## 搜索音乐

> https://u.y.qq.com/cgi-bin/musicu.fcg

*请求方式：POST*

**提交数据**
<details>
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
                "grp": 1,
                "num_per_page": 1,
                "page_num": 1,
                "query": ""
            }
        }
    }
```

</details>

