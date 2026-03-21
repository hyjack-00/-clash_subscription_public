# ClashMeta Downstream Mirror

A fork-style public mirror for Clash-compatible artifacts and compatibility files.

## Overview

这个仓库采用 Clash 开源项目下游镜像的门面结构，对外只保留公开产物与兼容性文件。

上游参考项目：

- `MetaCubeX/ClashMetaForAndroid`

当前公开发布内容位于 `dist/`，用于兼容订阅分发与状态查询。

## Repository Layout

- `app/`：保留 fork 风格目录占位
- `common/`：保留公共模块目录占位
- `docs/`：公开说明与发布通道说明
- `dist/config.yaml`：Mihomo/Clash 兼容订阅入口
- `dist/metadata.json`：生成时间、解析方式、节点统计

## Release Channel

Raw 订阅地址保持不变：

`https://raw.githubusercontent.com/hyjack-00/-clash_subscription_public/main/dist/config.yaml`

状态元数据：

`https://raw.githubusercontent.com/hyjack-00/-clash_subscription_public/main/dist/metadata.json`

## Notes

- 这个仓库不包含私有源订阅地址
- 这个仓库不包含 GLM 凭据或推送 token
- 公开目录只保留分发所需产物
