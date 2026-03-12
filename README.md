**Monitoring and Observability Platform**

Centralized monitoring and logging stack for Kubernetes environments.

---

**Overview**

This project demonstrates an observability platform that collects metrics and logs from infrastructure and applications.
The stack provides monitoring dashboards and log aggregation capabilities.

---

**Technologies**

- Prometheus
- Grafana
- Loki
- Kubernetes

---

**Architecture**

```
Applications
     │
     ▼
Prometheus (metrics)
     │
     ▼
Grafana (dashboards)

Logs
     │
     ▼
Loki
     │
     ▼
Grafana
```

---

**Repository Structure**

```
monitoring-prometheus-grafana-loki
│
├ helm
│
├ dashboards
│
└ configs
```

---

**Features**

- Infrastructure metrics collection
- Centralized log aggregation
- Visualization dashboards
