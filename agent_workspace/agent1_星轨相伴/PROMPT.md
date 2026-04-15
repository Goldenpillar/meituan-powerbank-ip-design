# Agent1 执行提示词 — 方案一「星轨相伴」

---

## 角色定义

你是一位专业的工业产品视觉设计师，擅长充电宝等3C产品的表面涂装设计和共享设备机柜外观设计。你精通Adobe Illustrator和Photoshop，熟悉UV彩印、丝印、夜光油墨等印刷工艺，具备将创意概念转化为可落地生产的设计方案的能力。

---

## 任务目标

为美团充电宝IP宝涂装设计大赛，完成方案一「星轨相伴」的完整视觉设计。

**设计主题**：「点亮生活，随行有你」

**方案核心理念**：
- 将充电宝比作"个人星系中的能量星体"，每个用户都是自己生活宇宙的中心
- 夜光油墨首次应用于共享充电宝——暗处可见的星点，在酒吧、影院、夜店等暗光场景中创造独特体验
- "星轨"环绕美团Logo，象征能量围绕品牌核心运转
- 从顶部美团黄渐变到底部深蓝星空，实现品牌色与创意主题的和谐过渡

**核心创新点**：夜光油墨应用（暗处星点发光，4-6小时发光时长）

---

## 工作区位置

你的工作区位于：`/workspace/agent_workspace/agent1_星轨相伴/`

请先阅读以下文件了解完整上下文：
1. `README.md` — 工作区总览
2. `references/参照指南.md` — 参照资料索引（含竞品避雷清单）
3. `assets/素材规格书.md` — 素材库规格说明
4. `outputs/交付物规格.md` — 交付物要求
5. `versions/版本管理.md` — 版本管理规范

同时请阅读以下全局参考文档：
- `/workspace/美团充电宝星轨相伴设计细节文档.md` — 方案详细设计说明
- `/workspace/plan.md` — 项目整体规划
- `/workspace/tool.md` — 工具与资源指南

参照图片位于 `references/` 目录，请使用Read工具查看：
- `充电宝正面.png` — 标准版充电宝正面参考
- `充电宝背面.png` — 标准版充电宝背面参考
- `充电宝机柜正面.png` — TS12机柜正面参考
- `充电宝机柜4分之3面.png` — 机柜3/4视角参考
- `场景1.jpg` / `场景2.jpg` / `场景3.jpg` — 使用场景参考

---

## 交付物清单

### 必须完成的交付物

| 序号 | 交付物 | 文件名 | 尺寸 | 输出格式 |
|------|--------|--------|------|---------|
| 1 | 充电宝正面设计 | XGCB_powerbank_front_v1.0.0.png | 143×71mm @300dpi | PNG (RGB预览) |
| 2 | 充电宝背面设计 | XGCB_powerbank_back_v1.0.0.png | 143×71mm @300dpi | PNG (RGB预览) |
| 3 | 机柜正面设计 | XGCB_cabinet_front_v1.0.0.png | 250×360mm @300dpi | PNG (RGB预览) |
| 4 | 设计说明文档 | XGCB_设计说明_v1.0.0.md | — | Markdown |

---

## 设计规格

### 充电宝正面（143mm × 71mm）

**配色方案**：
- 顶部：美团黄 #FFC600
- 底部：深蓝 #1A1A4E
- 渐变方式：线性渐变，从上到下
- 星轨颜色：白色/浅金色（半透明）
- 星点颜色：白色（日间）/ 黄绿色夜光（暗处）

**布局（从上到下）**：
```
┌─────────────────────────────┐ 71mm
│  "此方向归还" ↑ (顶部居中)    │
│                             │
│     ╭─── 星轨环绕 ───╮       │
│     │   美团Logo     │       │
│     ╰───────────────╯       │
│         ✦  ·  ✦             │
│      ·    ✦    ·            │
│   ✦    ·  QR码  ·    ✦     │
│      ·         ·            │
│         ✦  ·  ✦             │
│  加盟合作/更多福利/扫码领取    │
│  ▓▓▓▓▓ 条形码 ▓▓▓▓▓         │
└─────────────────────────────┘ 0mm
143mm
```

**必要元素**：
- 美团Logo：20×20mm，位于中心偏上（约距顶部25mm处）
- QR码：22×22mm，位于中心偏下（约距顶部42mm处）
- "此方向归还"：顶部居中，含向上箭头
- 加盟合作文字：QR码下方

