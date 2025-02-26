# **Certificate Verification Plugin**  
**Contributors:** Anand-Bora-0001  
**Donate link:** **UPI: anandbora241@oksbi**  
**Tags:** certificate, verification, course, authentication, education  
**Requires at least:** 4.0  
**Tested up to:** 4.8  
**Stable tag:** trunk  
**Requires PHP:** 5.4  
**License:** GPLv2 or later  
**License URI:** [GNU GPL v2](https://www.gnu.org/licenses/gpl-2.0.html)  

---

### **🙏 Support This Project (Donate ₹1)**  
If you find this plugin useful, consider donating just **₹1** via **UPI** to support its development:  

📌 **UPI ID:** `anandbora241@oksbi`  

Your contribution helps in improving and maintaining this plugin. **Thank you for your support!**  

---

## **📌 Description**  

The **Certificate Verification Plugin** is a simple yet powerful WordPress plugin that allows administrators to manage course certificate data and enables users to verify certificates using a **unique certificate code**.  

It is designed for **educational institutions, training centers, and online courses** to provide a seamless certificate verification experience.  

---

## **🔹 Key Features**  

✅ **Admin Panel for Certificate Management** – Easily add, edit, or delete certificate details.  
✅ **Search & Verification System** – Users can enter their **certificate code** to verify authenticity.  
✅ **Search by Multiple Parameters** – Search using:  
   - **Certificate Code**  
   - **Student Name**  
   - **Course Name**  
   - **Course Duration**  
   - **Award Date**  
✅ **Shortcode Integration** – Add a search form anywhere using `[get_certificate_search_form]`.  
✅ **User-Friendly Interface** – Simple, responsive design for both admin and users.  
✅ **Secure & Reliable** – Prevents duplicate entries and ensures data integrity.  
✅ **CSV Upload (Bulk Certificate Management)** – Easily upload multiple certificates at once.  
✅ **Fast & Lightweight** – Optimized for performance.  

---

## **🛠️ Installation Guide**  

### **Method 1: Install via WordPress Admin Panel**  
1. **Download & Upload:**  
   - Download the plugin from GitHub or WordPress.  
   - Navigate to **Plugins → Add New → Upload Plugin**.  
   - Upload `Anand-Bora-0001-course-certificate-verification.zip`.  

2. **Activate the Plugin:**  
   - Go to **Plugins** in the WordPress dashboard.  
   - Click **Activate** next to the plugin.  

3. **Add Certificate Data:**  
   - Navigate to the **Certificate Codes** menu.  
   - Enter certificate details such as **student name, course name, certificate code, duration, and award date**.  

4. **Embed the Search Form:**  
   - Copy and paste the shortcode:  
     ```  
     [get_certificate_search_form]  
     ```  
   - Place it on any **page, post, or widget** where users will search for certificates.  

5. **Test Certificate Verification:**  
   - Go to the page where you added the search form.  
   - Enter a certificate code and hit **Search** to verify.  

---

## **🔍 How the Search Feature Works**  

The search system allows users to find certificates based on multiple filters:  

| **Search Parameter**  | **Example Input**      |  
|----------------------|----------------------|  
| Certificate Code    | `CERT12345`         |  
| Student Name       | `John Doe`          |  
| Course Name       | `Python Basics`     |  
| Course Duration   | `3 Months`          |  
| Award Date       | `2025-01-15`        |  

- Users enter any **valid information** in the search bar.  
- The plugin fetches the corresponding **certificate details** from the database.  
- If the certificate exists, it will display the **verified details**.  
- If no match is found, it shows a **“Certificate Not Found”** message.  

---

## **🆕 Changelog**  

### **v1.0.0** (Initial Release)  
- Certificate data entry and storage.  
- Search feature with **multiple parameters**.  
- Shortcode for embedding the search form.  

---

## **⚠️ Upgrade Notice**  

For any issues or feature requests, **contact us at**:  
📧 **Email:** hello@Anand-Bora-0001.com  
