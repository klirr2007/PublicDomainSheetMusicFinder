
# Public Domain Sheet Music Finder

## Introduction

PublicDomainSheetMusicFinder is a project designed to identify the works of notable 20th-century composers that might be in the public domain within the EU. The project leverages Wikipedia page views as a metric to filter relevant composers. Additionally, it incorporates an IMSLP parser to locate available links to scanned sheet music.

## Version 1.1 Updates

### New Features and Improvements

- **PublicDomainSheetMusicFinder.ipynb**: Code optimization and refactoring for improved performance and readability.
- **imslp_extract.ipynb**: Newly added notebook to parse all available scores for a selected composer from the IMSLP database.
- **llm_parse_local.ipynb**: Experimental notebook for parsing, summarizing, and answering questions about a selected composer based on their Wikipedia article. This notebook utilizes local running large language models provided in LM Studio. Tested with Mistral 7B and Llama 3 models and 8192 token input.

## Included Files

This repository includes two TSV files: `composers.tsv` and `composers_imslp.tsv`. These files contain full data dumps based on Wikipedia data for the year 2022. `composers.tsv` includes basic information about the composers, while `composers_imslp.tsv` includes additional IMSLP links where available.

This repository now includes the following notebooks alongside the original TSV files:
- `PublicDomainSheetMusicFinder.ipynb`
- `imslp_extract.ipynb` (New)
- `llm_parse_local.ipynb` (New)

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

Run the Jupyter Notebooks to start the project. Each notebook contains detailed comments and explanations for each part of the code.

## Contributing

If you want to contribute to this project, please fork the repository and use a feature branch. Pull requests are warmly welcome.

## License

The code in this project is licensed under the MIT license.
