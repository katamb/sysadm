## Lab 1

* Task 1:
    *  ls
    *  cat flag.txt
    * -> SysAdm-starthere
*  Task 2:
    *  history (echo "U3lzQWRtLWJhc2U2NApodHRwczovL3Jyb2xsLnRvL0g0ekwxUAo=" | base64 -d)
    *  run command
    * -> SysAdm-base64 
    * with an added rickroll https://rroll.to/H4zL1P
*  Task 3:
    *   find . -print | grep -i Sys
    *  -> SysAdm-recursion
*  Task 4:
    *  grep SysAdm /var/log/audit.log -B 3 -A 3
    * -> SysAdm-surveillance
*  Task 5:
    *  cat /etc/passwd
    *  -> SysAdm-user
*  Task 6:
    *  echo SysAdm-user > file.txt
    *  ./ctf --target file.txt
    *  -> SysAdm-binary
*  Task 7:
    *  curl localhost
    *  -> SysAdm-port31222
*  Task 8:
    *  nmap -sV -p 31222 localhost
    *  -> SysAdm-endex
*  Task 9:
    *   echo karltamb | nc localhost 31222
    *   -> SysAdm-endex
    * 