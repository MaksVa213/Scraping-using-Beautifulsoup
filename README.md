## Golf Club Scraper

This Python script scrapes booking data for the Albertpark Golf Club and exports it to Excel files.

### Features

- Scrapes booking data for the next 5 days
- Extracts information such as tee time, slot, price, and available count
- Exports the scraped data to Excel files with each sheet representing a day

### Prerequisites

- Python 3.x
- Required libraries:    `requests`, `beautifulsoup4`, `pandas`, `datetime`, `logging`, `os`

### Installation

1. Clone the repository:

```bash
git clone https://github.com/MaksVa213/Scraping-using-Beautifulsoup.git
```

2. Navigate to the project directory:

```bash
cd Scraping-using-Beautifulsoup
```

3. Create a virtual environment (optional but recommended):

```bash
python -m venv env
source env/bin/activate  # On Windows, use `env\Scripts\activate`
```

4. Install the required libraries:

```bash
pip install -r requirements.txt
```

### Usage

1. Update the `base_url` variable in the script with the appropriate URL for the SandringHam Golf Club booking page.

2. Run the script:

```bash
python scraper.py
```

The script will scrape the booking data and export it to Excel files in the `SandringHam-Golfclub-data` directory.

### Logging

The script uses logging to record important events and errors. The log file is saved as `scraper.log` in the `SandringHam-Golfclub-Data` directory.

### Contributing

If you find any issues or have suggestions for improvements, feel free to create an issue or submit a pull request.

### License

This project is licensed under the [MIT License](LICENSE).
