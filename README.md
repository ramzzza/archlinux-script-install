# archlinux-kde--script-install-uefi-nogrub   
РЕЖИМ UEFI и Legacy

Для установки  ArchLinux(KDE) вам необходимо загрузиться с установочного диска ArchLinux и в теринале выполнить   

1 wget http://bit.do/arch-kde-install

2 chmod + x arch-kde-install

3 ./arch-kde-install

Данный скрипт позваляет установить ArchLinux(KDE), как рядом с Windows так и произвести чистую установку.
___________________________________________________________________________________________________________
Файловая система для root раздела "ext4"
Файловая система для home раздела "ext4"
Файловая система для boot раздела "FAT32" < так требует стандарт UEFI(загрузчик для ArchLinux systemD)
Файловая система для boot раздела "ext2" < в legacy режиме
__________________________________________________________________________________________________________
Список пакетов установленных по умолчанию

пакеты драйверов xorg-server xorg-drivers (после установки можно будет установить/дополнить )

pulseaudio-bluetooth  flameshot ark exfat-utils filezilla gparted unrar neofetch screenfetch 

alsa-utils android-tools unzip  gwenview steam steam-native-runtime ktorrent  kwalletmanager 

speedtest-cli ntfs-3g spectacle vlc  telegram-desktop latte-dock  pulseaudio-equalizer-ladspa 

zsh(С таким же плагином и подцветкой как в усановочном образе archlinux ) 

так же можно установить Mozilla Firefox(russian) или GoogleChrome на выбор

удален только браузер  браузер konqueror

__________________________________________________________________________________________________________

По всем вопросам пишите https://vk.com/poruncov или https://t.me/poruncov

Более подробная информация по ArchLinux в группе в ВК https://vk.com/arch4u

Скрипт находиться на этапе финишной подгонки!!!!
