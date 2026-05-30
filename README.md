# n8n Automated Lead Routing System for Ad Consultancy

An automated backend workflow built with n8n to streamline lead management for an advertising consultancy agency. This system eliminates manual data entry, decreases lead response time, and ensures high-intent leads are instantly routed.

---

## 📊 Business Impact & Results
* **Response Time:** Reduced lead routing time from several hours to **under 2 minutes** (instant).
* **Efficiency:** Initially, the admin had to check each incoming order one by one and manually filter which customers were premium and which were regular customers to adjust the packages that could be accessed by customers. With this system, the company can eliminate manual administrative work by automating the data entry flow..
* **Lead Automation:** Automatically captures and processes data right after form submission.

---

## 🛠️ Integrated Tools & Nodes
* **n8n Webhook Node (`Webhook - Form Pendaftaran`)** – Captures incoming lead registration data in real-time.
* **n8n Switch / If Node** – Evaluates and filters lead data based on pre-defined conditions or criteria.
* **Automated Actions** – Routes and updates the filtered data into the target destination system.

---

## 🚀 How to Use / Import This Workflow
1. Download the `n8n-automated-lead-routing.json` file from this repository.
2. Open your n8n instance.
3. Create a new workflow, click on the **three dots** on the top right corner, and select **Import from File**.
4. Upload the downloaded JSON file.
5. Configure your own credentials or webhooks for each node and activate the workflow.
