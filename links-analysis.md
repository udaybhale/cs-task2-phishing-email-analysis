
# 🔗 Detailed URL Analysis: Phishing Email Sample

## Suspicious URL Found in Email
**Displayed URL in Email:**
```
https://paypal-verification.secure-update-login.com
```

## 1. **Visual Deception**
- **Looks like**: a PayPal verification link.
- **Actually is**: a subdomain of `secure-update-login.com`, **not owned by PayPal**.
- The domain is carefully crafted to **appear legitimate** (using terms like "paypal", "secure", "login", "verification").

## 2. **Actual Domain Breakdown**
| Part | Value |
|------|-------|
| Protocol | `https` |
| Subdomain | `paypal-verification` |
| Domain | `secure-update-login` |
| TLD | `.com` |

> The real registered domain is: **secure-update-login.com**  
> **PayPal's official domain** is: **paypal.com**

## 3. **Techniques Used by Attackers**
- **Typosquatting**: Using common words associated with PayPal to build trust.
- **Subdomain spoofing**: Putting "paypal" in the subdomain to trick users.
- **Secure connection (HTTPS)**: Makes users trust the site even though it is malicious.

## 4. **DNS & WHOIS Lookup** _(Simulated)_
- Domain: `secure-update-login.com`
- Registrar: Unknown / Privacy Protected
- Creation Date: Recently registered (possible red flag)
- Hosting: Anonymous IP address or country with lax cybercrime enforcement

## 5. **Why This is Dangerous**
- Users are tricked into thinking it's a real PayPal link.
- On clicking, they may be led to a **fake login page** that harvests credentials.
- Some pages may also serve **malware** or **track user input**.

## ✅ Recommendation
- Never trust links just by appearance. Always check the **real domain**.
- Use browser tools or services like:
  - [https://www.virustotal.com/](https://www.virustotal.com/)
  - [https://urlscan.io/](https://urlscan.io/)
  - [https://whois.domaintools.com/](https://whois.domaintools.com/)

---

> 🚨 Always hover over a link before clicking. If the root domain doesn’t match the official source (like `paypal.com`), **don’t click it**.
