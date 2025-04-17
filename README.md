# Credential Harvesting with Social-Engineer Toolkit (SET) – Week 9 Mini Lab

This mini-lab demonstrates the use of the Social-Engineer Toolkit (SET) on Kali Linux to simulate a credential harvesting attack using a cloned website. It highlights the risks of social engineering and helps build awareness about how attackers may trick users into giving up sensitive information.

## 🧠 Lab Goals

- Run the Social-Engineer Toolkit (`setoolkit`) on a Kali VM.
- Clone a known website (Google) to simulate a phishing page.
- Set up a credential harvester to collect submitted login credentials.
- Understand the importance of being cautious with login prompts and URLs.

## 🔧 Tools Used

- **Kali Linux**
- **SET (Social-Engineer Toolkit)** – for creating phishing websites
- **Falkon Browser** – for accessing the fake page
- **hostname -I** – to retrieve the Kali machine's IP address

## 📌 Steps Overview

1. Run SET as root:
   sudo setoolkit

2. In the SET menu, select:
    1) Social-Engineering Attacks
    2) Website Attack Vectors
    3) Credential Harvester Attack Method
    4) Web Templates
  
3. Find POST back address:
   In another terminal use 'hostname -I' to return local IP address

4. Select 2) Google as website template

5. Open browser and enter IP address in step 3

6. Enter FAKE credentials and click "Sign In"

7. Return to terminal where SET is running and view captured credentials.

⚠️ Disclaimer:
For education purposes only!!!
