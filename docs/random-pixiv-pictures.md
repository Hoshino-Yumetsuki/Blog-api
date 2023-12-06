# Random Pixiv Pictures

## 使用示例

```
https://pixiv.anjiurine.top/api/illust/random
```
返回随机图片

- max {number} 返回图片的个数
- mode {'all' | 'safe' | 'r18'} 其中 r18 只有在登录状态且参数设置允许时才会返回
- format {'image' | 'json'} 返回的格式，如果 Accept 包含 image 则预设为 image