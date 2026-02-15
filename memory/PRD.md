# Ambulanta Care Medical Website - Product Requirements Document

## Project Overview
**Company:** Ambulanta Roganovic AB (Brand: Ambulanta Care)
**Type:** Multi-Language Medical Services Website
**Location:** Gothenburg, Sweden
**Last Updated:** 2025-12-15

## Original Problem Statement
Build a professional multi-language website for a medical company specializing in family medicine and general medicine with home visit services. The website should feature:
- Navy blue branding (matching logo)
- Multi-language support (English, Swedish, Serbian)
- Embedded Carepatron booking system
- Comprehensive service descriptions
- Transparent pricing
- Contact information

## User Personas
1. **Swedish-Speaking Patients**
   - Need: Local medical care in native language
   - Age: 25-80+
   - Pain Point: Prefer Swedish language medical services

2. **English-Speaking Expats**
   - Need: Medical care in English
   - Age: 25-65
   - Pain Point: Language barrier in Swedish healthcare system

3. **Serbian-Speaking Community**
   - Need: Medical care in native language
   - Age: 30-70
   - Pain Point: Communication difficulties with healthcare providers

4. **Patients Seeking Home Care**
   - Need: Convenient medical care at home
   - Age: 45-80+
   - Pain Point: Reduced mobility or preference for home-based care

## Core Requirements

### Design
- ✅ Navy blue color scheme (#1B3A60 / hsl(218, 100%, 20%))
- ✅ Professional medical aesthetic
- ✅ Responsive design
- ✅ Smooth scroll navigation
- ✅ Cropped logo only (no text next to logo)
- ✅ Language switcher in header

### Multi-Language Support
- ✅ English (en)
- ✅ Swedish (sv - Svenska)
- ✅ Serbian (sr - Serbo-Croatian Latin script)
- ✅ Language switcher: Svenska | English | Serbian
- ✅ All content fully translated
- ✅ Dynamic language switching without page reload

### Content Sections
- ✅ Header with navigation and language switcher
- ✅ Hero section with updated value proposition
- ✅ Services section (5 services)
- ✅ Conditions management section
- ✅ Extra Services section (3 specialized services)
- ✅ Second Opinion & Blood Test Review block
- ✅ Transparent pricing section
- ✅ Booking section with iframe
- ✅ Contact section
- ✅ Footer with company info

### Services Offered
1. **Family Medicine** - Comprehensive care for whole family
2. **General Medicine** - Acute and chronic conditions in adults
3. **Home Visit Services** - Medical care at patient's home
4. **Video Consultations** - Secure online consultations
5. **Health Checks** - Structured health assessments (NEW)

### Extra Services (NEW)
1. **Health Checks** - Comprehensive assessments with blood tests
2. **Second Opinion** - Independent medical opinions on diagnoses
3. **Blood Test Review** - Detailed lab result explanations

### Key Features (NEW)
- Licensed doctor AND licensed district nurse
- On-site testing: CRP, PCT, TSH
- Second opinions on diagnoses and treatment plans
- Consultations in Swedish, English, and Serbo-Croatian
- Management of cardiovascular, metabolic, thyroid disorders
- Acute infection treatment

### Pricing
- Home Visit: 2500 SEK per 60 minutes (clinical assessment, diagnostics, treatment)
- Video Consultation: 2500 SEK per consultation (up to 60 minutes)
- Prescription Renewal: 50 SEK per medication

### Contact Information
- Phone: +46 737 35 43 54
- Email: roganovic@dr.com / ambulanta@dr.com
- Address: Lindholmshamnen 23, 417 56 Gothenburg, Sweden

## What's Been Implemented

### Phase 1: Initial Website (Completed - 2025-12-15)
- ✅ Single-page application
- ✅ Basic structure with 4 services
- ✅ Navy blue branding
- ✅ Booking iframe integration

### Phase 2: Multi-Language Update (Completed - 2025-12-15)
- ✅ Multi-language translation system
- ✅ Language switcher in header (Svenska | English | Serbian)
- ✅ Comprehensive translations for all three languages
- ✅ Dynamic language switching
- ✅ Updated logo (cropped version, logo only)
- ✅ Expanded to 5 services (added Health Checks)
- ✅ New Extra Services section (3 services)
- ✅ Second Opinion & Blood Test Review block
- ✅ Updated hero copy mentioning licensed professionals
- ✅ Enhanced conditions management content
- ✅ Mobile-responsive language switcher

### Technology Stack
- **Frontend:** React 19, Tailwind CSS, Shadcn UI components
- **Routing:** React Router DOM
- **Icons:** Lucide React
- **Styling:** Custom navy blue color palette
- **State Management:** React useState for language selection
- **Translation System:** JavaScript object-based translations

### Files Created/Modified
- `/app/frontend/src/pages/Home.jsx` - Main homepage with multi-language support
- `/app/frontend/src/translations.js` - Translation file (NEW)
- `/app/frontend/src/App.js` - Updated routing
- `/app/frontend/src/index.css` - Navy blue color system
- `/app/memory/PRD.md` - This file

### Translation Coverage
All sections fully translated:
- Navigation menu
- Hero section
- Services (all 5)
- Extra Services (all 3)
- Conditions management
- Second Opinion block
- Pricing section
- Booking section
- Contact section
- Footer

## Conditions Managed
### Chronic Conditions:
- Hypertension
- High cholesterol
- Type 2 diabetes
- Hypothyroidism
- Obesity
- Chronic migraine
- Asthma
- Mild COPD
- Anxiety
- Depression (mild-moderate)
- Sleep problems
- Gastrointestinal complaints
- Musculoskeletal complaints

### Acute Infections:
- Respiratory infections
- Urinary tract infections
- Ear infections
- Sore throat / Tonsillitis
- Sinusitis
- Eye infections
- Simple gynecological infections

## Next Tasks

### Phase 3: SEO & Analytics (Optional)
- [ ] Multi-language SEO meta tags
- [ ] Google Analytics integration
- [ ] Structured data markup (JSON-LD)
- [ ] Sitemap generation
- [ ] Language-specific URLs or parameters

### Phase 4: Content Enhancements (Optional)
- [ ] Patient testimonials (multi-language)
- [ ] Doctor profile/credentials page
- [ ] FAQ section (multi-language)
- [ ] Blog for medical information
- [ ] Cookie consent banner (GDPR compliance)

### Phase 5: Advanced Features (Future)
- [ ] Contact form with email notifications
- [ ] Newsletter subscription
- [ ] Patient portal integration
- [ ] Online prescription management
- [ ] Medical records access
- [ ] Insurance information section
- [ ] Appointment reminder system
- [ ] Live chat support

## Success Metrics
- ✅ Multi-language support (3 languages)
- ✅ Clear call-to-action for booking
- ✅ Mobile-friendly interface
- ✅ Fast load times
- ✅ Professional medical aesthetic
- ✅ Easy navigation
- ✅ Trust-building elements (credentials, transparent pricing)
- ✅ Accessibility for diverse patient populations

## Technical Notes
- Website is frontend-only at this stage
- Booking system handled by external Carepatron platform
- Language preference stored in component state (resets on page reload)
- No backend required for current MVP
- All content is static and can be easily updated via translations.js file
- Language switching is instant (client-side only)

## Content Management
To update content:
1. Edit `/app/frontend/src/translations.js`
2. Find the appropriate language object (en, sv, or sr)
3. Update the text strings
4. Changes reflect immediately after page refresh

## Language Codes
- `en` - English
- `sv` - Swedish (Svenska)
- `sr` - Serbian (Serbo-Croatian, Latin script)

