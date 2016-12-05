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
단 줄 처음부터 작성했으면 상관이 없습니다.
▼가능한 행동▼
```java
//스팰시작
start magicspell-metatron
#스팰끝
end magicspell-metatron 
```

#명령어들
```java
//플레이어 체력 0으로 설정
set player's health 0
//플레이어 체력 5감소
subtract player's health 5
//플레이어 체력 5증가
add player's health 5
//플레이어 이동속도 100으로설정 (기본값)
set player's movespeed 100
```
등등이 있습니다.
