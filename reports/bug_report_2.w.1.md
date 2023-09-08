### Bug Report #2.w.1 [🔙](../solutions/solution_2.md)
**Summary:**
> Очень долго скачивается файл (иногда, flaky) 

**Description:**
> Время скачивания файла небольшого размера (менее 1Мб) составляет 17 мин - 1 час\
> Ожидаемое событие - даже при низкой скорости интернета (например, xDSL 10Мб/сек)
> такой файл должен скачиваться за несколько секунд

**Steps to reproduce:**
> - Перейти по ссылке http://cloud.hh-demo.np-internal.ru/
> - Ввести Логин: *napopravku*, Пароль: *adminNaPopravku* 
> - Нажать кнопку "+ Upload File"
> - Нажать на название файла, например "1.docx" 
> - Начинается скачивание файла, прогресс скачивания отображается в браузере
> - Время скачивания составляет 17 мин - 1 час



**Reproducibility:**
> Иногда
> 
**Severity:**
> Значительный (Major)   
> 
**Priority:**
> Высокий (High)
> 
**Symptoms, labels, tags:**
> #cloud #upload #major #flaky
> 
**Workaround:**
> yes
> 
**Comments**
> 
 
**Attachments:**
> [Время скачивания 1 час](../attachments/2.w.1_actual.png)


# [🔙](../solutions/solution_2.md)