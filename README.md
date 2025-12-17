# XKCD Archive Downloader

### Overview
This is a Python-based utility designed to automate the retrieval of XKCD comic images directly from the official website. The program begins at the XKCD homepage, downloads the currently featured comic image, and then follows the “Previous Comic” link to continue collecting earlier comics.

This process repeats in a controlled loop until one of two conditions is met:
- the first XKCD comic is reached, or
- a predefined maximum download limit is exceeded.

The project demonstrates practical web scraping concepts, including HTTP requests, HTML parsing, link traversal, and file handling. It is well-suited as a learning project for developers seeking hands-on experience with automation, iterative scraping, and respectful, rule-based content downloading.
