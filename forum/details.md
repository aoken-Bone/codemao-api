# 帖子信息

> 获取帖子信息  
> `/web/forums/posts/<forum_id>/details` `GET`

## 返回内容

|      key      |          value           |  type  |
| :-----------: | :----------------------: | :----: |
| ask_help_flag |       是否为求助帖       |  int   |
|   board_id    |     帖子所在板块 ID      | string |
|  board_name   |     帖子所在板块名称     | string |
|    content    |         帖子内容         | string |
|  created_at   |        发布时间戳        |  int   |
|      id       |         帖子 ID          | string |
| is_authorized |       是否为官方贴       |  bool  |
|  is_featured  |       是否为精选贴       |  bool  |
|   is_hotted   |       是否为热门贴       |  bool  |
|   is_pinned   |       是否为置顶帖       |  bool  |
|  n_comments   | （每个回帖下的）评论数量 |  int   |
|   n_replies   |         回帖数量         |  int   |
|    n_views    |         浏览次数         |  int   |
|     title     |         帖子标题         | string |
| tutorial_flag |       是否为教程帖       |  int   |
|  updated_at   |        更新时间戳        |  int   |

> 更新于 2021.07.16
