# oos-service-upload-java
服务端签名后直传

流程如下：

1. 用户发送上传Policy请求到应用服务器。
2. 应用服务器返回上传Policy和签名给用户。
3. 用户使用Plupload直接上传数据到OSS。
