# 🎯 EXACTLY WHERE TO ADD GOHIGHLEVEL ELEMENTS

This guide shows you EXACTLY where to add your GoHighLevel calendars, forms, and surveys.

---

## 📄 FILE TO USE: `jliittrell-FINAL.html`

This is your complete website with **bright yellow placeholder boxes** showing exactly where to add GHL elements.

---

## 🚀 QUICK START

### Step 1: Open the File in GoHighLevel
1. Copy ALL the contents of `jliittrell-FINAL.html`
2. Log into GoHighLevel
3. Create a new website/page
4. Paste the entire code into a Custom HTML element

### Step 2: You'll See Yellow Placeholder Boxes
When you preview the page, you'll see **bright yellow boxes** with dashed borders that say things like:
- "📅 REPLACE WITH GOHIGHLEVEL CALENDAR"
- "📝 REPLACE WITH GOHIGHLEVEL FORM"
- "📋 OPTIONAL: ADD GOHIGHLEVEL SURVEY"

### Step 3: Replace Each Yellow Box
Follow the instructions below for each element.

---

## 🔶 ELEMENT #1: CALENDAR BOOKING (Required)

### Where is it?
Look for the bright yellow box that says:
```
📅 REPLACE WITH GOHIGHLEVEL CALENDAR
```

### What to Delete
Delete this entire section:
```html
<div class="ghl-placeholder">
    <h3>📅 REPLACE WITH GOHIGHLEVEL CALENDAR</h3>
    ...everything inside...
</div>
```

### What to Add Instead

**In GoHighLevel:**
1. Go to **Calendars** → Create new calendar
2. Name it: "Free Restaurant Cost Analysis Call"
3. Settings:
   - Duration: 30 minutes
   - Buffer: 15 minutes between appointments
   - Ask these questions when booking:
     - Business Name
     - Annual Revenue (dropdown)
     - Biggest Challenge (text area)
4. Get the **Calendar Widget Code**
5. Paste it where you deleted the yellow placeholder

**Result:** Visitors can book a free 30-minute consultation directly on your website.

---

## 🔶 ELEMENT #2: CONTACT FORM (Required)

### Where is it?
Look for the bright yellow box in the orange section near the bottom that says:
```
📝 REPLACE WITH GOHIGHLEVEL FORM
```

### What to Delete
Delete this entire section:
```html
<div class="ghl-placeholder">
    <h3>📝 REPLACE WITH GOHIGHLEVEL FORM</h3>
    ...everything inside...
</div>
```

### What to Add Instead

**In GoHighLevel:**
1. Go to **Forms** → Create new form
2. Name it: "Free Cost Analysis Request"
3. Add these fields:
   - **Name** (text, required)
   - **Email** (email, required)
   - **Phone** (phone, required)
   - **Business Name** (text, required)
   - **Business Type** (dropdown):
     - Independent Restaurant
     - Restaurant Group (2+ locations)
     - Hotel/Resort F&B
     - Catering Operation
     - Other
   - **Biggest Challenge** (textarea, optional)
4. Submit button text: "Get My Free Analysis"
5. Set up automation:
   - Send confirmation email
   - Add to "New Leads" pipeline
   - Send you a notification
6. Get the **Form Embed Code**
7. Paste it where you deleted the yellow placeholder

**Result:** Visitors can request a free analysis and automatically enter your CRM.

---

## 🔶 ELEMENT #3: SURVEY (Optional)

### Where is it?
Look for the yellow box that says:
```
📋 OPTIONAL: ADD GOHIGHLEVEL SURVEY
```

### Two Options:

#### Option A: Delete It (Simpler)
If you don't want a survey, just delete the entire yellow box section. Your website will work fine without it.

#### Option B: Add a Survey (More Qualification)
Use this to qualify leads before they book a call.

**What to Delete:**
```html
<div class="ghl-placeholder">
    <h3>📋 OPTIONAL: ADD GOHIGHLEVEL SURVEY</h3>
    ...everything inside...
</div>
```

**What to Add Instead:**

