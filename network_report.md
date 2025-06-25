# 🛡️ Network Monitoring Report

Generated on: Wed Jun 25 05:36:23 AM EDT 2025

---

## 🔒 Listening Ports and Services
```bash
Active Internet connections (only servers)
Proto Recv-Q Send-Q Local Address           Foreign Address         State       PID/Program name    
tcp        0      0 0.0.0.0:22              0.0.0.0:*               LISTEN      653/sshd: /usr/sbin 
tcp6       0      0 :::22                   :::*                    LISTEN      653/sshd: /usr/sbin 
udp        0      0 10.0.3.15:3702          0.0.0.0:*                           3965/python3        
udp        0      0 239.255.255.250:3702    0.0.0.0:*                           3965/python3        
udp        0      0 192.168.56.103:3702     0.0.0.0:*                           3965/python3        
udp        0      0 239.255.255.250:3702    0.0.0.0:*                           3965/python3        
udp        0      0 0.0.0.0:60219           0.0.0.0:*                           3965/python3        
udp        0      0 0.0.0.0:38824           0.0.0.0:*                           3965/python3        
udp6       0      0 fe80::5318:2472:3e:3702 :::*                                3965/python3        
udp6       0      0 ff02::c:3702            :::*                                3965/python3        
udp6       0      0 fe80::7013:5332:94:3702 :::*                                3965/python3        
udp6       0      0 ff02::c:3702            :::*                                3965/python3        
udp6       0      0 :::51838                :::*                                3965/python3        
udp6       0      0 :::52257                :::*                                3965/python3        
```

## 🔗 Active Network Connections
```bash
Netid State  Recv-Q Send-Q                         Local Address:Port        Peer Address:PortProcess                                  
udp   UNCONN 0      0                                  10.0.3.15:3702             0.0.0.0:*    users:(("python3",pid=3965,fd=12))      
udp   UNCONN 0      0                            239.255.255.250:3702             0.0.0.0:*    users:(("python3",pid=3965,fd=10))      
udp   UNCONN 0      0                             192.168.56.103:3702             0.0.0.0:*    users:(("python3",pid=3965,fd=9))       
udp   UNCONN 0      0                            239.255.255.250:3702             0.0.0.0:*    users:(("python3",pid=3965,fd=7))       
udp   UNCONN 0      0                                    0.0.0.0:60219            0.0.0.0:*    users:(("python3",pid=3965,fd=8))       
udp   UNCONN 0      0                                    0.0.0.0:38824            0.0.0.0:*    users:(("python3",pid=3965,fd=11))      
udp   ESTAB  0      0                             10.0.3.15%eth1:68              10.0.3.2:67   users:(("NetworkManager",pid=593,fd=33))
udp   ESTAB  0      0                        192.168.56.103%eth0:68        192.168.56.100:67   users:(("NetworkManager",pid=593,fd=32))
udp   UNCONN 0      0           [fe80::5318:2472:3e50:aa59]%eth1:3702                [::]:*    users:(("python3",pid=3965,fd=18))      
udp   UNCONN 0      0                             [ff02::c]%eth1:3702                [::]:*    users:(("python3",pid=3965,fd=16))      
udp   UNCONN 0      0           [fe80::7013:5332:944f:cf9e]%eth0:3702                [::]:*    users:(("python3",pid=3965,fd=15))      
udp   UNCONN 0      0                             [ff02::c]%eth0:3702                [::]:*    users:(("python3",pid=3965,fd=13))      
udp   UNCONN 0      0                                          *:51838                  *:*    users:(("python3",pid=3965,fd=17))      
udp   UNCONN 0      0                                          *:52257                  *:*    users:(("python3",pid=3965,fd=14))      
tcp   LISTEN 0      128                                  0.0.0.0:22               0.0.0.0:*    users:(("sshd",pid=653,fd=7))           
tcp   ESTAB  0      0                                  10.0.3.15:47396       40.74.98.195:443  users:(("code",pid=1761,fd=18))         
tcp   LISTEN 0      128                                     [::]:22                  [::]:*    users:(("sshd",pid=653,fd=8))           
tcp   ESTAB  0      0      [fd17:625c:f037:3:a662:24a:8177:b3f2]:59210 [2620:1ec:bdf::67]:443  users:(("code",pid=1761,fd=19))         
```

## 🚩 Suspicious Open Ports (>1024)
```bash
udp        0      0 10.0.3.15:3702          0.0.0.0:*                           3965/python3        
udp        0      0 239.255.255.250:3702    0.0.0.0:*                           3965/python3        
udp        0      0 192.168.56.103:3702     0.0.0.0:*                           3965/python3        
udp        0      0 239.255.255.250:3702    0.0.0.0:*                           3965/python3        
udp        0      0 0.0.0.0:60219           0.0.0.0:*                           3965/python3        
udp        0      0 0.0.0.0:38824           0.0.0.0:*                           3965/python3        
udp6       0      0 fe80::5318:2472:3e:3702 :::*                                3965/python3        
udp6       0      0 ff02::c:3702            :::*                                3965/python3        
udp6       0      0 fe80::7013:5332:94:3702 :::*                                3965/python3        
udp6       0      0 ff02::c:3702            :::*                                3965/python3        
udp6       0      0 :::51838                :::*                                3965/python3        
udp6       0      0 :::52257                :::*                                3965/python3        
```

## ⚠️ Quick SYN Packet Check (tcpdump)
_Capturing max 20 SYN packets or max 10 seconds...
```bash
```

## ✅ Summary and Recommendations

- Review listening ports for unknown or unexpected services.
- High numbered ports (>1024) might be unusual and worth investigating.
- Frequent SYN packets from same IP may indicate scanning or attack attempts.
- Keep tcpdump and packet capturing commands optional due to permissions and runtime.

Report generated. Review and investigate as needed.
                                                   
                                                   




