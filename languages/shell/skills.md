1. ##### 实现倒计时

   ```shell
   seq 10 | tac | awk '{printf "\r%s%d%s", "server shutdown in 10s...",$0,"...";system ("sleep 1")}'
   ```

   

2. 

