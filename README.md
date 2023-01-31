# bruteSubdomains
Python script to bruteforce subdomains

    $ python3 bruteSubdomains.py [-d] [-f FILE] [DOMAIN]
    
    -d       To bruteforce with most common subdomains (20k)
    -f       File containing subdomains to test


##### Bruteforce 20k most common subdomains:
    $ python3 bruteSubdomains.py -d [DOMAIN]

##### Bruteforce based on a list of subdomains:
    $ python3 bruteSubdomains.py -f [FILE] [DOMAIN]
