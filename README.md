# LIRAT

## The vedio of the tool can be seen at:

## LIRAT: Layout and Image Recognition Driving Automated Testing of Cross-Platform

The fragmentation issues spreads over mobile platforms such as Android, iOS, mobile Web and even Wechat, which hinders test scripts from running across platforms. To reduce the cost of adapting scripts for various platforms, some existing tools apply conventional computer vision techniques to replay the same script on multiple platforms automatically. However, because these solutions can hardly identify dynamic elements, it becomes difficult for engineers to apply them in practice.

In this paper, we present an image-driven tool, namely LIRAT, to record and replay test scripts cross platforms. LIRAT records screenshots and layouts of the widgets, and leverages image understanding techniques to locate them in the replay process. Based on accurate widget localization, LIRAT supports replaying test scripts across devices and platforms. To validate LIRAT, we experimented on 25 scripts from 5 applications. We employed LIRAT to replay these scripts across 8 Android devices and 2 iOS devices. The results show that LIRATcan replay 88% scripts on Android platforms and 60% on iOS platforms.

![workflow](workflow.png)