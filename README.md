# Использование API #
## Постановка задачи: ##
Требуется, используя, API В Контакте (или Facebook, yandex) получить информацию и вывести ее в удобочитаемом виде. Например, вывести
список друзей указанного пользователя, вывести названия фотоальбомов указанного пользователя и т. п.

## Использование: ##
Скрипт поддерживает следующие команды:
+ get_status (команда для получения статуса пользователя)
```
python using_the_vk_api.py *ID-пользователя* get_status
```
+ set_status (команда для того, чтобы задать статуса пользователя)
```
python using_the_vk_api.py *ID-пользователя* set_status -t *Текст, который выхотите задать в качесве статуса*
```
+ get_friends (команда для получения списка друзей пользователя)
```
python using_the_vk_api.py *ID-пользователя* get_friends -c *Указываем то количество людей. Сколько хотим вывести*
```
+ get_followers (команда для получения списка подписчиков пользователя)
```
python using_the_vk_api.py *ID-пользователя* get_followers
```
+ get_subscriptions (команда для получения списка подписок пользователя)
```
python using_the_vk_api.py *ID-пользователя* get_subscriptions
```
+ get_video_albums (команда для получения списка видео альбомов пользователя)
```
python using_the_vk_api.py *ID-пользователя* get_video_albums
```
## Видео пример работы скрипта ##
+ https://youtu.be/UJ6kBd4EqCs

___Задачу выполнил: Матус Матвей КН-201(МЕН-210201)___