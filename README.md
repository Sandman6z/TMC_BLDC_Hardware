# TMC_BLDC_Hardware
TMC_BLDC 电路板部分

## TMC_BLDC
[TMC_BLDC 软件部分](https://github.com/Sandman6z/TMC_BLDC)

[TMC_BLDC HAL](https://github.com/Sandman6z/TMC_BLDC_HAL)

## BUGList:
- v1.1
   1. add 12V, 5V, 3.3V test pad
   2. check PMOS package(Q1), Rgs(R27), Rg(R24)
   3. remove HALL
   4. crystal & capacitor package
   5. inner Power layer shrinks 15mil
   6. add TMC debug port
   7. LDO current: TMC:110mA*2 + MCU:180mA = 400mA    CHANGE package from SOT-223 -> SOT-89
   8. remove Q8
   9. remove R65
   10. remove Q10
   11. 因为当前采集两相电机电流，导致直通的那相有直流分量，导致底板的输出电感温度比其他两个高10℃，考虑在直通相增加一个相同的检流电阻
   12. Power-In FUSE
   13. 复位电路换成芯片CAT809
   14. 有源晶振串个电阻，磁珠上并个大电容
   15. 有位置增加LED
