# RASUN

全栈仓库。前端、后台、合约、测试分目录存放，并用同名长期分支并行开发，完成后合回 `main`。

## 目录与分支

| 目录 | 分支 | 用途 |
| --- | --- | --- |
| `frontend/` | `frontend` | 前端 |
| `backend/` | `backend` | 后台 |
| `contracts/` | `contract` | 合约 |
| `test/` | `test` | 测试 |

`main` 是集成主分支，四套代码都在这里汇合。

## 用法

在对应分支上开发，再合并回 `main`。

```bash
git checkout frontend
# 改 frontend/ 后提交
git checkout main
git merge frontend
```

后台、合约、测试把分支名换成 `backend`、`contract`、`test` 即可。
