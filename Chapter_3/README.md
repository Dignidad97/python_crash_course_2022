## EX 3-1
```python
names = ['Andrew', 'Dima', 'Vlad']
print(names[0])
print(names[1])
print(names[-1])
```
```
Andrew
Dima
Vlad
```
## EX 3-2
```python
names = ['Andrew', 'Dima', 'Vlad']
message = "Hi, " + names[0] + "! How are you?"
print(message)

message = "Hi, " + names[1] + "! How are you?" 
print(message)

message = "Hi, " + names[2] + "! How are you?"
print(message)
```
```
Hi, Andrew! How are you?
Hi, Dima! How are you?
Hi, Vlad! How are you?
```
## EX 3-3
```python
cars = ["Дев'ятка" , "Форд" , "Метро"]
message = 'Мій батя має авто, це ' + cars[0] + '. Думаю, що б краще він мав ' + cars[1] + '. Ну а мені, в принципі, й на ' + cars[-1].lower() + ' норм).'
print(message)
```
```
Мій батя має авто, це Дев'ятка. Думаю, що б краще він мав Форд. Ну а мені, в принципі, й на метро норм).
```
## EX 3-4
```python
friends = ['дмитро', 'анастасія', 'сашко']
print('Любий, ' + friends[0].title() + ', я хочу запросити тебе на вечерю! Чекаю на зустріч!')
print('Люба, ' + friends[1].title() + ', я хочу запросити тебе на вечерю! Чекаю на зустріч!')
print('Любий, ' + friends[2].title() + ', я хочу запросити тебе на вечерю! Чекаю на зустріч!')
```
```
Любий, Дмитро, я хочу запросити тебе на вечерю! Чекаю на зустріч!
Люба, Анастасія, я хочу запросити тебе на вечерю! Чекаю на зустріч!
Любий, Сашко, я хочу запросити тебе на вечерю! Чекаю на зустріч!
```
## EX 3-5
```python
friends = ['дмитро', 'анастасія', 'сашко']
print('Любий, ' + friends[0].title() + ', я хочу запросити тебе на вечерю! Чекаю на зустріч!')
print('Люба, ' + friends[1].title() + ', я хочу запросити тебе на вечерю! Чекаю на зустріч!')
print('Любий, ' + friends[2].title() + ', я хочу запросити тебе на вечерю! Чекаю на зустріч!')
print('\t'+ friends[2].title() + ' на жаль, прийти не зможе.')
friends[2] = 'данило'
print('Любий, ' + friends[0].title() + ', я хочу запросити тебе на вечерю! Чекаю на зустріч!')
print('Люба, ' + friends[1].title() + ', я хочу запросити тебе на вечерю! Чекаю на зустріч!')
print('Любий, ' + friends[2].title() + ', я хочу запросити тебе на вечерю! Чекаю на зустріч!')
```
Любий, Дмитро, я хочу запросити тебе на вечерю! Чекаю на зустріч!

Люба, Анастасія, я хочу запросити тебе на вечерю! Чекаю на зустріч!

Любий, Сашко, я хочу запросити тебе на вечерю! Чекаю на зустріч!


Сашко на жаль, прийти не зможе.

Любий, Дмитро, я хочу запросити тебе на вечерю! Чекаю на зустріч!


Люба, Анастасія, я хочу запросити тебе на вечерю! Чекаю на зустріч!

Любий, Данило, я хочу запросити тебе на вечерю! Чекаю на зустріч!

