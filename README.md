# codex-pet
Store fan-made desktop pets in codex

This is an unofficial fan-made desktop pet. Character rights belong to their respective owners.

本项目仅为非官方粉丝创作桌面宠物，用于个人学习、展示和非商业分享。原角色及相关权利归其各自权利方所有。

## Package format / 宠物包格式

Each pet lives in its own folder. 每个宠物使用独立文件夹，并包含以下文件：

```text
<pet-folder>/
  README.md
  pet.json
  spritesheet.webp
  preview.png       # optional / 可选
```

- `README.md`：角色说明、安装方式、文件结构及版权说明。
- `pet.json`：UTF-8、两空格缩进、末尾换行；字段顺序统一为 `id`、`displayName`、`description`、`spriteVersionNumber`、`spritesheetPath`、`kind`。
- `spriteVersionNumber`：保留图集实际版本，v1 为 `1536 × 1872`，v2 为 `1536 × 2288`。仅补齐版本标记，不转换动画布局。
- `spritesheetPath`：统一使用相对路径 `spritesheet.webp`；当前角色包的 `kind` 均为 `person`。
- `preview.png`：可选预览，已有文件保留。宠物 ID 保持稳定，不要求与文件夹名称一致。

Import complete pet packages only; skip pets already present. 临时生成目录、验证报告和重复压缩包不作为宠物包导入。
