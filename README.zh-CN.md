<h1 align="center">Codex Pets</h1>

<p align="center"><strong>让角色陪伴你的桌面。</strong><br>面向 Codex 的非官方角色桌宠合集。</p>

<p align="center"><a href="README.md">English</a> · <strong>简体中文</strong></p>

<p align="center">
  <img src="https://img.shields.io/badge/pets-83-8F9FFF?style=flat-square" alt="83 个桌宠">
  <img src="https://img.shields.io/badge/sprite_atlas-v1_%2B_v2-70CFC0?style=flat-square" alt="支持 v1 和 v2 图集">
  <img src="https://img.shields.io/badge/collection-fan--made-D5AD79?style=flat-square" alt="非官方粉丝创作合集">
</p>

<p align="center">
  <a href="#宠物合集"><strong>浏览宠物</strong></a> ·
  <a href="#快速开始">快速开始</a> ·
  <a href="#包格式">包格式</a> ·
  <a href="https://github.com/MarkYang44/codex-pet/issues">反馈问题</a>
</p>

## 动画预览

![六个宠物的实际待机动画：Shirao Eri、Hina Maid、Misono Mika、Plana Ex、Kozeki Maid 和 Clawd](docs/images/pet-lineup.gif)

[Shirao Eri](shirao-eri/) · [Hina Maid](hina-maid/) · [Misono Mika](misono-mika/) · [Plana Ex](plana-ex/) · [Kozeki Maid](kozeki-maid/) · [Clawd](clawd-4/)

预览取自仓库图集中的实际待机帧，播放速度为展示设置。[预览制作说明](docs/images/README.md)。

## 项目介绍

选一个喜欢的角色，复制它的文件夹，再到 Codex 中选择使用。每个宠物包都包含元数据、透明 WebP 动画图集和独立安装说明，素材本身无需编译。

- **83 个可直接复制的宠物包**，涵盖像素角色、插画风角色和吉祥物。
- **保留两代图集布局**：71 个 v1、12 个 v2，每个包都明确标注版本。
- **统一打包规范**：整个合集采用一致的元数据字段和文件结构。

## 快速开始

需要使用支持自定义宠物包的 Codex 桌面版本。动画播放和宠物选择由应用提供。

