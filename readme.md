if you want to connect your instalation to the interenet without having intenet, you can use a other netwerk like this one (LoraWAN,Sigfox).
this is made for long distant communication and can transfor small data a few times a day.

LoraWan is free to use if you have a account on the tings network (TTN);
https://www.thethingsnetwork.org/

all you need is ;
- arduino and a Lora shield
  https://www.youtube.com/watch?v=bfSxdOnqfik&t=220s
- (TTN)-account 
  https://www.thethingsnetwork.org/
  the code is specialy for my (TTN)-account, so you need change this variables to your situation:
  - const PROGMEM u1_t NWKSKEY[16]
  - static const u1_t PROGMEM APPSKEY[16]
  - static const u4_t DEVADDR
  
