# MASVS-CODE-4

## Контроль
Приложение проверяет и сантитизирует весь ввод ненадежных данных.
The app validates and sanitizes all untrusted inputs.

## Описание

Apps have many data entry points including the UI, IPC, the network, the file system, etc. This incoming data might have been inadvertently modified by untrusted actors and may lead to bypass of critical security checks as well as classical injection attacks such as SQL injection, XSS or insecure deserialization. This control ensures that this data is treated as untrusted input and is properly verified and sanitized before it's used.

GPT: У приложений есть множество точек ввода данных, включая пользовательский интерфейс, межпроцессное взаимодействие, сеть, файловую систему и т.д. Эти входящие данные могут быть случайно изменены ненадежными лицами, что может привести к обходу критически важных проверок безопасности, а также классическим атакам инъекций, таким как SQL-инъекция, XSS или небезопасная десериализация. Этот контроль гарантирует, что эти данные рассматриваются как ненадежный ввод и должным образом проверяются и очищаются перед использованием.



Приложение имеет множество точек входа включая пользовательский интерфейс, IPC, сеть, файловая система и т.д. Эти входные данные могли быть неосторожно модифицированы недоверенными лицами и могут привести к обходу критических проверок безопасности с таким же успехом как классические атаки иньекций типа SQL иньекций, XSS или небезопасной десереализации.
Этот контроль обеспечивает что эти данные обращаются 




