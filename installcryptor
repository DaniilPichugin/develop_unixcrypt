#!/bin/bash

echo "CRYPTOR 1.2 (rus) version"
echo "by Daniil Pichugin"

echo "Вы можете прочитать все инструккции и справки в документе README.md"
echo "==================================================================="

#######################################################################################
##проверка наличия необходимых пакетов. 

echo "Установка и обновления необходимых пакетов"


packinst=$(
	sudo apt-get install git gpg base64 base32

	git clone https://github.com/alexanderepstein/Bash-Snippets
	cd Bash-Snippets

	sudo ./install.sh crypt
		)

echo -n "Начать процесс? [Y/n]: "
raad answer

	case $answer in
		Y|y) $packlist
			;;
		N|n) echo "Программа остановлена!"

##########################################################################
##Выбор дальнейших действий

	if $* ; 
		then echo "Все прошло успешно!"
		     $selectprg;
		else echo "Неизвестная ошибка!"
	fi

selectprg=$(

	echo "Для продолжения программы, мы сменим скрипт."
	echo -n "Хотите продолжить?[Y|n]: "
	read answer2
		)
	case $answer2 in 
		Y|y) ./CRYPTOR.sh
			;;
		N|n) echo "Программа остановлена"
			;;
	esac
#############################################################################
##окончание программы

echo "Завершение программы"
echo "Спасибо за исопльзование! :-)"
