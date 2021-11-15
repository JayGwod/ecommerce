# E-commerce V2

## Pytest

```bash
pytest -m "not selenium" -rP
```

## PowerShell - Prepare fixtures

```powershell
$topicsjson = import-csv .\db_product_inventory.csv | ConvertTo-Json
$topicsjson | Add-Content -Path "mydata.json"
```
