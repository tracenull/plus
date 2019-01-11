---
title: 用户接口
---

## 权限节点

```
GET /api/v2/user/abilities
```

响应：

```
Status: 200 OK
```
```json5
[
    {
        "name": "[feed] Delete Feed",     // 权限唯一标识
        "display_name": "[动态]->删除动态", // 权限显示名称
        "description": "删除动态权限"       // 权限描述
    }
]
```