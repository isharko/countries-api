# Countries Service
The countries service should expose the data to external services, and allow for the following:
- [ ] Retrieve country data based on a code
- [ ] Convert from one country code to another
- [ ] Retrieve country name in a particular language

| Code        |    Description    | Example |
| ----------- | :---------------: | ------: |
| alpha2      | ISO 2 Letter Code |      DE |
| alpha3      | ISO 3 Letter Code |     DEU |
| nationality | Nationality Code  |       D |
| name        |   Country Name    | Germany |

### Data
Data is located in `data/countries.json`, but may move to a DB.

### Use Cases:
- [ ] get an alpha3 based on alpha2
- [ ] get a country name based on alpha2
- [ ] get a nationality based on alpha3
- [ ] get a country name in Spanish