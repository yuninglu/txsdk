This document describes how to run the TRTC web quick demo (Vanilla js).

English | [简体中文](./README.zh.md)

## Tryout

We offer an [online web demo (Vanilla js)](https://web.sdk.qcloud.com/trtc/webrtc/v5/demo/quick-demo-js/index.html) for you to try out TRTC features.

Enter your application’s `SDKAppID` and secret key on the webpage to enter a room. For how to get the `SDKAppID` and secret key, see <a href="#getAppInfo">[Getting Application Information]</a>.

After joining a room, you can use a share link to invite others to try the audio/video call feature with you.

## Local Run

#### Download the demo source code

Download the source code of the TRTC web quick demo (Vanilla js) at [GitHub](https://github.com/LiteAVSDK/TRTC_Web/v5/) (in `TRTC_Web/v5/quick-demo-js`).

#### Run the demo

- Open the `index.html` file in the Demo root directory with Chrome browser to run the Demo.

+ Enter the `SDKAppID` and secret key. For detailed directions, see <a href="#getAppInfo">[Getting Application Information]</a>.

#### Try the demo

- Input userId and roomId
- Click the "Enter Room" button to enter the room
- Click the "Start Local Audio/Video" button to capture microphone or camera
- Click the "Stop Local Audio/Video" button to stop capturing microphone or camera
- Click the "Start Share Screen" button to start screen sharing
- Click the "Stop Share Screen" button to stop screen sharing

#### Others

- To package the code to deploy to production, run the command below:

  ```shell
  npm run build
  ```

- If an "eslint" error occurs when you modify the code, run the command below to troubleshoot the issue:

  ```shell
  npm run lint:fix
  ```

## Getting Application Information

#### Create an application

- Log in to the [TRTC console](https://console.cloud.tencent.com/trtc), and select **Development Assistance > [Demo Quick Run](https://console.cloud.tencent.com/trtc/quickstart)** on the left sidebar.

- Select **New** and enter an application name such as `TestTRTC`. If you have already created an application, select **Existing**.

- Add or edit tags according to your actual needs and click **Create**.

  ![img](https://qcloudimg.tencent-cloud.cn/raw/7805a202a8e0c96b748116f17aa8524c.png)

#### Get the `SDKAppID` and `userSig`

- Copy the `SDKApppID` and secret key.

  ![img](https://qcloudimg.tencent-cloud.cn/raw/85489ab5999afbd64604a4e3c76f2249.png)

