# Тоже устали от гайдов где рекомендуют поставить ***? Не хотите, чтобы проксировалась вся система и был высокий PING в играх?

## Выключите ***, GoodbyeDPI и другие ускоряторы — они будут конфликтовать.
### Шаг 1
Качаем амнезию (https://github.com/amnezia-vpn/amneziawg-windows-client/releases/download/1.0.0/amneziawg-amd64-1.0.0.msi)

Регистрируемся на Github (если у Вас нет аккаунта) и далее переходим по этой ссылке (https://github.com/codespaces/templates)

Находим "Blank" и нажимаем Use this template.
![image1](https://i.imgur.com/hegS3ZO.png)

# Вставляем в терминал данный код
curl -sSL https://raw.githubusercontent.com/ImMALWARE/bash-warp-generator/main/warp_generator.sh  | bash
и жмем Enter.

Через 1-4 минуты Вам предложит скачать конфиг, открываем ссылку в терминале с помощь ctrl+лкм
![image2](https://i.imgur.com/5wX2e4G.png)

### Шаг 2

После того, как вы успешно выполнили 1 шаг и скачали конфиг, редактируем его через текстовик и меняем следующее:
⁡AllowedIPs = 0.0.0.0/0, ::/0 ⁡на AllowedIPs = 162.159.0.0/16, 66.22.0.0/16

Хотите настроить еще и YouTube? То прописываем к предыдущим IP адресам следующее:
8.8.4.0/24, 8.8.8.0/24, 8.34.208.0/20, 8.35.192.0/20, 23.236.48.0/20, 23.251.128.0/19, 34.0.0.0/10, 35.184.0.0/13, 35.192.0.0/14, 35.196.0.0/15, 35.198.0.0/16, 35.199.0.0/17, 35.199.128.0/18, 35.200.0.0/13, 35.208.0.0/12, 64.18.0.0/20, 64.233.160.0/19, 66.102.0.0/20, 66.249.64.0/19, 70.32.128.0/19, 72.14.192.0/18, 74.114.24.0/21, 74.125.0.0/16, 104.132.0.0/23, 104.133.0.0/23, 104.134.0.0/15, 104.156.64.0/18, 104.237.160.0/19, 108.59.80.0/20, 108.170.192.0/18, 108.177.0.0/17, 130.211.0.0/16, 136.112.0.0/12, 142.250.0.0/15, 146.148.0.0/17, 162.216.148.0/22, 162.222.176.0/21, 172.110.32.0/21, 172.217.0.0/16, 172.253.0.0/16, 173.194.0.0/16, 173.255.112.0/20, 192.158.28.0/22, 192.178.0.0/15, 193.186.4.0/24, 199.36.154.0/23, 199.36.156.0/24, 199.192.112.0/22, 199.223.232.0/21, 207.223.160.0/20, 208.65.152.0/22, 208.68.108.0/22, 208.81.188.0/22, 208.117.224.0/19, 209.85.128.0/17, 216.58.192.0/19, 216.239.32.0/19, 216.239.36.0/24, 216.239.38.0/23, 216.239.40.0/22

Подключаемся и кайфуем с пацанами в дисике и смотрим ютубчик)))
