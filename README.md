# vue-test

## Задание 1
Ссылка - https://codesandbox.io/s/1-577iu

### Что было изменено:

1. В компоненте TimerComponent.vue
- в data было удалено пустое значение startDate, так как startDate уже имеется в родительском компоненте. 
Вместо этого добавлен inject startDate от родительского компонента и добавлено mutableStartDate в data для возможности изменения injected data.
- created() было заменено на mounted(), так как в родительском компоненте обновление данных происходит в mounted, 
а хук created() выпонляется раньше mounted()

2. В app.vue 
- в данном случае нет необходимости использования immediate: true в Watch

3. Варианты решения задачи: 
https://codesandbox.io/s/1-1-b9m1j
https://codesandbox.io/s/1-2-1gojo

## Задание 2
Ссылка - https://codesandbox.io/s/2-dcv2n

### Что было изменено:

1. Стили и классы были вынесены в отдельные объекты в computed (classObject, styleObject) для улучшения читаемости кода.

## Задание 3 (решена первая часть)
Ссылка - https://codesandbox.io/s/3-z5vuu

