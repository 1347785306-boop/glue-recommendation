# 热熔胶智能推荐系统

## 部署步骤

### 1. 部署到 Vercel

#### 方式A：通过 GitHub 部署（推荐）

1. **创建 GitHub 仓库**
   - 访问 https://github.com/new
   - 仓库名：`glue-recommendation`
   - 选择公开或私有
   - 点击创建

2. **上传文件**
   - 点击 "uploading an existing file"
   - 上传 `index.html` 和 `vercel.json`
   - 提交更改

3. **部署到 Vercel**
   - 访问 https://vercel.com/new
   - 导入 GitHub 仓库 `glue-recommendation`
   - 点击 Deploy
   - 等待部署完成，获得域名

#### 方式B：直接上传（更简单）

1. 访问 https://vercel.com/new
2. 选择 "Upload" 选项
3. 直接上传 `index.html` 文件
4. 点击 Deploy

### 2. 配置飞书应用

1. 登录 https://open.feishu.cn/
2. 进入应用管理页面
3. 点击「网页应用」
4. 修改首页地址为 Vercel 部署的链接
5. 发布应用

### 3. 同事使用

- 在飞书工作台找到应用
- 点击即可使用

## 功能特性

- 智能产品推荐
- 飞书数据实时同步
- 业务权限价和建议销售价显示
- 利润空间计算
