# git init

Створення порожнього Git-репозиторію (приклад з поясненнями) або повторна ініціалізація існуючого


```
git init [-q | --quiet] [--bare] [--template=<template_directory>]
	  [--separate-git-dir <git dir>] [--object-format=<format>]
	  [-b <branch-name> | --initial-branch=<branch-name>]
	  [--shared[=<permissions>]] [directory]
```

## Опції

| Приклади команди з використанням опцій | Опис особливостей результату |
| ----------- | ----------- |
| **git init -q**<br>або<br>**git init --quiet**  | Команда з відключеним виводом повідомлень які не містять інформацію про помилку або не є попередженнями |
| **git init --bare** | Команда створення **чистого** репозиторію (приклад з поясненнями) |
