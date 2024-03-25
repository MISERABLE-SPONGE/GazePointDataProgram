# 
C++的数据采集程序：使用摄像头采集使用者面部图像，并记录此刻对应的屏幕注视点
#
学习记录：
#
将外部库放入项目文件夹中（与Debug同级）
使用相对路径$(SolutionDir)+路径
#
使用SFML图形库创建全屏窗口、绘制内容以及调用键盘、鼠标事件：
#
SFML安装步骤参考CSDN：
https://blog.csdn.net/Hsianus/article/details/130727463?ops_request_misc=%257B%2522request%255Fid%2522%253A%2522171135333016800182774958%2522%252C%2522scm%2522%253A%252220140713.130102334..%2522%257D&request_id=171135333016800182774958&biz_id=0&utm_medium=distribute.pc_search_result.none-task-blog-2~all~top_click~default-1-130727463-null-null.142^v99^pc_search_result_base2&utm_term=sfml%E5%BA%93vs2022%E9%85%8D%E7%BD%AE&spm=1018.2226.3001.4187
#
问题找不到sfml-graphics-2.dll解决方法：
https://blog.csdn.net/VLOKL/article/details/133978470?ops_request_misc=%257B%2522request%255Fid%2522%253A%2522171135333016800182774958%2522%252C%2522scm%2522%253A%252220140713.130102334..%2522%257D&request_id=171135333016800182774958&biz_id=0&utm_medium=distribute.pc_search_result.none-task-blog-2~all~sobaiduend~default-2-133978470-null-null.142^v99^pc_search_result_base2&utm_term=sfml%E5%BA%93vs2022%E9%85%8D%E7%BD%AE&spm=1018.2226.3001.4187
#
使用OpenCV库调用摄像头拍照保存视频帧：
#
opencv库的安装（注意opencv_world的版本号）：
https://blog.csdn.net/weixin_50918736/article/details/130176469?ops_request_misc=&request_id=&biz_id=102&utm_term=C++%20%E5%AE%89%E8%A3%85opencv%E5%BA%93&utm_medium=distribute.pc_search_result.none-task-blog-2~all~sobaiduweb~default-2-130176469.142^v99^pc_search_result_base2&spm=1018.2226.3001.4187
#
未找到依赖dll
https://blog.csdn.net/luzaijiaoxia0618/article/details/108241147?ops_request_misc=&request_id=&biz_id=102&utm_term=%E6%9C%AA%E6%89%BE%E5%88%B0%E4%BE%9D%E8%B5%96%20dll&utm_medium=distribute.pc_search_result.none-task-blog-2~all~sobaiduweb~default-1-108241147.nonecase&spm=1018.2226.3001.4187
#
GitHub
#
Github上传方法：
https://blog.csdn.net/VLOKL/article/details/132344964?ops_request_misc=%257B%2522request%255Fid%2522%253A%2522171136774816777224467082%2522%252C%2522scm%2522%253A%252220140713.130102334..%2522%257D&request_id=171136774816777224467082&biz_id=0&utm_medium=distribute.pc_search_result.none-task-blog-2~all~sobaiduend~default-1-132344964-null-null.142^v99^pc_search_result_base2&utm_term=github%20%E4%B8%8A%E4%BC%A0&spm=1018.2226.3001.4187
#
找不到.git文件夹解决方法：
https://blog.csdn.net/men_ma/article/details/109396784?ops_request_misc=&request_id=&biz_id=102&utm_term=github%20%E6%B2%A1%E6%9C%89.git&utm_medium=distribute.pc_search_result.none-task-blog-2~all~sobaiduweb~default-1-109396784.142^v99^pc_search_result_base2&spm=1018.2226.3001.4187
#
上传错误解决方法：
https://blog.csdn.net/qq_41590178/article/details/125213086?ops_request_misc=%257B%2522request%255Fid%2522%253A%2522171137071516800226587595%2522%252C%2522scm%2522%253A%252220140713.130102334..%2522%257D&request_id=171137071516800226587595&biz_id=0&utm_medium=distribute.pc_search_result.none-task-blog-2~all~top_positive~default-2-125213086-null-null.142^v99^pc_search_result_base2&utm_term=github%E4%B8%8A%E4%BC%A0%E4%BB%A3%E7%A0%81&spm=1018.2226.3001.4187
#
GitHub项目改名：
https://blog.csdn.net/Tisfy/article/details/124348891?ops_request_misc=%257B%2522request%255Fid%2522%253A%2522171137240916800226550371%2522%252C%2522scm%2522%253A%252220140713.130102334.pc%255Fall.%2522%257D&request_id=171137240916800226550371&biz_id=0&utm_medium=distribute.pc_search_result.none-task-blog-2~all~first_rank_ecpm_v1~rank_v31_ecpm-2-124348891-null-null.142^v99^pc_search_result_base2&utm_term=github%E9%A1%B9%E7%9B%AE%E6%96%87%E4%BB%B6%E6%80%8E%E4%B9%88%E6%94%B9%E5%90%8D&spm=1018.2226.3001.4187
