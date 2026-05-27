# Codex 宠物合集

这个仓库打包了两只本地 Codex 桌面宠物。

## 宠物

- `luoxi` - 查看 `pets/luoxi/pet.json`
- `cartethyia` - 查看 `pets/cartethyia/pet.json`

每个宠物目录都包含：

- `pet.json`
- `spritesheet.webp`

贴图文件是带透明通道的 `1536x1872` WebP 文件，符合 Codex 宠物图集布局。

## 本地安装

把宠物目录复制到 Codex 的宠物目录：

```powershell
Copy-Item -Recurse -Force .\pets\luoxi "$env:USERPROFILE\.codex\pets\luoxi"
Copy-Item -Recurse -Force .\pets\cartethyia "$env:USERPROFILE\.codex\pets\cartethyia"
```

