### Bug Report #2.d.1 [🔙](../solutions/solution_2.md)
**Summary:**
> Нельзя удалить файл (иногда, flaky) 

**Description:**
> При попытке удаления файла возникает ошибка браузера "Не удается получить доступ к сайту" либо "503 Forbidden"\
> Файл не удаляется из облака\
> Ожидаемое событие согласно требований - возможность удалить файл из облака 

**Steps to reproduce:**
> - Перейти по ссылке http://cloud.hh-demo.np-internal.ru/
> - Ввести Логин: *napopravku*, Пароль: *adminNaPopravku* 
> - Нажать кнопку "+ Upload File"
> - Нажать на кнопку ❌ напротив любого файла 
> - Браузер отображает ошибку "Не удается получить доступ к сайту" либо "503 Forbidden"
> - Файл не удалён и отображается в списке загруженных



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
> [Не удается получить доступ к сайту](../attachments/2.d.1_actual1.png)\


# [🔙](../solutions/solution_2.md)