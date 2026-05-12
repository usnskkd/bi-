[README.md](https://github.com/user-attachments/files/27641820/README.md)
# 鱼智能 BI（Vue3 版）

本项目已从 `React + Umi + Ant Design Pro` 完整迁移为：

- Vue 3
- Vite
- TypeScript
- Pinia
- Vue Router
- Ant Design Vue
- Axios
- ECharts（`vue-echarts`）

## 开发

推荐使用 `pnpm`：

```bash
pnpm install
pnpm dev
```

默认本地启动端口：`8000`

## 构建

```bash
pnpm build
pnpm preview
```

## 类型检查

```bash
pnpm typecheck
```

## 路由

- `/user/login` 登录页
- `/add_chart` 智能分析
- `/add_chart_async` 智能分析（异步）
- `/my_chart` 我的图表
- `/admin` 管理页（仅 admin）
- `/welcome` 欢迎页

## 后端联调

请求配置位于 `src/services/request.ts`：

- `baseURL`: `http://localhost:8080`
- `withCredentials`: `true`

如需改后端地址，直接修改该文件即可。