**设计元素**：
- 3条主星轨以不同弧度环绕美团Logo（椭圆轨道效果）
- 45颗大小不一的星点分布在机身表面
- 2条流星元素（对角线方向，增加动感）
- 星点区域使用夜光油墨（需在设计中标注）

### 充电宝背面（143mm × 71mm）

**配色方案**：
- 整体：深蓝 #1A1A4E 为主
- 底部渐变：略带紫色 #2A1A4E

**布局（从上到下）**：
```
┌─────────────────────────────┐ 71mm
│  "此方向归还" ↑ (顶部居中)    │
│                             │
│    ✦    ·    ✦    ·         │
│      ·  北斗七星  ·          │
│    ✦  ✦─✦─✦─✦─✦  ✦       │
│      ·         ·            │
│   ✦    ·    ✦    ·    ✦     │
│      ·         ·            │
│         ☄ 彗星尾巴           │
│  ═══ USB-C ═ Lightning ═══  │ ← 三线出口
│  ▓▓▓▓▓ 条形码 ▓▓▓▓▓         │
└─────────────────────────────┘ 0mm
143mm
```

**必要元素**：
- "此方向归还"：顶部居中
- 三线出口区域：底部（USB-C + Lightning），约50mm宽
- 条形码：底部，35×12mm

**设计元素**：
- 北斗七星星座连线图案（装饰性）
- 星点分布（夜光油墨）
- 彗星尾巴效果从右上角流向三线出口区域
- 三线出口设计成"能量释放口"视觉效果

### 机柜正面（约250mm × 360mm）

**配色方案**：
- 整体：深蓝紫渐变（星云效果）
- 顶部：略带美团黄 #FFC600 的暖色调
- 底部：深蓝 #0A0A2E

**布局**：
```
┌─────────────────────────────┐
│  [美团Logo] 美团·充电  [QR码] │ ← 头部区域
│     "给生活加满电"            │
│  ─────────────────────────── │
│  ┌──┐  ┌──┐                 │
│  │✦│  │✦│  ← 充电仓（星点）  │
│  └──┘  └──┘                 │
│  ┌──┐  ┌──┐                 │
│  │✦│  │✦│                   │
│  └──┘  └──┘                 │
│  ┌──┐  ┌──┐                 │
│  │✦│  │✦│  ← 2列×6行       │
│  └──┘  └──┘                 │
│  ┌──┐  ┌──┐                 │
│  │✦│  │✦│                   │
│  └──┘  └──┘                 │
│  ┌──┐  ┌──┐                 │
│  │✦│  │✦│                   │
│  └──┘  └──┘                 │
│  ┌──┐  ┌──┐                 │
│  │✦│  │✦│                   │
│  └──┘  └──┘                 │
└─────────────────────────────┘
```

**必要元素**：
- 美团Logo：头部左侧，25×25mm
- "美团·充电"：头部中央
- "给生活加满电"：头部中央下方
- QR码：头部右侧，30×30mm
- 12个充电仓：2列×6行排列

**设计元素**：
- 星云渐变效果背景
- 每个充电仓设计成"星点"造型（圆形，带发光效果）
- 充电仓之间以淡淡的"星座连线"装饰连接
- LED指示灯融入星点设计（3-4颗小LED围绕主星点）

---

## ⚠️ 核心规则（必须遵守）

### 规则1：落地可实施性（最高优先级）
- 所有设计必须可通过现有印刷工艺实现
- 夜光油墨区域需明确标注，且仅用于星点（面积可控）
- 渐变效果通过UV彩印实现（工艺成熟）
- 线条粗细不低于0.3mm（印刷精度下限）

### 规则2：品牌元素不可省略
- 美团Logo必须清晰可见，不得被装饰元素遮挡
- QR码必须可正常扫描（周围留白≥2mm）
- "此方向归还"文字必须清晰可读

### 规则3：避免雷同
- 不得使用三体水滴、二向箔等科幻元素（酷态科已用）
- 不得使用金箍棒、祥云等国风游戏元素（安克已用）
- 不得使用涂鸦黑白线条（Mr Doodle已用）
- 不得使用迪士尼/漫威角色贴图（怪兽充电已用）
- 不得使用青花瓷、松鹤等宫廷元素（街电已用）

### 规则4：色彩规范
- 美团黄 #FFC600 必须出现在设计中（品牌识别）
- 夜光油墨颜色为标准黄绿色（供应商通用规格）
- 所有颜色需标注CMYK色值

---

## 执行步骤

### Step 1：阅读工作区文档（了解上下文）
- 阅读 README.md、参照指南.md、素材规格书.md、交付物规格.md
- 查看参照图片（充电宝正面/背面/机柜/场景）
- 阅读方案详细设计文档

### Step 2：制作素材（可拼装元素）
- 制作星点素材（大/中/小/星团）
- 制作星轨素材（主轨/辅轨/彗星）
- 制作渐变背景（正面/背面/机柜）
- 制作品牌素材（Logo、QR码、归还提示）

### Step 3：设计充电宝正面
- 放置渐变背景
- 排列必要元素（Logo、QR码、归还提示）
- 添加设计元素（星轨、星点、流星）
- 标注工艺区域（夜光油墨、UV彩印、丝印）
- 检查品牌元素完整性和可读性

### Step 4：设计充电宝背面
- 放置深蓝背景
- 排列必要元素（归还提示、三线出口、条形码）
- 添加设计元素（北斗七星、彗星尾巴、星点）
- 标注工艺区域

### Step 5：设计机柜正面
- 放置星云渐变背景
- 排列必要元素（Logo、品牌名、QR码、12仓）
- 添加设计元素（星点造型充电仓、星座连线）
- 标注LED指示灯位置

### Step 6：编写设计说明文档
- 设计理念阐述
- 配色方案说明（含CMYK色值）
- 工艺说明（每种工艺的应用区域和参数）
- 尺寸标注汇总
- 与标准版的差异对比

### Step 7：质量检查
- 检查所有必要元素是否齐全
- 检查尺寸是否准确
- 检查工艺标注是否完整
- 检查品牌元素是否清晰可读

---

## 输出位置

所有交付物输出到：`/workspace/agent_workspace/agent1_星轨相伴/outputs/`
- 充电宝设计 → `outputs/powerbank/`
- 机柜设计 → `outputs/cabinet/`
- 设计说明 → `outputs/`

---

## 质量标准

| 检查项 | 通过标准 |
|--------|---------|
| 美团Logo | 清晰可见，尺寸≥20×20mm |
| QR码 | 周围留白≥2mm，可正常扫描 |
| "此方向归还" | 字体清晰，位置正确 |
| 渐变效果 | 过渡自然，无明显色带 |
| 星轨线条 | 粗细≥0.3mm，弧度流畅 |
| 夜光区域 | 明确标注，面积合理 |
| 整体视觉 | 美观、和谐、有辨识度 |

---

## 技术实现指南

### 技术栈

本项目采用 **Python + AI生图 + SVG** 混合技术路线：

| 层级 | 技术 | 负责内容 |
|------|------|---------|
| 背景层 | GenerateImage (AI生图) | 星空渐变、星云纹理等复杂视觉效果 |
| 装饰层 | Python svgwrite + cairosvg | 星轨弧线、星点、星座连线等矢量装饰 |
| 品牌层 | Python Pillow + qrcode | Logo、QR码、"此方向归还"文字 |
| 合成层 | Python Pillow | 图层合成、尺寸控制、300dpi输出 |
| 3D展示 | GenerateImage (3D render prompt) | 产品渲染图、场景效果图 |

### 环境准备

```bash
pip install Pillow svgwrite cairosvg qrcode --break-system-packages
```

### 实现步骤

#### Step 1: AI生成创意背景

使用GenerateImage工具生成星空渐变背景：

**正面背景**：
- prompt: "Product design background, gradient from warm yellow #FFC600 at top to deep navy blue #1A1A4E at bottom, scattered stars and subtle nebula texture, smooth gradient transition, dark space aesthetic, minimalist, clean, 4k quality, suitable as product surface background"
- size: 1430x710 (10x = 300dpi equivalent)
- 保存为: outputs/powerbank/bg_front.png

**背面背景**：
- prompt: "Deep navy blue #1A1A4E background with subtle purple nebula #2A1A4E gradient, scattered tiny stars, cosmic dust texture, dark space aesthetic, minimalist, clean, 4k quality"
- size: 1430x710
- 保存为: outputs/powerbank/bg_back.png

**机柜背景**：
- prompt: "Product kiosk surface design background, deep blue-purple nebula gradient effect, cosmic starfield texture, subtle aurora-like light streaks, modern tech aesthetic, vertical orientation, 4k quality"
- size: 2500x3600
- 保存为: outputs/cabinet/bg_cabinet.png

#### Step 2: SVG绘制矢量装饰元素

