
# Admin Login Finder

This is a Node.js script that attempts to find admin panel login pages on a website by checking a list of common admin panel paths.

## Features

- Uses `https` and `http` modules to make GET requests to potential admin panel paths.
- Checks if the response status code is 200, indicating the presence of an admin login page.
- Opens a specified URL (e.g., a Telegram link) in your default browser.

## Prerequisites

Make sure you have Node.js installed on your system. You can download it from [here](https://nodejs.org/).

## Usage

To run the script, follow these steps:

1. Open a terminal or command prompt.
2. Navigate to the folder containing the `login.js` script.
3. Run the following command:
   ```bash
   node login.js
   ```

4. Enter the website URL when prompted.
5. The script will check for common admin login paths and display the results.

## Example

```bash
Enter website url -> https://example.com
```

The script will display the results for each path it checks.
