# Пермутации

## Условие

След като вече напълно разбирате пермутациите сигурно можете и да ги броите. Намерете **K**-тата пермутация на числата **от 1 до N**. Пермутация **А** e по-малка от **B** когато първото различаващо се число на двете пермутации е по-малко при **A**.

## Вход
- От първия ред се четат числата **N** и **K** разделени с интервал

## Изход
- Да се изведе **K**-тата пермутация на числата **от 1 до N** на единствен ред
  - Числата да са разделени с интервал

## Ограничения
- 1 <= **N** <= 20
- 1 <= **K** <= **N!**
- Лимит за памет: **8MiB**
- Лимит за време: **0.1 секунди**

## Примери

### Вход
```
5 7
```

### Изход
```
1 3 2 4 5
```

### Пояснение
```
1:  1 2 3 4 5
2:  1 2 3 5 4
3:  1 2 4 3 5
4:  1 2 4 5 3
5:  1 2 5 3 4
6:  1 2 5 4 3
7:  1 3 2 4 5
```

### Вход
```
11 493737
```

### Изход
```
1 3 6 4 11 9 7 5 8 2 10
```
