# Курс «DevOps. Системный инженер»

## Выполненные задания:

#### 1. 05.Git
---
#### Создал у себя на локальной машине Git репозиторий со следующими ветками:

  * master - в ней 2 коммита
  * staging - в ней 2 коммита из master + 2 дополнительных
  * test - в ней 2 коммита из master + 2 дополнительных из staging + 1 дополнительный
  * fix/prod_is_down - в ней 2 коммита из master + 1 дополнительный

#### Предположим следующие сценарии:

  1. Релиз в production - все коммиты должны быть в ветке master 
     (кроме коммитов в ветке fix/prod_is_down);
  2. Развертывание fix - коммит из ветки fix/prod_is_down должен быть во всех ветках;
