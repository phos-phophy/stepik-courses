### [Первая задача](elf_1.cpp)

Напишите функцию, которая по заданному имени ELF файла возвращает адрес точки входа.


### [Вторая задача](elf_2.cpp)

В это задании вам нужно для ELF файла найти все его program header-ы, которые описывают участки памяти (p_type == PT_LOAD), и посчитать, сколько места в памяти нужно, чтобы загрузить программу.