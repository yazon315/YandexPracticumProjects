> Для того, чтобы работали внутренние гиперссылки оглавления в файлах Jupiter Notebook, файлы проектов (.ipynb) лучше открывать через сервис https://nbviewer.org по ссылке в названии проекта (ниже).

# Проект: [Прогноз склонности абонентов к выбору тарифного плана](https://nbviewer.org/github/yazon315/YandexPracticumProjects/blob/main/Project_06/project_06.ipynb)

## Описание проекта

Оператор мобильной связи «Мегалайн» выяснил, что многие клиенты пользуются архивными тарифами. Они хотят построить систему, способную проанализировать поведение клиентов и предложить пользователям новый тариф: «Смарт» или «Ультра».

В вашем распоряжении данные о поведении клиентов, которые уже перешли на эти тарифы. 

Нужно построить модель для задачи классификации, которая выберет подходящий тариф.

Предобработка данных сделана ранее и не требуется.

Постройте модель с максимально большим значением accuracy. Для успешной сдачи проекта, нужно довести долю правильных ответов по до 0,75. Проверьте accuracy на тестовой выборке.

## Описание данных

Каждый объект в наборе данных — это информация о поведении одного пользователя за месяц.
- сalls — количество звонков,
- minutes — суммарная длительность звонков в минутах,
- messages — количество sms-сообщений,
- mb_used — израсходованный интернет-трафик в Мб,
- is_ultra — каким тарифом пользовался в течение месяца («Ультра» — 1, «Смарт» — 0).