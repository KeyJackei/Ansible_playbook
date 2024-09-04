Удалённая установка nginx для fedora

Для выполнения установки прописать:
ansible-playbook -i hosts.yml nginx_install.yml --ask-vault-pass

В файле hosts прописан IP-адрес машины
