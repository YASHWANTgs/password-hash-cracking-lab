# Password Cracking and Hash Analysis

This Project shows the basic fundamentals of password cracking which uses the common hash types like SHA-512 and MD5.

# Sample Hashes Used
- `SHA-512`- Linux file format (e.g. `$6$`)
- `MD5`- Example dynamic hash (e.g., `$dynamic_0$`)
- `SHA-1`: Classic one-way hash

---

# Tools & Commands
 **Tool**: John the Ripper
- **Wordlist**: rockyou.txt
- **Platform**: Kali Linux
- **Commands**:
  ```bash
  john --format=sha512crypt testhash.txt --wordlist=mylist.txt
  john hashes2.txt --wordlist=rockyou.txt
  john --format=raw-sha1 sha1.txt --wordlist=rockyou.txt

# MITRE ATT&CK Mapping
- T1110.002-Password Cracking: Demonstrates brute-force attacks against hash values to reveal laintext passwords.

# Learning Outcomes 
- Understood how hashing and cracking work
- Hands-on with John the Ripper
- Practical security awareness on password vulnerabilities

# Author 
-YASHWANT G S
