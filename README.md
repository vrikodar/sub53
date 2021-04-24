![Capture](https://github.com/SxNade/sub53/blob/main/sub53.png)


**sub53 is a Lightening Fast multi-threaded subdomain hunter that uses  CA certificates to Hunt Down subdomains**

***Now sub53 can also filter the alive subdomains from all the information gathered***

# Running sub53

        $ sudo apt install git
        $ git clone https://github.com/SxNade/sub53
        $ cd sub53
        $ chmod +x sub53
        
        $ ./sub53 <domain1> <domain2>..................<domainN>

![Capture](https://github.com/SxNade/sub53/blob/main/sub53.gif)
    
**sub53 also saves the discovered subdomains to a text file for later use**

![Capture](https://github.com/SxNade/SxNade.github.io/blob/main/sub53fl.gif)

# Filtering
                Once Finished with finding subdomains, sub53 prompts the user for filtering the discovered subdomains
                accordingly with the user action sub53 goes ahead and performs multithreaded filtering of the data.
                This not only makes it Fast But also more reliable.
# Install

*sub53 depends on curl , install curl on your system

                $ sudo apt install curl

