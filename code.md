##기본작성법
파일확장자는 .msl입니다.
명령어 작성은 소문자를 기준으로하나 메세지 입력 부분에서는 대문자를 허용합니다.
파일 최상단에는 다음과 같은 코드가 있어야 합니다.
```java
start magicspell-metatron
```
파일 최하단에는 다음과 같은 코드가 있어야 합니다.
```java
end magicspell-metatron
```
공백은 금지되어 있으며 한줄을 비워도 안됩니다.
▼금지된 행동▼
```java
 w r o n g c o d e
 
```
명령어 작성시 맨앞에 공백이 있어도 안됩니다.
▼금지된 행동▼
```java
 start magicspell-metatron
```
주석은 줄 처음부터 작성하지 않으면 안됩니다.
▼금지된 행동▼
```java
start magicspell-metatron//스팰시작
 
```
단 줄 처음부터 작성했으면 상관이 없습니다. (//주석만 가능)
▼가능한 행동▼
```java
//스팰시작
start magicspell-metatron
//스팰끝
end magicspell-metatron 
```

#명령어들

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


```java
//example
set player's health 1
add player's health 1
subtract player's health 1
```
