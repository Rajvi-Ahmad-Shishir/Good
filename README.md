Examples

    Make a search of subdomains and print the info in the screen:

findomain -t example.com

    Make a search of subdomains and export the data to a output file (the output file name in it case is example.com.txt):

findomain -t example.com -o

    Make a search of subdomains and export the data to a custom output file name:

findomain -t example.com -u example.txt

    Make a search of only resolvable subdomains:

findomain -t example.com -r

    Make a search of only resolvable subdomains, exporting the data to a custom output file.

findomain -t example.com -r -u example.txt

    Search subdomains from a list of domains passed using a file (you need to put a domain in every line into the file):

findomain -f file_with_domains.txt

    Search subdomains from a list of domains passed using a file (you need to put a domain in every line into the file) and save all the resolved domains into a custom file name:

findomain -f file_with_domains.txt -r -u multiple_domains.txt

    Query the Findomain database created with Subdomains Monitoring.

findomain -t example.com --query-database

    Query the Findomain database created with Subdomains Monitoring and save results to a custom filename.

findomain -t example.com --query-database -u subdomains.txt

    Import subdomains from several files and work with them in the Subdomains Monitoring process:

findomain --import-subdomains file1.txt file2.txt file3.txt -m -t example.com
