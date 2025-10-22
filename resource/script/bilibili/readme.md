# Bilibili 广告拦截规则

## 界面相关广告

### 皮肤推送
```
/x/resource/show/skin
```

### 首页顶部标签页
```
/x/resource/show/tab/v2
```

### 右上角活动入口
```
/x/resource/top/activity
```

## 用户页面相关

### 我的页面
```
/x/v2/account/mine
/x/v2/account/mine/ipad
```

### 会员清晰度
```
/x/v2/account/myinfo
```

## 内容推荐广告

### 首页推荐广告
```
/x/v2/feed/index?
```

### 直播内容和大会员专享
```
/x/v2/feed/index/story
```

## 搜索相关广告

### 热搜广告
```
/x/v2/search/square
```

### 搜索结果推广
```
/bilibili\.polymer\.app\.search\.v1\.Search\/SearchAll$
```

## 观影页面广告

### 观影页广告
```
/pgc/page/bangumi
/pgc/page/cinema/tab
```

## 直播相关广告

### 直播广告
```
/xlive/app-room/v1/index/getInfoByRoom
```

## 开屏广告

### 开屏广告（正则表达式）
```
^https:\/\/app\.bilibili\.com\/x\/v2\/splash\/(brand\/list|event\/list2|list|show)\?
```

### 开屏广告（路径匹配）
```
/x/v2/splash/list
```