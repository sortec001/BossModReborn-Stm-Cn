# BossModReborn-Stm-Cn

国服卫月 **BossModReborn** 插件分发库（STM / 简体中文）。

## 安装

在卫月 **第三方插件仓库** 添加：

```
https://raw.githubusercontent.com/sortec001/BossModReborn-Stm-Cn/main/pluginmaster.json
```

## 发版（维护者）

1. 在 `F:\FFIX\FFXIVWY\BossmodReborn` 更新 `BossMod\BossModReborn.json`（`AssemblyVersion`、`Changelog`）
2. `dotnet build BossMod\BossModReborn.csproj -c Release`
3. 确认本目录 `pluginmaster.json` 与 `release/BossModReborn/latest.zip`
4. `git add` → `commit` → `push origin main`

## 免责声明

第三方插件，使用风险自负；与 Square Enix / 国服运营商无关联。
