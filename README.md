# Проект по тестированию мобильного приложения *wikipedia.org*

## Список проверок
 - Проверка начального экрана;
 - Проверка выдачи списка найденных статей;
 - Проверка перехода на найденную статью.

## Технoлoгии и инструмeнты
<p align="center">
<a href="https://www.python.org/"><img src="design/icons/python.svg" width="50" height="50"  alt="Python" title="Python"/></a>
<a href="https://docs.pytest.org/"><img src="design/icons/pytest.svg" width="50" height="50"  alt="PyTest" title="PyTest"/></a>
<a href="https://www.selenium.dev//"><img src="design/icons/selenium.svg" width="50" height="50"  alt="Selenium" title="Selenium"/></a>
<a href="https://appium.io/docs/en/2.1/"><img src="design/icons/appium.png" width="50" height="50"  alt="Selenium" title="Selenium"/></a>
<a href="https://www.browserstack.com/"><img src="design/icons/browserstack.png" width="50" height="50"  alt="Selenoid" title="Selenoid"/></a>
<a href="https://www.jenkins.io/"><img src="design/icons/jenkins.svg" width="50" height="50"  alt="Jenkins" title="Jenkins"/></a>
<a href="https://qameta.io/allure-report/"><img src="design/icons/allure.png" width="50" height="50"  alt="allure-report" title="allure-report"/></a>
<a href="https://qameta.io/allure-report/"><img src="design/icons/allure_testops.png" width="50" height="50"  alt="allure-report" title="allure-report"/></a>
<a href="https://github.com/"><img src="design/icons/github.png" width="50" height="50"  alt="Github" title="Github"/></a>
<a href="https://web.telegram.org/"><img src="design/icons/telegram.png" width="50" height="50"  alt="Telegram" title="Telegram"></a>
</p>

## Запуск автотестов в Jenkins
#### 1. Открыть <a target="_blank" href="https://jenkins.autotests.cloud/job/C07-elena_ching-python_mobile_tests_final/">проект</a>
#### 2. Нажать **Build**
![This is an image](design/jenkins_build.png)
#### 3. Результат запуска сборки можно посмотреть в отчёте Allure
![This is an image](design/allure_results.png)


#### Пример видеозаписи прохождения теста
Mobile
![This is an image](design/mobile_gif.gif)

# Интеграция с Allure TestOps и Telegram
#### Результаты прохождения тестов, а также сами тест-кейсы будут отправлены в Allure TestOps
![This is an image](design/testopts.png)
# Настроено автоматическое оповещение о результатах сборки Jenkins в Telegram
![This is an image](design/telegram.png)