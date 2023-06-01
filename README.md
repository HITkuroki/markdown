# hithit-back-python


## API List
### 收藏模块
- 收藏番剧
- /animedetail POST
- 请求数据格式
```
Mid: 番剧id
Uid：用户id
```
- 响应数据格式
```json
{
code:"0"
data:null
msg:"成功"
}
```
收藏成功后，收藏量改变
当Uid为空时，显示用户未登录，登录后再进行收藏

取消番剧收藏

收藏文章

取消文章收藏

获取番剧收藏状态

获取文章收藏状态

获取番剧收藏列表

获取文章收藏列表

### 评价模块

评论

获取评论列表

删除评论

文章点赞

获取文章点赞状态

番剧点赞

获取番剧点赞状态

番剧评分

获取番剧平均评分

获取个人番剧评分

### 详情
获取番剧详情信息

获取文章详情信息

### 文章管理
上传图片？干嘛的

上传文章

获取已发布文章列表

删除文章

编辑文章

### 用户管理
**用户登录**

- Post /user/login

  |   参数   | 参数说明 | 备注 |
  | :------: | :------: | :--: |
  | account  |   账号   |      |
  | password | 登录密码 |      |

  

- 响应参数

  |  参数  | 参数说明 | 备注 |
  | :----: | :------: | :--: |
  |  flag  |   状态   |      |
  | errMsg | 错误信息 |      |

  

**用户注册**

- Post /user/register

  |   参数   | 参数说明 | 备注 |
  | :------: | :------: | :--: |
  | account  |   账号   |      |
  | password | 登录密码 |      |
  | username |  用户名  |      |

- 响应参数

  |  参数  | 参数说明 | 备注 |
  | :----: | :------: | :--: |
  |  flag  |   状态   |      |
  | errMsg | 错误信息 |      |



**用户信息编辑**

- Post /user/edit

  |   参数    | 参数说明 | 备注 |
  | :-------: | :------: | :--: |
  | username  |  用户名  |      |
  | password  | 登录密码 |      |
  | headimage | 用户头像 |      |

- 响应参数

  

### 后台管理

后台用户查询

后台番剧查询

后台文章查询

删除文章

注销用户

用户授权

删除番剧

上传番剧信息

修改番剧信息（？

获取番剧tag列表

更新番剧tag列表

审核评论

获取待审核评论

获取待审核文章

审核文章

### 信息检索模块

精确搜索（返回番剧和文章的列表）

按Tag搜索（返回番剧和文章的列表）







