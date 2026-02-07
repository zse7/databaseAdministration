# Лабораторная работа: Развертывание Greenplum Database

## Описание репозитория
Данный репозиторий содержит материалы лабораторной работы по развертыванию Greenplum Database в Docker-контейнере. Проект демонстрирует практические навыки работы с распределенными базами данных и контейнеризацией.

## Структура проекта
greenplum-launch/
├── docker_greenplum_launch.sh
└── greenplum_launch.md


## Содержание

1. **[Запуск Greenplum Database](greenplum-launch/greenplum_launch.md)**  
   - Подробное руководство по развертыванию Greenplum в Docker
   - Инструкция по запуску скрипта `docker_greenplum_launch.sh`
   - Скриншоты работоспособности решения
   - Параметры подключения к базе данных

## Быстрый старт

Для запуска Greenplum Database выполните:

```bash
# Перейдите в директорию с скриптами
cd greenplum-launch

# Дайте права на выполнение скрипта
chmod +x docker_greenplum_launch.sh

# Запустите скрипт
./docker_greenplum_launch.sh