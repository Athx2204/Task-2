# 🛡️ Phishing Email Analysis Report

## 📄 Sample Email Summary  
**Subject**: ⚠️ Immediate Action Required: Account Access Limited  
**Sender**: service@paypal-security.com  
**Link**: http://paypal-security-update-login.com/verify

---

## 🔍 Identified Phishing Indicators

| Indicator                          | Observed | Description |
|-----------------------------------|----------|-------------|
| Spoofed sender                    | ✅       | Domain `paypal-security.com` is not officially owned by PayPal. |
| Suspicious link                   | ✅       | Redirects to a fake login page mimicking PayPal. |
| Urgent/threatening language       | ✅       | Email creates panic by claiming account access is limited. |
| Grammar/spelling issues           | ✅       | Example: "Your account are under risk" indicates poor grammar. |
| Hover link mismatch               | ✅       | Visible link is disguised; actual redirect points to phishing site. |
| Header discrepancies              | ✅       | Using **Google Admin Toolbox**, SPF and DKIM authentication failed. |

---

## ✅ Conclusion

This email exhibits clear phishing characteristics including a **spoofed sender domain**, **urgent call to action**, and a **fake login page**. Header analysis using Google Admin Toolbox confirms **authentication failures**, making this a **high-risk phishing attempt**.

---

## 🔧 Tools Used

- [Google Admin Toolbox Messageheader](https://toolbox.googleapps.com/apps/messageheader/)  
- Manual inspection using Google and text editor

---

## 👨‍💻 Created by

Atharva Kavale  
Cybersecurity Intern at Elevate Labs
