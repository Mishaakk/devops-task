# Автоматизировать процесс сборки, тестирования и деплоя Node.js-приложения при пуше в ветку main.


✅ Подзадачи:
CI:
1. Настроить GitHub Actions (или GitLab CI, Jenkins и т.п.) для запуска тестов при каждом коммите.
2. Настроить линтинг и проверку кода (eslint, prettier).
3. Добавить кэширование зависимостей (node_modules) для ускорения сборки.



CD:
4. Создать скрипт автодеплоя (через SSH, Docker, или Kubernetes).
5. Реализовать автоматический деплой при пуше в main.
6. Добавить откат (rollback) на предыдущую версию в случае ошибки.


Monitoring & Observability:
7. Подключить логирование (например, через Loki, ELK или другой стек).
8. Настроить базовый мониторинг (Prometheus + Grafana).
9. Установить алерты (например, при 5xx-ошибках или высоком CPU).



Security:
10. Проверка зависимостей на уязвимости (например, через npm audit, Snyk).
11. Секреты — хранение в GitHub Secrets / Vault / dotenv-vault


# stack:
###  CI/CD: GitHub Actions && 
###  Infra: Docker, Nginx && 
###  Monitoring: Prometheus + Grafana && 
###  Хостинг: Ubuntu VPS / AWS EC2

