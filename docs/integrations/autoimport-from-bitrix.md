---
sidebar_position: 3
sidebar_label: 'Настройка импорта из Bitrix24'
---

import copyBitrixSubdomain from '/img/integrations/autoimport-from-bitrix/copy-bitrix-subdomain.png';

# Как настроить автоматический импорт из «Битрикса»

В Sendsay можно настроить автоматический импорт email-адресов из сервиса Bitrix24. Это можно сделать в шесть шагов:

## 1. Установите приложение Sendsay в свой Битрикс

1. Перейдите по ссылке: [https://www.bitrix24.ru/apps/?app=subscriberu.sendsay](https://www.bitrix24.ru/apps/?app=subscriberu.sendsay)
2. Нажмите «Установить» и разрешите приложению доступ к своему аккаунту.

## 2. Создайте интеграцию в Sendsay

1. Перейдите перейдите в предыдущий интерфейс [по ссылке](https://sendsay.ru/account/#dashboard), либо откройте меню аккаунта в правом верхнем углу и выберите пункт **Предыдущий интерфейс**.
2. Откройте раздел **Подписчики → Интеграции** и выберите пункт **Bitrix24**.

![How to create integration with Bitrix](/img/integrations\autoimport-from-bitrix/how-to-create-integration-with-bitrix.gif) <br />

## 3. Настройте интеграцию

После создания интеграции откроется страница настроек.

### Подключите аккаунт Bitrix24

1. Нажмите «Подключить аккаунт».
2. Введите поддомен из адреса вашего Битрикса. Адрес поддомена можно скопировать в адресной строке:

<p align="center">
  <img src={copyBitrixSubdomain} alt="Copy Bitrix subdomain" />
</p>

3. Нажмите «Продолжить».

![How to connect Bitrix](/img/integrations\autoimport-from-bitrix/how-to-connect-bitrix.gif) <br />

### Выберите список для подписчиков

Вы можете создать новый список, выбрать существующий или просто загрузить контакты в базу. Рекомендуем загружать контакты из сторонних систем в списки, чтобы в дальнейшем с ними можно было работать отдельно.

### Выберите переменные для загрузки

Поставьте галочки рядом с разделами CRM, откуда вы хотите импортировать email-адреса:

- company (раздел «Компании»),
- lead («Лиды»),
- contact («Контакты»).

### Загрузите контакты или создайте действие по расписанию

Есть два варианта загрузки контактов:

**1. Импортировать один раз** — для этого нужно нажать «Загрузить адреса из Битрикс24».<br />

**2. Настроить автоматический импорт.** Для этого нажмите «Создать автоимпорт», введите название и нажмите «Создать автоимпорт» ещё раз. Это сгенерирует и активирует действие по расписанию — контакты будут импортироваться ежедневно в 00:00 по московскому времени. Чтобы изменить настройки, нажмите на автоимпорт — откроется страница с параметрами загрузки.

:::tip Важно

Не создавайте список при настройке автоматического импорта, иначе при каждой загрузке контактов список будет дублироваться

:::
