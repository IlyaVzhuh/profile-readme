# Илья Толстиков

Системный администратор Linux / DevOps, Санкт-Петербург. Один веду инфраструктуру компании на ~150 сотрудников: сеть трёх площадок на MikroTik, Proxmox VE и VMware ESXi, Linux- и Windows-серверы, мониторинг, self-hosted сервисы.

**Стек:** Linux · Bash · Terraform · Ansible · Docker Compose · Proxmox VE · VMware ESXi · Zabbix · PostgreSQL (Patroni) · MikroTik · BGP (BIRD) · WireGuard · Active Directory · PowerShell

**Сейчас изучаю:** Kubernetes (k3s), Helm, GitLab CI

## Проекты

| Репозиторий | О чём |
| --- | --- |
| [vm-provisioning](../vm-provisioning) | ВМ на Proxmox / ESXi одной командой: Terraform + cloud-init + Ansible, секреты из Bitwarden |
| [mikrotik-bgp-split](../mikrotik-bgp-split) | Раздельная маршрутизация RU / VPN для трёх площадок через BIRD и BGP communities |
| [zabbix-sla-tools](../zabbix-sla-tools) | SLA для руководства в Zabbix 7: двухуровневые SLO, рабочие часы, пропорциональный SLA, восстановление истории через API |
| [mail-ad-sync](../mail-ad-sync) | Postfix/Dovecot ↔ Active Directory: синхронизация ящиков, Kerberos SSO в Thunderbird через GPO, защита от массовых ошибок |
| [guacamole-ad-pc-sync](../guacamole-ad-pc-sync) | Удалённый доступ к «своему ПК» через Apache Guacamole + AD + GPO |
| [onvif-bulk-codec](../onvif-bulk-codec) | Массовый перевод IP-камер на H.265 через ONVIF и Playwright |
| [gdocs-to-docspace](../gdocs-to-docspace) | Импорт Google Docs в ONLYOFFICE DocSpace: CLI и веб-страница в контейнере |
| [selfhosted-compose](../selfhosted-compose) | Compose-стеки: Vaultwarden, Nextcloud + ONLYOFFICE, Vikunja, стенд для выбора вики |

📫 iljatolstikov90@gmail.com
