# 山城选题日报

[![GitHub Pages](https://github.com/flyyq135/shancheng-daily-preview/actions/workflows/pages.yml/badge.svg)](https://github.com/flyyq135/shancheng-daily-preview/actions/workflows/pages.yml)

面向重庆房产经纪人的内容选题与运营日报。每天整理已核验的全国房产政策、重庆楼市资讯、本地热点和区域动态，并将信息转化为可拍摄、可复用的客户向选题。

> 在线阅读：[重庆楼市选题日报](https://flyyq135.github.io/shancheng-daily-preview/)

![山城选题日报](assets/chongqing-city-banner-title-designed.png)

## 日报包含什么

- **资讯速递**：全国房产、重庆房产、重庆本地热点与贝壳重庆楼市周报。
- **区域聚焦**：两江新区、渝中、南岸、沙坪坝、九龙坡、巴南、大渡口、北碚 8 个重点区域动态。
- **购房百科**：围绕贷款、税费、合同、产权、过户、验房和物业等实操问题整理官方依据。
- **选题推荐**：将政策、数据和城市变化转化为客户能听懂、经纪人能落地拍摄的内容角度。
- **灵感补给**：提供不依赖当日热点的常青选题，便于持续更新账号内容。

## 仓库说明

本仓库是日报的 **GitHub Pages 静态发布镜像**，保存最新一期页面、历史归档和企微分发文件，不包含完整采集与生产源码。

| 路径 | 用途 |
|---|---|
| `index.html` | 最新一期日报入口 |
| `report-data.js` | 最新一期页面数据 |
| `archive/YYYY/MM/DD/` | 按日期保存的历史日报 |
| `archive/index.html` | 往期日报索引 |
| `assets/` | 页面图片与企微封面 |
| `latest-wecom.*` | 企微转发文案与消息卡片数据 |
| `.github/workflows/pages.yml` | GitHub Pages 部署工作流 |

`main` 分支更新后由 GitHub Actions 自动部署到 Pages。查看最新内容请始终访问站点首页；历史内容可从日报内的“往期日报”入口进入。

## 内容与数据说明

- 日报优先使用政府、统计部门、公开政策页及权威媒体等可追溯来源。
- 页面中的“要点总结”用于概括原文事实，创作建议与事实信息分开呈现。
- 房地产政策、市场数据和项目进度可能随时间变化，请以来源页面及主管部门最新发布为准。
- 本项目用于内容研究和选题辅助，不构成购房、投资、法律或金融建议。

## 使用方式

直接访问 [GitHub Pages 站点](https://flyyq135.github.io/shancheng-daily-preview/) 即可，无需安装依赖或本地运行。
