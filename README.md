#Canadian sales tax in JSON.
This repository contains sales tax information for all the Canadian provinces and territories in JSON format.

##Example

```json
{
    "QC": {
        "name": "Quebec",
        "taxes": [
          {
              "code": "GST",
              "name": "Goods and Services Tax",
              "type": "federal",
              "tax": 0.05
          },
          {
              "code": "QST",
              "name": "Quebec Sales Tax",
              "type": "provincial",
              "tax": 0.09975
          },
        ],
    }
}
```

## How to contribute?
You can simply submit a pull request and I'll gladly review them and merge them if the changes are acceptable.
 - Indent using spaces with a tab width of 4 in the json5 source.
 - Make sure to rebuild the distribution version by executing grunt before submiting a pull request.

## Change log
See the [change log](https://github.com/wiredmax/canadian-sales-tax/blob/master/CHANGELOG.md).


## To do
 - [X] All the taxes rates of the provinces and territories of Canada.
 - [ ] More formats such as XML, YAML and CSV.

## Sources
http://www.canadabusiness.ca/eng/page/2651/

## License
See [LICENSE](https://github.com/wiredmax/canadian-sales-tax/blob/master/LICENSE).

*A Mari Usque Ad Mare*