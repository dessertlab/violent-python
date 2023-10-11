# Violent Python Dataset

***violent-python*** is a manually curated dataset, where a sample contains a piece of Python code from an offensive software, and its corresponding description in natural language (plain English). We built the dataset using the popular book _"Violent Python"_ by T.J. O'Connor, which presents several examples of offensive programs using the Python language. Our dataset covers multiple areas of offensive security, including penetration testing (e.g., an automated exploit for an SMB vulnerability, a port scanner, an SSH botnet); forensic analysis (e.g., geo-locating individuals, recovering deleted items, inspecting the Windows registry, examining metadata in documents and images, and analyzing data from mobile and desktop applications); network traffic analysis (e.g., capturing packets and geo-locating IP addresses, identifying DDoS toolkits, discovering decoy scans, analyzing botnet traffic, foiling intrusion detection systems); OSINT and social engineering (e.g., anonymously browsing the web, working with developer APIs, scraping popular social media sites, creating a spear-phishing email). 

The dataset consists of __1,372__ samples and it is divided into three subsets, one including individual lines, one multi-line blocks and one functions. 


## Individual Lines

This subset contains __1,129__ pairs of _individual lines_ of Python code and their English descriptions.

## Multi-line Blocks

This subset contains __171__ pairs of _multi-line blocks_ of Python code and their English descriptions. Single lines in the same block are separated by the newline character (i.e., "\n").

## Functions

This subset contains __72__ pairs of complete, multi-line Python _functions_ and their English descriptions. Single lines in the same function are separated by the newline character (i.e., "\n").


