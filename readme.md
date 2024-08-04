# Google Scraper

Google Scraper is a command-line tool for scraping Google search results. It supports various country and language codes, allowing for localized searches.

## Features

- Scrapes Google search results for a given term.
- Supports multiple country and language codes.
- Configurable number of pages and results per page.
- Proxy server support.
- Configurable backoff time to avoid bans.

## Installation

1. Clone the repository:
    ```sh
    git clone https://github.com/Golang-programming/GoogleScraper
    cd GoogleScraper
    ```

2. Install dependencies:
    ```sh
    go mod tidy
    ```

3. Build the application:
    ```sh
    go build -o GoogleScraper
    ```

## Usage

1. Run the application:
    ```sh
    ./GoogleScraper
    ```

2. Enter the required information when prompted:
    - Search term
    - Country code (e.g., `com`, `uk`)
    - Language code (e.g., `en`, `fr`)
    - Number of pages to scrape
    - Number of results per page
    - Backoff time in seconds

3. View the search results in the terminal.

Example input:
```sh
Enter search term: Go programming language
Enter country code: com
Enter language code: en
Enter number of pages to scrape: 2
Enter number of results per page: 10
Enter backoff time (seconds): 2
```

## License

This project is licensed under the MIT License.

## Contributing

Feel free to contribute by opening issues or submitting pull requests.

## Support

For support and feature, please open an issue on the [GitHub repository](https://github.com/Golang-programming/GoogleScraper/issues).
For questions, contact [your email](mailto:zeshanshakil0@gmail.com).

If you find this project useful, please star the repository and follow me on [GitHub](https://github.com/zeshantech).
