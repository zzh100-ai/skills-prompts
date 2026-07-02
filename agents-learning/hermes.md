# 命令

## 配置相关

### 配置模型

```
hermes model
```

---

## 会话

### 列出所有会话

```
hermes sessions list
```

### 删除所有会话

```
hermes sessions prune # 默认删除90天前的会话
hermes sessions prune --older-than 30  # 删除30天前的会话
```

###  交互式选择

```
hermes sessions browse
```

### 删除指定的会话

```
hermes sessions delete <id>
```

### 查看会话存储统计信息

```
hermes sessions stats
```

---