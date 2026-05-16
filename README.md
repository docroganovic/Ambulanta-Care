# Ambulanta Care Website - Full Source Code

## 🏥 Complete Medical Website Project

Professional medical website for Ambulanta Care with:
- ✅ Multi-language support (English, Swedish, Serbian)
- ✅ React frontend with Tailwind CSS
- ✅ FastAPI backend (optional)
- ✅ MongoDB integration (optional)
- ✅ Responsive design
- ✅ Carepatron booking system

---

## 📁 Project Structure

```
ambulanta-care/
├── frontend/              # React application
│   ├── public/           # Static files (index.html, favicon)
│   ├── src/              # Source code
│   │   ├── components/   # Reusable components (Shadcn UI)
│   │   ├── pages/        # Page components (Home.jsx)
│   │   ├── translations.js  # All language translations
│   │   ├── App.js        # Main app component
│   │   └── index.css     # Global styles
│   ├── package.json      # Dependencies
│   └── .env              # Environment variables
│
├── backend/              # FastAPI backend (optional)
│   ├── server.py         # Main server file
│   ├── requirements.txt  # Python dependencies
│   └── .env              # Backend environment
│
└── README.md            # This file
```

---

## 🚀 Quick Start - Frontend Only

### **Prerequisites:**
- Node.js (v16+)
- Yarn

### **Setup:**

```bash
# 1. Clone repository
git clone https://github.com/docroganovic/Ambulanta-Care-v2.git
cd Ambulanta-Care-v2

# 2. Install frontend dependencies
cd frontend
yarn install

# 3. Start development server
yarn start

# Website opens at http://localhost:3000
```

### **Build for Production:**

```bash
cd frontend
yarn build

# Output in frontend/build/ folder
# Upload to Hostinger
```

---

## 📝 Make Changes

### **Change Text Content:**

Edit `/frontend/src/translations.js`:

```javascript
export const translations = {
  en: {
    hero: {
      title: 'Your new title here',
      subtitle: 'Your new description',
      // ...
    }
  }
}
```

### **Change Prices:**

In `translations.js`, update the pricing section:

```javascript
pricing: {
  items: [
    {
      title: 'Home Visit',
      price: '2000 SEK',  // Change this
      // ...
    }
  ]
}
```

### **Change Colors:**

Edit `/frontend/src/index.css` - update CSS variables:

```css
:root {
  --navy-800: 218 100% 20%;  /* Change navy blue */
}
```

---

## 🌍 Languages

All translations in `/frontend/src/translations.js`:
- `en` - English
- `sv` - Swedish (Svenska)
- `sr` - Serbian (Srpski)

To add new language:
1. Copy existing language object
2. Translate all text
3. Add language button in Home.jsx

---

## 🎨 Styling

- **Framework:** Tailwind CSS
- **Components:** Shadcn UI
- **Theme:** Navy blue (#1B3A60)
- **Custom colors:** Defined in index.css

---

## 📦 Dependencies

### Frontend:
- React 19
- React Router DOM
- Tailwind CSS
- Shadcn UI components
- Lucide React (icons)
- Axios (API calls)

### Backend (Optional):
- FastAPI
- MongoDB with Motor
- Python 3.9+

---

## 🔧 Available Scripts

### Frontend:

```bash
yarn start        # Start dev server
yarn build        # Build for production
yarn test         # Run tests
```

---

## 📤 Deploy to Hostinger

### **Method 1: Build & Upload**

```bash
# 1. Build
cd frontend
yarn build

# 2. Upload frontend/build/ contents to Hostinger public_html:
# - index.html
# - static/ folder
# - asset-manifest.json
```

### **Method 2: Use Pre-built Version**

Download latest build from:
https://github.com/docroganovic/Ambulanta-Care-v2/releases

---

## 🌐 Environment Variables

### Frontend (`/frontend/.env`):

```env
REACT_APP_BACKEND_URL=https://your-domain.com
```

### Backend (`/backend/.env`):

```env
MONGO_URL=mongodb://localhost:27017
DB_NAME=ambulanta_care
```

---

## 🔍 Features

### Current Features:
- ✅ Multi-language (English, Swedish, Serbian)
- ✅ Auto language detection
- ✅ 6 service cards
- ✅ Discount pricing with strikethrough
- ✅ Mobile floating phone button
- ✅ Carepatron booking integration
- ✅ Contact form
- ✅ Social media preview (Open Graph)
- ✅ Favicon
- ✅ Responsive design
- ✅ No "Made with Emergent" badge

### Pricing:
- Home Visit: ~~2000/2500 SEK~~ → **1000/1250 SEK** (50% off)
- Video Consultation: ~~1000 SEK~~ → **750 SEK** (25% off)
- Prescription Renewal: 50 SEK

---

## 🆘 Troubleshooting

### White screen when opening index.html:
- React apps need a web server
- Use `yarn start` or upload to Hostinger
- Don't open index.html directly

### Changes not showing:
- Clear browser cache (Ctrl+F5)
- Rebuild with `yarn build`
- Make sure you edited translations.js

### Port already in use:
- Kill existing process or use different port
- Change port in package.json

---

## 📞 Contact

**Ambulanta Care**
- Phone: +46 737 35 43 54
- Email: ambulanta@dr.com
- Location: Gothenburg, Sweden

---

## 📄 License

© 2025 Ambulanta Care. All rights reserved.

---

## 🔗 Links

- **Live Website:** (Your Hostinger domain)
- **GitHub:** https://github.com/docroganovic/Ambulanta-Care-v2
- **Support:** ambulanta@dr.com

---

**Built with React, Tailwind CSS, and ❤️**
