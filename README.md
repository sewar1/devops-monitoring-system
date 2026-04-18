# 📡 System Monitoring & Alerting Tool

A Python-based real-time system monitoring tool that tracks CPU, RAM, and Disk usage, logs system performance, and detects resource anomalies.

The system generates alerts when resource usage exceeds defined thresholds (e.g., high RAM usage).

## 🚀 Features

- Real-time system monitoring (CPU, RAM, Disk)
- Automatic warning detection when thresholds are exceeded
- Structured logging with timestamps
- Live terminal dashboard output

## 📊 Example Output
CPU: 0.60% | RAM: 94.20% | DISK: 16.90%

[2026-04-12 21:04:24] CPU: 1.30% | RAM: 89.00% | DISK: 16.90% | WARNINGS: High RAM usage detected
[2026-04-12 21:04:27] CPU: 3.50% | RAM: 88.90% | DISK: 16.90% | WARNINGS: High RAM usage detected


## 🧠 How it works

The system continuously collects hardware metrics using Python's psutil library.

It evaluates system health against predefined thresholds:

- CPU > 80% → Warning
- RAM > 80% → Warning
- Disk > 80% → Warning

If a threshold is exceeded, the system logs the event and generates a warning message.


## 🎯 Why this project matters

This project simulates real-world DevOps monitoring systems used in production environments for:

- Server health monitoring
- Infrastructure observability
- Incident detection
- System performance tracking

## 🛠️ Skills Learned

- Python scripting
- System monitoring concepts
- Logging and observability
- Real-time data processing
- Basic DevOps principles
