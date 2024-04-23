
## 项目介绍 | Info

- 通过 API 将 Stable Diffusion 3 引入 ComfyUI

- Stable Diffusion 3：目前通过 API 开放，[详情](https://stability.ai/news/stable-diffusion-3-api?utm_source=twitter&utm_medium=website&utm_campaign=blog)，API申请：[Stability API key](https://platform.stability.ai/account/keys)，每个账户提供 25 个免费积分

- 模型：
   - SD3 6.5 积分/张
   - SD3 Turbo 4 积分/张 
  
- 版本：V1.5 支持多种比例的 SD3 文生图，修复 图生图 和 Turbo 的 bug，可以正常使用了



## 节点说明 | Features

- 🔥Stable Diffusion 3
    - positive：正向提示词
    - negative：负向提示词（Turbo 模型不支持）
    - aspect_ratio：画面比例，共 9 种："21:9", "16:9", "5:4", "3:2", "1:1", "2:3", "4:5", "9:16", "9:21"（图生图不适用）
    - mode：文生图 或 图生图
    - model：SD3 或 SD3 Turbo
    - seed：种子
    - image：非必要，仅用于图生图
    - strength：非必要，仅用于图生图
    - api_key：SD3 的API 密钥


## 安装 | Install

- 使用前请先申请 API ：[Stability API key](https://platform.stability.ai/account/keys)，每个账户提供 25 个免费积分

- 将 Stability API key 添加到 config.json 文件中，运行时会自动加载

- 推荐使用管理器 ComfyUI Manager 安装（On The Way）

- 手动安装：
    1. `cd custom_nodes`
    2. `git clone 
    3. 重启 ComfyUI


## Credits

[Stable Diffusion 3](https://stability.ai/news/stable-diffusion-3-api?utm_source=twitter&utm_medium=website&utm_campaign=blog)
