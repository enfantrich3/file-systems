## Вводное задание
1. Создание новой директории:\
   mkdir project_files
2. Создание файлов:\
   touch project_files/file1.txt
   touch project_files/file2.txt
   touch project_files/file3.txt
3. Ввод текста в файлы:\
   echo "Текст" > project_files/file1.txt
   echo "Текст" > project_files/file2.txt
   echo "Текст" > project_files/file3.txt
4. Проверка текущих прав доступа:\
   ls -l project_files
5. Изменение прав доступа:\
   chmod u+x project_files/file1.txt   # Только для владельца
   chmod u+w,g+w project_files/file2.txt   # Для владельца и группы
   chmod a+x project_files/file3.txt   # Все пользователи
6. du -sh project_files или ls -l project_files
## Задание 1
1. mkdir ~/my_files
2. cd ~/my_files
3. touch file1.txt file2.txt file3.txt
4. chmod u=rw,go= file1.txt
5. chmod u=rw,go=r file2.txt
6. chmod u=rwx,go=rwx file3.txt
7. mkdir subfolder\
   mv file1.txt subfolder/
8. mv file2.txt renamed_file.txt
9. rm file3.txt
10. nano renamed_file.txt
11. ln -s renamed_file.txt link_to_file.txt
