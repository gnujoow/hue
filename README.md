# Hue.py

---

Hue.py는 Hue의 전구들을 제어하고, 각전구의 상태를 읽을수 있는 함수를 제공한다.

* Variables
 * conn 
* Functions
  * on(light) <br>
  light에 해당하는 전구를 점등한다.
  * off(light)
  light를 끈다.
  * putSat(light, sat)
  light의 saturation을 변경한다. 0~255
  * putBri(light, bri)
  light의 brightness을 변경한다. 0~255
  * putHue(light, hue)
  light의 hue을 변경한다. 0~65536
  * getLightState(light)
  * getState()
  * 
  
---

## Todo
- [ ] 객체로 다시 짜기
- [ ] 패키지화 해서 배포하기

---

## reference

 - [HUE API](http://www.developers.meethue.com/)