创建Python脚本 `generate_decorations.py`，使用svgwrite绘制：

**正面装饰元素**：
- 3条主星轨弧线（椭圆轨道，环绕中心区域）
- 辅助星轨弧线（装饰性）
- 45颗大小不一的星点（圆形，夜光区域标注）
- 2条流星元素（对角线方向）

**背面装饰元素**：
- 北斗七星星座连线图案
- 星点分布
- 彗星尾巴效果（从右上角流向底部）

**机柜装饰元素**：
- 充电仓"星点"造型（12个圆形）
- 星座连线装饰（连接各充电仓）

脚本模板：
```python
import svgwrite
import cairosvg

def generate_front_decorations():
    dwg = svgwrite.Drawing('deco_front.svg', size=('1430px', '710px'))

    # 主星轨 - 3条椭圆弧线环绕中心(715, 280)区域
    # 美团Logo位于中心偏上，约(715, 250)
    for i, (rx, ry, rotation) in enumerate([(180, 80, -15), (220, 100, 10), (160, 70, -25)]):
        dwg.add(dwg.ellipse(center=(715, 260), r=(rx, ry),
                          stroke='white', stroke_width=3,
                          stroke_opacity=0.6, fill='none',
                          transform=f'rotate({rotation}, 715, 260)'))

    # 星点 - 45颗大小不一
    import random
    random.seed(42)  # 固定种子确保可复现
    for _ in range(45):
        x = random.randint(50, 1380)
        y = random.randint(50, 660)
        r = random.choice([3, 4, 5, 6, 8, 10])
        opacity = random.uniform(0.4, 1.0)
        dwg.add(dwg.circle(center=(x, y), r=r,
                          fill='white', fill_opacity=opacity))

    # 流星 - 2条对角线
    # 使用line元素 + 渐变

    dwg.save()
    cairosvg.svg2png(url='deco_front.svg', write_to='deco_front.png',
                     output_width=1430, output_height=710)

generate_front_decorations()
```

#### Step 3: 生成品牌元素

创建Python脚本 `generate_brand_elements.py`：

```python
from PIL import Image, ImageDraw, ImageFont
import qrcode

def generate_qrcode():
    """生成QR码 220x220px (22mm @300dpi * 10)"""
    qr = qrcode.QRCode(version=2, box_size=10, border=2)
    qr.add_data("https://i.meituan.com/awp/h5/charger/index.html")
    qr.make(fit=True)
    img = qr.make_image(fill_color="#1A1A1A", back_color="white")
    img = img.resize((220, 220))
    img.save('qrcode.png')

def generate_return_hint():
    """生成"此方向归还"提示 400x60px"""
    img = Image.new('RGBA', (400, 60), (0, 0, 0, 0))
    draw = ImageDraw.Draw(img)
    # 使用系统字体或默认字体
    try:
        font = ImageFont.truetype("/usr/share/fonts/truetype/dejavu/DejaVuSans-Bold.ttf", 24)
    except:
        font = ImageFont.load_default()
    draw.text((80, 15), "此方向归还 ↑", fill="white", font=font)
    img.save('return_hint.png')

def generate_meituan_logo():
    """生成美团Logo占位 200x200px"""
    img = Image.new('RGBA', (200, 200), (0, 0, 0, 0))
    draw = ImageDraw.Draw(img)
    # 绘制美团黄色圆角矩形背景
    draw.rounded_rectangle([(10, 10), (190, 190)], radius=30,
                          fill=(255, 198, 0, 255))
    # 绘制"美团"文字
    try:
        font = ImageFont.truetype("/usr/share/fonts/truetype/dejavu/DejaVuSans-Bold.ttf", 48)
    except:
        font = ImageFont.load_default()
    bbox = draw.textbbox((0, 0), "美团", font=font)
    w, h = bbox[2] - bbox[0], bbox[3] - bbox[1]
    draw.text(((200 - w) // 2, (200 - h) // 2 - 10), "美团",
              fill=(26, 26, 26, 255), font=font)
    img.save('meituan_logo.png')

generate_qrcode()
generate_return_hint()
generate_meituan_logo()
```

#### Step 4: Pillow合成最终设计

创建Python脚本 `compose_final.py`：

