# Desktop Pets

这里收集可用于桌面宠物程序的动画角色资源。

## 仓库结构

每个作品单独放在 `pets/` 下，每个角色使用自己的文件夹：

```text
pets/
└─ 作品名/
   ├─ README.md
   └─ 角色名/
      ├─ pet.json
      ├─ spritesheet.webp
      └─ preview.png
```

## Codex 使用方法

Codex v2 宠物需要将 `pet.json` 和 `spritesheet.webp` 放在同一个宠物目录中。Windows 默认目录为：

```text
C:\Users\你的用户名\.codex\pets\角色名\
```

复制文件后，完全退出并重新打开 Codex，再在宠物设置中选择对应角色。

## 图集格式

当前动画资源使用 8×11 图集：

- 每格尺寸：`192×208`
- 图集尺寸：`1536×2288`
- 前 9 行：标准动作
- 后 2 行：16 个视线方向
- `spriteVersionNumber`：`2`

其他支持 Sprite Sheet 的桌面宠物程序也可以使用 `spritesheet.webp`。如果程序不支持 WebP，可使用同目录的 `preview.png`，并按 `192×208` 设置帧尺寸。

## 版权说明

其中的同人角色属于原作权利方。本仓库仅用于个人学习、展示和非商业桌面宠物使用。
