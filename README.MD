# RAR Cracker

## Особенности

- Возможность задать количество одновременно работающих горутин.
- На входе должен быть ваш файл с паролями, например слитыми в открытый доступ или сгенерированный/подобранный вами.
- Интегрированный прогресс-бар для отслеживания подбора.


## Установка и запуск

```bash
git clone https://github.com/yourusername/rarcracker.git
cd rarcracker
go build
./rarcracker -f <путь_к_rar_файлу> -d <путь_к_словарю> -c <количество_горутин>
```

## На примере из проекта:
```bash
go run crack.go -f open_me.rar -d dict.txt -c 100
```
