# DevOps, Scripting & Hacking
# Attack is the best defense

## Description
What you should learn from this project:
- Network basics
- Docker

---

### [0. ARP spoofing and sniffing unencrypted traffic](./0-sniffing)
* 

### [1. Dictionary attack](./1-dictionary_attack)
* Password-based authentication systems can be easily broken by using a dictionary attack (you’ll have to find your own password dictionary). Let’s try it on an SSH account.
- Install Docker on your machine Ubuntu
- Pull and run the Docker image sylvainkalache/264-1 with the command docker run -p 2222:22 -d -ti sylvainkalache/264-1
- Find a password dictionary (you might need multiple of them)
- Install and use hydra to try to brute force the account sylvain via SSH on the Docker container
- Because the Docker container is running locally, hydra should access the SSH account via IP 127.0.0.1 and port 2222
- Hint: the password is 11 characters long

Once you found the password, share it in your answer file.

---

## Author
* **Nahashon Kuria** - [Nahashon-Kuria](https://github.com/Nahashon-Kuria)

End;

    @phantom-0308