1. [下载仓库 ZIP](https://github.com/MarkYang44/codex-pet/archive/refs/heads/main.zip) 并解压，或克隆本仓库。
2. 从[宠物合集](#宠物合集)选择角色，将它的**整个文件夹**复制到 Codex 宠物目录；目录不存在时可自行创建。

   | 系统 | 默认宠物目录 |
   | --- | --- |
   | macOS | `~/.codex/pets/` |
   | Windows | `%USERPROFILE%\.codex\pets\` |

3. `pet.json` 与 `spritesheet.webp` 必须放在同一个角色文件夹内，位于宠物目录下一层。例如：

   ```text
   .codex/pets/plana-ex/
   ├── README.md
   ├── pet.json
   └── spritesheet.webp
   ```

4. 重新打开 Codex，在宠物选择器中选择对应的显示名称，例如 **Plana Ex**。

复制角色文件夹即可，不要把最外层的 `codex-pet-main` 当作角色文件夹。替换已有角色前请先备份。如果宠物未出现，先核对上面的目录层级，再确认应用支持该图集版本。

## 宠物合集

**共 83 个宠物包 · 71 个 v1 · 12 个 v2。** 点击名称可查看对应宠物的文件和 README；不同服装与角色变体使用独立文件夹。

<details>
<summary><strong>展开全部 83 个宠物 · 按文件夹名称排序</strong></summary>

| 宠物 | 文件夹 | 图集 |
| --- | --- | --- |
| [Aikiyo Fuka](aikiyo-fuka/) | `aikiyo-fuka` | v1 |
| [Akeboshi Himari](akeboshi-himari/) | `akeboshi-himari` | v1 |
| [AL-1S Armed](al-1s-armed/) | `al-1s-armed` | v1 |
| [AL-1S Maid](al-1s-maid/) | `al-1s-maid` | v1 |
| [AL-1S Winter](al-1s-winter/) | `al-1s-winter` | v1 |
| [Arona](arona-v1/) | `arona-v1` | v1 |
| [Asuma Toki](asuma-toki/) | `asuma-toki` | v1 |
| [Azusa](azusa/) | `azusa` | v1 |
| [Clawd](clawd-4/) | `clawd-4` | v1 |
| [Hakari Atsuko](hakari-atsuko/) | `hakari-atsuko` | v1 |
| [Hina Kimono](hina-kimono/) | `hina-kimono` | v2 |
| [Hina Maid](hina-maid/) | `hina-maid` | v2 |
| [Hina Pajama](hina-pajama/) | `hina-pajama` | v1 |
| [Hina Uniform](hina-uniform/) | `hina-uniform` | v1 |
| [Hoshino Hanfu](hoshino-hanfu/) | `hoshino-hanfu` | v2 |
| [Hoshino Junior](hoshino-junior/) | `hoshino-junior` | v1 |
| [Igusa Haruka](igusa-haruka/) | `igusa-haruka` | v1 |
| [Itagaki Kanoe](itagaki-kanoe/) | `itagaki-kanoe` | v1 |
| [Kadenokoji Yukari](kadenokoji-yukari/) | `kadenokoji-yukari` | v1 |
| [Kasuga Tsubaki](kasuga-tsubaki/) | `kasuga-tsubaki` | v1 |
| [Kei](kei/) | `kei` | v1 |
| [Kei Anothermaid](kei-anothermaid/) | `kei-anothermaid` | v1 |
| [Kei Maid](kei-maid/) | `kei-maid` | v1 |
| [Kinui Rena](kinui-rena/) | `kinui-rena` | v1 |
| [Kirifuji Nagisa](kirifuji-nagisa/) | `kirifuji-nagisa` | v1 |
| [Kiryu Kikyo](kiryu-kikyo/) | `kiryu-kikyo` | v1 |
| [Kisaki Swimsuit](kisaki-swimsuit/) | `kisaki-swimsuit` | v1 |
| [Kiyosumi Akira](kiyosumi-akira/) | `kiyosumi-akira` | v1 |
| [Kozeki Maid](kozeki-maid/) | `kozeki-maid` | v2 |
| [Kuromi Serika](kuromi-serika/) | `kuromi-serika` | v1 |
| [Kurosaki Koyuki](kurosaki-koyuki/) | `kurosaki-koyuki` | v1 |
| [Kurumi JK](kurumi-jk/) | `kurumi-jk` | v1 |
| [Kurumi Maid](kurumi-maid/) | `kurumi-maid` | v1 |
| [Kurumi Uniform](kurumi-uniform/) | `kurumi-uniform` | v1 |
| [Kyoyama Kazusa](kyoyama-kazusa/) | `kyoyama-kazusa` | v1 |
| [Mari Gym](mari-gym/) | `mari-gym` | v1 |
| [Mari Maid](mari-maid/) | `mari-maid` | v2 |
| [Mayoi Shigure](mayoi-shigure/) | `mayoi-shigure` | v1 |
| [Miko Serika](miko-serika/) | `miko-serika` | v1 |
| [Misaka Mikoto](misaka-mikoto/) | `misaka-mikoto` | v1 |
| [Misono Mika](misono-mika/) | `misono-mika` | v1 |
| [Mitsuki Robe](mitsuki-robe/) | `mitsuki-robe` | v1 |
| [Miyoshi Takane](miyoshi-takane/) | `miyoshi-takane` | v1 |
| [Morizuki Suzumi](morizuki-suzumi/) | `morizuki-suzumi` | v1 |
| [Nagisa Maid](nagisa-maid/) | `nagisa-maid` | v2 |
| [Neuro-sama](neuro-sama/) | `neuro-sama` | v1 |
| [Niko Delivery](niko-delivery/) | `niko-delivery` | v1 |
| [Niko JK](niko-jk/) | `niko-jk` | v1 |
| [Niko Maid (pt.2)](niko-maid-pt-2/) | `niko-maid-pt-2` | v2 |
| [Niyaniya Maid](niyaniya-maid/) | `niyaniya-maid` | v1 |
| [Niyaniya Uniform](niyaniya-uniform/) | `niyaniya-uniform` | v2 |
| [Otogi Maid](otogi-maid/) | `otogi-maid` | v1 |
| [Otogi Maid (pt.2)](otogi-maid-pt-2/) | `otogi-maid-pt-2` | v2 |
| [Otogi Uniform](otogi-uniform/) | `otogi-uniform` | v2 |
| [Plana](plana/) | `plana` | v1 |
| [Plana Ex](plana-ex/) | `plana-ex` | v2 |
| [President(?)](president/) | `president` | v1 |
| [Prof Niyaniya](prof-niyaniya/) | `prof-niyaniya` | v1 |
| [Professor Maid](professor-maid/) | `professor-maid` | v1 |
| [Sakurai Miyo](sakurai-miyo/) | `sakurai-miyo` | v1 |
| [Seia](seia/) | `seia` | v1 |
| [Seia Maid](seia-maid/) | `seia-maid` | v2 |
| [Serika Idol](serika-idol/) | `serika-idol` | v1 |
| [Sexy Seia](sexy-seia/) | `sexy-seia` | v1 |
| [Shichido Yukino](shichido-yukino/) | `shichido-yukino` | v1 |
| [Shiranui Kaya](shiranui-kaya/) | `shiranui-kaya` | v1 |
| [Shirao Eri](shirao-eri/) | `shirao-eri` | v1 |
| [Shiroko](shiroko/) | `shiroko` | v1 |
| [Sorasaki Hina](sorasaki-hina/) | `sorasaki-hina` | v1 |
| [Sumi Serina](sumi-serina/) | `sumi-serina` | v1 |
| [Tachibana Nozomi](tachibana-nozomi/) | `tachibana-nozomi` | v1 |
| [Takakura Kurumi](takakura-kurumi/) | `takakura-kurumi` | v1 |
| [Takanashi Hoshino](takanashi-hoshino/) | `takanashi-hoshino` | v1 |
| [Tendo AL-1S](tendo-al-1s/) | `tendo-al-1s` | v1 |
| [Tenjinyama Otogi](tenjinyama-otogi/) | `tenjinyama-otogi` | v1 |
| [Tsukiyuki Miyako](tsukiyuki-miyako/) | `tsukiyuki-miyako` | v1 |
| [Kozeki Ui](ui/) | `ui` | v1 |
| [UZ Queen](uz-queen/) | `uz-queen` | v1 |
| [Uzawa Reisa](uzawa-reisa/) | `uzawa-reisa` | v1 |
| [Yoshino Niko](yoshino-niko/) | `yoshino-niko` | v1 |
| [Yukino Maid](yukino-maid/) | `yukino-maid` | v1 |
| [Yuuka Pajama](yuuka-pajama/) | `yuuka-pajama` | v1 |
| [Yuzu Maid](yuzu-maid/) | `yuzu-maid` | v1 |

</details>

## 包格式

```text
<pet-folder>/
├── README.md          # 角色说明、安装方法与版权信息
├── pet.json           # 元数据与图集版本
├── spritesheet.webp   # 透明动画图集
└── preview.png        # 可选预览，部分包附带
```

`pet.json` 使用 UTF-8、两空格缩进和末尾换行，字段顺序如下。示例取自 [Plana Ex](plana-ex/pet.json)：

```json
{
  "id": "plana-ex",
  "displayName": "Plana Ex",
  "description": "A petite white-haired anime girl with a dark navy raincoat, lace-edged black parasol, pink halo, and white ribbon, preserving the supplied reference pose and proportions.",
  "spriteVersionNumber": 2,
  "spritesheetPath": "spritesheet.webp",
  "kind": "person"
}
```

| 图集版本 | 尺寸 | 宠物数量 |
| --- | --- | --- |
| v1 | 1536 × 1872 | 71 |
| v2 | 1536 × 2288 | 12 |

版本标记必须与实际图集布局一致。`spritesheetPath` 统一使用相对文件名 `spritesheet.webp`；`kind` 按角色类型使用 `person` 或 `animal`。已有宠物 ID 保持稳定，可以与文件夹名称不同。

## 参与贡献

新增宠物时，请使用唯一文件夹名称，附带对应 README，并遵循上面的包格式。提交 Pull Request 前检查 ID、版本、尺寸、透明通道以及图集能否正常解码。生成工作目录、验证报告、临时文件和重复压缩包不纳入合集。

如果发现包有问题，请在 [Issues](https://github.com/MarkYang44/codex-pet/issues) 中提供宠物文件夹名称、应用版本和问题现象。

## 版权与使用说明

本项目为非官方粉丝创作合集，用于个人学习、展示和非商业分享。角色名称、图像及相关权利归各自权利方所有。本项目与 OpenAI 及原角色权利方不存在隶属或官方背书关系，仓库不对第三方角色或图像授予统一使用许可。

<p align="center">由 <a href="https://github.com/MarkYang44">Mark Yang</a> 整理维护</p>
