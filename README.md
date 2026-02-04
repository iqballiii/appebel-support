# Appebel Support Page

Simple support/feedback page for Appebel mobile application.

## 🌐 Live Website

Visit: [https://YOUR-USERNAME.github.io/appebel-support](https://YOUR-USERNAME.github.io/appebel-support)

## 📁 Files

- `index.html` - Support/feedback form page
- `thankyou.html` - Thank you page after submission
- `README.md` - This file
- `.gitignore` - Git ignore rules

## 🚀 Deploy to GitHub Pages

1. Create new repository: `appebel-support`
2. Upload all files
3. Go to Settings → Pages
4. Select `main` branch
5. Save!

Your page will be live at:
```
https://YOUR-USERNAME.github.io/appebel-support/
```

## 🔌 Connect Your API

1. Open `index.html`
2. Find the `API_CONFIG` section (around line 115)
3. Update with your backend API:

```javascript
const API_CONFIG = {
    endpoint: 'https://your-backend-api.com/api/support',
    enabled: true  // Change to true
};
```

## 📤 API Data Format

Your backend will receive this JSON:

```json
{
    "name": "User Name",
    "email": "user@example.com",
    "feedback": "User's message here",
    "timestamp": "2026-02-04T10:30:00.000Z"
}
```

## 📱 For App Store/Play Store

Use this as your support URL:
```
https://YOUR-USERNAME.github.io/appebel-support/
```

## 🧪 Testing

Currently in **TEST MODE**:
- Form submissions are logged to browser console
- Open browser DevTools (F12) to see the logged data
- Change `enabled: true` to connect real API

## ✅ Form Validation

The form includes comprehensive validation:

**Name Field:**
- Minimum 2 characters
- Maximum 100 characters
- Only letters, spaces, hyphens, and apostrophes allowed

**Email Field:**
- Valid email format required (example@domain.com)
- Cannot be empty

**Message Field:**
- Minimum 10 characters
- Maximum 1000 characters

**Real-time Validation:**
- Errors appear when you leave a field (on blur)
- Green border shows valid input
- Red border shows invalid input
- Form cannot be submitted with invalid data

## 📧 Support

For questions, email: support@appebel.com

---

© 2026 Appebel. All rights reserved.
