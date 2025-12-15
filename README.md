# OpenSearch Dashboards for iptables

Проект для сбора, обработки и визуализации логов `iptables`
с использованием **Logstash**, **OpenSearch** и **OpenSearch Dashboards**.

---

## 📁 Структура проекта

```text
opensearch_project/
├── docker-compose.yml
├── README.md
├── logstash/
│   ├── logstash.conf
│   └── data/
│       └── iptables.log
└── dashboards/
