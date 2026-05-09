触发 STNManager__MMStartTask （ida搜 [MMStartTask]()）
图片hook: startUploadMedia （ida搜）, OnUploadCompleted （ce查）
startUploadMedia 上传图片，OnUploadCompleted 上传图片完成后的回调
加密后的图片在 _OnRecvFileData
download系列都是_OnRecvFileData，在不同的文件下面
var downloadImagAddr  // image_download
var downloadFileAddr // c2c_download
var downloadVideoAddr // hdvideo_streaming OnRecvedData

WeChatExt中会有导致idapro出问题的代码