## EX 3-6
```python
friends = ['дмитро', 'анастасія', 'сашко']
print('Любий, ' + friends[0].title() + ', я хочу запросити тебе на вечерю! Чекаю на зустріч!')
print('Люба, ' + friends[1].title() + ', я хочу запросити тебе на вечерю! Чекаю на зустріч!')
print('Любий, ' + friends[2].title() + ', я хочу запросити тебе на вечерю! Чекаю на зустріч!')
print('\n')
print(friends[2].title() + ' на жаль, прийти не зможе.')
print('\n')
friends[2] = 'данило'
print('Любий, ' + friends[0].title() + ', я хочу запросити тебе на вечерю! Чекаю на зустріч!')
print('Люба, ' + friends[1].title() + ', я хочу запросити тебе на вечерю! Чекаю на зустріч!')
print('Любий, ' + friends[2].title() + ', я хочу запросити тебе на вечерю! Чекаю на зустріч!')
print('\n')
print('Гостей буде більше, адже мені таки вдалось придбати новий стіл!')
print('\n')
friends.insert(0, 'Іван')
friends.insert(2, 'Владислав')
friends.append('Аліна')
print('Любий, ' + friends[0].title() + ', я хочу запросити тебе на вечерю! Чекаю на зустріч!')
print('Люба, ' + friends[1].title() + ', я хочу запросити тебе на вечерю! Чекаю на зустріч!')
print('Любий, ' + friends[2].title() + ', я хочу запросити тебе на вечерю! Чекаю на зустріч!')
print('Любий, ' + friends[3].title() + ', я хочу запросити тебе на вечерю! Чекаю на зустріч!')
print('Люба, ' + friends[4].title() + ', я хочу запросити тебе на вечерю! Чекаю на зустріч!')
print('Любий, ' + friends[5].title() + ', я хочу запросити тебе на вечерю! Чекаю на зустріч!')
```
```
Любий, Дмитро, я хочу запросити тебе на вечерю! Чекаю на зустріч!

Люба, Анастасія, я хочу запросити тебе на вечерю! Чекаю на зустріч!

Любий, Данило, я хочу запросити тебе на вечерю! Чекаю на зустріч!

Гостей буде більше, адже мені таки вдалось придбати новий стіл!


Любий, Іван, я хочу запросити тебе на вечерю! Чекаю на зустріч!

Люба, Дмитро, я хочу запросити тебе на вечерю! Чекаю на зустріч!

Любий, Владислав, я хочу запросити тебе на вечерю! Чекаю на зустріч!

Любий, Анастасія, я хочу запросити тебе на вечерю! Чекаю на зустріч!

Люба, Данило, я хочу запросити тебе на вечерю! Чекаю на зустріч!

Любий, Аліна, я хочу запросити тебе на вечерю! Чекаю на зустріч!
```
## EX 3-7
```python
friends = ['дмитро', 'анастасія', 'сашко']
friends[2] = 'данило'
friends.insert(0, 'іван')
friends.insert(2, 'владислав')
friends.append('аліна')
notif = "Мені дуже не зручно, але на вечерю будуть запрошені лише двоє... "
print(notif)
print('\n')
notif_2 = "Вибач, "
notif_3 = ", але я змушений скасувати твоє запрошення. Вибач за незручності."
person = friends.pop()
print(notif_2 + person.title() + notif_3)
person_1 = friends.pop()
print(notif_2 + person_1.title() + notif_3)
person_2 = friends.pop()
print(notif_2 + person_2.title() + notif_3)
person_3 = friends.pop()
print(notif_2 + person_3.title() + notif_3)
print('\n')
notif_4 = ", наша вечірка в силі, чекаю на зустріч!"
print(friends[0].title() + notif_4)
print(friends[1].title() + notif_4)
del friends[0]
del friends[0]
print(friends)
```
```
Мені дуже не зручно, але на вечерю будуть запрошені лише двоє... 

Вибач, Аліна, але я змушений скасувати твоє запрошення. Вибач за незручності.
Вибач, Данило, але я змушений скасувати твоє запрошення. Вибач за незручності.
Вибач, Анастасія, але я змушений скасувати твоє запрошення. Вибач за незручності.
Вибач, Владислав, але я змушений скасувати твоє запрошення. Вибач за незручності.

Іван, наша вечірка в силі. чекаю на зустріч!
Дмитро, наша вечірка в силі. чекаю на зустріч!
[]
```







