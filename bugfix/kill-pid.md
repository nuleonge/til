####window
```shell
netstat -ano | find "<port>" // 해당 port의 pid 확인
tasklist /fi "PID eq <port>" // 해당 pid의 프로세스 확인
taskkill /f /pid <pid> // 해당 pid 킬
```s

####linux
```sheel
ps -aux | grep <port> // 해당 port의 pid 확인
kill -9 <pid> // 해당 pid 킬
```
