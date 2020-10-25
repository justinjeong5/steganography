
# steganography 구현

window bitmap file(.bmp) 형태의 파일에 1000자 이내로 원하는 message를 숨기고 열어볼 수 있는 프로그램

## 실행결과
|origin.bmp|stego.bmp|
|:---:|:---:|
|<img src="https://user-images.githubusercontent.com/44011462/92374126-49656380-f13a-11ea-9cb5-82189412bc38.jpg">|<img src="https://user-images.githubusercontent.com/44011462/92374126-49656380-f13a-11ea-9cb5-82189412bc38.jpg">|
|<img src="https://user-images.githubusercontent.com/44011462/93299536-2b7dba00-f830-11ea-9f6a-9e440eb4b009.png">|<img src="https://user-images.githubusercontent.com/44011462/93299550-2f114100-f830-11ea-8cff-a324be282500.png" >|   

*작성한 프로그램을 이용하여 얻은 origin.bmp와 stego.bmp*  

## 개발환경  
visual studio

## 사용언어
c++

## 사용방법
```
> stego.exe e
(insert message to Steganograph)
<!-- 원하는 메세지를 입력 (1000자 이내) -->
(encoding success!!)
(...program exit)

> stego.exe d
<!-- 입력된 메세지를 출력 -->
(decoding success!!)
(...program exit)
```  
