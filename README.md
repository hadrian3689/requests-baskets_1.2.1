# CVE-2023-27163 SSRF for Requests Baskets 1.2.1
This repository contains a Proof-of-Concept for CVE-2023-27163, a Server-Side Request Forgery (SSRF) vulnerability discovered in request-baskets up to version 1.2.1.

## Getting Started

### Executing program

* SSRF Execution 
```
python3 exploit.py -u 'http://requests.basket/' -w wordlist.txt -s 'http://localhost/'
```

## Help

For Help Menu
```
python3 exploit.py -h
```

## Acknowledgments

Backstory and Inspiration
* [Original Post](https://notes.sjtu.edu.cn/s/MUUhEymt7#)

## Disclaimer
All the code provided on this repository is for educational/research purposes only. Any actions and/or activities related to the material contained within this repository is solely your responsibility. The misuse of the code in this repository can result in criminal charges brought against the persons in question. Author will not be held responsible in the event any criminal charges be brought against any individuals misusing the code in this repository to break the law.