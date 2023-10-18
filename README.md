# myip
myip is a simple command-line tool that retrieves your public IP address along with additional location and ISP information. It's a convenient way to quickly check your IP information directly from the terminal.

To use myip, simply run it in your terminal:

$ myip

This command will fetch and display your public IP address, city, region, and ISP name.

## Dependencies
myip relies on the following tools and libraries:

curl: Used to fetch your IP information from "ipinfo.io."
jq: Used to parse the JSON response and extract specific details.
