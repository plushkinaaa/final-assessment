# Alexandra Plyukhaeva final assessment

## Hello, thank you for checking my work!

## Checklist 
[Link to check list](https://docs.google.com/document/d/1qCK5OnOLGbhVihGZNepfqwMa4RNDuvCXGn8ZUx_ogSg/edit?usp=sharing)
## Please use the following instructions to see the result:

1. Upload the postman file `Plyukhaeva.postman_collection.json`
2. Run the collection

### More Checks
1. Upload csv file `Plyukhaeva.Test_data.csv`
2. Run the folder `Authorized requests/Positive checks`

## Comments

> I wanna pay attention that for my opinion for the `get word details` endpoint for queries in the `Authorized requests/Negative checks/status code 400` folder:
   > * get word details with extra space in the end of row
   > * get word details with digits only
   > * get word details with spaces only
   >
   > should be 400 status code, not 200. Because it's not described in the requirements and shouldn't be allowed.
