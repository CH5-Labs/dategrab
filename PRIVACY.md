# Privacy Policy for DateGrab – Web to Google Calendar

**Publisher:** CH5 Labs  
**Last updated:** November 18, 2026

## 1. Overview
DateGrab ("the Extension") is a browser extension developed by CH5 Labs to help users extract upcoming dates, times, and event links from webpages and create Google Calendar links. Your privacy is important to us, and this extension is built on a local-first principle: CH5 Labs operates no servers and receives none of your data.

## 2. Data Collection and Storage
* **No Personal Data Collected by CH5 Labs:** DateGrab does not collect, store, track, or transmit any personally identifiable information, browsing history, or usage analytics to CH5 Labs or any analytics service.
* **Local API Key Storage:** To use DateGrab, you provide your own Groq API key. This key is stored locally on your device using your browser's built-in `chrome.storage.local` API. It is never sent to CH5 Labs. It is sent only to Groq's API, as authentication for the requests you trigger.

## 3. How Webpage Data is Processed
* **User-Initiated Action Only:** DateGrab does not read or monitor webpages in the background. Opening the DateGrab popup does not read or send any page content. Text and links from the active tab are accessed only when you click the **Scan this page** button.
* **What is sent:** When you click **Scan this page**, the following is sent directly from your browser to Groq's API (`https://api.groq.com`) using your personal API key, solely to identify event dates and details:
  * the visible text of the active webpage (limited to a maximum length),
  * a list of links on the page (link text and URL path), and
  * today's date.
* **Sensitive pages:** Because page text is sent to a third-party AI service, please do not scan pages that contain private or sensitive information.
* **Google Calendar Links:** Clicking "+ Add to Google Calendar" opens a standard pre-filled Google Calendar template URL in a new tab. DateGrab does not request or receive access to your Google Calendar account.

## 4. Third-Party Services
Your use of the Groq API is governed by Groq's own terms and privacy policy. CH5 Labs has no control over, and assumes no responsibility for, Groq's data handling practices. Google Calendar is a service of Google and is subject to Google's terms and privacy policy.

## 5. Permissions
* **activeTab / scripting:** to read the text and links of the current tab when you click **Scan this page**.
* **storage:** to save your Groq API key locally in your browser.
* **Access to `api.groq.com`:** to send scan requests to Groq's API.

DateGrab does not load or execute remote code.

## 6. Changes to This Policy
CH5 Labs may update this Privacy Policy from time to time to reflect improvements to the extension or regulatory requirements. Any changes will be posted on this page with an updated revision date.

## 7. Contact
If you have any questions regarding this Privacy Policy or the DateGrab extension, please contact CH5 Labs at: **[add your email address or GitHub Issues link here]**
