# Mobile-Application-Testing-of-Mahfil-App

# Mobile Application Testing: Mahfil App

## 📌 Project Overview
This project involves comprehensive quality assurance and functional testing of the **Mahfil App**, a specialized "halal" video streaming and social platform. The testing focused on the **User Authentication** module, ensuring a seamless and secure onboarding experience for users across various sign-up methods.

## 🛠 Testing Types Covered
Based on the documentation in `Mobile Application Testing (Mahfil_App_).xlsx`, the following testing methodologies were applied:

*   **Manual Testing**: All scenarios were executed manually to observe UI/UX behavior.
*   **Black Box Testing**: Testing focused on inputs and expected outputs without viewing the underlying code.
*   **Functional Testing**: Verified core features including Sign-In/Sign-Up via Apple, Google, Email, and Mobile Number.
*   **Positive & Negative Testing**: Validated successful user flows as well as error handling for invalid emails, duplicate accounts, and incorrect OTPs.
*   **Boundary Value Analysis (BVA)**: Tested character limits for input fields (e.g., Name field minimum 3 and maximum 50 characters).
*   **Compatibility Testing**: Verified authentication integration with third-party providers like Google and Apple.
*   **Smoke & Sanity Testing**: Performed initial checks to ensure the build was stable and specific logic (like the 120-second OTP resend timer) functioned correctly.

## 📱 Test Environment
Testing was conducted on physical hardware to ensure real-world accuracy:
*   **Device**: iPhone 8
*   **Operating System**: iOS (Latest supported version)
*   **Network**: Wi-Fi / 4G LTE
*   **App Version**: [Insert Version, e.g., v1.0.2]

## 📂 File Structure
*   **`Mobile Application Testing (Mahfil_App_).xlsx`**: Contains the full Test Case Suite and Bug Report.
    *   **Sheet 1 (Test Case)**: Includes Test ID, Description, Test Data, Expected vs. Actual Results, and Status.
    *   **Sheet 2 (Bug Report)**: Details any defects found during the execution phase.

## 🚀 Key Highlights from Test Suite
*   **Authentication Diversity**: Tested 4+ different methods of user entry.
*   **Robust Validation**: Extensive testing of the OTP (One-Time Password) system for both Email and Mobile routes.
*   **Error Messaging**: Confirmed that the system provides clear feedback when invalid data is entered.

---
*Tested with ❤️ by [Your Name]*
