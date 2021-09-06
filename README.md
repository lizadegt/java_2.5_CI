## Домашнее задание к занятию «Выстраивание процесса непрерывной интеграции (CI): Github Actions. Покрытие кода с JaCoCo, статический анализ кода: CheckStyle, SpotBugs»

### Счетчики покрытия тестами:
**INSTRUCTION** - инструкцией байт-кода. Охват инструкций указывает, какие инструкции были выполнены или пропущены. Этот индекс  независим от исходного формата и действителен при любых обстоятельствах и не требует отладочной информации для файлов классов.

**LINE** - Для всех файлов классов, которые были скомпилированы с отладочной информацией, можно рассчитать информацию о покрытии для отдельных строк. Исходная строка считается выполненной, если была выполнена хотя бы одна инструкция, назначенная этой строке.

**BRANCH** - Рассчитывает покрытие ветви для всех инструкций if и switch. Этот индикатор будет подсчитывать количество всех ветвей и одновременно сообщать какие ветви выполняются, а какие не выполняются.

***Почему мною был выбран BRANCH:***
1. Есть условие IF
2. При запуске и сравнении показателей трех счетчиков, именно у BRANCH было наименьшее значение.