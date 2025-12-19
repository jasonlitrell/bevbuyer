# 🎯 FINAL WEBSITE - SETUP INSTRUCTIONS

## 📄 FILE TO USE: `jliittrell-BRANDED.html`

This is your complete, branded website with:
- ✅ Your brand colors (#07223d navy, #52ca28 green, #eb4171 pink)
- ✅ All 4 products (Kinetic, JLOS, Rockey Method, MistakesWereMade)
- ✅ Both hospitality AND spirits brand services
- ✅ Free community opt-in section
- ✅ Clear green placeholder boxes for GoHighLevel elements

---

## 🚀 QUICK START

### Step 1: Upload Your Logo to GoHighLevel
1. In GoHighLevel, go to **Media Library**
2. Upload your JL logo (the black version or white version)
3. Copy the URL of the uploaded image

### Step 2: Paste Website Code
1. Copy ALL the contents of `jliittrell-BRANDED.html`
2. In GoHighLevel, create a new website
3. Add a Custom HTML element
4. Paste the entire code

### Step 3: Update Logo URL
Find this line in the code (around line 227):
```html
<img src="YOUR_LOGO_URL_HERE.png" alt="Jason Littrell Logo">
```

Replace `YOUR_LOGO_URL_HERE.png` with your actual logo URL from Step 1.

### Step 4: Replace Green Placeholder Boxes
You'll see **3 green placeholder boxes** in the website. Replace them with:
1. **Community Opt-in Form** (free resources signup)
2. **Calendar Widget** (strategy call booking)
3. **Contact Form** (general inquiries)

---

## 🔶 GREEN PLACEHOLDER BOX #1: FREE COMMUNITY OPT-IN

### Where is it?
Pink section that says "Join the Hospitality Strategy Lab"

### What to Replace
Delete the green box and add a **GoHighLevel Form** with these fields:
- Name (required)
- Email (required)
- Business Type (dropdown):
  - Restaurant Owner
  - Bar/Nightclub Owner
  - Spirits Brand
  - Hospitality Consultant
  - Other

### Button Text
"Get Free Access"

### After Submit
- Add to email list: "Free Community - Hospitality Strategy Lab"
- Send welcome email with first free resource
- Redirect to thank you page

### Purpose
Build your email list for the free community

---

## 🔶 GREEN PLACEHOLDER BOX #2: CALENDAR BOOKING

### Where is it?
White section that says "Book a Strategy Call"

### What to Replace
Delete the green box and add a **GoHighLevel Calendar Widget**

### Calendar Settings
- **Name:** "Strategy Call with Jason"
- **Duration:** 30 minutes
- **Buffer:** 15 minutes between appointments
- **Questions to ask when booking:**
  - Business Name
  - Business Type (Restaurant, Bar, Spirits Brand, Multi-unit, Other)
  - Current Biggest Challenge (text area)
  - Annual Revenue Range (dropdown)

### Confirmation
- Send email confirmation
- Send SMS reminder 24 hours before
- Send SMS reminder 1 hour before

### Purpose
Let prospects book a free strategy call with you

---

## 🔶 GREEN PLACEHOLDER BOX #3: CONTACT FORM

### Where is it?
Navy blue section at the bottom that says "Ready to Transform Your Business?"

### What to Replace
Delete the green box and add a **GoHighLevel Form**

### Form Fields
- Name (required)
- Email (required)
- Phone (required)
- Business Type (dropdown):
  - Restaurant
  - Bar/Nightclub
  - Hotel F&B
  - Spirits Brand
  - Multi-unit Operation
  - Other
- Interested In (checkboxes - allow multiple):
  - Kinetic Management Systems
  - JLOS (Coaching)
  - The Rockey Method
  - MistakesWereMade Event
  - General Consulting
- Message (text area, optional)

### Button Text
"Send Message"

### After Submit
- Add to "New Leads" pipeline
- Send notification to you
- Send auto-reply email to prospect
- Assign to sales team (if applicable)

### Purpose
General contact form for all inquiries

---

## 🎨 YOUR BRAND COLORS (Already Implemented)

The website uses your exact colors:
- **Navy:** #07223d (main brand color, header, titles)
- **Green:** #52ca28 (CTAs, accents, highlights)
- **Pink:** #eb4171 (secondary accents, Rockey Method card)
- **Grey:** #4a5568 (MistakesWereMade card, text)

---

## 📦 YOUR PRODUCTS (All Featured)

### 1. Kinetic Management Systems (Green card)
- Your GoHighLevel implementation
- Marked as "Most Popular"
- Complete hospitality operating system

### 2. JLOS (Navy card)
- Your coaching & project management
- 1-on-1 guidance
- Strategic planning

### 3. The Rockey Method (Pink card)
- Spirits sales system
- Marked as "For Spirits Brands"
- Distribution & velocity building

### 4. MistakesWereMade (Grey card)
- Your signature event
- Community building
- Real stories & lessons

---

## 🏢 SERVICES (All Listed)

1. KMS Implementation
2. Operations Optimization
3. Cost Reduction Strategy
4. Menu Engineering
5. Spirits Brand Consulting (NEW - for your spirits clients)
6. Full Property Assessments

---

## 📝 CONTENT UPDATES

The website now includes:
- Article: "How to Reduce Restaurant Food Costs by 15-30%"
- Article: "Building a Spirits Brand Sales System That Actually Works" (NEW)
- Article: "Why Your Restaurant Needs a Kitchen Management System"

All content references your actual products (Kinetic, JLOS, Rockey Method).

---

## 🖼️ LOGO SETUP

### Your Logo Files
You shared 3 logo variations:
1. Black logo (solid)
2. White outline logo
3. Detailed outline logo

### Which One to Use Where

**In the Header (navy background):**
Use the **white logo** or add this CSS to make it white:
```css
style="filter: brightness(0) invert(1);"
```
This is already in the code!

**If you want to change it:**
Find line ~227 and update the image URL.

### Logo Size
The logo is set to `height: 50px` - adjust if needed:
```css
.logo img {height: 50px; width: auto;}
```

---

## ⚙️ CUSTOMIZATION OPTIONS

### Change Logo Size
Find this CSS (around line 41):
```css
.logo img {height: 50px; width: auto;}
```
Change `50px` to whatever size looks good.

### Update Contact Email
Find `jason@jliittrell.com` in the code and replace with your actual email.

### Update Statistics
Update these numbers in the Trust Bar section (around line 247):
- `$2.1M+` → Your total savings generated
- `50+` → Number of clients/operations
- `23%` → Your average cost reduction
- `100%` → Client satisfaction

---

## 📱 MOBILE RESPONSIVE

The site automatically adapts to:
- ✅ Desktop
- ✅ Tablet
- ✅ Mobile phones

No extra work needed!

---

## ✅ PRE-LAUNCH CHECKLIST

Before publishing:
- [ ] Upload logo to GoHighLevel Media Library
- [ ] Update logo URL in code (line ~227)
- [ ] Replace green box #1 with Community Opt-in Form
- [ ] Replace green box #2 with Calendar Widget
- [ ] Replace green box #3 with Contact Form
- [ ] Update email address if needed
- [ ] Update statistics if you have different numbers
- [ ] Preview on desktop
- [ ] Preview on mobile
- [ ] Test community opt-in form
- [ ] Test calendar booking
- [ ] Test contact form
- [ ] Publish!

---

## 🎯 WHAT MAKES THIS VERSION DIFFERENT

### Reflects Your ACTUAL Business:
- ✅ Dual focus: Hospitality + Spirits brands
- ✅ All 4 real products featured
- ✅ Free community prominently placed
- ✅ Your brand colors throughout
- ✅ Logo ready to drop in

### Better User Journey:
1. **Hero:** Clear value prop for both audiences
2. **Trust Bar:** Social proof
3. **Free Community:** Low-friction opt-in
4. **Products:** All 4 offerings clearly explained
5. **Services:** Consulting options
6. **Content:** Educational SEO articles
7. **Calendar:** Book a call
8. **Contact:** Alternative to booking

---

## 🆘 TROUBLESHOOTING

### "Logo doesn't show up"
- Make sure you uploaded it to GHL Media Library
- Copy the FULL URL (including https://)
- Paste it exactly in the code

### "Green boxes won't delete"
- You need to delete the entire `<div class="ghl-placeholder">...</div>` section
- Don't just edit it - fully delete and replace with your GHL widget

### "Colors look different"
- Make sure you're viewing in a modern browser
- Clear your cache
- The exact hex codes are in the CSS

### "I want to add more products"
- Copy one of the existing product cards
- Paste it below
- Change the icon, title, description
- Pick a class: `green`, `navy`, `pink`, or `grey`

---

## 💡 PRO TIPS

1. **Logo:** Use the white version in the header (navy background)
2. **Community Form:** Keep it simple (just name + email) for more signups
3. **Calendar:** Ask 2-3 qualifying questions max
4. **Contact Form:** The checkboxes help you route leads to the right product

---

## 🎉 YOU'RE READY!

This website reflects your actual business, brand, and offerings. Just:
1. Add your logo
2. Replace the 3 green boxes
3. Publish

All done! 🚀
