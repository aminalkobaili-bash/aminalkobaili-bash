# Amin Alkobaili — Junior DevOps Engineer

Linux, Bash-автоматизация, сети, Docker (Compose, Swarm), мониторинг (Prometheus/Grafana), PostgreSQL.

<p>
  <img src="https://skillicons.dev/icons?i=linux,ubuntu,bash,docker,nginx,rabbitmq,postgresql,prometheus,grafana,git,github,python,flask" />
</p>

## Stack

- **OS / Shell:** Ubuntu, Bash
- **Networking:** iptables, NAT (SNAT/DNAT), DHCP, static routing, tcpdump, iperf3, SSH tunneling
- **Containers:** Docker (multi-stage, non-root, healthcheck), Docker Compose, Docker Swarm, nginx (reverse proxy), Vagrant, Portainer
- **Monitoring:** Prometheus, Grafana, GoAccess
- **Databases / MQ:** PostgreSQL, MS SQL, SQL, RabbitMQ
- **Dev / CI:** Git, GitHub, GitLab CI, GitHub Actions, Python (Flask, SQLAlchemy), Postman / newman

## Projects

| Project | Что сделано | Stack |
|---|---|---|
| [linux-administration-basics](https://github.com/aminalkobaili-bash/linux-administration-basics) | установка ОС, пользователи, настройка сети, сервисы, логи | Ubuntu, Bash |
| [linux-networking](https://github.com/aminalkobaili-bash/linux-networking) | многоузловая сеть: static routing, NAT, DHCP, firewall, SSH tunneling | iptables, netplan, tcpdump, iperf3 |
| [linux-system-monitoring](https://github.com/aminalkobaili-bash/linux-system-monitoring) | Bash-скрипты сбора системной информации и логов, метрики и дашборды | Bash, awk, Prometheus, Grafana |
| [sql-postgresql-practice](https://github.com/aminalkobaili-bash/sql-postgresql-practice) | 10 модулей: JOIN, CTE, DML, индексы и `EXPLAIN ANALYZE`, ограничения, уровни изоляции транзакций | PostgreSQL |
| [gitlab-cicd-pipeline](https://github.com/aminalkobaili-bash/gitlab-cicd-pipeline) | CI/CD на self-hosted GitLab Runner: build → style → test → manual deploy по SSH → Telegram-уведомления; зеркало build/style/test в GitHub Actions; разбор найденных багов (секрет в истории, `allow_failure` у manual-job) | GitLab CI, GitHub Actions, Bash, SSH |
| [docker-nginx-fastcgi](https://github.com/aminalkobaili-bash/docker-nginx-fastcgi) | свой образ nginx + FastCGI-сервер на C, харденинг по Dockle (non-root, без SUID/SGID, healthcheck), multi-stage 397 → 149 MB, docker-compose с reverse proxy | Docker, Compose, nginx, C |
| [docker-compose-microservices](https://github.com/aminalkobaili-bash/docker-compose-microservices) | 9 контейнеров (7 Spring Boot + PostgreSQL + RabbitMQ) одной командой `docker compose up`, затем Docker Swarm на 3 ВМ Vagrant за nginx; общий multi-stage Dockerfile, healthcheck + `service_healthy`, non-root, JWT-ключи в `.env`; Postman/newman 5/5 | Docker, Compose, Swarm, nginx, Vagrant, RabbitMQ |
| [flask-tictactoe-api](https://github.com/aminalkobaili-bash/flask-tictactoe-api) | REST API: JWT access/refresh, игра с компьютером (minimax) и PvP, leaderboard на SQL; после ревью — хеширование паролей, проверка типа токена, фикс NULL в рейтинге | Python, Flask, SQLAlchemy 2.0, PostgreSQL |

## Contacts

[![Email](https://img.shields.io/badge/Email-333333?style=flat&logo=gmail&logoColor=red)](mailto:amin.alkobaili@gmail.com)
[![Telegram](https://img.shields.io/badge/Telegram-2CA5E0?style=flat&logo=telegram&logoColor=white)](https://t.me/warex26)
