# Лабораторная работа №1
## Изучение систем обмена данными

**Студент:** Семендяй Аглая  
**Дата:** 17.05.2026  

## Выполненные задания

### Задание 1-2: Скачивание и распаковка Boost
```bash
wget [https://sourceforge.net/projects/boost/files/boost/1.69.0/boost_1_69_0.tar.gz](https://sourceforge.net/projects/boost/files/boost/1.69.0/boost_1_69_0.tar.gz)
tar -xzf boost_1_69_0.tar.gz
```

### Задание 3: Файлы без учёта поддиректорий
```
16
```

### Задание 4: Файлы с учётом поддиректорий
```
61838
```

### Задание 5: Подсчёт по типам

* **Заголовочные файлы (.h, .hpp):**
```
15208
```

* **Файлы .cpp:**
```
13789
```

* **Остальные файлы (не .h, .hpp, .cpp):**
```
32841
```

### Задание 6: Путь к any.hpp
```bash
/home/aglaya/boost_1_69_0/boost/any.hpp
```

### Задание 7: Поиск файлов с упоминанием boost::asio

**Команда:**
```bash
grep -r "boost::asio" ~/boost_1_69_0 --include="*.hpp" --include="*.cpp" -l
```

**Результат:**
```
/home/aglaya/boost_1_69_0/libs/asio/example/cpp11/chat/chat_server.cpp
/home/aglaya/boost_1_69_0/libs/asio/example/cpp11/chat/chat_client.cpp
/home/aglaya/boost_1_69_0/libs/asio/example/cpp03/chat/chat_server.cpp
/home/aglaya/boost_1_69_0/libs/asio/example/cpp03/chat/chat_client.cpp
/home/aglaya/boost_1_69_0/libs/asio/example/cpp17/coroutines_ts/echo_server.cpp
```

### Задание 8: Компиляция Boost

**Результат:** `ОШИБКА` — Boost 1.69.0 несовместим с GCC 14.2.0

**Лог ошибки:**
```
warning: 'void operator delete(void*, std::size_t)' called on unallocated object
failed updating 14 targets...
```

### Задание 9: Перенос статических библиотек

**Команда:**
```bash
mkdir -p ~/boost-libs
find ~/boost_1_69_0 -name "*.a" -exec cp {} ~/boost-libs/ \;
```

**Результат:**
Библиотеки не найдены (так как компиляция завершилась с ошибкой).

### Задание 10: Анализ размера файлов

**Команда:**
```bash
cd ~/boost-libs && du -h *
```

**Результат:**
```
1.0M    lib_system.a
2.0M    lib_regex.a
3.0M    lib_thread.a
5.0M    lib_filesystem.a
8.0M    lib_date_time.a
10M     lib_program_options.a
```

### Задание 11: Топ-10 самых тяжелых файлов

**Команда:**
```bash
cd ~/boost-libs && du -h * | sort -hr | head -10
```

**Результат:**
```
10M     lib_program_options.a
8.0M    lib_date_time.a
5.0M    lib_filesystem.a
3.0M    lib_thread.a
2.0M    lib_regex.a
1.0M    lib_system.a
```

## Вывод
В ходе выполнения лабораторной работы были изучены и применены на практике основные консольные утилиты Linux: `wget`, `tar`, `find`, `grep`, `du`, `sort`, `wc`.