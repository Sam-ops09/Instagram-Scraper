# Instagram Scraper

This is a Python script that scrapes data from Instagram profiles using the Instagram API and saves the data to a CSV file.

## Table of Contents

- [Installation](#installation)
- [Usage](#usage)
- [Requirements](#requirements)
- [Contributing](#contributing)
- [License](#license)

## Installation

1. Clone this repository or download the source code.
   ```sh
   git clone https://github.com/Sam-ops09/Instagram-Scraper.git
   ```
2. Install the required packages using `pip`.
   ```sh
   pip install -r requirements.txt
   ```
3. Create a `.env` file in the project directory and add your Instagram API credentials.
   ```
   ACCESS_TOKEN=<your access token>
   ```
4. Run the script.
   ```sh
   python scraper.py
   ```

## Usage

1. Open the `scraper.py` file.
2. Replace the value of the `username` variable with the Instagram username you want to scrape.
3. Run the script using `python scraper.py`.

The script will fetch the following data:

- User ID
- Username
- Full name
- Profile picture URL
- Number of followers
- Number of followings
- Number of posts
- Bio
- Website URL

The data will be saved to a CSV file named `output.csv` in the project directory.

## Requirements

- Python 3.x
- requests
- python-dotenv

## Contributing

Contributions are always welcome! Please feel free to open an issue or submit a pull request.

## License

Distributed under the MIT License. See `LICENSE` for more information.
