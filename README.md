# Web Scrapping Flight Data

This is a personal project to extract and compare flight prices from two different websites: [Decolar.com](https://www.decolar.com/) and [Passagens Promo](https://www.passagenspromo.com.br/). The objective is to be able to compare the prices between the two websites after extracting, transforming, and loading the data. The project is inspired by a real business need that I experienced and it aims to help me train my web scraping skills that I have studied for real-world projects.

## Project Description

The project consists of 3 main .ipynb files:

- [webScrappingFlightData.ipynb](https://github.com/Lacerdash/WebScrapping-Flight-Data/blob/master/webScrappingFlightData.ipynb): This file contains all the code documentation and explanations of how it works and the logic behind it
    - [webScrappingFunctions.ipynb](https://github.com/Lacerdash/WebScrapping-Flight-Data/blob/master/webScrappingFunctions.ipynb): This file contains all the functions used to generate the final result
    - [searchParametersGenerator.ipynb](https://github.com/Lacerdash/WebScrapping-Flight-Data/blob/master/searchParametersGenerator.ipynb): This file contains the function to randomly generated search parameters for the main scripts.

Additionally, the repository includes the following files:

- [Fligh Data.xlsx](https://github.com/Lacerdash/WebScrapping-Flight-Data/blob/master/Flight%20Data.xlsx): This file contains the final output data
- [Dim_iata.xlsx](https://github.com/Lacerdash/WebScrapping-Flight-Data/blob/master/Dim_iata.xlsx): This file contains a list of IATA codes for airports used by the .ipynb files
- [search_parameters.xlsx](https://github.com/Lacerdash/WebScrapping-Flight-Data/blob/master/search_parameters.xlsx): This file contains randomly generated search parameters for the .ipynb files

## Requirements

This project requires the following dependencies:

- Python 3
- Requests
- Beautiful Soup 4
- Pandas

## Usage

To run this project, follow these steps:

1. Clone the repository to your local machine:

    ```bash
    git clone https://github.com/Lacerdash/WebScrapping-Flight-Data.git
    ```

2. Navigate to the repository directory:

    ```bash
    cd WebScrapping-Flight-Data
    ```

3. Open the [`WebScrappingPassagens.ipynb`](https://github.com/Lacerdash/WebScrapping-Flight-Data/blob/master/WebScrappingPassagens.ipynb) file in a Jupyter notebook environment or your preferred IDE, and run the cells to execute the code.

4. The output files will be saved in the `output` directory.