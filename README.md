# fuzzyhttp

Fuzzyhttp is a bash script that will take a URL and output a the HTTP Header response for each HTTP response type.

# Compatibility 

This has only been successfully tested on Kali Linux. It does not output the data properly on Mac. 

# POC

To run the script, simply enter the following command:
`./fuzzyhttp`

It will then prompt you for the URL you would like to test and then output the results.

To include the DELETE command, use the `-d` flag. Example:
`./fuzzyhttp -d`
