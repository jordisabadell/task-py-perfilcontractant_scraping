# Scraping PCG to CSV files

Given a list of URLs of P.C.G web, it scrapes the content and save to CSV file. It needs a configuration JSON file.

## Arguments

| Parameter      | Type                        | Description                                                      | Required | Default value |
|----------------|-----------------------------|------------------------------------------------------------------|----------|---------------|
| --help (or -h) | Show help message and exit. |                                                                  |          |               |
| --inputfile    | String                      | Input file name with configuration (i.e: 'urls_to_scrape.json'). | True     |               |
| --outputfolder | String                      | Output folder name (i.e: 'c:/tmp/').                             | True     |               |

## Configuration JSON file

** urls_to_scrape_EMTPY.json **

```JSON
[
    {
        "url": "https://www.url-1.com",
        "file": "output-file-1.csv"
    },
    {
        "url": "https://www.url-2.com",
        "file": "output-file-2.csv"
    }
]
```
