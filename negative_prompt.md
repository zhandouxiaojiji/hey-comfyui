# 常用反向提示

### 通用反向词
+ EasyNegative 通用负面词
+ badhandv4 手部缺陷排除
+ (worst quality:2) 最差质量
+ (low quality:2) 低质量
+ (normal quality:2) 普通质量
+ lowres 低分辨率
+ bad anatomy 不良解剖结构
+ DeepNegative 深度负面
+ badhandv4 手部问题（第四版）
+ ng_deepnegative_v1_75t 常用负面模型
+ verybadimagenegative_v1.3 非常差的图像

### 图像问题
+ blurry 模糊
+ jpeg artifacts JPEG压缩痕迹
+ chromatic aberration 色差
+ image noise 图像噪点
+ grain 颗粒感
+ interlaced 交错线
+ pixelated 像素化
+ ugly 丑陋
+ duplicate 重复元素
+ error 错误
+ fewer digits 少了手指
+ cropped 被裁剪
+ out of frame 画面外
+ signature 签名
+ watermark 水印
+ username 用户名
+ text 文字

### 肢体问题
+ malformed hands 畸形手
+ poorly drawn hands 绘制不良的手
+ mutated hands 变异手
+ too many fingers 太多手指
+ fused fingers 融合的手指
+ missing fingers 缺少手指
+ extra limbs 多余的肢体
+ missing limbs 缺少的肢体
+ fused limbs 融合的肢体
+ bad feet 不良的脚
+ missing arms 缺少手臂
+ bad proportions 不良比例
+ liquid body 流体状身体
+ disconnected limbs 肢体不连接

### 面部问题
+ deformed face 变形脸
+ badly drawn face 绘制不良的脸
+ closed eyes 闭眼
+ poorly drawn eyes 绘制不良的眼睛
+ gross proportions 比例扭曲
+ asymmetric eyes 不对称眼睛
+ cross-eye 斗鸡眼
+ lazy eye 懒眼
+ extra ears 额外的耳朵
+ missing ears 缺少耳朵

### 皮肤和身体特征
+ ((monochrome)) 单色
+ ((grayscale)) 灰阶
+ skin spots 皮肤斑点
+ acnes 痤疮
+ skin blemishes 皮肤瑕疵
+ (fat:1.2) 肥胖
+ moles 痣
+ missing nipples 缺少乳头
+ large breasts 过大的胸部
+ huge breasts 巨大的胸部

### 构图问题
+ facing away 背对
+ looking away 看向别处
+ tilted head 倾斜的头
+ multiple heads 多个头
+ multiple girls 多个女孩
+ multiple views 多个视角
+ multiple panels 多个面板
+ mutation 突变
+ poorly drawn 绘制不良的
+ long neck 长脖子
+ mutation 变异
+ deformed 变形的

### 艺术风格排除
+ western 西方风格
+ anime 动漫风格
+ cartoon 卡通风格
+ 3d render 3D渲染
+ sketch 素描
+ painting 绘画
+ digital art 数字艺术
+ photoshop 图像编辑
+ anime screencap 动漫截图
+ comic 漫画

### 技术组合词
+ nsfw 成人内容
+ (worst quality:2), (low quality:2), (normal quality:2) 质量问题加权
+ lowres, bad anatomy, bad hands, text, error 常见问题组合
+ missing fingers, extra digit, fewer digits, cropped, worst quality, low quality 手指问题组合
+ easynegative, badhandv4, verybadimagenegative_v1.3 常用负面合集
+ deformed iris, deformed pupils, semi-realistic, cgi, 3d, render, sketch, cartoon, drawing, anime 风格排除组合
+ paintings, sketches, (worst quality:2), (low quality:2), (normal quality:2), lowres, normal quality, ((monochrome)), ((grayscale)), skin spots, acnes, skin blemishes, age spot 质量和皮肤问题组合 