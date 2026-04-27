# 🐛 BrowserStack & Adidas BugHunt 2026

Welcome to the BrowserStack & Adidas Developer Day BugHunt! 

As part of this exercise, you will act as a Quality Assurance engineer hunting for visual inconsistencies, functional failures, and accessibility blockers in a **web application**. We have planted few **bugs** in our staging environment [1]. Gather your team of 5, pick your tools, and start hunting! [1]

## 🌍 Environments

You will be working with two separate environments. Your task is to ensure the Staging environment matches the quality and functionality of the Production environment [2].

*   **Production Environment (Golden Copy):** [https://ecommbs-prod.vercel.app/](https://ecommbs-prod.vercel.app/)
*   **Staging Environment (Buggy "FashionStack"):** [https://ecommbs-stage.vercel.app/](https://ecommbs-stage.vercel.app/)

## 🛠 Tools at Your Disposal

To maximize your score, utilize the following BrowserStack tools during the hunt [1-3]:

1. **BrowserStack Test Management:** You will use this tool to log your defects, manage test cases, and leverage AI features [3].[https://www.browserstack.com/docs/test-management/overview/what-is-test-management](https://www.browserstack.com/docs/test-management/overview/what-is-test-management)
2.  **BrowserStack Testing Toolkit:** For identifying **Functional bugs** across different browsers and real devices [4, 5]. [https://www.browserstack.com/docs/testing-toolkit/get-started](https://www.browserstack.com/docs/testing-toolkit/get-started)]
3.  **BrowserStack Percy (Visual Scanner):** For identifying **Visual bugs**. You will use this to run URL-based scanning to compare the production URL against the staging clone URL (no automation setup required) [2]. [https://www.browserstack.com/docs/website-scanner/choose-scanner](https://www.browserstack.com/docs/website-scanner/choose-scanner)
4.  **BrowserStack Accessibility Toolkit:** Use the Web Accessibility Chrome extension scanner to catch **A11Y (Accessibility) bugs** [3].[https://www.browserstack.com/docs/accessibility/overview/introduction](https://www.browserstack.com/docs/accessibility/overview/introduction)

---

## 📸 How to Capture and Log Bugs

It is crucial that your team accurately documents every bug you find so that points can be awarded. You have two options for logging bugs:

### Option A: Using the BrowserStack Bug Capture Extension
Bug Capture is a browser extension that records your screen and automatically captures technical background data like clicks, keystrokes, network requests, script errors, and DOM mutations [1, 2]. 

1. **Trigger the Capture:** Use the Bug Capture browser extension to choose your recording mode. You can **"Record current tab"** or **"Record entire screen"** [7]. Alternatively, use the **Replay** feature to instantly watch and capture the last two minutes of your background activity [2].
2. **Annotate & Highlight:** Click **"Take a screenshot"** to capture the tab and use the toolbar to annotate it [8]. If recording a video, you can use **Markers** to pause the recording, add a note highlighting the specific issue, and create chapters for engineers to review [9]. 
3. **Add Context:** You can easily add your own voiceover or webcam input to explain the bug as it happens [2]. 
4. **Upload and Share:** Once you finish recording, a local version will appear for review [10]. Make sure you are signed in, select your team's workspace folder, and click **Upload** [10]. Share the link to the uploaded report in any file or email with Browserstack Team.


### Option B: Capturing Information in a Shared Document
If your team prefers a centralized spreadsheet or document [3], please ensure every entry includes:
1. **Bug ID & Title:** A short, descriptive name (e.g., "Dead Add to Bag Button").
2. **Category:** Functional, Visual, or Accessibility.
3. **Screenshot/Video Recording:** Take a manual screenshot of your BrowserStack session and paste it into the document. Ensure the bug is clearly visible.
4. **Reproduction Steps:** Provide clear, step-by-step instructions so our engineers can replicate the issue.
5. **Severity Guess:** (Easy, Moderate, Complex) - *Points will be awarded based on our official grading rubric!*

*Note: All final bug sheets must be submitted to the BrowserStack team via email at the end of the BugHunt session [3].*

---

## 📂 Additional Resources for the Exercise

To fully test the application, you will need to simulate real-world user behaviors. Please use the following resources provided for specific testing scenarios:

### 1. Image Scanning Asset (`Shirt.png`)
Some features on the web application require testing image upload and scanning logic. 
*   **Action:** Download the provided test asset: `Shirt.png` (A plain black t-shirt) [6]. 
*   **Testing Method:** Use BrowserStack's **Image Injection** feature to upload this specific image into the application's scanner to test data-handling logic and verify if the correct search results or product details are returned [7].

### 2. Product Requirements Document (PRD) Exercise
At **12:15 PM**, we will transition to the "Findings & Test Case Management" segment of the agenda [8]. 
*   **The Task:** Your team will use the PRD to generate set of test cases that can help you in identifying the bugs. 
*   **AI Generation:** You will input this PRD into BrowserStack Test Management's AI agent. You will then provide prompts to generate  test cases which can be executed to identify Bugs. 
*   **Preparation:** As you hunt, keep notes on *why* these bugs affect the user experience, as this will help you write a stronger PRD later.

---

## 💯 Scoring System

The team with the most points wins. Points are hidden and will be awarded at the end of the session based on the severity and complexity of the bug [1]:

*   🟢 **Easy:** 1 point
*   🟡 **Moderate:** 2 points
*   🔴 **Complex:** 3 points

Good luck, and happy hunting! 
