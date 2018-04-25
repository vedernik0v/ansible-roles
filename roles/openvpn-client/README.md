OpenVPN client
==============

Настраивает клиент OpenVPN

Requirements
------------

На целевой системе должен быть установлен Python2

Role Variables
--------------

* `openvpn_client_ca_crt` - корневой сертификат
* `openvpn_client_client_crt` - сертифика клиента
* `openvpn_client_client_key` - ключ клиента
* `openvpn_client_host` - адрес сервера (`12.34.56.78`)
* `openvpn_client_package_version` - версия пакета openvpn (`2.3.10-1ubuntu2.1`)
* `openvpn_client_port` - порт сервера (`1194`)
* `openvpn_client_protocol` - протокол (`UDP`)
* `openvpn_client_ta_key` - ключ безопасного соединения

License
-------

BSD
