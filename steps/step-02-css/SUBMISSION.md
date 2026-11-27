# Отчёт по шагу 02 — Матвеев Андрей, ИСр25-1

- **Ссылка на Pages:** https://anbier-gazer.github.io/kitis-isr/steps/step-02-css/check.html
- **Ссылка на папку шага в репозитории:** https://github.com/anbier-gazer/kitis-isr/tree/main/steps/step-02-css
- **Автопроверка:** 10 / 10 (прогнал check.html, число честное)

## Что сделано

- [x] в индексе скопировал три карточки по образцу, переименовал назвния и нумерацию, также subject-color
- [x] добавил gap для .lesson, 10px кажется хватает
- [x] в .lesson-card добавил display, align-items, gap, border-left с цветом subject-color, border-radius и background как в TODO
- [x] в .lesson-num добавил width, height, background-color, border-radius, border, color, font-weight на 700 и display: flex; align-items: center как в TODO
- [x] текст c номерами не централизован поэтому попробовал align-content, align-self, font-weight - без удачи. потом вставил text-align и padding-top для частичной централизации; flex убран
- [x] добавил вместе с subject-color subjec-grad-begin и end, использую их для разных цветов карточек

## ИИ (обязательно, честно)

- не использовал

## Затыки и вопросы

- текст номеров карточек не центрируется как указано с flex, добился частичной централизации с text-align и padding-top, хоть и сам бокс уже не 40x40
- не смог нормально добавить градиент для каждой карточки, так что поступил так же как и с subject-color
- данные о преподах и времени взяты с README корневого
- в таблице README даны оттенок 22% и 10%. в коде TODO 45% и 100% до #FFFFFF

## Готов к защите

Да