**In GoHighLevel:**
1. Go to **Surveys** → Create new survey
2. Name it: "Restaurant Operations Assessment"
3. Add these questions:
   - What type of operation do you run? (radio buttons)
   - What's your annual revenue range? (dropdown)
   - What's your current food cost %? (text)
   - Are you currently using a KMS? (Yes/No/What's that?)
   - What's your biggest challenge? (checkboxes: High food costs, Labor issues, Low profits, Poor systems)
4. After survey completion:
   - Redirect to calendar booking page
   - OR show a "Thanks! Someone will contact you" message
5. Get the **Survey Embed Code**
6. Paste it where you deleted the yellow placeholder

**Result:** You qualify leads and gather useful info before the call.

---

## 📋 SUMMARY - WHAT TO REPLACE

| Yellow Box Says | What to Replace It With | GoHighLevel Section |
|----------------|------------------------|-------------------|
| 📅 REPLACE WITH GOHIGHLEVEL CALENDAR | Calendar widget | Calendars |
| 📝 REPLACE WITH GOHIGHLEVEL FORM | Contact form | Forms |
| 📋 OPTIONAL: ADD SURVEY | Survey widget OR delete entirely | Surveys |

---

## 🎨 CUSTOMIZATION AFTER ADDING GHL ELEMENTS

Once you've added your GHL elements, update these:

### 1. Contact Information
Search and replace:
- `(555) 123-4567` → Your real phone number
- `jason@jliittrell.com` → Your real email

### 2. Statistics (if different)
Update the numbers in the trust bar:
- `$2.1M+` → Your total cost savings
- `23%` → Your average cost reduction
- `50+` → Number of clients

### 3. Results Section
Update the case study numbers with your real results:
- `$180K` → Actual savings from a client
- `23%` → Actual food cost reduction
- Etc.

---

## 🔍 HOW TO FIND THE YELLOW BOXES

### In GoHighLevel Page Builder:
1. After pasting the code, click **Preview**
2. Scroll through the page
3. You'll see bright **yellow/orange boxes** with dashed borders
4. Each box has clear instructions inside it
5. Replace them one at a time with your GHL elements

### Can't See Them?
If you can't see the yellow boxes:
- Make sure you're in **Preview mode**, not edit mode
- The boxes have this style: Yellow background, orange dashed border, orange text
- Search the code for "ghl-placeholder" to find them

---

## ⚡ FASTEST SETUP (5 Minutes)

1. **Paste the code** into GoHighLevel custom HTML
2. **Preview the page** - you'll see 3 yellow boxes
3. **Replace yellow box #1** with a Calendar widget (30-min consultation)
4. **Replace yellow box #2** with a Contact Form
5. **Delete yellow box #3** (survey - optional)
6. **Update** phone number and email at the bottom
7. **Publish!**

---

## 🆘 TROUBLESHOOTING

### "I can't find the yellow boxes"
- Make sure you copied the ENTIRE file (all ~600 lines)
- Preview the page (don't just edit the code)
- Look for orange/yellow sections with dashed borders

### "The GHL element doesn't fit the design"
- In GoHighLevel, edit the form/calendar styling
- Match the colors: Primary blue (#1e40af), Accent orange (#f59e0b)
- Set form width to 100% so it fills the space

### "Do I NEED all three elements?"
No! Minimum required:
- ✅ Calendar OR Contact Form (pick one)
- ❌ Survey is totally optional

Most people use: Calendar + Contact Form (no survey)

---

## 📞 FINAL RESULT

When done, visitors can:
1. ✅ Read about your services and expertise
2. ✅ See real cost-saving results
3. ✅ Learn HOW you reduce costs (the articles)
4. ✅ Book a free call via calendar
5. ✅ OR submit a contact form
6. ✅ Enter your CRM automatically

---

## 💡 PRO TIP

**After someone books via calendar:**
1. Set up an automated email sequence
2. Send them a questionnaire before the call
3. Ask for: Current food cost %, # of employees, annual revenue
4. This makes your consultation call WAY more valuable

---

## ✅ CHECKLIST

Before publishing:
- [ ] Pasted full code into GoHighLevel
- [ ] Replaced calendar placeholder with actual calendar widget
- [ ] Replaced form placeholder with actual contact form
- [ ] Deleted OR replaced survey placeholder
- [ ] Updated phone number
- [ ] Updated email address
- [ ] Updated statistics (if you have different numbers)
- [ ] Previewed on desktop
- [ ] Previewed on mobile
- [ ] Tested calendar booking
- [ ] Tested form submission
- [ ] Published!

---

You're done! 🎉
