# TLabShareScreen_Client_Unity_Android
Client program (UnityAsset) to decode packets from TLabShareScreen_Server

## demonstration

### 1: in local machine

[demonstration](https://youtu.be/PK0eoB0jQ_M)

https://user-images.githubusercontent.com/121733943/210447171-dd79dcfd-c64e-460e-81b2-7078929e0ea3.mp4

### 2: in real android device

[demonstration_1](https://youtu.be/g4nKSnYe6RA)

![DSC_0002](https://user-images.githubusercontent.com/121733943/211289979-46bfc2f3-c247-4015-b21d-ba5839f11a41.JPG)

## Operating environment
OS: Android 10, 12  
GPU: Qualcomm Adreno 505, 619  

## Requires
Unity project --> Project settings --> Rendering --> Color space --> Gamma  
Unity project --> Project settings --> Rendering --> Graphics API --> Open GL only (remove valkan) and check "require OpenGL ES 3.1".

## Note
- This asset works by using it together with [TLabShareScreen_Server](https://github.com/TLabAltoh/TLabShareScreen_Server).  
- Very slow performance due to software encoder. Also, it does not work properly with Oculus quest.

## link  
[TLabShareScreen_Server](https://github.com/TLabAltoh/TLabShareScreen_Server)
