![示例图片](https://github.com/kyler719/Netease2SP/blob/main/Demo.png)


# 网易云音乐转Spotify 油猴脚本

这是一个油猴脚本，可以将网易云音乐的歌曲快速转链到Spotify进行搜索。

## 注意事项

1. **适用范围**：此脚本仅在网易云音乐网站（https://music.163.com/*）  上生效
2. **依赖环境**：需要安装[ScriptCat](https://scriptcat.org/)或类似的用户脚本管理器扩展
3. **标题解析**：脚本通过解析页面标题来获取歌曲信息，对于特殊格式的标题可能解析不准确
4. **网络环境**：使用此脚本需要能够正常访问Spotify网站


## 安装方法

1. 安装[ScriptCat](https://scriptcat.org/)浏览器扩展
   - Chrome/Edge: 通过Chrome Web Store安装
   - Firefox: 通过Firefox Add-ons安装
2. 安装本脚本
   - 点击ScriptCat扩展图标
   - 点击上方小房子图标打开管理界面
   - 将`Netease2SP.js`文件直接拖入完成安装
   - 点击安装脚本：[点我](https://update.greasyfork.org/scripts/544519/%E7%BD%91%E6%98%93%E4%BA%91%E9%9F%B3%E4%B9%90%E8%BD%ACSpotify.user.js)

## 功能特点

1. **悬浮按钮**：在网易云音乐页面左下角显示一个绿色的Spotify品牌按钮
2. **一键转链**：点击按钮即可将当前页面的歌曲信息在Spotify中搜索
3. **智能解析**：自动从页面标题中提取歌曲名和歌手信息
4. **响应式设计**：按钮具有悬停效果 可拖动
5. **轻量级**：脚本体积小，不影响页面加载速度
