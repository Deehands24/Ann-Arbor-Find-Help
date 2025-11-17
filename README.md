# Ann Arbor.help - Resource Directory

A modern, fast-loading resource directory connecting Ann Arbor residents to housing, mental health, and food assistance.

**<� YOUR SITE IS LIVE!** Check your Vercel deployment URL.

---

## =� Start Here - Documentation

### **New to monetization?** Start with these guides:

1. **[QUICK-START.md](QUICK-START.md)** P **READ THIS FIRST**
   - Make your first $100 this week
   - 3 simple steps to activate revenue
   - Social media promotion templates

2. **[AFFILIATE-SETUP.md](AFFILIATE-SETUP.md)** =�
   - 14 affiliate programs ready to activate
   - Step-by-step signup instructions
   - Expected earnings: $200-1,200/month

3. **[MONETIZATION-MASTER-PLAN.md](MONETIZATION-MASTER-PLAN.md)** =�
   - 12+ revenue streams beyond affiliates
   - Scale to $3,000-10,000/month
   - Lead generation, sponsorships, grants, API licensing, and more

---

## =� Deploy to Vercel

Your site is already deployed! To update:

```bash
vercel --prod
```

Or use the Vercel Dashboard:
- Go to [vercel.com](https://vercel.com)
- Your project: ann-arbor-find-help
- Click "Redeploy" after making changes

---

## ( What's Included

### **Modern Design:**
- Animated gradient header
- Color-coded categories (blue/green/pink)
- Smooth hover effects & animations
- Mobile-responsive
- Fast loading (no framework overhead)

### **Interactive Features:**
- Real-time search/filter
- One-click copy phone numbers
- Bookmark resources (localStorage)
- Share resources (Web Share API)
- Crisis hotline pulse animations

### **Monetization Ready:**
- 4 affiliate programs pre-integrated (BetterHelp, Talkspace, Apartments, Instacart)
- 10 more documented with signup links
- Sponsored card templates
- AdSense placeholder (hidden until qualified)
- Clear FTC-compliant disclosures

### **30+ Real Resources:**
- Housing: Shelters, legal aid, rentals, utilities
- Mental Health: Crisis lines, therapists, support groups
- Food: Pantries, SNAP, clothing

---

## =� Revenue Potential

### **Month 1:** $200-500
- Activate affiliates
- Social media traffic
- First local sponsor

### **Month 3:** $750-1,500
- Multiple affiliates converting
- 2-3 local sponsorships
- SEO traffic growing

### **Year 1:** $2,000-4,000/month
- Optimized affiliates
- Lead generation active
- Premium listings
- Grant funding

### **Year 2+:** $5,000-12,000/month
- All revenue streams active
- White-label other cities
- API licensing
- Corporate partnerships

---

## <� Quick Wins (Do This Week)

- [ ] Sign up for BetterHelp affiliate (highest earner)
- [ ] Share site in 3 Ann Arbor Facebook groups
- [ ] Email 5 local therapists about sponsorships
- [ ] Set up Google Analytics
- [ ] Add email capture to homepage

**Target: First $100 in 7-14 days**

---

## =� Technical Stack

- **Frontend:** HTML, CSS (Tailwind via CDN), Vanilla JavaScript
- **Hosting:** Vercel (static site)
- **Dependencies:** None (except Tailwind CDN)
- **Build:** None required
- **Database:** None (all data in JavaScript)

**Why this approach:**
-  Instant deployment
-  Zero maintenance
-  Perfect SEO (server-side rendered)
-  Free hosting forever
-  Fast loading (no build step)

---

## =� Analytics & Tracking

### Add Google Analytics:
1. Sign up: https://analytics.google.com
2. Get tracking ID: `G-XXXXXXXXXX`
3. Add to `<head>` in `index.html`:

```html
<script async src="https://www.googletagmanager.com/gtag/js?id=G-XXXXXXXXXX"></script>
<script>
  window.dataLayer = window.dataLayer || [];
  function gtag(){dataLayer.push(arguments);}
  gtag('js', new Date());
  gtag('config', 'G-XXXXXXXXXX');
</script>
```

---

## <� Customization

### Add New Resources:
Edit the `resources` object in `index.html` (line ~421):

```javascript
resources.housing.shelters.push({
    name: "Organization Name",
    desc: "Brief description",
    website: "https://example.com",
    phone: "(734) 555-0123",
    address: "123 Main St, Ann Arbor, MI 48104"
});
```

### Change Colors:
Edit gradients in `<style>` section (line ~34):

```css
.housing-gradient {
    background: linear-gradient(135deg, #YOUR_COLOR 0%, #YOUR_COLOR_2 100%);
}
```

---

## <� Need Help?

**Check the docs first:**
- Technical questions � This README
- Affiliate setup � [AFFILIATE-SETUP.md](AFFILIATE-SETUP.md)
- Revenue growth � [MONETIZATION-MASTER-PLAN.md](MONETIZATION-MASTER-PLAN.md)

**Common Issues:**
- Site not deploying � Check `vercel.json` format
- Affiliate links not tracking � Test in incognito mode
- Low conversions � Add more trust signals, testimonials

---

## =� License

Free to use, modify, and monetize. No attribution required.

---

## =� Ready to Make Money?

**Next step:** Open [QUICK-START.md](QUICK-START.md) and follow the 3-step plan to make your first $100 this week.

Built with d for the Ann Arbor community
