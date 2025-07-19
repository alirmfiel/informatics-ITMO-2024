1.Проверила работу на файле script.bash
<img width="1029" height="244" alt="image" src="https://github.com/user-attachments/assets/fbfc09f3-f4db-444f-8b3d-de6bfa89da21" />
2.Для своего удобства создала файл lab1.bash: touch lab1.bash
3.Выполнила gedit lab1.bash и вписала нужную команду
<img width="1029" height="244" alt="image" src="https://github.com/user-attachments/assets/ac4970aa-702c-4d91-93b1-dfede4016fd2" />


  строка #!/bin/bash
    -я могла бы сделать файл исполняемым, то есть написать "chmod +x lab1.bash", а потом запускать через "./lab1.bash", как любую другую обычную программу
    -могу ничего не менять и запускать через "bash lab1.bash", как в примере, тогда строка "#!/bin/bash" ни на что не влияет, так как я через "bash" при запуске говорю, каким интерпретатором работать
  
  
  строка echo "Welcome, $*"
    -"echo" команда для вывода текста; "Welcome, $*" - строка, куда подставляются значения переменных
    -"$*" все аргументы (позиционные параметры), в виде одной строки (слова)
