# 网易云音乐 API 整理

> ⚠️ 官方未公开接口，仅供学习。

---

## 歌曲详情

```
https://music.163.com/api/song/detail?ids=[{歌曲id}]
```

### 示例

```
https://music.163.com/api/song/detail?ids=[1830419924]
```

---

## 搜索接口

```
https://music.163.com/api/search/get
```

### 示例

```
https://music.163.com/api/search/get?s=Peaches&type=1
```

### 参数

| 参数   | 说明                     |
|--------|--------------------------|
| s      | 搜索关键词               |
| type   | 类型（1为单曲）           |
| offset | 偏移量（分页）           |
| limit  | 返回数量      |

---

## 歌词

```
https://music.163.com/api/song/media?id={歌曲ID}
```

### 示例

```
https://music.163.com/api/song/media?id=1830419924
```

---

## 双语歌词

```
https://music.163.com/api/song/lyric?id={歌曲ID}&lv=-1&tv=-1
```

### 示例

```
https://music.163.com/api/song/lyric?id=1830419924&lv=-1&tv=-1
```
