### Сергей Фролов — Junior Security Engineer / SecOps

Студент 4-го курса ЮУрГУ, «Информационная безопасность» (выпуск 2027). Занимаюсь безопасностью и эксплуатацией Linux-инфраструктуры. Ищу удалённую работу или стажировку в ИБ, 4–6 часов в день.

**Инфраструктура.** С 2024 года веду собственный распределённый сервис на 6 серверах Linux. Связь узлов идёт по mTLS: включал поэтапно, с автооткатом. Флот обновлён до Ubuntu 26.04 LTS и PostgreSQL 18 без простоя. Есть воспроизводимые сборки, внешний мониторинг и восстановление из бэкапа, проверенное на отдельной машине.

**Open source.** [72 принятых PR](https://github.com/MHSanaei/3x-ui/pulls?q=is%3Apr+author%3An0ctal+is%3Amerged) в [3x-ui](https://github.com/MHSanaei/3x-ui) (~50k ★):

- безопасность — токены с областью и сроком действия ([#6201](https://github.com/MHSanaei/3x-ui/pull/6201)), повторная проверка 2FA ([#5610](https://github.com/MHSanaei/3x-ui/pull/5610)), проверка сертификатов mTLS ([#6188](https://github.com/MHSanaei/3x-ui/pull/6188)), проверка SHA-256 загрузок ([#5396](https://github.com/MHSanaei/3x-ui/pull/5396));
- целостность данных — побочные эффекты только после коммита транзакции, устранение гонок, CI для тестов на PostgreSQL;
- Security Advisory [GHSA-xqqw-jqqv-99h6](https://github.com/MHSanaei/3x-ui/security/advisories/GHSA-xqqw-jqqv-99h6) — указан как Reporter.

**Проекты.**

- [Zephyr](https://github.com/n0ctal/Zephyr) — утилита для Intel Mac с разделением привилегий: привилегированный помощник через XPC проверяет подпись вызывающего приложения.
- Bifrost (alpha) — удалённый рабочий стол для совместных игр. QUIC/TLS 1.3 с закреплением ключа хоста, mTLS для устройств гостей.

**Стек.** Linux (Ubuntu, Debian), systemd, nginx, TCP/IP, TLS/mTLS, IPsec, UFW, Fail2ban, PostgreSQL, Git. ПАК «Соболь», Guardant ID. Работаю с ИИ-агентами (Claude Code, Codex): ставлю задачу с критериями и принимаю результат по проверкам.

---

*Junior Security Engineer (Russia, remote). 72 merged PRs to 3x-ui, GitHub Security Advisory reporter. Linux, networking, mTLS, PostgreSQL.*
