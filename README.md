# LLMs Scientometrics

This repository contains the code and data for the paper titled **"Analyzing Diversity in Healthcare LLM Research: A Scientometric Perspective"**. The study provides a comprehensive scientometric analysis of large language model (LLM) research in healthcare, focusing on diversity in terms of gender, geography, and funding sources.

## Table of Contents

- [Project Overview](#project-overview)
- [Repository Structure](#repository-structure)
- [Installation](#installation)
- [Usage](#usage)
- [Data](#data)
- [Results](#results)
- [Contributing](#contributing)
- [License](#license)
- [Contact](#contact)

## Project Overview

The deployment of large language models (LLMs) in healthcare has shown potential for improving clinical decision-making and patient outcomes. However, the underrepresentation of diverse groups in LLM research can perpetuate biases, leading to inequitable healthcare delivery. This project presents a scientometric analysis of LLM research in healthcare, using data from PubMed and Dimensions. The analysis highlights gender and geographic disparities and proposes strategies to enhance diversity and inclusivity in AI research.

## Repository Structure

```plaintext
├── .gitignore
├── 1. Global Health PMIDs Extraction.ipynb
├── 2. Data_extraction.ipynb
├── 3. Preprocessing.ipynb
├── 4. EDA.ipynb
├── List of economies.csv
└── README.md
```

- **1. Global Health PMIDs Extraction.ipynb**: Notebook for extracting PMIDs related to global health from PubMed.
- **2. Data_extraction.ipynb**: Notebook for extracting metadata from Dimensions using the extracted PMIDs.
- **3. Preprocessing.ipynb**: Notebook for preprocessing the extracted metadata, including gender identification and country classification.
- **4. EDA.ipynb**: Notebook for exploratory data analysis, including gender distributions, geographic distributions, funding source analysis, and journal diversity index.
- **List of economies.csv**: CSV file containing the list of economies for classification purposes.
- **README.md**: This README file.

## Installation

All the notebooks were created using google colab, so you can also try it there!

## Usage

1. **Global Health PMIDs Extraction**:
   - Open the `1. Global Health PMIDs Extraction.ipynb` notebook.
   - Run the notebook to extract PMIDs related to global health from PubMed.

2. **Data Extraction**:
   - Open the `2. Data_extraction.ipynb` notebook.
   - Run the notebook to extract metadata from Dimensions using the extracted PMIDs. For this step you'll need an API key of dimensions. Place your API key in a .env file!

3. **Preprocessing**:
   - Open the `3. Preprocessing.ipynb` notebook.
   - Run the notebook to preprocess the extracted metadata, including gender identification and country classification.

4. **Exploratory Data Analysis**:
   - Open the `4. EDA.ipynb` notebook.
   - Run the notebook to perform exploratory data analysis, including gender distributions, geographic distributions, funding source analysis, and journal diversity index.

## Data

The primary datasets used in this study were obtained from PubMed and Dimensions. The data includes metadata such as authors' affiliations, countries, funding sources, and publication details. The `List of economies.csv` file is used for classifying countries into high-income countries (HICs) and low- and middle-income countries (LMICs).

## Results

The results of the analysis highlight significant gender and geographic disparities in LLM research for healthcare. Key findings include:
- A predominance of male authors and contributions primarily from high-income countries (HICs).
- Geographic disparities with most research contributions coming from North America and Europe.
- Funding source analysis indicating potential biases in the distribution of research funds.

## Contributing

Contributions to this project are welcome. If you have any suggestions or improvements, please create a pull request or open an issue.

## License

This project is licensed under the MIT License. See the [LICENSE](LICENSE) file for more details.

## Contact

For any questions or inquiries, please contact the corresponding author:
- **David Restrepo**: davidres@mit.edu
