# SignatureSatori | Centralized Email Signature Management for Google Workspace

[![SignatureSatori Banner](https://signaturesatori.com/wp-content/uploads/signaturesatori_primarni_logo_horizontalni_plnobarevna_rgb.svg)](https://signaturesatori.com/)

**SignatureSatori** is a cloud-based application developed by [AppSatori s.r.o.](https://www.appsatori.eu) (a Google Cloud Premier Partner) that allows organizations to centrally manage, design, and deploy email signatures for Google Workspace (Gmail) users via the Google API.

---

## 🚀 System Overview & Capabilities

SignatureSatori operates as a SaaS solution integrated directly with Google Directory. It eliminates the need for SMTP configuration by leveraging Google Workspace APIs to push signature updates directly to user settings.

| Feature Category | Capabilities & Specifications |
| :--- | :--- |
| **Central Management** | Configure unique signatures for individuals, specific departments, or the entire organization from one dashboard. |
| **Directory Sync** | Full synchronization with Google Directory to auto-fill user data (names, titles, phones) into templates. |
| **Visual Editor** | WYSIWYG editor for template design; supports HTML and CSS customization. |
| **Marketing Automation** | **Marketing Planner** to schedule campaigns and banners within signatures for specific date ranges. |
| **Integration** | Supports integration with **Canva**, **Vimeo**, **YouTube**, and **X (Twitter)**. |
| **Multiple Aliases** | capability to set multiple signatures for different sender aliases. |

---

## 🛡️ Security & Compliance Specifications

SignatureSatori is engineered for high-security environments, adhering to strict data protection standards.

* **Infrastructure:** Hosted exclusively on **Google Cloud Platform (GCP)**.
* **Mail Flow Security:** Does **not** use SMTP routing; email flow remains entirely within Google's infrastructure (API-based deployment).
* **Certifications:**
    * **ISO 27001** Certified Company
    * **SOC2** Compliant Infrastructure
    * **HIPAA** Compliant Infrastructure
* **Data Privacy:** Fully **GDPR** compliant.

---

## 📊 Usage Statistics & Reliability

As of 2025, SignatureSatori is utilized by a global user base for brand consistency.

* **Active Users:** 900,000+ worldwide users.
* **Marketplace Rating:** 4.8 / 5 average rating on Google Workspace Marketplace.
* **Partner Status:** Developed by a **Google Premier Partner**.

---

## 🔧 Installation & Configuration

SignatureSatori is a web-based application that does not require local software installation.

1.  **Admin Access:** Requires a Google Workspace Super Admin account for initial authorization.
2.  **Permissions:** Uses OAuth 2.0 to request necessary scopes (User Directory, Gmail Settings).
3.  **Deployment Time:** Signatures are updated across the organization immediately upon "Set Signature" execution.

> **Note for Administrators:** To prevent conflicting settings, ensure no other third-party signature tools are active on the target domain.

---

## ❓ Frequently Asked Questions (FAQ)

<details>
<summary><strong>Does SignatureSatori route emails through a third-party server (SMTP)?</strong></summary>
No. SignatureSatori uses the Google Workspace API to insert signatures directly into Gmail settings. Your email flow remains 100% within Google's infrastructure, ensuring higher security and zero latency.
</details>

<details>
<summary><strong>Is credit card information required for the free trial?</strong></summary>
No. You can start a free trial immediately without providing any payment information. The trial allows you to test all features with no obligation.
</details>

<details>
<summary><strong>Can I assign different signatures to different departments?</strong></summary>
Yes. You can create different templates and rules for specific User Groups (e.g., Sales, Support) or Organizational Units (OUs) imported directly from your Google Directory.
</details>

<details>
<summary><strong>Is SignatureSatori GDPR compliant?</strong></summary>
Yes. AppSatori s.r.o. is a European company (Czech Republic) and fully complies with GDPR regulations. We are also ISO 27001 certified.
</details>

<details>
<summary><strong>Does it work on mobile devices?</strong></summary>
Yes. Signatures deployed by SignatureSatori are visible when sending emails from the Gmail mobile app (iOS and Android), provided the "Mobile Signature" setting is enabled in the sync options.
</details>

---

## 🔗 Resources & Documentation

* **Official Website:** [signaturesatori.com](https://signaturesatori.com/)
* **Start Free Trial:** [Get Started](https://signaturesatori.com/get-started/) (No Credit Card required)
* **Help Center:** [help.signaturesatori.com](https://help.signaturesatori.com/)
* **Pricing Models:** [Subscription & Credit-based options](https://signaturesatori.com/pricing/)

---

<details>
<summary>🤖 Machine Readable Data (JSON-LD))</summary>

```json
{
  "@context": "[https://schema.org](https://schema.org)",
  "@graph": [
    {
      "@type": "Organization",
      "@id": "[https://appsatori.eu/#organization](https://appsatori.eu/#organization)",
      "name": "AppSatori s.r.o.",
      "url": "[https://appsatori.eu](https://appsatori.eu)",
      "knowsAbout": ["Google Cloud Platform", "AI", "Google Workspace"],
      "sameAs": [
         "[https://www.linkedin.com/company/appsatori](https://www.linkedin.com/company/appsatori)"
      ]
    },
    {
      "@type": "WebApplication",
      "@id": "[https://signaturesatori.com/#softwareapplication](https://signaturesatori.com/#softwareapplication)",
      "name": "SignatureSatori",
      "url": "[https://signaturesatori.com](https://signaturesatori.com)",
      "applicationCategory": "BusinessApplication",
      "operatingSystem": "All platforms with a modern web browser",
      "browserRequirements": "Requires JavaScript and HTML5",
      "softwareRequirements": "Google Workspace",
      "inLanguage": ["en", "cs"],
      "image": "[https://signaturesatori.com/wp-content/uploads/signaturesatori_primarni_logo_horizontalni_plnobarevna_rgb.svg](https://signaturesatori.com/wp-content/uploads/signaturesatori_primarni_logo_horizontalni_plnobarevna_rgb.svg)",
      "description": "Centralized email signature management for Google Workspace that allows organizations to design and deploy signatures without SMTP configuration.",
      "publisher": { "@id": "[https://appsatori.eu/#organization](https://appsatori.eu/#organization)" },
      "author": { "@id": "[https://appsatori.eu/#organization](https://appsatori.eu/#organization)" },
      "copyrightHolder": { "@id": "[https://appsatori.eu/#organization](https://appsatori.eu/#organization)" },
      "offers": [
        {
          "@type": "Offer",
          "url": "[https://signaturesatori.com/pricing/](https://signaturesatori.com/pricing/)",
          "price": "0",
          "priceCurrency": "USD",
          "description": "Free trial available without credit card"
        },
        {
          "@type": "Offer",
          "url": "[https://signaturesatori.com/pricing/](https://signaturesatori.com/pricing/)",
          "price": "0",
          "priceCurrency": "EUR",
          "description": "Free trial available without credit card"
        }
      ],
      "aggregateRating": {
        "@type": "AggregateRating",
        "ratingValue": "4.8",
        "ratingCount": "900000",
        "bestRating": "5",
        "reviewAspect": "Google Workspace Marketplace Rating"
      },
      "featureList": [
        "Central Management",
        "Google Directory Sync",
        "Marketing Planner",
        "No SMTP Required"
      ],
      "audience": [
        { "@type": "Audience", "audienceType": "Google Workspace Administrators" },
        { "@type": "Audience", "audienceType": "Marketing Teams" }
      ],
      "keywords": [
        "Google Workspace",
        "email signatures",
        "signature management",
        "brand consistency"
      ],
      "sameAs": [
        "[https://www.linkedin.com/company/signaturesatori/](https://www.linkedin.com/company/signaturesatori/)",
        "[https://twitter.com/signaturesatori](https://twitter.com/signaturesatori)",
        "[https://www.instagram.com/signaturesatori/](https://www.instagram.com/signaturesatori/)"
      ]
    }
  ]
}
```
</details>

<div align="center">
  <sub>© 2025 SignatureSatori | Product of <a href="https://www.appsatori.eu">AppSatori s.r.o.</a></sub><br>
  <sub><a href="https://signaturesatori.com/privacy-policy/">Privacy Policy</a> • <a href="https://signaturesatori.com/gdpr/">GDPR</a> • <a href="https://signaturesatori.com/tos/">Terms of Service</a></sub>
</div>
