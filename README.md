## Общее
* https://github.com/den11100/crm-api-call#readme
* Во всех запросах В header нужно передавать параметр `X-Api-Key` иначе будет ошибка `Bad Authorization` → 401

* msg - сообщение об ошибке


### Получить список офисов
`POST /api/v1/call-info/add-call-missed` → 200, 400, 401, 405

#### Ответы
##### success
code → 200
в теле ответа пусто


##### fail
code → 400, 401, 405
```json
{
    "msg": "Текст ошибки",   
}
```
