# HSyed.dev Professional Website

Professional business website for HSyed.dev software development services, designed to meet Twilio verification requirements for SMS compliance.

## 📁 Project Structure

```
website/
├── index.html              # Main homepage
├── sms-terms.html          # SMS Terms & Conditions
├── privacy-policy.html     # Privacy Policy
├── terms-of-service.html   # Terms of Service
└── README.md              # This file
```

## 🚀 Deployment to GitHub Pages

### Option 1: New Repository (Recommended)

1. **Create a new repository on GitHub:**
   - Go to https://github.com
   - Click "New Repository" 
   - Name: `hsyed-dev-website` (or similar)
   - Set to Public
   - Initialize with README

2. **Upload files:**
   - Click "uploading an existing file"
   - Drag and drop all HTML files from the `website/` folder
   - Commit changes

3. **Enable GitHub Pages:**
   - Go to repository Settings
   - Scroll to "Pages" section
   - Source: "Deploy from a branch"
   - Branch: `main`
   - Folder: `/ (root)`
   - Click Save

4. **Your live website will be at:**
   ```
   https://[your-username].github.io/hsyed-dev-website/
   ```

### Option 2: Update Existing Repository

If you want to use your existing `sms-consent` repository:

1. **Copy files to root:**
   ```bash
   cp website/*.html .
   ```

2. **Commit and push:**
   ```bash
   git add *.html
   git commit -m "Add professional HSyed.dev website"
   git push origin main
   ```

3. **Your website will be at:**
   ```
   https://[your-username].github.io/sms-consent/
   ```

## 🌐 Custom Domain Setup (Optional)

To use `hsyed.dev` domain:

1. **Add CNAME file:**
   ```bash
   echo "hsyed.dev" > CNAME
   git add CNAME
   git commit -m "Add custom domain"
   git push
   ```

2. **Configure DNS:**
   - Add CNAME record: `www.hsyed.dev` → `[username].github.io`
   - Add A records for apex domain to GitHub's IPs:
     - 185.199.108.153
     - 185.199.109.153
     - 185.199.110.153
     - 185.199.111.153

## 📋 Twilio Compliance Features

### Business Information
- ✅ Clear business name and contact information
- ✅ Professional service descriptions
- ✅ Legitimate business purpose

### SMS Compliance
- ✅ Comprehensive SMS Terms & Conditions
- ✅ Clear opt-in process description
- ✅ STOP/HELP keyword instructions
- ✅ Message frequency disclosure
- ✅ Data rate warnings
- ✅ Business name clearly reflected in opt-ins

### Legal Documentation
- ✅ Privacy Policy with SMS-specific sections
- ✅ Terms of Service covering SMS services
- ✅ Contact information prominently displayed
- ✅ TCPA and CTIA compliance statements

## 🔧 Customization

Before submitting to Twilio, customize the following:

### Contact Information
Replace placeholder information in all files:
- `contact@hsyed.dev` → Your actual email
- Business address (if applicable)
- Phone number (if applicable)
- Business registration details

### SMS Services
Update SMS terms to reflect your specific:
- Message types and frequency
- Opt-in processes
- Service descriptions
- Business use cases

### Branding
- Update colors in CSS to match your brand
- Add your logo (replace FontAwesome icons)
- Customize content to reflect your actual services

## 📱 For Twilio Verification

When submitting to Twilio, provide:

1. **Website URL:**
   ```
   https://[your-username].github.io/[repository-name]/
   ```

2. **SMS Terms URL:**
   ```
   https://[your-username].github.io/[repository-name]/sms-terms.html
   ```

3. **Privacy Policy URL:**
   ```
   https://[your-username].github.io/[repository-name]/privacy-policy.html
   ```

## ✅ Verification Checklist

Before submitting to Twilio:

- [ ] Website is live and accessible
- [ ] All pages load without errors
- [ ] Business information is clearly displayed
- [ ] SMS terms clearly reflect your business
- [ ] Contact information is accurate
- [ ] Opt-in process is clearly described
- [ ] STOP/HELP instructions are prominent
- [ ] Privacy policy covers SMS data handling
- [ ] Mobile responsive design works
- [ ] All links work correctly

## 🎨 Features

- **Responsive Design:** Works on all devices
- **Professional Appearance:** Clean, modern design
- **Fast Loading:** Minimal dependencies
- **SEO Optimized:** Proper meta tags and structure
- **Accessibility:** Screen reader friendly
- **Compliance Ready:** Meets legal requirements

## 🔧 Technical Details

- **Framework:** Pure HTML/CSS/JavaScript
- **Dependencies:** Font Awesome (CDN)
- **Hosting:** GitHub Pages compatible
- **SSL:** Automatic with GitHub Pages
- **Performance:** Optimized for fast loading

## 📞 Support

For questions about this website:
- Email: contact@hsyed.dev
- Website: www.hsyed.dev

---

**© 2024 HSyed.dev. Professional Software Development Services.** 