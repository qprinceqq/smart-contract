Смарт-контракт для голосования - my ballot

# Как запустить проект

Установите зависимости 

```
yarn install
```

Проверьте работоспособность контракта

```
yarn test
```

Запустите локальную сеть Ethereum 

```
yarn chain
```

Откройте новый терминал
Разверните смарт-контракт 

```
yarn deploy
```

Запустите фронтенд 

```
yarn start
```

Откройте приложение 

```
http://localhost:3000
```

(в проекте ипсользовался hardhat версии 22.10.0)

# Функционал смарт-контракта

1. Создание голосования (только создатель сети)
2. Редактирование голосования (добавление/удаление кандидатов и деактивация голосования - только создатель сети)
3. Возможность проголосовать (любой участник и только один раз за одно голосование)
4. Возможность унзать резултьат того или иного голосования.
