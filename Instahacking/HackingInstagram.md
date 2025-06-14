# Instagram Information & Brute-force Tool
```
HackInstagram
```
This Python script is designed to **gather detailed information** about an Instagram account and perform a simple **brute-force password attack** using a list of passwords provided in a `.txt` file.

---

## Features

- **Auto-detects system platform** (Windows, Linux, macOS)
- **Detects user location** using `ip-api`
- Shows a stylized banner with current **date and time**
- Fetches Instagram account details using `instaloader`, including:
  - Full name
  - User ID
  - Number of followers and followees
  - IGTV count, post count
  - Business category and external link
  - Account status (private, verified, business, etc.)
- Saves gathered info into both `.txt` and `.json` formats
- Supports optional redirection to the Instagram profile in a **web browser**

---

## Password Attack

- Uses a list of passwords from the file:  
  \`passkey.txt\`

- Attempts login through Instagram's endpoint:
  \`https://www.instagram.com/accounts/login/ajax/\`

- For each **password**, the script:
  - Sends an **authenticated POST request**
  - Waits for the response
  - If successful, it **saves the credentials**
  - If not, it continues to the next password

- Displays real-time feedback with:
  - `Trying password: ...`
  - `Login successful` or `Not correct password`

- After a successful login:
  - Account data is saved to:
    - \`<username>.txt\`
    - \`<username>.json\`
  - Additional account analysis is shown in a table

---

## Output Files

- `TXT File`: Contains basic credentials and bio  
- `JSON File`: Structured data for further use  
- Example file names:  
  - \`targetuser.txt\`  
  - \`targetuser.json\`

---

## Notes

- You can **cancel** the process anytime with `Ctrl + C`
- If no correct password is found, the script will notify:
  > `All passwords tested. No successful login!`

---

<div align="center">
<table>
  <tr>
    <td align="center">
      <a href="1.png" target="_blank">
        <img src="1.png" alt="" width="250"/>
      </a><br><sub></sub>
    </td>
    <td align="center">
      <a href="2.png" target="_blank">
        <img src="2.png" alt="" width="250"/>
      </a><br><sub></sub>
    </td>
  </tr>
  <tr>
    <td align="center">
      <a href="3.png" target="_blank">
        <img src="3.png" alt="" width="250"/>
      </a><br><sub></sub>
    </td>
    <td align="center">
      <a href="4.png" target="_blank">
        <img src="4.png" alt="" width="250"/>
      </a><br><sub></sub>
    </td>
  </tr>
</table>
</div>

---
### Compatibility and System Support

| Operating System | Logo | Supported |
|------------------|------|-----------|
| **Windows**      | ![Windows](https://custom-icon-badges.demolab.com/badge/Windows-0078D6?logo=windows11&logoColor=white) | ✅ |
| **Linux**        | ![Linux](https://img.shields.io/badge/Linux-FCC624?logo=linux&logoColor=black) | ✅ |
| **macOS**        | ![macOS](https://img.shields.io/badge/macOS-000000?logo=apple&logoColor=F0F0F0) | ✅ |
| **Android**      | ![Android](https://img.shields.io/badge/Android-3DDC84?logo=android&logoColor=white) | ✅ |

---
### **The price of the tool is**
- <img src="money.jpg" alt="money" width="100">

---


### ![Connect](https://img.shields.io/badge/Connect_whit_me-0056D2?style=for-the-badge&logo=links&logoColor=white)

- [![Instagram](https://img.shields.io/badge/Instagram-E4405F?logo=instagram&logoColor=white)](https://www.instagram.com/wsl.iq)
- [![Telegram](https://img.shields.io/badge/Telegram-2CA5E0?logo=telegram&logoColor=white)](https://t.me/wsl-iq)
- [![TikTok](https://img.shields.io/badge/TikTok-black?logo=tiktok&logoColor=white)](https://www.tiktok.com/@wsl.iq)

---
