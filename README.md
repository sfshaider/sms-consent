# 📱 SMS Consent Documentation

This repository contains SMS consent forms and documentation for Twilio compliance and A2P 10DLC registration.

## 🔗 Live Site

**GitHub Pages URL:** `https://[your-username].github.io/sms-consent`

## 📋 Files Included

- **`index.html`** - Main SMS consent form
- **`sms-terms.html`** - Complete SMS terms and conditions
- **`privacy.html`** - Privacy policy (optional)
- **`thank-you.html`** - Confirmation page after consent

## 🚀 Quick Setup

### 1. Create Repository
```bash
# Create new repository on GitHub named 'sms-consent'
# Clone to your local machine
git clone https://github.com/[your-username]/sms-consent.git
cd sms-consent
```

### 2. Add Files
```bash
# Copy all HTML files to the repository
# Commit and push
git add .
git commit -m "Add SMS consent forms and documentation"
git push origin main
```

### 3. Enable GitHub Pages
1. Go to repository **Settings**
2. Scroll to **Pages** section
3. Source: **Deploy from a branch**
4. Branch: **main** / **root**
5. Click **Save**

### 4. Access Your Site
- Your site will be available at: `https://[your-username].github.io/sms-consent`
- May take a few minutes to deploy

## 📝 Compliance Features

### ✅ Twilio Requirements Met
- **Clear opt-in language** with explicit consent
- **Frequency disclosure** (varies based on activity)
- **Opt-out instructions** (STOP/HELP keywords)
- **Message rate warnings** clearly stated
- **Company identification** throughout forms
- **Double opt-in flow** ready for implementation

### ✅ A2P 10DLC Ready
- **Documented consent process** for registration
- **Sample message content** examples
- **Clear use case description** (slot availability alerts)
- **Professional presentation** for carrier approval

## 🔧 Customization

### Update Company Information
Edit these placeholders in the HTML files:
- `[Your Company]` → Your business name
- `[Your Email]` → Your support email
- `[Your Business Address]` → Your business address

### Modify Consent Language
Update the consent text in `index.html` to match your specific use case:
```html
<label for="sms-consent">
    Yes, I consent to receive SMS notifications from [YOUR SERVICE]...
</label>
```

### Add Your Styling
- Customize CSS in the `<style>` sections
- Add your brand colors and fonts
- Include your logo images

## 📊 Data Collection

The form collects:
- **Name** (required)
- **Email** (required) 
- **Phone Number** (required)
- **SMS Consent** (checkbox)
- **Timestamp** (automatic)
- **IP Address** (for audit trail)

### Integration with Backend
Replace the JavaScript form handler with your actual API:
```javascript
// Replace this simulation with real API call
fetch('/api/consent', {
    method: 'POST',
    headers: { 'Content-Type': 'application/json' },
    body: JSON.stringify(formData)
});
```

## 🔒 Privacy & Security

- **HTTPS enforced** via GitHub Pages
- **No data stored** in this static site
- **Frontend validation** prevents empty submissions
- **Privacy policy** link included
- **Clear data usage** statements

## 📱 Mobile Responsive

- **Mobile-first design** optimized for all devices
- **Touch-friendly** form controls
- **Readable fonts** and spacing
- **Fast loading** static files

## 🎯 Twilio Integration Ready

This documentation supports:
- **A2P 10DLC registration** with carrier approval
- **Trust Hub verification** for business profiles
- **Compliance audits** with proper consent records
- **TCPA compliance** with explicit opt-in

## 📞 Support

For questions about this consent system:
- **File an issue** in this repository
- **Review Twilio docs**: [A2P 10DLC Registration](https://www.twilio.com/docs/sms/a2p-10dlc)
- **Check compliance**: [Twilio Messaging Policy](https://www.twilio.com/legal/messaging-policy)

## 🚨 Important Notes

### Before Going Live:
1. **Update all placeholder text** with your actual information
2. **Add real backend integration** to store consent data
3. **Test the complete flow** including SMS delivery
4. **Register with Twilio** A2P 10DLC using this documentation
5. **Verify carrier approval** before sending promotional messages

### Legal Disclaimer:
This is a template for SMS consent collection. Consult with legal counsel to ensure compliance with:
- **TCPA** (Telephone Consumer Protection Act)
- **CAN-SPAM Act**
- **State and local** telecommunications laws
- **Your specific industry** regulations

---

## 🎉 Ready to Deploy!

Your SMS consent documentation is now ready for:
- ✅ **GitHub Pages hosting**
- ✅ **Twilio A2P 10DLC submission**
- ✅ **Professional compliance presentation**
- ✅ **Integration with your slot monitoring app**

**Next Steps:** Enable GitHub Pages and share the URL with Twilio for your A2P 10DLC registration!