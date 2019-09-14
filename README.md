
Код для Arduino UNO и MEGA .

1. Просто установите Потенциометры в каждый аналоговый порт с 0 до 7 по аналогии с рисунком: 
http://arduino.cc/en/uploads/Tutorial/joy_sch_480.jpg

2. Для кнопок просто установите кнопочный переключатель или тумблер между GND и Digital Port 02 - 13 (например). 

3. Залейте этот скетч в Ардуино с помощью Ардуино IDE: https://github.com/asovetov/Arduino-Joystick-Yoke-Steering-wheel/blob/master/Arduino-yoke.ino

4. Используйте Flip, чтобы записать эту прошивку DFU: https://github.com/asovetov/Arduino-Joystick-Yoke-Steering-wheel/blob/master/Arduino-big-joystick.hex
Это превратит Ардуину в джойстик! Она престанет шиться из Ардуино IDE

5. Используйте Flip, чтобы записать эту прошивку USB Serial: https://github.com/asovetov/Arduino-Joystick-Yoke-Steering-wheel/blob/master/Arduino-usbserial.hex
Это вернет Ардуино в начальное состояние - можно прошивать скетчи из Ардуино IDE

Чтобы посмотреть демонстрационное видео:
