# Umer-Broken-Link

**Umer-KHANZADA** is a Python tool designed for identifying broken social media links on websites. It efficiently scans a given domain or subdomain for various social media links and checks their status codes to determine if they are broken or valid.

## Features

- Scans websites for social media links.
- Checks the status codes of social media links.
- Highlights the results with different colors for various status codes.
- Reports broken social media links specifically for platforms like Twitter (X.com), Facebook, LinkedIn, Instagram, GitHub, Reddit, Discord, and Pinterest.
- Provides clear output and easy-to-read results.

## Installation

To use the `UMER-Broken-Link` tool, follow these steps:

1. **Clone the Repository:**

     
       git clone https://github.com/umerkhanzada-xp/broken-link-finder.git

2. **Navigate to the Directory:**
   
      
       cd umer-broken-link

3. **Install Required Libraries:**

Install the necessary Python libraries using pip:  

    pip install requests
    pip install requests beautifulsoup4
    pip install pyfiglet
    pip install termcolor
    
## Usage

1. **Run the Script:**

Execute the Python script to start the scanning process:

   
     python3 broken.py

2. **Enter the Domain or Subdomain:**

When prompted, enter the domain or subdomain you want to scan. For example:

    
    Enter the domain or subdomain: https://example.com

3. **View the Results:**

The tool will display the status of social media links found on the provided domain. Links will be categorized as either "Not vulnerable," "Forbidden," or "Vulnerable" based on their status codes. Errors in accessing pages will also be reported.

## Example Output

    ```bash
    Visiting: https://www.example.com
    Social media links found on https://www.example.com:
    Not vulnerable: https://twitter.com/example (Status code: 200)
    Forbidden: https://x.com/example (Status code: 403)
    Not vulnerable: https://github.com/example (Status code: 200)
    Vulnerable! Broken social media link found: https://www.facebook.com/example (Status code: 404)

 
# umer-broken-link
