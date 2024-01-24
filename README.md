# BeraChainTools

BeraChainTools Коллекция инструментов для экосистемы BeraChain, призванных помочь пользователям легко выполнять различные взаимодействия и операции.

# # Установка зависимостей

Прежде чем начать использовать BeraChainTools, убедитесь, что вы установили все необходимые зависимости.

Выполните следующую команду для установки зависимостей:

``
pip install -r requirements.txt
```

### Руководство по настройке

#### 1. Настройка агента

- Откройте файл `.env`.
- Найдите `PROXY_URL` и замените его на ссылку извлечения прокси. Убедитесь, что формат извлечения - текстовый, а количество извлечений установлено на 1.

  Пример:
  ``
  PROXY_URL=http://example.com/get-proxy?nums=1
  ```

#### 2. Настройка ключа YesCaptcha

- Если у вас еще нет учетной записи YesCaptcha, сначала зарегистрируйтесь здесь: [yescaptcha registration link](https://yescaptcha.com/i/0vVEgw).
- Получите свой ключ клиента YesCaptcha.
- Найдите `YesCaptchaClientKey` в файле `.env` и заполните свой ClientKey.

  Пример:
  ```
  YesCaptchaClientKey=YOUR_CLIENTKEY_HERE
  ```

#### 3. Установка MaxWorkers

- Найдите `MaxWorkers` в файле `.env` и впишите количество потоков, которое вы хотите установить.

  Пример:
  ``
  MaxWorkers=8
  ```

## Особенности и использование

### BeraChain Collateral Water

drip_tokens.py
Создает или указывает адрес для получения воды.

- **Ссылка доступа**: [BeraChain water collection](https://artio.faucet.berachain.com/)
- **Статус**: завершен

### Взаимодействие с бексами

bex_swap.py
Поддержка обмена токенов и повышения ликвидности

- **Ссылка**: [взаимодействие с bex](https://artio.bex.berachain.com/swap)
- **Статус**: завершен

### взаимодействие с медом

honey_swap.py
Поддержка майнинга и выкупа

- **Ссылка на доступ**: [взаимодействие с медом](https://artio.honey.berachain.com)
- **Статус**: завершен

### bend interaction

Используется для взаимодействия с сервисом BeraChain's bend.

- **Ссылка**: [bend interaction](https://artio.bend.berachain.com/)
- **Статус**: в процессе

### berps interaction

Используется для взаимодействия с сервисом berps компании BeraChain.

- **Ссылка на доступ**: [berps interaction](https://artio.berps.berachain.com/)
- **Статус**: в процессе

### взаимодействие со станцией

Используется для взаимодействия со станционным сервисом BeraChain.

- **Ссылка на доступ**: [взаимодействие со станцией](https://artio.station.berachain.com/)
- **Статус**: ожидается

---

Спасибо за использование
BeraChainTools! Если у вас есть вопросы или предложения, пожалуйста, свяжитесь с нами через [GitHub Issues](https://github.com/ym)
