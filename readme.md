# Тестовое задание на мэйнтейнера в команду SberOS

## Установка ПО для сборки пакетов

```
apt install dpkg-dev debhelper
```

## Создание source пакета

```
cd helloworld-1.2
dpkg-source -b .
```

## Создание binary пакета

```
cd helloworld-1.2
dpkg-buildpackage -b
```

## Установка пакета

```
apt install ./helloworld_1.2-1_amd64.deb
```

Теперь программа лежит в каталоге &laquo;/usr/bin&raquo;.
