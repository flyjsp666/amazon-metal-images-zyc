# 铁艺金属产品深度生图规则

本参考来自用户提供的 `AI-生图指令.xlsx`，用于把 `zyc0531` 技能固定为更适合亚马逊美国站铁艺/金属切割产品的七图工作流。

## 总规则

- 使用前必须有 3 张用户上传的指定产品参考图：基础产品图、打孔产品图、顶部吊环产品图。
- 使用前必须有用户输入的产品标题。
- 如果缺少任意一张指定参考图或缺少产品标题，必须先要求用户补充，不生成概念草稿、七图方案、提示词或最终图片。
- 所有输出默认 1600 x 1600 像素、1:1 正方形、JPG 风格。
- 产品图案、轮廓、文字、镂空和比例必须严格保持，不允许拉伸、压缩、变形、重绘或简化。
- 默认材质为坚固铁制结构/金属切割产品，黑色哑光粉末涂层，表面有细微颗粒感。
- 需要表现黑色金属光泽、细微哑光反光、激光切割锐利边缘、轻微倒角和金属厚度。
- 光线可使用右上角主光源、侧面柔光、轻微环境遮蔽和柔和阴影，让产品更有 3D 实体感。
- 图片内文字默认全部使用英文，不能出现中文。
- 不要添加侵权文字、Logo、品牌元素或未授权图案。

## 七图结构

### 1. 主图

- 纯白背景，RGB 255/255/255。
- 产品正面居中，完整展示，不能裁切。
- 产品占画面主要区域，符合亚马逊主图要求。
- 不添加文字、道具、水印、边框、人物或场景。
- 除非用户上传的产品本身有孔，否则主图不要添加打孔。
- 强调黑色粉末涂层、金属光泽、细微颗粒、切割边缘和厚度。

可用英文提示词重点：

```text
ultra-realistic custom laser-cut metal wall art, exact same outline and cutouts as the uploaded reference, black matte powder-coated finish, subtle fine grain texture, crisp beveled laser-cut edges, visible metal thickness, centered on pure white RGB 255 255 255 background, front view, studio lighting, soft shadow, no text, no props, no watermark, no border, 1600 x 1600 px
```

### 2. 打孔/螺丝套件图

- 用于说明产品可以打孔并附送螺丝套件。
- 产品必须完整展示，不能变形，建议产品大图居中或略偏左，占画面主体区域。
- 圆形产品的预打孔默认位于外圈左右两侧，约 9 点钟和 3 点钟位置；不要把孔放在顶部、底部、中心或产品图案内部，除非用户上传图或标注明确要求。
- 使用两个放大镜/放大圆窗分别展示左侧孔位和右侧孔位，放大圈内应能清楚看到黑色金属外圈上的圆形孔、粉末涂层颗粒和金属厚度。
- 右上角可放大标题 `EASY TO HANG`，旁边可加简洁挂钩图标。
- 右侧或底部必须说明附带安装硬件，推荐文案：`INCLUDED MOUNTING HARDWARE KIT (SCREWS & WALL ANCHORS)`。
- 可用螺丝和墙锚的小图标/小插画展示配件包含，但不要让买家误以为包含未说明的铁链或其他配件。
- 底部可加横向卖点栏，包含图标和短文案：`WEATHER-RESISTANT POWDER-COATED FINISH`、`14 GAUGE STEEL for durability`、`201 STAINLESS STEEL [OUTDOOR] for superior outdoor resistance`。只有当这些材质/卖点适用于该产品时才使用。
- 背景建议暖色、柔和、干净，可使用浅米色墙面、门廊或室内墙面质感。
- 文案必须英文，例如：
  - `Easy to Hang`
  - `Pre-Drilled Mounting Holes`
  - `Included Mounting Hardware Kit (Screws & Wall Anchors)`
  - `Powder Coated`
  - `Weather-Resistant`
  - `Waterproof & Moisture-Proof`

### 3. 颜色选项图

- 如果用户上传颜色板/颜色图片，必须优先参考该图片的颜色色相、粉末涂层颗粒、哑光/微光质感和表面细节；但最终颜色选项图仍应展示产品本体的 6 个颜色版本，不要只展示色块，除非用户明确要求只做色卡图。
- 创建 2 行 3 列颜色图，产品之间间距均匀，画面干净。
- 保持产品轮廓、文字、镂空、切口细节和比例完全一致，只改变粉末涂层颜色。
- 默认颜色：
  - 第一行：Black, White, Gold
  - 第二行：Silver, Blue, Red
- 每个产品下方用干净无衬线英文大写标注颜色名：`BLACK`、`WHITE`、`GOLD`、`SILVER`、`BLUE`、`RED`。
- 顶部英文标题优先使用：`Colors available - Powder coating` 或 `Colors Available - Powder Coating`。
- 底部英文文案：`Powder Coated - Water and Moisture Resistant`，两侧可加简洁水滴/防潮线条图标，但不要使用侵权图案。
- 背景可用浅米白、浅暖米色或淡墙面纹理，避免白色产品看不清；白色产品应加轻微阴影或浅灰边缘以保证轮廓清楚。
- 产品应表现为真实金属切割件：轻微厚度、切割边缘、柔和投影、粉末涂层颗粒和细微金属光泽。
- 不要添加 Amazon 徽章、评分、折扣、Best Seller、Amazon's Choice、优惠券、额外颜色或未提供的配件。

