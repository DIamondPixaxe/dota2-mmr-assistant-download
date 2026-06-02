# dota2-mmr-assistant-download
Dota2 MMR 记录助手公开下载页（仅发布成品，不包含源码）
# Dota2 MMR 记录助手

这是 Dota2 MMR 记录助手的公开下载页。

## 下载

请在右侧或下方的 **Releases** 中下载最新 Windows 成品包。

## 功能

- 本地 OCR 识别 Dota2 分数变化
- - OBS 浏览器源叠加显示
  - - 本地控制页记录胜负与 MMR
    - - 支持快捷键唤起/隐藏窗口
     
      - ## 本地地址
     
      - - OBS 叠加页：`http://127.0.0.1:8765/overlay`
        - - 控制页：`http://127.0.0.1:8765/control`
         
          - ## 安全说明
         
          - - 不需要 Steam/Dota2 账号密码
            - - OCR 在本机运行，截图不会上传
              - - 只启动本机服务 `127.0.0.1:8765`
                - - 用户数据保存在本地 `data/state.json`
                 
                  - ## 注意
                 
                  - Windows 可能会因为软件未签名弹出安全提示。确认来源后继续运行即可。
