<h1 align="center">Проект UI автотестов книжного магазина
<p align="center">
<a href="respublica.ru"> <img src="readme_resources/respublica_logo.svg" width="" height="110"> </a> </h1>


<h3 align="center">Python | Pytest | Selene | Jenkins | Allure | Selenoid | Telegram</h3>
<h3 align="center">
<img height="50" src="readme_resources/icons/python.png"/>      &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;
<img height="50" src="readme_resources/icons/Pytest.svg"/>      &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;
<img height="50" src="readme_resources/icons/Selene.png"/>      &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;
<img height="50" src="readme_resources/icons/jenkins.svg"/>     &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;
<img height="50" src="readme_resources/icons/allure.png"/>      &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;
<img height="50" src="readme_resources/icons/Selenoid.svg"/>    &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;
<img height="50" src="readme_resources/icons/Telegram.svg"/>
</h3>



---

### Проверки:
- [x] Логин
- [x] Добавление одного товара в корзину
- [x] Добавление нескольких товаров одного типа в корзину
- [x] Добавление нескольких разных товаров в корзину
- [x] Удаление одного товара из корзины
- [x] Очистка корзины


## Настройка и запуск локально

1. Клонируйте репозиторий

```bash
git clone https://github.com/vinterbris/qa_guru_python_9_15.git
```

2. Создайте и активируйте виртуальное окружение

```bash
cd qa_guru_python_9_15
python -m venv .venv
```
Для Linux и Mac:
```bash
source .venv/bin/activate
```
Для Windows:
```bash
.venv/Scripts/activate
```

3. Установите зависимости с помощью pip

```bash
pip install -r requirements.txt
```

<details open>
  <summary><b>4. Установите Allure</b></summary>

Linux\Mac через Homebrew
```bash
brew install allure
```

Windows через scoop
```bash
scoop install allure
```


[Или из напрямую из релизов с github](https://github.com/allure-framework/allure2/releases)

<details>
    <summary>Инструкция при установке из архива</summary>

1. Скачать последнюю версию под свою систему 
2. Разархивировать в корень проекта
3. Папку (например `allure-2.27.0`) переименовываем в `allure`
4. Аллюр из архива готов, теперь запускать отчет можно из корня проекта командой:

Linux\Mac: 
```bash
allure/bin/allure serve
```

Win: 
```bash
allure/bin/allure.bat serve
```

</details>

[Другие варианты](https://allurereport.org/docs/gettingstarted-installation/)

</details>


5. Запустите автотесты

```bash
pytest tests
```

6. Получите отчёт allure командой (если добавлен в PATH)  

Linux\Mac

```bash
allure serve
```
Windows
```bash
allure.bat serve
```



## Запуск через jenkins+selenoid


## Оповещения в мессенджер



> Настроена отправка оповещений в телеграм канал. Возможна настройка для email, slack, discord, skype, mattermost

<img src="readme_resources/telegram.png" height="350"/>

<video src="readme_resources/selenoid_video.mp4" height=""/>

https://github.com/vinterbris/qa_guru_python_9_15/blob/master/readme_resources/selenoid_video.mp4
