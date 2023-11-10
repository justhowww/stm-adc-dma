1. 由 logic analyzer 可以看出 buffer 從一次半滿到下一次半滿的時間間隔為 2ms
2. 所以 buffer 需要 2ms 來填滿 長度為 64/2 的 buffer
3. 所以sampling rate = (1/0.002)*32 = 16000
   ![image](https://github.com/justhowww/stm-adc-dma/assets/73697339/4090e021-b25a-4705-9adc-709b51e43efd)
   
![image](https://github.com/justhowww/stm-adc-dma/assets/73697339/e14ac399-bc92-4d8f-974e-b8a07507a0c6)
