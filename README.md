# Moments Marketplace

朋友圈专家市场 - 专为教练/咨询师设计的朋友圈内容专家集合。

## 包含专家

| 专家 | 说明 |
|------|------|
| **朋友圈文案师** (moments-writer) | 把日常琐碎写成让人愿意停下来读完的朋友圈文案 |
| **朋友圈导演** (moments-director) | 连续剧式朋友圈营销导演，每天生成3-5条自然流淌文案 |

## 安装方式

### 方式一：本地路径安装

将本目录放到任意位置，然后在 WorkBuddy 中执行：

```
/plugin marketplace add /path/to/moments-marketplace
```

### 方式二：GitHub 仓库安装（推荐）

将本目录推送到 GitHub 仓库后，其他人执行：

```
/plugin marketplace add your-username/moments-marketplace
```

### 安装专家

添加市场后，安装专家：

```
/plugin install moments-writer@moments-marketplace
/plugin install moments-director@moments-marketplace
```

或者打开交互式管理器：`/plugin` → 发现标签页 → 选择安装。

## 更新

修改专家提示词后，重新推送到仓库。用户端执行：

```
/plugin marketplace update moments-marketplace
```

即可获取最新版本。

## License

MIT
