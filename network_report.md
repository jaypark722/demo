# 🛡 Network Monitoring Report
_Generated on: Mon Jun 23 04:55:29 AM EDT 2025_

---

## 🔒 Listening Ports and Services
```bash
Active Internet connections (only servers)
Proto Recv-Q Send-Q Local Address           Foreign Address         State       PID/Program name    
tcp        0      0 0.0.0.0:22              0.0.0.0:*               LISTEN      694/sshd: /usr/sbin 
tcp6       0      0 :::22                   :::*                    LISTEN      694/sshd: /usr/sbin 
```

## 🔗 Active Network Connections
```bash
Netid State  Recv-Q Send-Q       Local Address:Port   Peer Address:PortProcess                                  
udp   ESTAB  0      0      192.168.56.103%eth0:68   192.168.56.100:67   users:(("NetworkManager",pid=573,fd=26))
tcp   LISTEN 0      128                0.0.0.0:22          0.0.0.0:*    users:(("sshd",pid=694,fd=7))           
tcp   LISTEN 0      128                   [::]:22             [::]:*    users:(("sshd",pid=694,fd=8))           
```

## 🚩 Suspicious Open Ports (>1024)
```bash
```

## ⚠ Quick SYN Packet Check (tcpdump)
_Capturing max 20 SYN packets or max 10 seconds...
```bash
     20 192.168.56.102
```

## ✅ Summary and Recommendations
- Review listening ports for unknown or unexpected services.
- High numbered ports (>1024) might be unusual and worth investigating.
- Frequent SYN packets from same IP may indicate scanning or attack attempts.
- Keep tcpdump and packet capturing commands optional due to permissions and runtime.

Report generated. Review and investigate as needed.




