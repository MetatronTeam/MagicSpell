#Player Command

##Return List
https://github.com/MetatronTeam/MagicSpell/blob/master/command.md

##Command List

###플레이어 체력관련 명령어
```
//체력 설정 (단, amount >= 0 and amount <= 2147483647, amount = (amount < 0) ? 0 : amount; 적용)
set player's h[p|ealth] <amount>
subtract player's h[p|ealth] <amount>
add player's h[p|ealth] <amount>
//최대체력 설정 (단, amount >= 1 and amount <= 2147483647, 1보다 작으면 에러)
set player's maxh[p|ealth] <amount>
subtract player's maxh[p|ealth] <amount>
add player's maxh[p|ealth] <amount>
```
###플레이어 이동관련 명령어
```
//이동속도 설정 (단, amount >= 0 and amount <= 2147483647, 0보다 작거나 같을시 이동불가, 기본값 100)
set player's move[spd|speed|ment] <amount>
subtract player's move[spd|speed|ment] <amount>
add player's move[spd|speed|ment] <amount>
```
