实现长按蓄力的机制

## 必要的变量

-ChargeTime  
-ChargeSpeed  
-MaxChargeTime  

ChargeTime，当前蓄力的时间进度，以毫秒为单位。  
MaxChargeTime，可以蓄力的最大时间，数值越大，需要蓄力越久。  
ChargeSpeed，每次蓄力增加的时间，数值越大，蓄力速度越快。  
  
这里，我是将它作为实例变量使用。    

<img width="460" src="https://user-images.githubusercontent.com/45864744/152938917-5abeb2f8-2077-4668-b0cc-bfd04d5cbc1d.png">
  
## 事件表

1 长按空格键时，进行蓄力。

<img width="460" src="https://user-images.githubusercontent.com/45864744/152938988-1993d3cd-2735-46b7-838d-dfaae6f18807.png">