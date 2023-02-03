копирует файлы конфигурации на прокси сервера squid

запукск плэйбука
ansible-playbook -i inventory/test.yml site.yml
ansible-playbook -i inventory/prod.yml site.yml

запускаем плэйбук от учетки ansible

# v01 | копирует файлы конфигурации из локальной папки ./files/URLacls/black_list.acl
