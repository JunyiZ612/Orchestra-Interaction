ORCHESTRA 手势可变字体测试（第三版）

本版改动：
1. 摄像头小预览恢复镜像。
2. 手势的水平坐标同步反转，因此画面、手和文字的左右方向一致。
3. 中央圆形替换为大写 ORCHESTRA。
4. 手掌位置控制文字位置；手指张开程度控制字重。
5. 使用开源可变字体 Roboto Flex，固定字宽轴，只改变 Weight（wght）。

运行方法：
1. 解压 ZIP。
2. 用 VS Code 打开 mediapipe-hand-demo-v3 文件夹。
3. 右键 index.html，选择 Open with Live Server。
4. 浏览器中点击“开启摄像头并开始识别”，允许摄像头权限。

注意：
- 第一次运行需要联网加载 MediaPipe、模型和 Google Fonts。
- 手势识别在本地浏览器中运行；本页面没有上传摄像头画面的代码。
- 摄像头需通过 localhost 或 HTTPS 启动，不要直接双击 HTML 文件。
- 字体：Roboto Flex，SIL Open Font License。
