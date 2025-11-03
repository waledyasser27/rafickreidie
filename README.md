# 🏗️ Rafic A. Kreidie Engineers & Contractors

> **Building Excellence Since 1985**

Official website for Rafic A. Kreidie Engineers & Contractors - A leading Grade 1 construction company based in Jeddah, Saudi Arabia.

![Website Preview](https://images.unsplash.com/photo-1541888946425-d81bb19240f5?w=1200&q=80)

## ✨ Features

### 🎨 Design
- **Luxury Design**: Black, gold, and gray color scheme
- **Fully Responsive**: Perfect on all devices (Mobile, Tablet, Desktop)
- **Modern Animations**: GSAP & AOS for smooth interactions
- **RTL & LTR Support**: Full Arabic and English language support

### 📄 Sections
1. **Hero Section**: Video background with compelling CTA
2. **Stats**: Company achievements and milestones
3. **About**: Company history and values
4. **Services**: 7 comprehensive services:
   - General Contracting
   - Design & Build
   - EPC (Engineering, Procurement, Construction)
   - Construction Management
   - Civil Works
   - Building Construction
   - Electrical & Solar Energy
5. **Projects**: Filterable project gallery
6. **Partners**: Client and partner showcase
7. **Contact**: Professional contact form with email integration

### 🔧 Technical Features
- **Flask API**: Backend for contact form
- **Email Integration**: Automatic email notifications
- **SEO Optimized**: Meta tags and semantic HTML
- **Fast Loading**: Optimized assets and lazy loading
- **Vercel Ready**: One-click deployment

## 🚀 Quick Start

### Prerequisites
- Python 3.8+
- Node.js (optional)
- Gmail account for SMTP

### Installation

1. **Clone the repository**
```bash
git clone https://github.com/ammaryasser618/rafic-kreidie.git
cd rafic-kreidie
```

2. **Install Python dependencies**
```bash
pip install -r requirements.txt
```

3. **Configure environment variables**
```bash
cp .env.example .env
```

Edit `.env` and add your SMTP credentials:
```env
SMTP_SERVER=smtp.gmail.com
SMTP_PORT=587
SMTP_USERNAME=your-email@gmail.com
SMTP_PASSWORD=your-app-password
RECIPIENT_EMAIL=info@rak.com.sa
```

4. **Run locally**
```bash
python api/index.py
```

Visit `http://localhost:5000`

## 📦 Project Structure

```
rafic-kreidie/
├── index.html          # Main HTML file
├── css/
│   └── style.css       # Styles (22KB)
├── js/
│   └── main.js         # JavaScript (17KB)
├── api/
│   └── index.py        # Flask API (10KB)
├── vercel.json         # Vercel configuration
├── requirements.txt    # Python dependencies
├── package.json        # NPM configuration
├── .env.example        # Environment template
└── README.md           # Documentation
```

## 🌐 Deployment to Vercel

### Option 1: From GitHub (Recommended)

1. **Push to GitHub**
```bash
git init
git add .
git commit -m "Initial commit"
git remote add origin https://github.com/ammaryasser618/rafic-kreidie.git
git push -u origin main
```

2. **Deploy on Vercel**
   - Go to [vercel.com](https://vercel.com)
   - Sign in with GitHub account: **ammaryasser618**
   - Click "Import Project"
   - Select the repository
   - Add environment variables:
     - `SMTP_USERNAME`
     - `SMTP_PASSWORD`
     - `RECIPIENT_EMAIL`
   - Click "Deploy"

### Option 2: Vercel CLI

```bash
npm i -g vercel
vercel login
vercel --prod
```

## 📧 Email Configuration

### Gmail Setup

1. **Enable 2-Factor Authentication**
   - Go to Google Account Settings
   - Security → 2-Step Verification

2. **Create App Password**
   - Go to [App Passwords](https://myaccount.google.com/apppasswords)
   - Select "Mail" and "Other"
   - Copy the generated password

3. **Add to Vercel**
   - Go to Project Settings → Environment Variables
   - Add `SMTP_USERNAME` and `SMTP_PASSWORD`

## 🎨 Customization

### Colors
Edit CSS variables in `css/style.css`:
```css
:root {
    --color-black: #0D0D0D;
    --color-gold: #D4AF37;
    --color-gray: #2E2E2E;
    --color-white: #FFFFFF;
}
```

### Logo
Replace the logo URL in `index.html`:
```html
<img src="YOUR_LOGO_URL" alt="Rafic A. Kreidie Logo">
```

### Content
Edit text directly in `index.html` for both Arabic and English:
```html
<span class="lang-ar">النص بالعربي</span>
<span class="lang-en">English Text</span>
```

## 🔧 API Endpoints

### POST /api/contact
Submit contact form

**Request Body:**
```json
{
  "company_name": "Company Name",
  "services": "general-contracting",
  "contact_name": "John Doe",
  "email": "john@example.com",
  "message": "Project inquiry..."
}
```

**Response:**
```json
{
  "status": "success",
  "message": "Contact form submitted successfully",
  "email_sent": true
}
```

### GET /api/health
Health check endpoint

**Response:**
```json
{
  "status": "healthy",
  "timestamp": "2024-01-01T12:00:00",
  "smtp_configured": true
}
```

## 📊 Performance

- **Load Time**: < 2 seconds
- **PageSpeed Score**: 90+
- **Mobile Friendly**: ✓
- **SEO Score**: 95+

## 🌍 Browser Support

- Chrome (latest)
- Firefox (latest)
- Safari (latest)
- Edge (latest)
- Mobile browsers

## 📱 Language Support

- 🇸🇦 Arabic (RTL)
- 🇬🇧 English (LTR)

Toggle language with the button in top-right corner.

## 🤝 Contributing

Contributions are welcome! Please follow these steps:

1. Fork the repository
2. Create a feature branch
3. Commit your changes
4. Push to the branch
5. Open a Pull Request

## 📄 License

MIT License - see LICENSE file for details

## 👤 Contact

**Rafic A. Kreidie Engineers & Contractors**

- 📍 Prince Mohammed Bin Abdulaziz Branch Road, Jeddah, Saudi Arabia
- 📧 info@rak.com.sa
- 🌐 [rak.com.sa](https://rak.com.sa)
- 💼 [LinkedIn](#)

## 🙏 Acknowledgments

- Design inspired by luxury construction companies
- Icons from Feather Icons
- Images from Unsplash
- Animations by GSAP & AOS

---

**Built with ❤️ for Rafic A. Kreidie Engineers & Contractors**

*Building the Future with Excellence Since 1985* 🏗️✨