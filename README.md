## 上马自动签到 [![Run Auto Sign](https://github.com/zhaohongxuan/shangma_auto_sign/actions/workflows/auto-sign.yaml/badge.svg)](https://github.com/zhaohongxuan/shangma_auto_sign/actions/workflows/auto-sign.yaml)

### 基于 Node.js + GitHub Action 实现上海马拉松官网每日签到

### Use 使用

1. Fork本项目（顺手点Star以示鼓励～🥳）
2. 在Repo的Setting页面，添加名为上马官网的用户名：`SM_USERNAME`和密码：`SM_PASSWORD`的Secret 
3. 手动测试运行
<img width="1444" alt="image" src="https://github.com/zhaohongxuan/shangma_auto_sign/assets/8613196/695683c9-fbc2-4cab-9ef8-41e2ddf59b78">
在控制台应该能看到 `签到成功/请勿重复签到` 的提示
<img width="990" alt="image" src="https://github.com/zhaohongxuan/shangma_auto_sign/assets/8613196/399e89f7-2ad6-486e-9e67-8953564ec528">


### 关于Job执行时间
签到Job执行时间是**UTC时间0点**，也就是**北京时间8点**执行，**不过由于GitHub的负载比较重**，真正签到时间可能延后一段时间，一般是几十分钟，这个延迟时间取决于GitHub Action的负载。

