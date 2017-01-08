# Проект сборки для команды Cars

## Для инициализации собственного проекта по сборке:

* Иметь установленный node
* Запустить команды в рабочей директории:

	npm init
	
	Необходимо ответить на все интересующие вопросы в консоли

	npm install -g gulp
	
	Установит Gulp глобального
	npm install --save-dev gulp
	
	Установит Gulp глобально к вашему проекту (Пропишет его автоматически в файле package.json в ветке devDependencies)

Далее необходимо установить все необходиые плагины для gulp'а, такие [к примеру](https://habrahabr.ru/post/252745/), командой 
	npm install plugin-name --save-dev
	
	эта команда добавит зависимости к проекту в файле package.json
