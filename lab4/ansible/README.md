1. Образ ОС Linux семейства RMP (Выключаем там firewall и selinux)
2. Создаем vagrant box
3. В директории ansible пишем 'vagrant up'
4. Затем 'vagrant-playbook nginx.yml'
5. Complete! Можем увидеть результат в браузере, введя <ip_address>:<port> 
   Например: '192.168.11.111:8080'