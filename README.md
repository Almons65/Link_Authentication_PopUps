# IV Link Authenticator (Prototype)
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
   bash git clone [https://github.com/yourusername/project-name.git](https://github.com/yourusername/project-name.git)

2. install dependencies:
   bash pip install -r requirements.txt

3. start the API:
  bash uvicorn Link_algo:app --reload

## Future Improvements
* Implement real API integration.
* Refactor components for better performance.




