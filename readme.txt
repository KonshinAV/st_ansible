ansible -i hosts.txt staging_servers -m ping
# -i файл инвентори
# staging_servers имя группы где выполнять, all - все что есть в intentory
# -m модуль

ansible-inventory --list
# Показать invertory
