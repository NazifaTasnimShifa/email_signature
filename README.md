<div align="center">

# ✉️ Professional Email Signature Template

### A Modern, Responsive HTML Email Signature with Social Media Integration

[![HTML5](https://img.shields.io/badge/HTML5-E34F26?style=for-the-badge&logo=html5&logoColor=white)](https://html.spec.whatwg.org/)
[![CSS3](https://img.shields.io/badge/CSS3-1572B6?style=for-the-badge&logo=css3&logoColor=white)](https://www.w3.org/Style/CSS/)
[![FontAwesome](https://img.shields.io/badge/Font_Awesome-339AF0?style=for-the-badge&logo=fontawesome&logoColor=white)](https://fontawesome.com/)
[![License](https://img.shields.io/badge/License-MIT-green.svg?style=for-the-badge)](LICENSE)

[Features](#-features) • [Preview](#-preview) • [Installation](#-installation) • [Customization](#-customization) • [Email Client Setup](#-email-client-setup) • [Author](#-author)

</div>

---

## 📖 About The Project

A **clean, professional, and modern email signature template** built with HTML and CSS. Perfect for students, professionals, and academics who want to make their emails stand out with a polished signature that includes social media links, contact information, and institutional branding.

This template features:
- 📱 Responsive design that works across all email clients
- 🎨 Clean and professional appearance
- 🔗 Integrated social media icons
- 📞 Contact information with FontAwesome icons
- 🏛️ University/Organization branding support

---

## ✨ Features

<table>
<tr>
<td width="50%">

### 🎯 Design Elements
- ✅ Professional layout
- ✅ Social media icon integration
- ✅ FontAwesome icons for contacts
- ✅ Custom branding support
- ✅ Clean typography
- ✅ Optimized for email clients

</td>
<td width="50%">

### 🔗 Included Links
- 📘 Facebook profile
- 📱 WhatsApp contact
- 🐦 Twitter handle
- 📸 Instagram profile
- 📧 Email address
- 📍 Physical address

</td>
</tr>
<tr>
<td width="50%">

### 💼 Information Display
- 👤 Name and title
- 🎓 Educational credentials
- 🏢 Institution details
- 📞 Phone number
- 📧 Email address
- 🗺️ Location

</td>
<td width="50%">

### 🛠️ Technical Features
- 📱 Responsive design
- 🌐 Cross-client compatibility
- ⚡ Lightweight code
- 🎨 Easy customization
- 🔧 No dependencies (except FA)
- 📦 Ready to use

</td>
</tr>
</table>

---

## 🖼️ Preview

<div align="center">

![Email Signature Preview](email_template.png)

*Professional email signature with social links and contact information*

</div>

---

## 🚀 Installation

### Prerequisites

- 📝 A text editor (VS Code, Sublime Text, Notepad++, etc.)
- 🌐 A web browser (for testing)
- 📧 An email client (Gmail, Outlook, Apple Mail, etc.)

### Quick Start

#### 1️⃣ Clone the Repository

```bash
# Clone the repository
git clone https://github.com/NazifaTasnimShifa/email_signature.git

# Navigate to the project folder
cd email_signature

# Or download ZIP from GitHub and extract
```

#### 2️⃣ Open and Test

```bash
# Open the HTML file in your browser
open index.html

# Or double-click index.html to open in default browser
```

#### 3️⃣ Customize (See [Customization](#-customization) section)

---

## 📁 Project Structure

```
email_signature/
├── 📄 index.html              # Main signature HTML
├── 📄 style.css               # Styling for the signature
├── 📄 README.md               # Project documentation
├── 🖼️ favicon.jpg             # Favicon
├── 🖼️ email_template.png      # Preview screenshot
│
└── 📂 images/                 # Social media and logo images
    ├── FB.jpg                 # Facebook icon
    ├── Whatsapp_LOGO.jpg      # WhatsApp icon
    ├── TWITTER_LOGO.jpg       # Twitter icon
    ├── Instagram.jpg          # Instagram icon
    └── RUET_logo.svg.png      # Institution logo
```

---

## 🎨 Customization

### Step 1: Update Personal Information

Open `index.html` and modify the following sections:

#### 📝 Name and Title

```html
<div class="Identity">
  <p><em><b>Your Name Here</em></b></p><br>
  <div class="cse_section">
    <p2><b><i>Your Title/Position</i></b></p2>
  </div>
</div>
```

#### 📞 Contact Information

```html
<div class="Information">
  <i class="fas fa-phone-alt"><em><b> &nbsp+1 234 567 8900</b></em></i><br>
  <i class="far fa-envelope">
    <a href="mailto:your.email@example.com">
      <em><b>&nbsp your.email@example.com</b></em>
    </a>
  </i><br>
  <i class="fas fa-map-marker-alt"><em><b> &nbspYour Address Here</b></em></i>
</div>
```

#### 🏢 Institution/Organization

```html
<div class="RUET">
  <p><em><b>Your Institution Name</b></em>
    <img src="your_logo.png" alt="Logo"></p>
</div>
```

### Step 2: Update Social Media Links

```html
<div class="data">           
  <pre>
    <a href="https://www.facebook.com/yourprofile" target="_blank">
      <img src="FB.jpg" alt="Facebook">
    </a>
    <a href="https://wa.me/1234567890" target="_blank">
      <img src="Whatsapp_LOGO.jpg" alt="WhatsApp">
    </a>
    <a href="https://twitter.com/yourhandle" target="_blank">
      <img src="TWITTER_LOGO.jpg" alt="Twitter">
    </a>
    <a href="https://www.instagram.com/yourhandle/" target="_blank">
      <img src="Instagram.jpg" alt="Instagram">
    </a>
  </pre>
</div>
```

### Step 3: Customize Colors and Styling

Edit `style.css` to match your brand:

```css
/* Example customizations */
.container {
  background-color: #f8f9fa; /* Change background */
  border: 2px solid #007bff; /* Add border */
  border-radius: 10px;        /* Rounded corners */
}

.Identity p {
  color: #333;                /* Name color */
  font-size: 20px;            /* Name size */
}

.Information a {
  color: #007bff;             /* Link color */
  text-decoration: none;      /* Remove underline */
}
```

### Step 4: Replace Images

Replace the following image files with your own:

- `FB.jpg` - Facebook icon (recommended: 32x32px)
- `Whatsapp_LOGO.jpg` - WhatsApp icon (recommended: 32x32px)
- `TWITTER_LOGO.jpg` - Twitter icon (recommended: 32x32px)
- `Instagram.jpg` - Instagram icon (recommended: 32x32px)
- `RUET_logo.svg.png` - Your institution/company logo
- `favicon.jpg` - Your favicon

---

## 📧 Email Client Setup

### Gmail

1. **Copy the HTML:**
   - Open `index.html` in a web browser
   - Press `Ctrl+A` (Select All)
   - Press `Ctrl+C` (Copy)

2. **Paste in Gmail:**
   - Go to Gmail Settings (⚙️) → See all settings
   - Scroll to "Signature" section
   - Click "Create new" signature
   - Paste the copied content (`Ctrl+V`)
   - Save changes

### Outlook (Desktop)

1. **Copy the HTML content**
2. Go to **File → Options → Mail → Signatures**
3. Click **New** to create a signature
4. Paste the HTML in the signature editor
5. Click **OK** to save

### Outlook (Web)

1. Go to **Settings (⚙️) → View all Outlook settings**
2. Navigate to **Mail → Compose and reply**
3. Under **Email signature**, paste your HTML
4. Click **Save**

### Apple Mail

1. Go to **Mail → Preferences → Signatures**
2. Click **+** to add a new signature
3. In Terminal, run:
   ```bash
   open ~/Library/Mail/V*/MailData/Signatures/
   ```
4. Replace the `.mailsignature` file with your HTML
5. Restart Mail

### Thunderbird

1. Go to **Tools → Account Settings**
2. Select your email account
3. Check **Attach the signature from a file**
4. Browse and select your `index.html` file
5. Check **Use HTML**
6. Click **OK**

---

## 🔧 Advanced Customization

### Adding More Social Icons

```html
<!-- LinkedIn -->
<a href="https://linkedin.com/in/yourprofile" target="_blank">
  <img src="linkedin_icon.jpg" alt="LinkedIn">
</a>

<!-- GitHub -->
<a href="https://github.com/yourusername" target="_blank">
  <img src="github_icon.jpg" alt="GitHub">
</a>
```

### Adding a Profile Picture

```html
<div class="profile-image">
  <img src="profile.jpg" alt="Profile Picture" 
       style="width: 80px; height: 80px; border-radius: 50%;">
</div>
```

### Adding a Website Link

```html
<i class="fas fa-globe">
  <a href="https://yourwebsite.com" target="_blank">
    <em><b>&nbsp yourwebsite.com</b></em>
  </a>
</i>
```

---

## 💡 Tips & Best Practices

### ✅ Do's

- ✔️ Keep it simple and professional
- ✔️ Use web-safe fonts
- ✔️ Optimize images (keep file size small)
- ✔️ Test across multiple email clients
- ✔️ Include only relevant information
- ✔️ Use clickable links for all contact methods

### ❌ Don'ts

- ❌ Don't use too many colors
- ❌ Avoid large images (increases email size)
- ❌ Don't use JavaScript (blocked by most clients)
- ❌ Avoid external CSS (use inline styles)
- ❌ Don't make it too long
- ❌ Avoid animated GIFs (can be distracting)

---

## 🛠️ Technology Stack

<div align="center">

| Technology | Purpose |
|------------|---------|
| ![HTML5](https://img.shields.io/badge/HTML5-E34F26?style=flat-square&logo=html5&logoColor=white) | Structure |
| ![CSS3](https://img.shields.io/badge/CSS3-1572B6?style=flat-square&logo=css3&logoColor=white) | Styling |
| ![FontAwesome](https://img.shields.io/badge/Font_Awesome-339AF0?style=flat-square&logo=fontawesome&logoColor=white) | Icons |

</div>

---

## 🐛 Troubleshooting

<details>
<summary><b>🔍 Click to expand troubleshooting guide</b></summary>

### Issue: Images not showing in email

**Solutions:**
- Use absolute URLs instead of relative paths
- Host images online (Imgur, GitHub, etc.)
- Ensure images are not blocked by email client
- Check image file extensions

### Issue: Formatting breaks in certain email clients

**Solutions:**
- Use inline CSS instead of external stylesheets
- Avoid `<div>` tags, use `<table>` for layout
- Test in multiple email clients
- Use email-safe fonts (Arial, Georgia, etc.)

### Issue: Links not clickable

**Solutions:**
- Ensure proper `href` attribute
- Use `target="_blank"` for external links
- Check for typos in URLs
- Verify anchor tags are properly closed

### Issue: Signature too large

**Solutions:**
- Compress images (use TinyPNG, ImageOptim)
- Remove unnecessary whitespace
- Minimize CSS
- Use fewer images

</details>

---

## 🌟 Features Roadmap

- [ ] Dark mode variant
- [ ] Multiple color themes
- [ ] QR code integration
- [ ] Animated hover effects
- [ ] Multiple layout options
- [ ] Signature generator tool
- [ ] Mobile-optimized version

---

## 🤝 Contributing

Contributions are welcome! Here's how you can help:

1. **Fork the repository**
2. **Create a feature branch**
   ```bash
   git checkout -b feature/AmazingFeature
   ```
3. **Commit your changes**
   ```bash
   git commit -m 'Add some AmazingFeature'
   ```
4. **Push to the branch**
   ```bash
   git push origin feature/AmazingFeature
   ```
5. **Open a Pull Request**

---

## 📝 License

Distributed under the MIT License. See `LICENSE` for more information.

---

## 👨‍💻 Author

<div align="center">

### **Nazifa Tasnim Shifa**

[![LinkedIn](https://img.shields.io/badge/LinkedIn-0077B5?style=for-the-badge&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/nazifa-tasnim-shifa)
[![GitHub](https://img.shields.io/badge/GitHub-100000?style=for-the-badge&logo=github&logoColor=white)](https://github.com/NazifaTasnimShifa)

**CSE'19, RUET | Software Developer | Web Enthusiast**

📍 Jashore, Bangladesh

</div>

---

## 🙏 Acknowledgments

- [FontAwesome](https://fontawesome.com/) for beautiful icons
- [RUET](https://www.ruet.ac.bd/) for institutional branding
- Email signature inspiration from professional templates
- All contributors and users of this template

---

## 📞 Support

Need help? Have questions?

- 📧 **Email**: [nazifatasnimshifa@gmail.com](mailto:nazifatasnimshifa@gmail.com)
- 🐛 **Report Issues**: [GitHub Issues](https://github.com/NazifaTasnimShifa/email_signature/issues)
- 💬 **Discussions**: [GitHub Discussions](https://github.com/NazifaTasnimShifa/email_signature/discussions)

---

## 📊 Compatibility

<div align="center">

| Email Client | Status | Notes |
|--------------|--------|-------|
| Gmail (Web) | ✅ Supported | Full support |
| Gmail (Mobile) | ✅ Supported | Full support |
| Outlook (Desktop) | ✅ Supported | Full support |
| Outlook (Web) | ✅ Supported | Full support |
| Apple Mail | ✅ Supported | Full support |
| Thunderbird | ✅ Supported | Full support |
| Yahoo Mail | ⚠️ Limited | Some styling may differ |
| ProtonMail | ⚠️ Limited | Basic HTML only |

</div>

---

<div align="center">

### ⭐ Star this repository if you found it helpful!

### 🔔 Watch for updates and new templates!

**Made with ❤️ by Nazifa Tasnim Shifa**

---

*Perfect for students, professionals, and anyone who wants a polished email signature!*

</div>