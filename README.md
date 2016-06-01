# adsquery

This tool let you query the ADS using a simple CLI.

## Installation
You'll need an API key from NASA ADS labs. Sign up for the newest version of ADS search at https://ui.adsabs.harvard.edu, visit account settings and generate a new API token. The official documentation is available at https://github.com/adsabs/adsabs-dev-api.

You can then install the tool through pip:
```
$ pip install adsquery
```

After that, you should be able to use it under the name `adsquery`:
```
$ adsquery --help
$ adsquery query --help
```

## Querying
To make a query to the ADS, try:
```
$ adsquery query [my-query]
```
The query can either be an ADS compatible query or a bashist one. For example:
```
$ adsquery query --first-author Einstein 1915
$ adsquery query ^Einstein 1915
```
will result in the same results (papers by Einstein in 1915).

## Getting
TODO

## Bib
TODO

# Features
- [x] query the ADS
- [x] interactively prompt the user
  - [x] show bibtex reference
  - [x] download pdf file
- [ ] oneliner to show the bibtex / download the pdf
- [ ] tested

## Bugs and suggestions
Feel free to fill in an issue if you have any problem or suggestion

## Thanks
Special thanks to andycasey for providing https://github.com/andycasey/ads and the ADS!

