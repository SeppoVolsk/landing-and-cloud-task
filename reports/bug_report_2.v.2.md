### Bug Report #2.v.2 [🔙](../solutions/solution_2.md)
**Summary:**
> Неправильно отображается время создания файла  

**Description:**
> Время создания файла, указанное в облаке, не совпадает с временем создания файла на ПК  
> Ожидаемое событие - время создания файла в облаке и на ПК одинаковое

**Steps to reproduce:**
> - Перейти по ссылке http://cloud.hh-demo.np-internal.ru/
> - Ввести Логин: *napopravku*, Пароль: *adminNaPopravku* 
> - Нажать кнопку "Выбрать файлы"
> - Выбрать файл для загрузки размером не более 1 Мб
> - Нажать кнопку "+ Upload File"
> - Файл отображается в списке загруженных
> - Время создания файла, указанное под именем файла не совпадает с временем создания в свойствах файла в ОС


**Reproducibility:**
> Всегда
> 
**Severity:**
> Значительный (Major)   
> 
**Priority:**
> Высокий (High)
> 
**Symptoms, labels, tags:**
> #cloud #upload #major
> 
**Workaround:**
> no
> 
**Comments**
> 
 
**Attachments:**
> [Время создания в облаке](../attachments/2.v_actual.png)\
> [Время создания в OS](../attachments/2.v_expected.png)

# [🔙](../solutions/solution_2.md)