# 🛡 Network Monitoring Report

Generated on: Wed Jun 25 04:05:51 AM EDT 2025

---

## 🔒 Listening Ports and Services
```bash
Active Internet connections (only servers)
Proto Recv-Q Send-Q Local Address           Foreign Address         State       PID/Program name    
tcp        0      0 0.0.0.0:22              0.0.0.0:*               LISTEN      708/sshd: /usr/sbin 
tcp6       0      0 :::22                   :::*                    LISTEN      708/sshd: /usr/sbin 
udp        0      0 0.0.0.0:40648           0.0.0.0:*                           4492/firefox-esr    
```

## 🔗 Active Network Connections
```bash
Netid State  Recv-Q Send-Q       Local Address:Port    Peer Address:PortProcess                                  
udp   UNCONN 0      0                  0.0.0.0:40648        0.0.0.0:*    users:(("firefox-esr",pid=4492,fd=41))  
udp   ESTAB  0      0           10.0.3.15%eth1:68          10.0.3.2:67   users:(("NetworkManager",pid=605,fd=33))
udp   ESTAB  0      0      192.168.56.103%eth0:68    192.168.56.100:67   users:(("NetworkManager",pid=605,fd=29))
tcp   LISTEN 0      128                0.0.0.0:22           0.0.0.0:*    users:(("sshd",pid=708,fd=7))           
tcp   ESTAB  0      0                10.0.3.15:53962  34.107.243.93:443  users:(("firefox-esr",pid=4492,fd=110)) 
tcp   ESTAB  0      0                10.0.3.15:36760  34.36.137.203:443  users:(("firefox-esr",pid=4492,fd=62))  
tcp   LISTEN 0      128                   [::]:22              [::]:*    users:(("sshd",pid=708,fd=8))           
```

## 🚩 Suspicious Open Ports (>1024)
```bash
udp        0      0 0.0.0.0:40648           0.0.0.0:*                           4492/firefox-esr    
```

## ⚠ Quick SYN Packet Check (tcpdump)
_Capturing max 20 SYN packets or max 10 seconds...
```bash
```

## ✅ Summary and Recommendations

- Review listening ports for unknown or unexpected services.
- High numbered ports (>1024) might be unusual and worth investigating.
- Frequent SYN packets from same IP may indicate scanning or attack attempts.
- Keep tcpdump and packet capturing commands optional due to permissions and runtime.

Report generated. Review and investigate as needed.
```

## ✅ Summary and Recommendations

- Review listening ports for unknown or unexpected services.
- High numbered ports (>1024) might be unusual and worth investigating.
- Frequent SYN packets from same IP may indicate scanning or attack attempts.
- Keep tcpdump and packet capturing commands optional due to permissions and runtime.

Report generated. Review and investigate as needed.
                                                   




