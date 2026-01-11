# IV Link Authenticator (Prototype)
# Contributors
Adisorn Numpradit - System UI design

Singchayapon Kliengma - System UI design

Pasu Leelahajiva - Algorithm design and Implementation

Theepapon Khwanna - Algorithm design and Implementation

# ** This is a prototype and use for demonstration purposes only ** 
# Goal
This system designed to detect phishing attempts, scam websites, and malicious domains in real-time. By combining deep SSL analysis, domain age verification, and content scraping, it provides users with an immediate Risk Score and actionable safety recommendations.
# Key Features
- Real-Time URL Scanning: Instantly analyzes the active tab in your browser.
- 4-Tier Risk System:
    - Safe (0-30%): Verified SSL, established domain history.
    - Medium (31-70%): Young domains (<6 months) or suspicious redirects.
    - High (71-90%): Gambling keywords or known scam patterns detected.
    - DANGER (91-100%): Dead servers, blacklisted TLDs (e.g., .vip, .bet), or combined risk factors.

- Deep Algorithmic Analysis: Unlike simple blacklists, our backend algorithm actively probes the server for validity.
- Visual Feedback: Simple color-coded popup interface for non-technical users.
# ScreenShots
## Low Threat
<img width="1919" height="1079" alt="low threat" src="https://github.com/user-attachments/assets/8e0f8bff-113e-4ded-a61b-389e3c852357" />

## Medium Threat
<img width="1919" height="1079" alt="medium threat" src="https://github.com/user-attachments/assets/dc0025bc-0306-4aa5-8d17-09bced5b1ce3" />

## High Threat
<img width="1919" height="1037" alt="high threat" src="https://github.com/user-attachments/assets/893d8165-5a35-4dce-9371-bda0d8f7f023" />

## Danger Threat
<img width="1919" height="1079" alt="DANGER" src="https://github.com/user-attachments/assets/5e962dd1-5252-4d85-94b1-7a6279f65b88" />




# Limitations
Mocked Data: returns static JSON.
No Persistence: Refreshing the page resets the state.
UI: Styling is minimal/functional only.
# How to Run
Prerequisites:
- Node.js
- Python
- FastAPI

Steps:
1.  Clone the repository:
   bash git clone https://github.com/Almons65/IV_Link_Authenticator.git

3. install dependencies:
   bash pip install -r requirements.txt

4. start the API:
  bash uvicorn Link_algo:app --reload

## Future Improvements
* Implement real API integration.
* Refactor components for better performance.




