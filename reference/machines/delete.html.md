```
curl -i -X DELETE \\
    -H "Authorization: Bearer ${FLY\_API\_TOKEN}" -H "Content-Type: application/json" \\
    "http://${FLY\_API\_HOSTNAME}/v1/apps/my-awesome-machine-app/machines/0e286e4ef14867" 

```
**Status: 200**
```json
{
  "ok": true
}
```