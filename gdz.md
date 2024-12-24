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
