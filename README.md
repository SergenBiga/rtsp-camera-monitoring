# rtsp-camera-monitoring
Real-world RTSP camera monitoring project focused on observability, uptime tracking, and alerting using Prometheus and Grafana.

# RTSP Camera Monitoring & Health Check System

This project is a real-world inspired RTSP camera monitoring and observability solution designed for Linux-based environments where camera uptime and stream availability are critical.

It focuses on monitoring RTSP camera streams, exporting health metrics, visualizing them via Grafana dashboards, and triggering alerts when cameras or related services become unavailable.

---

## 🚀 Project Goals

- Monitor RTSP camera stream availability in real time
- Detect camera outages, stream failures, and service downtime
- Export metrics in Prometheus-compatible format
- Visualize camera health and system metrics in Grafana
- Simulate production-like monitoring used in smart city, CCTV, and security systems

---

## 🧩 Architecture Overview

RTSP Cameras (real or simulated)  
→ Custom health checks (ffmpeg / ffprobe based)  
→ Prometheus Exporter  
→ Prometheus  
→ Grafana Dashboards & Alerts  

The system is designed to be lightweight, modular, and easily extendable.

---

## 🛠️ Technologies Used

- **Linux (Ubuntu)**
- **RTSP / ffmpeg / ffprobe**
- **Prometheus**
- **Node Exporter**
- **Custom Prometheus Exporter (Bash / Python)**
- **Grafana**
- **systemd & cron**
- **Networking tools (ss, ip, curl)**

---

## 📡 What Is Monitored?

### Camera-Level Metrics
- RTSP stream availability (up / down)
- Stream connection response
- Per-camera health status

### System-Level Metrics
- CPU usage
- Memory usage
- Disk usage
- Network status
- Exporter and service availability

---

## 📊 Grafana Dashboards

Grafana dashboards provide:
- Per-camera up/down status
- Number of active cameras
- Historical availability trends
- System resource usage
- Alert visibility

Dashboards are designed to resemble real production NOC / SOC views.

---

## 🚨 Alerting

Alerts can be configured in Prometheus/Grafana for:
- Camera stream down
- Exporter not responding
- High CPU / memory / disk usage
- Service failures

Alerts can be extended to email, Slack, or webhook-based notifications.

---

## 🧪 Use Cases

- Smart city traffic enforcement systems
- CCTV and perimeter security monitoring
- Airport camera infrastructure
- RTSP-based camera PoC environments
- DevOps / SRE observability practice
- Monitoring & incident response simulations

---

## 📦 Project Structure (Example)


