# Работа с GRUB

Для работы с GRUB создавалась ВМ с помощью Vagrant. box = "generic/ubuntu2204"

1) Включение отображения меню GRUB
   
![grub_config](https://github.com/user-attachments/assets/43d8b161-1acc-4611-9b15-ee4b174b42d0)

2) Изменение загрузки с добавлением параметра init=/bin/bash

![init_bin_bash1](https://github.com/user-attachments/assets/742cdf38-ed7b-496b-8ddb-d5a4fa52a87e)

3) C использованием Recovery mode

![recovery_mode](https://github.com/user-attachments/assets/00e077bd-4263-4e3f-a248-1e8c8963b21f)


4) После чего было произвдено переименование VG в ubuntu-otus

   
![grub_rename_vgs](https://github.com/user-attachments/assets/ae85bcee-3d26-4a96-858b-db5b54a841e3)

5) После перезагрузки убеждаемся, что все работает

![grub_vgs_rename_otus_finish](https://github.com/user-attachments/assets/d219fae9-c867-4d7a-8cf3-724c5683a520)
