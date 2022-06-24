# Назва проекту  **STEP-PROJECT-FORKIO**
 
Проект виконанно в трьох варіантах - 320px, 768px та 1200px.
Верстка зроблена з урахуванням принципів адаптивної верстки. 
Всі блоки змінюють своє взаємне розташування коли роздільна здатність екрану стає занадто малою, щоб розташовуватися на одній лінії.
Усі стилі в проекті написані у файлах формату SCSS.
Усі класи на сторінці задані за допомогою методології BEM.
Збірка проекту виконана за допомогою Gulp.

В проекті використанні такі технології:
  * Gulp
  * SASS
  * BEM
  
## Учасники проекту

* Denys Palyha
* Pavlo Nechai

### Denys Palyha 

Виконував завдання для студента №1

* Виконав налаштування Gulp для проекту.
* Зверстав шапку сайту з верхнім меню (включаючи випадаюче меню при малій роздільній здатності екрана).
* Зверстав секцію People Are Talking About Fork.

### Pavlo Nechai 

Виконував завдання для студента №2

* Зверстав блок Revolutionary Editor.
* Зверстав секцію Here is what you get.
* Зверстав секцію Fork Subscription Pricing.

## Основні npm команди для роботи над проектом.

Щоб розпочати розробку проєкту та запустити сервер потрібно скористатися командою:

#### npm start

Після завершеня розробки, для того щоб зібрати готову структуру проєкту для продакшена треба скористатися командою:

#### npm run build

Також сборка налаштована на деплой проекта на відаленний репозеторій на github, для цього потрібно в файлі package.json у розділі "homepage" записати "https:// назва репозиторія .github.io/ назва проекта", та виконати команду:

#### npm deploy
