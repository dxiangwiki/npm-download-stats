简体中文 | [English](./README.md)

# NPM包历史总下载量查询工具
一个纯前端网页工具，用于查询 NPM 包的历史累计下载量。

## 功能特性
- 查询单个NPM包下载统计数据
- 根据NPM作者用户名批量查询其全部公开包
- 自动生成每日下载量SVG趋势图表
- 中英文界面切换
- 深色/浅色主题切换
- 在本地存储（localStorage）保存语言与主题偏好
- 无需后端，直接调用 npm registry 和下载量官方API

## 使用方法
1. 切换查询模式：`Single Package Query`（单包查询） / `Batch by Author`（按作者批量查询）
2. 输入包名或者NPM作者用户名
3. 点击 Query 查询按钮
4. 查看累计下载数据与趋势图表

> 注意事项：
> 1. 受 NPM 官方API限流限制。如果作者名下包数量很多，批量查询可能出现部分查询失败。
> 2. 下载统计数据仅能追溯到约2015年之后。
> 3. 中国大陆用户访问 NPM 官方API可能遇到网络超时。

## 部署
你可以直接将项目部署到 GitHub Pages：
1. Fork 或者克隆这个仓库
2. 在仓库设置里开启 GitHub Pages，源设置为 `main` 分支 / 根目录
3. 访问你的 Pages 站点

## 开源协议
MIT License
Copyright (c) 2026 Dong Xiang
