# Объект RemovePassword

* `type` String - `password`.
* `origin` String (опционально) - когда предоставлено, информация аутентификации, связанная с происхождением( origin ), будет удалена только в том случае, если весь кэш будет очищен.
* `scheme` String (опционально) - схема аутентификации. Может быть `basic`, `digest`, `ntlm`, `negotiate`. Должна предоставляться, если удаление через `origin`.
* `realm` String (опционально) - область аутентификации. Должна предоставляться, если удаление через `origin`.
* `username` String (опционально) - учетные данные аутентификации. Должны предоставляться, если удаление через `origin`.
* `password` String (опционально) - учетные данные аутентификации. Должны предоставляться, если удаление через `origin`.