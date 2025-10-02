# Monitor System Resources Using Netdata

This project demonstrates lightweight server and application monitoring using **Netdata** inside a **Docker container**. Netdata provides real-time dashboards for CPU, memory, disk, network, and Docker containers with built-in alerts.

---

## 🚀 Quick Start

```bash
docker run -d --name=netdata -p 19999:19999 --cap-add SYS_PTRACE --security-opt apparmor=unconfined netdata/netdata
 

