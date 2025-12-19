# Setting Up jliittrell.com in GoHighLevel

## Method 1: Custom Website Builder (Recommended)

### Step 1: Access Website Builder
1. Log into your GoHighLevel account
2. Navigate to **Sites** → **Websites**
3. Click **+ New Website**
4. Choose **Blank Template** or **Custom Code**

### Step 2: Add Custom Code
1. Once in the website editor, look for **Custom Code** or **HTML/CSS** section
2. Add the HTML structure from `index.html`
3. Add the CSS from `styles.css` in the **Custom CSS** section
4. Add the JavaScript from `script.js` in the **Custom JavaScript** section

### Step 3: Using Sections (Alternative Approach)
If GoHighLevel doesn't allow full custom code, use their section builder:

1. Create separate sections for each part:
   - Header/Navigation
   - Hero Section
   - About Section
   - Skills Section
   - Projects Section
   - Contact Section (use GHL's form builder here)
   - Footer

2. For each section:
   - Click **Add Section** → **Custom HTML**
   - Copy the relevant HTML from `index.html`
   - Add section-specific CSS

### Step 4: Setup Contact Form Integration
1. In the Contact section, replace the HTML form with GoHighLevel's native form builder:
   - Go to **Forms** → **Create New Form**
   - Add fields: Name, Email, Message
   - Copy the form embed code
   - Replace the `<form>` section in your HTML

2. Or use GoHighLevel's form API:
```javascript
// Replace in script.js contact form handler
contactForm.addEventListener('submit', async (e) => {
    e.preventDefault();

    const formData = new FormData(contactForm);
    const data = {
        name: formData.get('name'),
        email: formData.get('email'),
        message: formData.get('message')
    };

    try {
        // GoHighLevel API endpoint (replace with your actual endpoint)
        const response = await fetch('YOUR_GHL_WEBHOOK_URL', {
            method: 'POST',
            headers: {
                'Content-Type': 'application/json',
            },
            body: JSON.stringify(data)
        });

        if (response.ok) {
            showNotification('Message sent successfully! I\'ll get back to you soon.', 'success');
            contactForm.reset();
        } else {
            showNotification('Something went wrong. Please try again.', 'error');
        }
    } catch (error) {
        showNotification('Network error. Please try again.', 'error');
    }
});
```

## Method 2: Custom Domain with External Hosting

If GoHighLevel's custom code features are limited, you can:

1. **Host the website externally:**
   - Use Netlify, Vercel, or GitHub Pages to host the static site
   - Point your custom domain to the external host
   - Use GoHighLevel for CRM and form submissions only

2. **Connect the form to GoHighLevel:**
   - Create a webhook in GoHighLevel
   - Submit form data to the webhook from your external site

## Method 3: Funnel Builder Approach

### Step 1: Create a Funnel
1. Go to **Sites** → **Funnels**
2. Click **+ Create Funnel**
3. Choose **Custom Funnel**

### Step 2: Add a Landing Page
1. Click **Add Step** → **Landing Page**
2. Choose **Blank** template
3. Use the page builder to recreate sections

### Step 3: Embed Custom Code
For each section:
```html
<!-- Add this in Custom Code blocks -->
<div id="custom-section">
    <!-- Copy relevant HTML here -->
</div>

<style>
    /* Copy relevant CSS here */
</style>

<script>
    // Copy relevant JS here
</script>
```

## Method 4: Using GoHighLevel's Page Builder

### Recreate with Native Elements:

1. **Header:**
   - Use Navigation Menu widget
   - Add logo image/text
   - Configure menu items

2. **Hero Section:**
   - Use 2-column layout
   - Add headline, subheadline, buttons
   - Use custom CSS for gradients and animations

3. **About Section:**
   - Use text blocks and columns
   - Add custom stat cards with HTML blocks

4. **Skills Section:**
   - Use card grid layout
   - Add icons (use Font Awesome or upload custom)
   - Add text blocks

5. **Projects Section:**
   - Use card/grid layout
   - Add images (replace placeholders)
   - Add tags using buttons or text

6. **Contact Section:**
   - Use GoHighLevel Form Builder
   - Style with custom CSS to match design

7. **Footer:**
   - Use footer widget
   - Add links and copyright

## Important: GoHighLevel-Specific Adjustments

### 1. Remove Google Fonts (Use GHL's Font Options)
Remove this from HTML:
```html
<link href="https://fonts.googleapis.com/css2?family=Inter:wght@300;400;600;700;900&display=swap" rel="stylesheet">
```

Or keep it if GHL allows external fonts.

### 2. Update Form Action
In GoHighLevel, forms typically submit to their system:
```html
<form action="https://api.leadconnectorhq.com/forms/submit" method="POST">
    <input type="hidden" name="location_id" value="YOUR_LOCATION_ID">
    <!-- rest of form fields -->
</form>
```

### 3. Add Tracking Codes
Add GoHighLevel tracking:
1. Go to **Settings** → **Custom Code**
2. Add tracking code to header/footer

### 4. SEO Settings in GoHighLevel
1. Go to page **Settings** → **SEO**
2. Add:
   - Page Title: "Jason Littrell | Software Developer & Technology Professional"
   - Meta Description: (copy from index.html)
   - Keywords: (copy from index.html)
   - OG Image: Upload a preview image

## Quick Setup Checklist

- [ ] Create new website/funnel in GoHighLevel
- [ ] Add custom HTML sections
- [ ] Add custom CSS (either globally or per section)
- [ ] Add custom JavaScript
- [ ] Replace contact form with GHL form builder
- [ ] Upload any images to GHL media library
- [ ] Configure SEO settings
- [ ] Set up custom domain
- [ ] Add favicon
- [ ] Upload robots.txt (in site settings)
- [ ] Configure SSL certificate
- [ ] Test on mobile devices
- [ ] Test form submissions
- [ ] Enable analytics tracking

## Tips for Best Results

1. **Use Custom Code Sections:** GoHighLevel's custom code sections give you the most flexibility
2. **Break into Chunks:** Don't try to add all HTML at once - add section by section
3. **Test Frequently:** Preview after each section to ensure styling works
4. **Mobile Responsiveness:** Use GHL's mobile preview to check responsive design
5. **Form Integration:** Use GHL's native forms for better CRM integration
6. **Speed Optimization:** Minimize external resources for faster loading

## Common Issues & Solutions

**Issue: CSS not applying**
- Solution: Add CSS in the global custom CSS area or use `<style>` tags in custom HTML blocks

**Issue: JavaScript not working**
- Solution: Add JS in footer custom code area or ensure scripts load after DOM

**Issue: Forms not submitting**
- Solution: Use GoHighLevel's form builder or webhook integration

**Issue: Fonts not loading**
- Solution: Check if GHL allows external fonts, or use GHL's built-in font options

## Need Help?

If GoHighLevel's restrictions are too limiting:
1. Host on Netlify/Vercel (free)
2. Use GoHighLevel only for forms/CRM
3. Connect via webhooks or API

Contact GoHighLevel support for specific questions about custom code capabilities in your plan tier.
