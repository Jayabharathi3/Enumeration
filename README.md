# Enumeration
Enumeration Techniques

# Explore Google hacking and enumeration 

# AIM:

To use Google for gathering information and perform enumeration of targets

# STEPS:

### Step 1:

Install kali linux either in partition or virtual box or in live mode

### Step 2:

Investigate on the various Google hacking keywords and enumeration tools as follows:

### Step 3:
Open terminal and try execute some kali linux commands

# Pen Test Tools Categories:  

Following Categories of pen test tools are identified:
Information Gathering.

## Google Hacking:

Google hacking, also known as Google dorking, is a technique that involves using advanced operators to perform targeted searches on Google. These operators can be used to search for specific types of information, such as sensitive data that may have been inadvertently exposed on the web. Here are some advanced operators that can be used for Google hacking:


## **SITE**: 

This operator allows you to search for pages that are within a specific website or domain. For example, "site:example.com" would search for pages that are on the example.com domain.
Following searches for all the sites that is in the domain udemy.com

![image](https://github.com/Jayabharathi3/Enumeration/assets/120367796/d77c3f26-78ac-46c9-b13c-7b8eabc0a73a)



## **FILETYPE:**
This operator allows you to search for files of a specific type. For example, "filetype:pdf" would search for all PDF files.
Following searches for pdf file in the domain udemy.com

![image](https://github.com/Jayabharathi3/Enumeration/assets/120367796/27f05469-b1f2-45b6-b037-56c5a9598584)


## **INTEXT**: 
This operator allows you to search for pages that contain specific text within the body of the page. For example, "intext:password" would search for pages that contain the word "password" within the body of the page.

![image](https://github.com/Jayabharathi3/Enumeration/assets/120367796/57fc7d08-eeee-4455-8fff-89dafd0b9a7c)


## **INURL**:
This operator allows you to search for pages that contain specific text within the URL. For example, "inurl:admin" would search for pages that contain the word "admin" within the URL.

![image](https://github.com/Jayabharathi3/Enumeration/assets/120367796/94e18585-3bfb-4820-9d33-02af1bac82f1)


## **INTITLE**:
This operator allows you to search for pages that contain specific text within the title tag. For example, "intitle:index of" would search for pages that contain "index of" within the title tag.

![image](https://github.com/Jayabharathi3/Enumeration/assets/120367796/78fa26fe-b8b5-4483-9a79-fa79d287df1f)



## **LINK** :
This operator allows you to search for pages that link to a specific URL. For example, "link:example.com" would search for pages that link to the example.com domain.

![image](https://github.com/Jayabharathi3/Enumeration/assets/120367796/2f7f6dd9-7de3-4418-bc97-724b1670a79f)


## **CACHE**:
This operator allows you to view the cached version of a page. For example, "cache:example.com" would show the cached version of the example.com website.

![image](https://github.com/Jayabharathi3/Enumeration/assets/120367796/c100bd91-4222-474f-829e-e200e554bc61)


 
# DNS Enumeration


## **DNS Recon**

provides the ability to perform:
Check all NS records for zone transfers
Enumerate general DNS records for a given domain (MX, SOA, NS, A, AAAA, SPF , TXT)
Perform common SRV Record Enumeration
Top level domain expansion


![image](https://github.com/Jayabharathi3/Enumeration/assets/120367796/f8d0312e-bd24-4bc0-aad3-55d38fc8fc3e)



## **DNSENUM**

Dnsenum is a multithreaded perl script to enumerate DNS information of a domain and to discover non-contiguous ip blocks. The main purpose of Dnsenum is to gather as much information as possible about a domain. The program currently performs the following operations:

Get the host’s addresses (A record).
Get the namservers (threaded).
Get the MX record (threaded).
Perform axfr queries on nameservers and get BIND versions(threaded).
Get extra names and subdomains via google scraping (google query = “allinurl: -www site:domain”).
Brute force subdomains from file, can also perform recursion on subdomain that have NS records (all threaded).
Calculate C class domain network ranges and perform whois queries on them (threaded).
Perform reverse lookups on netranges (C class or/and whois netranges) (threaded).
Write to domain_ips.txt file ip-blocks.
This program is useful for pentesters, ethical hackers and forensics experts. It also can be used for security tests.

![image](https://github.com/Jayabharathi3/Enumeration/assets/120367796/5ae9e48f-b6fa-4099-9492-f31f40548058)




## **smtp-user-enum**

Username guessing tool primarily for use against the default Solaris SMTP service. Can use either EXPN, VRFY or RCPT TO.


In metasploit list all the usernames using head /etc/passwd or cat /etc/passwd:

select any username in the first column of the above file and check the same

![image](https://github.com/Jayabharathi3/Enumeration/assets/120367796/160e26b5-7c05-4ec7-82ff-1e22793aa678)

  
  

## **nmap –script smtp-enum-users.nse <hostname>**

The smtp-enum-users.nse script attempts to enumerate the users on a SMTP server by issuing the VRFY, EXPN or RCPT TO commands. The goal of this script is to discover all the user accounts in the remote system.

![image](https://github.com/Jayabharathi3/Enumeration/assets/120367796/4c37f4c5-96ae-409a-8f17-b19ff1bf4477)




## RESULT:
The Google hacking keywords and enumeration tools were identified and executed successfully