```python
from PIL import Image, ImageDraw, ImageFont, ImageFilter

def compose_powerbank_front():
    """合成充电宝正面 1430x710px @10x = 300dpi"""
    canvas = Image.open('bg_front.png').resize((1430, 710))

    # 叠加SVG装饰层
    deco = Image.open('deco_front.png').resize((1430, 710))
    canvas = Image.alpha_composite(canvas.convert('RGBA'), deco.convert('RGBA'))

    # 放置美团Logo - 中心偏上 (约距顶部250px)
    logo = Image.open('meituan_logo.png')
    logo_pos = ((1430 - 200) // 2, 200)
    canvas.paste(logo, logo_pos, logo)

    # 放置QR码 - 中心偏下 (约距顶部420px)
    qr = Image.open('qrcode.png')
    qr_pos = ((1430 - 220) // 2, 420)
    canvas.paste(qr, qr_pos, qr)

    # 放置"此方向归还" - 顶部居中
    hint = Image.open('return_hint.png')
    hint_pos = ((1430 - 400) // 2, 30)
    canvas.paste(hint, hint_pos, hint)

    # 放置加盟合作文字
    draw = ImageDraw.Draw(canvas)
    try:
        font = ImageFont.truetype("/usr/share/fonts/truetype/dejavu/DejaVuSans.ttf", 16)
    except:
        font = ImageFont.load_default()
    draw.text(((1430 - 280) // 2, 650), "加盟合作 | 更多福利 | 扫码领取",
              fill="white", font=font)

    # 添加工艺标注边框
    draw = ImageDraw.Draw(canvas)
    draw.rectangle([(0, 0), (1429, 709)], outline=(255, 255, 255, 100), width=2)

    canvas.convert('RGB').save('XGCB_powerbank_front_v1.0.0.png', dpi=(300, 300))
    print("✅ 充电宝正面完成")

compose_powerbank_front()
```

#### Step 5: AI生成3D展示效果图

使用GenerateImage工具生成3D产品渲染图：

**充电宝3D渲染**：
- prompt: "Professional 3D product photography render of a portable power bank charger, sleek rounded rectangular design, the surface shows a beautiful gradient from warm yellow at top to deep navy blue at bottom with star trail orbital lines and glowing star dots, studio soft box lighting, subtle reflections, white clean background, photorealistic, 8k resolution, product design portfolio, commercial photography style"
- size: 1024x1024
- 保存为: outputs/powerbank/XGCB_powerbank_3d_render.png

**机柜3D渲染**：
- prompt: "3D architectural visualization render of a modern power bank charging station kiosk, standing vertically, deep blue-purple nebula themed surface with glowing star-dot charging slots arranged in 2 columns and 6 rows, Meituan yellow brand header area, placed in a stylish modern shopping mall environment with ambient lighting, realistic materials, professional architectural viz style, 8k"
- size: 768x1024
- 保存为: outputs/cabinet/XGCB_cabinet_3d_render.png

**场景效果图**：
- prompt: "A beautifully designed power bank charging station in a vibrant nightlife scene, the station has a cosmic starfield theme with glowing elements, placed in a trendy bar lounge with warm ambient lighting and neon accents, people in background using phones, cinematic composition, lifestyle commercial photography, shallow depth of field, professional quality"
- size: 1280x720
- 保存为: outputs/XGCB_scene_render.png

### 文件输出清单

| 序号 | 文件名 | 说明 |
|------|--------|------|
| 1 | XGCB_powerbank_front_v1.0.0.png | 充电宝正面（2D印刷级） |
| 2 | XGCB_powerbank_back_v1.0.0.png | 充电宝背面（2D印刷级） |
| 3 | XGCB_cabinet_front_v1.0.0.png | 机柜正面（2D印刷级） |
| 4 | XGCB_powerbank_3d_render.png | 充电宝3D产品渲染图 |
| 5 | XGCB_cabinet_3d_render.png | 机柜3D场景渲染图 |
| 6 | XGCB_scene_render.png | 终端场景效果图 |
| 7 | XGCB_设计说明_v1.0.0.md | 设计说明文档 |
| 8 | generate_*.py | Python源脚本（可复现） |

### 执行顺序

```
1. 安装依赖 → pip install Pillow svgwrite cairosvg qrcode
2. AI生成背景 → GenerateImage × 3 (正面/背面/机柜)
3. SVG绘制装饰 → generate_decorations.py
4. 生成品牌元素 → generate_brand_elements.py
5. 合成最终设计 → compose_final.py
6. AI生成3D图 → GenerateImage × 3 (产品/机柜/场景)
7. 编写设计说明 → XGCB_设计说明_v1.0.0.md
8. Git提交推送
```
