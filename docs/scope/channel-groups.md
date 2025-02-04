---
sidebar_position: 4
---

# Связки каналов

Данная функция позволяет объединить несколько каналов в группу, для выполнения действий на всех них сразу

## Создание связки
`!addg !key`
- `key` - уникальное название связки

Пример:
```
!addg !mygroup
```

:::tip
Название связки уникально для всех каналов, к которым подключен бот
:::

## Отправка приглашения в связку
`!addgi !key username`
- `key` - уникальное название связки
- `username` - название канала

Пример:
```
!addgi !mygroup oldboty
```

## Принятие приглашения в связку
`!accepti !key`

Пример:
```
!accepti !mygroup
```

## Удаление связки
`!delg !key`

Пример:
```
!delg !mygroup
```
:::caution
Для этого действия вы должны быть создателем связки
:::

## Отмена приглашения в связку
`!delgi !key username`

Пример:
```
!delgi !mygroup oldboty
```

## Просмотр ваших связок и их участников
Перейдите в **[телеграм бота](https://t.me/oldboty_tw_bot)**, введите команду `/info` и нажмите кнопку "Ваши связки каналов"
