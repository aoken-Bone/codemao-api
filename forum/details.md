# 帖子信息

> 获取帖子信息  
> `/web/forums/posts/<forum_id>/details` `GET`

## 返回内容

|           key           |              value               |  type  |
| :---------------------: | :------------------------------: | :----: |
|           id            |             帖子 ID              | string |
|          user           |      （[查看详情](#user)）       |  JSON  |
|       avatar_url        |             头像链接             | string |
|          email          |             邮箱地址             | string |
|          gold           |              金币数              |  int   |
|           qq            |             QQ 号码              | string |
|        real_name        |             真实姓名             | string |
|           sex           | 性别（`FEMALE`为女，`MALE`为男） | string |
|        username         |              用户名              | string |
|     voice_forbidden     |            是否被禁言            |  bool  |
|        birthday         |            生日时间戳            |  int   |
|       description       |             自我描述             | string |
|      phone_number       | 手机号（格式：123\*\*\*\*4567）  | string |
|       create_time       |          用户创建时间戳          |  int   |
|         oauths          |               `略`               |  JSON  |
|      has_password       |           是否设置密码           |  bool  |
|        user_type        |              `未知`              |  int   |
|     show_guide_flag     |              `未知`              |  int   |
|       has_signed        |       是否签订《友好契约》       |  bool  |
| has_seen_primary_course |              `未知`              |  int   |
|      author_level       |             用户等级             |  int   |

### user

|     key     |     value     |  type  |
| :---------: | :-----------: | :----: |
|     id      |    用户 ID    | string |
|  nickname   |     昵称      | string |
| avatar_url  |   头像 URL    | string |
| subject_id  | 用户工作室 ID | string |
| description |   自我描述    | string |
|    doing    |  正在做的事   | string |
|    level    |   用户等级    |  int   |

> 更新于 2021.05.14
