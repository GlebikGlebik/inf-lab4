### Отчет по лабораторной работе №4
## Ход работы
1. Установил Docker Desktop
2. Далее в файле Dockerfile я прописал образ, на основе которого работает файл и установил дополнительное ПО под названием libaa-bin и iputils-ping
   
![666](https://github.com/user-attachments/assets/f665bac4-f50c-425b-8af1-e50458f8bbc2)

3. Затем я запустил команду сборки образом с тегом aafire
   
![image](https://github.com/user-attachments/assets/87689743-2297-4ea1-92c5-a55da1a9b0aa)

4. Далее я запустил контейнер на основе образа с тегом aafire

![image](https://github.com/user-attachments/assets/d5264f63-e31e-4d5a-bcf2-916cf5794240)


5. Получилось!

![image](https://github.com/user-attachments/assets/34bb669a-4938-488d-b4d4-887581347b88)

6. Далее я создал два контейнера и запустил их в различных терминалах и вручную задал им хосты

![image](https://github.com/user-attachments/assets/93bed37e-f6d5-42e2-8bde-b8fe70beb4c8)

![image](https://github.com/user-attachments/assets/b80fac06-c26a-4948-81b5-8fb637b01208)

7. Далее я создал сеть и подключил оба контейнера к ней

![image](https://github.com/user-attachments/assets/37612389-014a-4559-92dc-8ec5fecd0252)

8. Проверяю оба контейнера с помощью ping

![image](https://github.com/user-attachments/assets/aaaafc1b-8c25-4be2-b7c3-89fdf0f30b8e)

![image](https://github.com/user-attachments/assets/3031f70a-d491-4899-8b8d-0947d7e079f3)

На этом работа завершена. 







