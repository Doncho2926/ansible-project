# ansible-project

## Описание

Този проект използва Ansible за автоматична инсталация на Docker и стартиране на nginx сайт в Docker контейнер с помощта на docker-compose.

## Роли

- `install_docker`: Инсталира Docker и класическия Docker Compose.
- `run_nginx_website`: Копира необходимите файлове и стартира nginx сайт чрез docker-compose.

## Изисквания

- Ubuntu (18.04 или по-нова версия)
- Ansible инсталиран локално или на управляващата машина

## Как да стартираш проекта локално

1. Клонирай репозитория:

```bash
git clone https://github.com/Doncho2926/ansible-project.git
cd ansible-project
Стартирай playbook-а:

bash
Copy
ansible-playbook playbook.yml