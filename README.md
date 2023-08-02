# PublicDomainSheetMusicFinder

## Introduction

PublicDomainSheetMusicFinder is a project designed to identify the works of notable 20th-century composers that might be in the public domain within the EU. The project leverages Wikipedia page views as a metric to filter relevant composers. Additionally, it incorporates an IMSLP parser to locate available links to scanned sheet music.

## Included Files

This repository includes two TSV files: `composers.tsv` and `composers_imslp.tsv`. These files contain full data dumps based on Wikipedia data for the year 2022. `composers.tsv` includes basic information about the composers, while `composers_imslp.tsv` includes additional IMSLP links where available.

## Table of Contents

1. [Installation](#installation)
2. [Usage](#usage)
3. [Contributing](#contributing)
4. [License](#license)

## Installation

The project requires Python and Jupyter Notebook to run. Required Python packages are:
- requests
- BeautifulSoup
- pandas
- tqdm
- numpy

These packages can be installed with pip:


```
pip install requests beautifulsoup4 pandas tqdm numpy

```

## Usage

Run the Jupyter Notebook `PublicDomainSheetMusicFinder.ipynb` to start the project. The notebook contains detailed comments and explanations for each part of the code.

## Contributing

If you want to contribute to this project, please fork the repository and use a feature branch. Pull requests are warmly welcome.

## License

The code in this project is licensed under the MIT license.
