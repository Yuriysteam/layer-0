## Подготовка среды

### Mac OS

1. Установить [Homebrew](https://brew.sh):
    ```shell
    /usr/bin/ruby -e "$(curl -fsSL https://raw.githubusercontent.com/Homebrew/install/master/install)"
    ```

2. Установить [Node.js](https://nodejs.org/en/) и [Yarn](https://yarnpkg.com/lang/en/):
    ```shell
    brew install yarn
    ```

### Windows

1. [Скачать](https://nodejs.org/en/) и установить Node.js.

2. [Скачать](https://yarnpkg.com/lang/en/docs/install/#windows-stable) и установить Yarn.

## Как начать пользоваться

1. Перейти в папку проекта в терминале. Для этого надо написать cd и путь до файла. Например:
    ```shell
    cd /Users/Intuition/Documents/layer-0/
    ```

2. Запустить сайт:
    ```shell
    yarn start
    ```

3. Сайт будет автоматически открыт в браузере по адресу [http://localhost:1234](http://localhost:1234).

4. Чтобы собрать билд, нужно выполнить:
    ```shell
    # сборка только JS и SCSS (для сайта с бэкэндом)
    yarn build

    # сборка HTML, SCSS и JS в папку site (для статического сайта)
    yarn build:static
    ```
