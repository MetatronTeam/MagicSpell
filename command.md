#

player's projectile[dmg\|damage]는
player's projectiledmg 또는 player's projectiledamage 를 사용할 수 있다는 말입니다.

|명령어|디폴트값|수치범위|타입|사용여부|비고 (꼭 알야야함)|
|:-----:|:-----:|:-----:|:-----:|:-----:|:---------:|
|player's health|20|0 ~ 20|integer|add/subtract/set|음수일시 에러|
|player's movespeed|100|-2147483648~2147483647|integer|add/subtract/set|0이하일시 이동불가|
|player's projectile[dmg\|damage]|4|0~32767|short|add/subtract/set|음수일시 에러|
|player's attack[dmg\|damage]|1|0~32767|short|add/subtract/set|음수일시 에러|
|player's [kc\|killcount]|0|0~Infinity|double|add/subtract/set|음수일시 비정상적인 동작가능|
|player's [dc\|deathcount]|0|0~Infinity|double|add/subtract/set|음수일시 비정상적인 동작가능|
|player's [ac\|assistcount]|0|0~Infinity|double|add/subtract/set|음수일시 비정상적인 동작가능|
|player's [def\|defence]|0|-2147483648~2147483647|integer|add/subtract/set|음수일시 더많은 데미지를 입음|
|player's [defper\|defenceper]|0|-100~100|double|add/subtract/set|수치범위내에 없을시 에러|
|player's [lv\|level]|1|1~999|integer|add/subtract/set|수치범위내에 없을시 에러|
|player's [exp\|experience]|0|0~100|doucle|add/subtract/set|수치범위내에 없을시 에러 (백분율로 수치 설정)|
|player's [fly\|flymode]|0|0~1|boolean|set|set만 사용가능, 수치범위내에 없을시 0으로 인식|
|player's [saveinv\|keepinv]|0|0~1|boolean|set|set만 사용가능, 수치범위내에 없을시 0으로 인식|
|player's [armoric\|armoriconc\|armoriconcount]|0|0~20|integer|1당 0.5칸, 수치범위내에 없을시 에러|
예시
```java
//example
set player's health 1
add player's health 1
subtract player's health 1
```
