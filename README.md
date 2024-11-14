## NODEPAY NETWORK PYTHON VERSION

![nodepay](assets/image.png)

A Nodepay Network Extension Node bot is a tool designed to automate interactions with the Nodepay network using WebSocket connections. It enables real-time, two-way communication, allowing the bot to send transactions, monitor network status, and provide instant notifications. This bot can streamline tasks such as processing payments, tracking transaction status, and detecting anomalies, all while enhancing efficiency and responsiveness within the decentralized network.

---

### PREREQUISITE

1. Nodepay Account [Register](https://app.nodepay.ai/register?ref=fkCYv2psxv9YkrM)

2. Proxies Static Residental

3. VPS (Optional) and Python3

### SETUP & CONFIGURE BOT

- Open [Nodepay](https://app.nodepay.ai/register?ref=fkCYv2psxv9YkrM) and login to dashboard

- Press F12 or CTRL + SHIFT + I

- Select Console

- At the console, type ```allow pasting``` and press enter

- Then type
  ```bash
  localStorage.getItem('np_token')
  ```

- The text that appears is your nodepay token and copy the text

---

### INSTALLATION

Install Python For Windows: [Python](https://www.python.org/ftp/python/3.13.0/python-3.13.0-amd64.exe)

- For Unix:
  ```bash
  apt install python3 python3-pip -y
  ```

1. Clone project repository
   ```bash
   git clone http://github.com/Rambeboy/Nodepay-Network.git && cd Nodepay-Network
   ```

2. Install dependencies
   ```bash
   pip install -r requirements.txt
   ```

---

### CONFIGURATION

Before running the bot, you need to set up your configuration:

1. `data.txt` **(Required)**

- Create a `data.txt` file in the root of your project and paste your token in the file (one token per line).

  **Example `data.txt`:**

  ```bash
  ey...
  ey...
  ey...
  ```

2. `proxies.txt` **(Optional)**

- Add your proxy details in `proxies.txt`. Each line should have the format:
  ```bash
  http://username:password@hostname:port
  ```

  **Example `proxies.txt`**

  ```bash
  http://username:password@123.45.67.89:8080
  socks5://username:password@123.45.67.89:8080
  ```

3. Start the Bot

---

### RUN BOT

1. Run
   ```bash
   python main.py
   ```
   or
   ```bash
   python main-multi.py
   ```

3. Press Enter then insert your nodepay token

4. Select the menu you want to use:

- **Auto-Fetch Proxies**
- **Load From Proxies**

---

### OPERATING STATUS

If the following log appears, it means it is running successfully.
```bash
2024-07-30 04:37:18.263 | INFO     | __main__:ping:110 - Ping successful: {'success': True, 'code': 0, 'msg': 'Success', 'data': {'ip_score': 88}}
2024-07-30 04:37:48.621 | INFO     | __main__:ping:110 - Ping successful: {'success': True, 'code': 0, 'msg': 'Success', 'data': {'ip_score': 90}}
2024-07-30 04:38:18.968 | INFO     | __main__:ping:110 - Ping successful: {'success': True, 'code': 0, 'msg': 'Success', 'data': {'ip_score': 94}}
2024-07-30 04:38:59.338 | INFO     | __main__:ping:110 - Ping successful: {'success': True, 'code': 0, 'msg': 'Success', 'data': {'ip_score': 98}}
```

---

### NOTE

- One account only can connect with 10 Proxies
- You can just run this bot at your own risk, I'm not responsible for any loss or damage caused by this bot. This bot is for educational purposes only.

---

### LICENSE

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

---
