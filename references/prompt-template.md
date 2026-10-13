# 生图提示词模板

每张单独生成。使用角色主参考和最接近动作的一张参考，不要一次加入全部动作图。

```text
Use case: stylized-concept
Asset type: standalone 16:9 horizontal Chinese article illustration

Reference images:
- Image 1: Lexie identity master reference. Preserve face, two-head-tall proportions, double braids, palette, beret, apple, dress, necklace, single bracelet, straight legs and shoes.
- Image 2: optional action/expression reference only. Adapt the action to the article concept while preserving Image 1 identity.

Visual DNA:
Pure white background. Minimalist deep-brown/black hand-drawn structural line art with slightly wobbly pen lines. Lots of empty white space. Sparse red/orange/blue handwritten Chinese annotations. Clean absurd product-sketch feeling. Lexie is the only fully colored subject, rendered with crisp hand-drawn outlines and controlled powder-blue, periwinkle, pink-lavender and cream watercolor fills.

Recurring IP character required:
Lexie, a two-heads-tall chibi woman with a very round apple face, large dark-brown eyes, two long powder-blue and pink-lavender braids, a muted blue beret with exactly one pink apple, a light cream dress with only 3–4 pale blue-lavender argyle diamonds, a purple-blue four-point-star necklace, exactly one bracelet, straight parallel tube-like legs, white socks and dusty periwinkle round shoes. Lexie must perform the core conceptual action, not decorate the scene. Preserve her warm, clever, slightly proud personality. Do not include 小黑 or any black blob mascot.

Theme:
{正文配图主题}

Structure type:
{Workflow / 系统局部 / 前后对比 / 角色状态 / 概念隐喻 / 方法分层 / 地图路线 / 小漫画分镜}

Core idea:
{这张图要表达的唯一核心意思}

Composition:
{Lexie 在哪里、亲自做什么、主要物件是什么、信息如何流动}

Suggested elements:
{元素1} / {元素2} / {元素3} / {可选元素4}

Chinese handwritten labels:
{标注词1} / {标注词2} / {标注词3} / {标注词4} / {可选标注词5}

Color use:
Keep Lexie in her fixed powder-blue, periwinkle, pink-lavender, cream and warm-skin palette. Use deep brown-black for structural line art. Use orange only for main flow/path/arrows, red only for warnings/problems/results, and blue only for secondary notes or system feedback.

Constraints:
One image explains one core structure. Main subject occupies about 40%–60%; preserve at least 35% blank white space. Use at most 5–8 short Chinese labels. Do not write a title in the top-left corner or the structure type anywhere. Do not create a PPT infographic, course slide, formal diagram, children's poster, commercial character poster, realistic UI or dense explainer. Invent a fresh visual metaphor for this article. The character may be cute, but the composition must stay sparse, strange, clean and concept-first.
```

## 局部编辑提示

### 去掉左上角标题

```text
Edit the provided image. Remove only the handwritten title "{要删除的文字}" and its underline from the top-left corner. Fill that area with clean white background. Preserve Lexie, all remaining labels, paths, line style, composition, aspect ratio and image quality. Add nothing new.
```

### 修复角色漂移

```text
Edit only Lexie to match Image 1 identity: restore the apple-round face, two powder-blue/pink-lavender braids, blue beret with one pink apple, cream argyle dress, four-point-star necklace, one bracelet, straight parallel legs and periwinkle round shoes. Preserve the scene, action, labels, objects and 16:9 composition. Do not add 小黑.
```

### 增强核心动作

```text
Regenerate with the same meaning and sparse layout, but make Lexie perform the strange work that explains the concept. She must physically operate, repair, move, sort or connect the main object rather than stand beside it. Preserve her identity and fixed palette. Keep the scene white, minimal, hand-drawn and concept-first.
```
