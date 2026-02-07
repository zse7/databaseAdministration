# Greenplum Database

## Описание
Данное руководство описывает процесс запуска Greenplum Database в Docker контейнере для тестирования и разработки.

### 1. Предварительные требования
- Установленный Docker
- Минимум 4ГБ свободной памяти
- Порты 5432/5433 и 2222 свободны

### 2. Запуск Greenplum
Выполните скрипт запуска:
```bash
cd greenplum-launch
chmod +x docker_greenplum_launch.sh
./docker_greenplum_launch.sh