### 4. 定制信息图

- 用于告诉客户产品可以定制文本。
- 如果用户用红色框标记定制位置，需要改成专业箭头、描边框或局部提示。
- 每个定制区域依次标注：
  - `Custom Text 1`
  - `Custom Text 2`
  - `Custom Text 3`
- 顶部英文标题可用：`Customize Your Personalized Sign`
- 产品必须完整展示，不能变形。

### 5. 尺寸图

- 画布垂直对半分为左右两侧。
- 左侧放完整产品，居中，约占左侧区域宽度 50%-70%，四周留白，不能裁切。
- 在产品上方按实际宽度添加尺寸线，并标注 `DIAMETER` 或更准确的尺寸名。
- 右侧放尺寸/材质表格。
- 默认尺寸选项：
  - 12 inches / 30.5 cm
  - 15 inches / 38.1 cm
  - 20 inches / 50.8 cm
  - 24 inches / 61.0 cm
  - 28 inches / 71.1 cm
  - 32 inches / 81.3 cm
  - 36 inches / 91.4 cm
- 默认材质：
  - `14 Gauge Steel`
  - `201 Stainless Steel [Outdoor]`
- 顶部英文标题可用：`Choose the Right Size`
- 左侧底部英文文案可用：`Choose Your Size - Customize Your Personalized Sign`

### 6. 场景图

- 产品必须与背景融合自然。
- 产品上的文本信息要清晰可读。
- 场景图里产品在墙面上时，产品本体必须保持干净，严禁出现螺丝、螺丝头、打孔、孔洞、悬挂环、吊环、链条、挂钩、吊耳、支架或任何可见安装五金。
- 墙面场景图只展示干净的产品正面；打孔、螺丝、挂环、链条等安装细节只能出现在打孔/螺丝套件图或两种安装方式图中。
- 产品完整展示，约占整张图片的 1/5。
- 用户画像：美国中产家庭。
- 至少一张场景图必须有人物，人物自然看着产品并开心微笑。
- 场景可选：客厅墙面、玄关、门廊、花园墙、厨房、家庭聚会、节日礼品场景。

### 7. 两种安装方式图

- 专业亚马逊功能对比图，左右分屏。
- 左侧：`Wall-Mounted`，展示墙面安装效果；圆形产品的预打孔必须位于外圈左右两侧，约 9 点钟和 3 点钟位置。不要把孔放在顶部、底部、中心或产品图案内部。可加入一个放大圆窗展示侧边孔位，并标注 `INCLUDES SCREW KIT` 或 `Screw Kit Included`。
- 右侧：`Top-Hanging`，展示产品用两根黑色金属链条从木梁或天花板下悬挂。圆形产品必须在产品本身外面、外圈上方左右两侧各添加 1 个小圆形吊环，约 10 点钟和 2 点钟位置；吊环是外置圆形金属环，连接在产品外框外侧，不是产品图案内部打孔，也不是扁平吊耳/吊片。黑色金属链条必须只穿过这两个外置圆环。不要使用单个顶部圆环、单个顶部孔、中心挂钩、夹子、支架、随机孔，也不要让链条直接穿过产品图案或镂空装饰。
- 顶部英文标题：`Choose Your Style: Two Mounting Options Available`
- 底部英文横条：`PERSONALIZE YOUR SIGN - POWDER COATED FOR SUPERIOR DURABILITY`
- 可加英文功能说明：`Waterproof & Moisture-Proof`
- 如果螺丝默认包含、铁链需要选择，必须明确写：`Screws Included - Chains Optional` 或 `Chains Optional`，避免误导买家以为铁链默认包含。
- 可用水滴、盾牌、绿叶等简洁图标，但不要使用侵权图案。
- 整体风格：现代简约居家风，柔和室内光影，高清商业图。

## 交付前检查

- 使用本技能生成的所有图片文件，必须保存或复制到电脑桌面文件夹：`C:\Users\bjenf\Desktop\zyc0531_generated_images`。如果生成多个批次，在该桌面文件夹内新建清晰命名的子文件夹。
- 是否所有图片都是 1600 x 1600。
- 是否所有图中产品都没有变形。
- 是否保留了产品轮廓、文字、镂空和关键细节。
- 主图是否纯白背景且无文字/道具/人物。
- 信息图文字是否全英文且适合亚马逊美国站。
- 是否包含主图、打孔图、颜色图、定制图、尺寸图、带人物场景图、两种安装方式图。
- 是否避免了中文、侵权内容、亚马逊徽章、评分、Best Seller、Amazon's Choice、优惠券和夸大承诺。
