# PDF Notebook Generator

This Python script automatically generates a custom PDF notebook based on a list of topics and number of pages provided in a `topics.csv` file.

## Features
- Adds topic headers to each page.
- Draws ruled lines across the pages for writing.
- Adds a footer repeating the topic title.
- Supports multiple pages per topic.

## Requirements
- Python 3
- [fpdf](https://pypi.org/project/fpdf/)
- [pandas](https://pypi.org/project/pandas/)

Install dependencies with:
```bash
pip install fpdf pandas
```

## How to Use
1. Create a `topics.csv` file with two columns: `Topic` and `Pages`.
2. Run the script.
3. An `output.pdf` file will be generated with your custom notebook.

## Example of `topics.csv`
```csv
Topic,Pages
Math,3
History,2
Science,4
```

## License
This project is licensed under the MIT License.
