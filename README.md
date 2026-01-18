# 网易云音乐 API 整理

> ⚠️ 非官方接口，仅供学习，可能随时失效。

---

## 歌曲详情

```
https://music.163.com/api/song/detail?ids=[歌曲ID]
```

---

## 搜索接口

```
https://music.163.com/api/search/get
```

### 参数

| 参数   | 说明                     |
|--------|--------------------------|
| s      | 搜索关键词               |
| type   | 类型（1为单曲）           |
| offset | 偏移量（分页）           |
| limit  | 返回数量      |
