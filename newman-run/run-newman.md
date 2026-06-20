# Newman Test Execution

## Basic Test Run
Execute the Postman collection with test data:

```bash
newman run dojo_products.postman.json -d data.csv
```

## Test Run with HTML Report
Execute the collection and generate an HTML report:

```bash
newman run dojo_products.postman.json -d data.csv -r htmlextra
```

### Flags
- `-d data.csv` - Load test data from CSV file
- `-r htmlextra` - Generate detailed HTML report