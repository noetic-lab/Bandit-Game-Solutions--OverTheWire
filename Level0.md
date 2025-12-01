
## 🎯 Level Goal: Log into the game using SSH

Alright, first step of Bandit: get in using **SSH**.  
If you’ve never used it before, SSH (Secure Shell) is basically a way to connect safely to another computer over the internet.

---

### 🔑 Connection Details
- **Host:** `bandit.labs.overthewire.org`  
- **Port:** `2220`  
- **Username:** `bandit0`  
- **Password:** `bandit0`  

---

### 🛠️ SSH Syntax
The general format looks like this:
<br>`ssh username@remote_host -p <port_number>`
<br>Think of the **port** like a door — it’s the entry point you use to get inside the system.

---

### 🚀 Example Command
Here’s exactly what you need to run for Level 0:
<br>`ssh bandit0@bandit.labs.overthewire.org -p 2220`
<br>Type the password when asked, and boom — you’re in.  
<br>Congrats, you’ve cleared your first level 🎉

---

### ⚡ Quick Tip from me
Don’t just copy-paste. Try to understand what each part of the command means — it’ll make the later levels way easier.
