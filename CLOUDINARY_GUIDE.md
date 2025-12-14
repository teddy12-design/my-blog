# Cloudinary Credentials Guide

Use this guide to locate the three required environment variables for your Vercel deployment.

## 1. CLOUDINARY_CLOUD_NAME
**What it is:** The unique identifier for your Cloudinary account.  
**Where to find it:**  
1. Log in to your [Cloudinary Dashboard](https://console.cloudinary.com/console/).
2. Look for the "Product Environment Credentials" section at the top left.
3. Copy the value next to **"Cloud Name"**.

---

## 2. CLOUDINARY_API_KEY
**What it is:** The public key used to authenticate requests to the Cloudinary API.  
**Where to find it:**  
1. In the same "Product Environment Credentials" section on your Dashboard.
2. Copy the number next to **"API Key"**.

---

## 3. CLOUDINARY_API_SECRET
**What it is:** The private key used to sign your secure API requests. **Keep this secret!**  
**Where to find it:**  
1. In the same "Product Environment Credentials" section.
2. It is usually hidden by dots (`••••`).
3. Click the **Copy** icon (or the Eye icon) next to **"API Secret"** to copy it.

---

### How to Add to Vercel:
1. Go to your Vercel Project.
2. Click **Settings** > **Environment Variables**.
3. Add each variable listed above with its corresponding value from your Cloudinary dashboard.