### 申明
- 本项目仅做学习交流, 禁止用于各种非法途径
- Auto Sign-in run successful on Fri Sep 13 06:46:04 UTC 2024
- Auto Sign-in run successful on Sat Sep 14 00:42:53 UTC 2024
- Auto Sign-in run successful on Sun Sep 15 00:49:58 UTC 2024
- Auto Sign-in run successful on Mon Sep 16 00:46:55 UTC 2024
- Auto Sign-in run successful on Tue Sep 17 00:36:34 UTC 2024
- Auto Sign-in run successful on Wed Sep 18 00:43:25 UTC 2024
- Auto Sign-in run successful on Thu Sep 19 00:44:07 UTC 2024
- Auto Sign-in run successful on Fri Sep 20 00:44:01 UTC 2024
- Auto Sign-in run successful on Sat Sep 21 00:43:29 UTC 2024
- Auto Sign-in run successful on Sun Sep 22 00:50:09 UTC 2024
- Auto Sign-in run successful on Mon Sep 23 00:46:06 UTC 2024
- Auto Sign-in run successful on Tue Sep 24 00:45:36 UTC 2024
- Auto Sign-in run successful on Wed Sep 25 00:46:27 UTC 2024
- Auto Sign-in run successful on Thu Sep 26 00:45:11 UTC 2024
- Auto Sign-in run successful on Fri Sep 27 00:45:37 UTC 2024
- Auto Sign-in run successful on Sat Sep 28 00:45:00 UTC 2024
- Auto Sign-in run successful on Sun Sep 29 00:51:09 UTC 2024
- Auto Sign-in run successful on Mon Sep 30 00:48:00 UTC 2024
- Auto Sign-in run successful on Tue Oct  1 00:51:42 UTC 2024
- Auto Sign-in run successful on Wed Oct  2 00:45:32 UTC 2024
- Auto Sign-in run successful on Thu Oct  3 00:45:38 UTC 2024
- Auto Sign-in run successful on Fri Oct  4 00:45:47 UTC 2024
- Auto Sign-in run successful on Sat Oct  5 00:44:59 UTC 2024
- Auto Sign-in run successful on Sun Oct  6 00:50:47 UTC 2024
- Auto Sign-in run successful on Mon Oct  7 00:48:17 UTC 2024
- Auto Sign-in run successful on Tue Oct  8 00:45:24 UTC 2024
- Auto Sign-in run successful on Wed Oct  9 00:45:16 UTC 2024
- Auto Sign-in run successful on Thu Oct 10 00:45:23 UTC 2024
- Auto Sign-in run successful on Fri Oct 11 00:45:27 UTC 2024
- Auto Sign-in run successful on Sat Oct 12 00:44:23 UTC 2024
- Auto Sign-in run successful on Sun Oct 13 00:50:23 UTC 2024
- Auto Sign-in run successful on Mon Oct 14 00:48:08 UTC 2024
- Auto Sign-in run successful on Tue Oct 15 00:46:30 UTC 2024
- Auto Sign-in run successful on Wed Oct 16 00:46:16 UTC 2024
- Auto Sign-in run successful on Thu Oct 17 00:45:51 UTC 2024
- Auto Sign-in run successful on Fri Oct 18 00:45:50 UTC 2024
- Auto Sign-in run successful on Sat Oct 19 00:45:12 UTC 2024
- Auto Sign-in run successful on Sun Oct 20 00:51:33 UTC 2024
- Auto Sign-in run successful on Mon Oct 21 00:48:29 UTC 2024
- Auto Sign-in run successful on Tue Oct 22 00:46:41 UTC 2024
- Auto Sign-in run successful on Wed Oct 23 00:50:42 UTC 2024
- Auto Sign-in run successful on Thu Oct 24 00:46:21 UTC 2024
- Auto Sign-in run successful on Fri Oct 25 00:46:49 UTC 2024
- Auto Sign-in run successful on Mon Oct 28 03:18:07 UTC 2024
- Auto Sign-in run successful on Tue Oct 29 00:53:09 UTC 2024
- Auto Sign-in run successful on Wed Oct 30 00:52:20 UTC 2024
- Auto Sign-in run successful on Thu Oct 31 00:52:33 UTC 2024
- Auto Sign-in run successful on Fri Nov  1 00:56:26 UTC 2024
- Auto Sign-in run successful on Sat Nov  2 00:51:07 UTC 2024
- Auto Sign-in run successful on Sun Nov  3 00:55:39 UTC 2024
- Auto Sign-in run successful on Mon Nov  4 00:53:47 UTC 2024
- Auto Sign-in run successful on Tue Nov  5 00:50:43 UTC 2024
- Auto Sign-in run successful on Wed Nov  6 00:50:56 UTC 2024
- Auto Sign-in run successful on Thu Nov  7 00:51:01 UTC 2024
- Auto Sign-in run successful on Fri Nov  8 00:50:48 UTC 2024
- Auto Sign-in run successful on Sat Nov  9 00:49:08 UTC 2024
- Auto Sign-in run successful on Sun Nov 10 00:54:17 UTC 2024
- Auto Sign-in run successful on Mon Nov 11 00:52:31 UTC 2024
- Auto Sign-in run successful on Tue Nov 12 00:50:23 UTC 2024
- Auto Sign-in run successful on Wed Nov 13 00:51:25 UTC 2024
- Auto Sign-in run successful on Thu Nov 14 00:51:38 UTC 2024
- Auto Sign-in run successful on Fri Nov 15 00:54:40 UTC 2024
- Auto Sign-in run successful on Sat Nov 16 00:53:58 UTC 2024
- Auto Sign-in run successful on Sun Nov 17 00:57:35 UTC 2024
- Auto Sign-in run successful on Mon Nov 18 00:56:06 UTC 2024
- Auto Sign-in run successful on Tue Nov 19 00:54:25 UTC 2024
- Auto Sign-in run successful on Wed Nov 20 00:53:59 UTC 2024
- Auto Sign-in run successful on Thu Nov 21 00:53:54 UTC 2024
- Auto Sign-in run successful on Fri Nov 22 00:54:55 UTC 2024
- Auto Sign-in run successful on Sat Nov 23 00:53:24 UTC 2024
- Auto Sign-in run successful on Sun Nov 24 00:58:53 UTC 2024
- Auto Sign-in run successful on Mon Nov 25 00:55:36 UTC 2024
- Auto Sign-in run successful on Tue Nov 26 00:54:49 UTC 2024
- Auto Sign-in run successful on Wed Nov 27 00:55:31 UTC 2024
- Auto Sign-in run successful on Thu Nov 28 00:55:23 UTC 2024
- Auto Sign-in run successful on Fri Nov 29 00:55:33 UTC 2024
- Auto Sign-in run successful on Sat Nov 30 00:54:05 UTC 2024
- Auto Sign-in run successful on Sun Dec  1 01:04:59 UTC 2024
- Auto Sign-in run successful on Mon Dec  2 00:57:50 UTC 2024
- Auto Sign-in run successful on Tue Dec  3 00:56:50 UTC 2024
- Auto Sign-in run successful on Wed Dec  4 00:56:52 UTC 2024
- Auto Sign-in run successful on Thu Dec  5 00:56:55 UTC 2024
- Auto Sign-in run successful on Fri Dec  6 00:56:10 UTC 2024
- Auto Sign-in run successful on Sat Dec  7 00:55:39 UTC 2024
- Auto Sign-in run successful on Sun Dec  8 01:00:45 UTC 2024
- Auto Sign-in run successful on Mon Dec  9 00:58:21 UTC 2024
- Auto Sign-in run successful on Tue Dec 10 00:57:38 UTC 2024
- Auto Sign-in run successful on Wed Dec 11 00:56:33 UTC 2024
- Auto Sign-in run successful on Thu Dec 12 00:56:24 UTC 2024
- Auto Sign-in run successful on Fri Dec 13 00:57:22 UTC 2024
- Auto Sign-in run successful on Sat Dec 14 00:54:51 UTC 2024
- Auto Sign-in run successful on Sun Dec 15 01:00:53 UTC 2024
- Auto Sign-in run successful on Mon Dec 16 00:58:54 UTC 2024
- Auto Sign-in run successful on Tue Dec 17 00:56:47 UTC 2024
- Auto Sign-in run successful on Wed Dec 18 00:54:33 UTC 2024
- Auto Sign-in run successful on Thu Dec 19 00:55:03 UTC 2024
- Auto Sign-in run successful on Fri Dec 20 00:52:14 UTC 2024
- Auto Sign-in run successful on Sat Dec 21 00:51:12 UTC 2024
- Auto Sign-in run successful on Sun Dec 22 00:56:23 UTC 2024
- Auto Sign-in run successful on Mon Dec 23 00:53:40 UTC 2024
- Auto Sign-in run successful on Tue Dec 24 00:52:03 UTC 2024
- Auto Sign-in run successful on Wed Dec 25 00:51:23 UTC 2024
- Auto Sign-in run successful on Thu Dec 26 00:51:42 UTC 2024
- Auto Sign-in run successful on Fri Dec 27 00:51:43 UTC 2024
- Auto Sign-in run successful on Sat Dec 28 00:50:51 UTC 2024
- Auto Sign-in run successful on Sun Dec 29 00:57:00 UTC 2024
- Auto Sign-in run successful on Mon Dec 30 00:53:53 UTC 2024
- Auto Sign-in run successful on Tue Dec 31 00:51:43 UTC 2024
- Auto Sign-in run successful on Wed Jan  1 00:56:58 UTC 2025
- Auto Sign-in run successful on Thu Jan  2 00:51:44 UTC 2025
- Auto Sign-in run successful on Fri Jan  3 00:52:05 UTC 2025
- Auto Sign-in run successful on Sat Jan  4 00:51:00 UTC 2025
- Auto Sign-in run successful on Sun Jan  5 00:56:39 UTC 2025
- Auto Sign-in run successful on Mon Jan  6 00:54:43 UTC 2025
- Auto Sign-in run successful on Tue Jan  7 00:52:42 UTC 2025
- Auto Sign-in run successful on Wed Jan  8 00:52:33 UTC 2025
- Auto Sign-in run successful on Thu Jan  9 00:52:08 UTC 2025
- Auto Sign-in run successful on Fri Jan 10 00:53:51 UTC 2025
- Auto Sign-in run successful on Sat Jan 11 00:52:32 UTC 2025
- Auto Sign-in run successful on Sun Jan 12 00:57:20 UTC 2025
- Auto Sign-in run successful on Mon Jan 13 00:55:25 UTC 2025
- Auto Sign-in run successful on Tue Jan 14 00:49:44 UTC 2025
- Auto Sign-in run successful on Wed Jan 15 00:51:28 UTC 2025
- Auto Sign-in run successful on Thu Jan 16 00:50:40 UTC 2025
- Auto Sign-in run successful on Fri Jan 17 00:50:24 UTC 2025
- Auto Sign-in run successful on Sat Jan 18 00:48:27 UTC 2025
- Auto Sign-in run successful on Sun Jan 19 00:54:44 UTC 2025
- Auto Sign-in run successful on Mon Jan 20 00:51:57 UTC 2025
- Auto Sign-in run successful on Tue Jan 21 00:50:32 UTC 2025
- Auto Sign-in run successful on Wed Jan 22 00:52:08 UTC 2025
- Auto Sign-in run successful on Thu Jan 23 00:51:01 UTC 2025
- Auto Sign-in run successful on Fri Jan 24 00:51:03 UTC 2025
- Auto Sign-in run successful on Sat Jan 25 00:47:19 UTC 2025
- Auto Sign-in run successful on Sun Jan 26 00:52:21 UTC 2025
- Auto Sign-in run successful on Mon Jan 27 00:52:17 UTC 2025
- Auto Sign-in run successful on Tue Jan 28 00:51:04 UTC 2025
- Auto Sign-in run successful on Wed Jan 29 00:51:09 UTC 2025
- Auto Sign-in run successful on Thu Jan 30 00:49:53 UTC 2025
- Auto Sign-in run successful on Fri Jan 31 00:51:16 UTC 2025
- Auto Sign-in run successful on Sat Feb  1 00:54:15 UTC 2025
- Auto Sign-in run successful on Sun Feb  2 00:53:50 UTC 2025
- Auto Sign-in run successful on Mon Feb  3 00:52:20 UTC 2025
- Auto Sign-in run successful on Tue Feb  4 00:51:13 UTC 2025
- Auto Sign-in run successful on Wed Feb  5 00:51:53 UTC 2025
- Auto Sign-in run successful on Thu Feb  6 00:51:54 UTC 2025
- Auto Sign-in run successful on Fri Feb  7 00:52:07 UTC 2025
- Auto Sign-in run successful on Sat Feb  8 00:50:27 UTC 2025
- Auto Sign-in run successful on Sun Feb  9 00:54:43 UTC 2025
- Auto Sign-in run successful on Mon Feb 10 00:53:05 UTC 2025
- Auto Sign-in run successful on Tue Feb 11 00:51:42 UTC 2025
- Auto Sign-in run successful on Wed Feb 12 00:52:02 UTC 2025
- Auto Sign-in run successful on Thu Feb 13 00:52:11 UTC 2025
- Auto Sign-in run successful on Fri Feb 14 00:51:48 UTC 2025
- Auto Sign-in run successful on Sat Feb 15 00:51:21 UTC 2025
- Auto Sign-in run successful on Sun Feb 16 00:56:22 UTC 2025
- Auto Sign-in run successful on Mon Feb 17 00:54:25 UTC 2025
- Auto Sign-in run successful on Tue Feb 18 00:51:47 UTC 2025
- Auto Sign-in run successful on Wed Feb 19 00:52:22 UTC 2025
- Auto Sign-in run successful on Thu Feb 20 00:52:36 UTC 2025
- Auto Sign-in run successful on Fri Feb 21 00:52:33 UTC 2025
- Auto Sign-in run successful on Sat Feb 22 00:50:44 UTC 2025
- Auto Sign-in run successful on Sun Feb 23 00:57:03 UTC 2025
- Auto Sign-in run successful on Mon Feb 24 00:54:18 UTC 2025
- Auto Sign-in run successful on Tue Feb 25 00:53:26 UTC 2025
- Auto Sign-in run successful on Wed Feb 26 00:53:25 UTC 2025
- Auto Sign-in run successful on Thu Feb 27 00:53:23 UTC 2025
- Auto Sign-in run successful on Fri Feb 28 00:53:35 UTC 2025
- Auto Sign-in run successful on Sat Mar  1 00:57:40 UTC 2025
- Auto Sign-in run successful on Sun Mar  2 00:56:59 UTC 2025
- Auto Sign-in run successful on Mon Mar  3 00:55:24 UTC 2025
- Auto Sign-in run successful on Tue Mar  4 00:54:24 UTC 2025
- Auto Sign-in run successful on Wed Mar  5 00:54:27 UTC 2025
- Auto Sign-in run successful on Thu Mar  6 00:54:13 UTC 2025
- Auto Sign-in run successful on Fri Mar  7 00:54:46 UTC 2025
- Auto Sign-in run successful on Sat Mar  8 00:42:17 UTC 2025
- Auto Sign-in run successful on Sun Mar  9 00:46:52 UTC 2025
- Auto Sign-in run successful on Mon Mar 10 00:45:05 UTC 2025
- Auto Sign-in run successful on Tue Mar 11 00:54:52 UTC 2025
- Auto Sign-in run successful on Wed Mar 12 00:54:06 UTC 2025
- Auto Sign-in run successful on Thu Mar 13 00:54:49 UTC 2025
- Auto Sign-in run successful on Fri Mar 14 00:54:14 UTC 2025
- Auto Sign-in run successful on Sat Mar 15 00:53:34 UTC 2025
- Auto Sign-in run successful on Sun Mar 16 00:58:50 UTC 2025
- Auto Sign-in run successful on Mon Mar 17 00:56:33 UTC 2025
- Auto Sign-in run successful on Tue Mar 18 00:54:52 UTC 2025
- Auto Sign-in run successful on Wed Mar 19 00:55:18 UTC 2025
- Auto Sign-in run successful on Thu Mar 20 00:54:23 UTC 2025
- Auto Sign-in run successful on Fri Mar 21 00:55:41 UTC 2025
- Auto Sign-in run successful on Sat Mar 22 00:53:45 UTC 2025
- Auto Sign-in run successful on Sun Mar 23 00:59:18 UTC 2025
