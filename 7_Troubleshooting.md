[TOC]

# 7 Устранение неполадок
В данном разделе приведен разбор наиболее частых неполадок, их причины и методы устранения.

> В случае невозможности устранения приведенных ниже ситуаций или возникновения новых обращайтесь к ответственному астроному Р.И. Уклеину.



| Неполадка                                                    | Причина                                                      | Устранение                                                   |
| :----------------------------------------------------------- | ------------------------------------------------------------ | ------------------------------------------------------------ |
| Программа поиска звезд показывает неправильные координаты телескопа. При фокусировке телескопа программа анализа изображений говорит что все значения фокуса одинаковые. В FITS-шапку записываются неправильные координаты и метеопараметры. | Сбой программы создания файла параметров телескопа *bta_write* на tb.sao.ru (перезагрузка сервера и т.п.) | 1. Кликнуть на иконку *bta_write* на рабочем столе<br />2. Напрямую запустить пакет d:/scorpio.cfg/bta_write.bat <br />3. Перезагрузить компьютер LERA/LERA2. |

   
