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
명령어 시작전에는 다음과 같은 코드가 있어야 합니다.
```java
start trigger
```
명령어 시작전에는 발동조건 코드를 삽입할 수 있습니다.
```java
itemid blaze_rod
itemdamage 0
itemcost blaze_rod
itemcostdamage 0
itemcostcount 0
playerlv 1
start trigger
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
https://github.com/MetatronTeam/MagicSpell/blob/master/command.md
