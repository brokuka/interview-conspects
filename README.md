# Конспекты

Всем привет, собрал небольшие конспекты, которые надеюсь будут полезны не только мне 🙃

### Типы данных

> [!NOTE]
> По ошибке языка, если проверять тип `null`, то покажет `object`, а на деле это не так.

Всего есть **8** типов данных в `JavaScript` и они разделяются на два варианта:

**1. Примитивы**

1.  number
2.  bigint
3.  string
4.  null
5.  undefined
6.  boolean
7.  symbol

**2. Объекты** (сюда заходят **массивы**, **функции** и т.д)

### Объявление переменной

> [!NOTE]
> Если переменная объявленна с помощью ключевых слов `let` и `var`, то по умолчанию у них значение `undefined`.

Переменные можно объявлять с помощью **специальных ключей** это:

1. var
2. let
3. const

#### `var`

До выхода ключевых слов `let` и `const`, переменные создавались с помощью `var`. Имеет **функциональный** и **глобальный** область видимости, может быть объявлён повторно и без значения.

#### `let` и `const`

Объявление переменной этими ключами схожи, у обоих есть блочный область видимости, а это значит что они видны только внутри блока `{}` и их нельзя применять вне этого блока и повторно объявлять.

Разница между ними:

1. При объявлении переменной с помощью ключевого слово `const` обязательно нужно присваивать значение, иначе ошибка.
2. Нельзя повторно задавать значение у переменных объявленных с помощью `const`, иначе ошибка.

> [!NOTE]
> На деле переменную объявлять нужно по современным стандартам с помощью `let` или `const`.

### Всплытие / Хоистинг

Всплытием называется механизм движка `JavaScript` когда до объявления переменной с помощью ключегого слово `var` можно проводить процедуры над ним, т.к под капотом движка переменная поднимается на самый вверх функции и инициализируется.

### Асиннхроность

Асиннхроностью называется код или участок кода который выполняется отложенно.

В языке есть `Promise` которой обрабатывает асиннхронный код.

### Event loop

...
