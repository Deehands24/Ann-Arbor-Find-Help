# Quick Affiliate Setup Guide

## 🚀 Get Started in 15 Minutes

Your site now has **4 affiliate programs** ready to earn money. Here's how to activate them:

---

## 1️⃣ BetterHelp (Highest Earning: $50-150/signup)

**Why**: Mental health therapy is your #1 revenue opportunity. High-intent traffic.

**Sign Up:**
1. Go to: https://www.betterhelp.com/partners/
2. Fill out application (takes 5 min)
3. Get approved in 24-48 hours
4. Get your tracking link: `https://www.betterhelp.com/rpc/YOUR-ID-HERE`

**Add to Site:**
- Open `index.html`
- Find line ~291: `href="https://www.betterhelp.com"`
- Replace with: `href="https://www.betterhelp.com/rpc/YOUR-ID-HERE"`
- Save and redeploy: `vercel --prod`

**Expected Earnings:**
- 1% of visitors click = 50 clicks/month (at 5,000 visitors)
- 10% sign up = 5 signups
- $80 average = **$400/month**

---

## 2️⃣ Talkspace (High Earning: $50-100/signup)

**Why**: Alternative to BetterHelp. Diversify income, catch people who prefer Talkspace.

**Sign Up:**
1. Go to: https://try.talkspace.com/affiliate
2. Join via Impact.com or CJ Affiliate network
3. Get approved (usually instant)
4. Get your tracking link: `https://www.talkspace.com/?ref=YOUR-CODE`

**Add to Site:**
- Open `index.html`
- Find line ~302: `href="https://www.talkspace.com"`
- Replace with your affiliate link
- Save and redeploy

**Expected Earnings:**
- Similar to BetterHelp: **$200-400/month**

---

## 3️⃣ Apartments.com (Medium Earning: $10-30/lead)

**Why**: People searching for housing help often need rentals. Easy conversions.

**Sign Up:**
1. Go to: https://www.shareasale.com
2. Create account (free)
3. Search for "Apartments.com" in merchant list
4. Apply to join their program
5. Get approved (usually same day)
6. Get tracking link from ShareASale dashboard

**Add to Site:**
- Open `index.html`
- Find line ~316: `href="https://www.apartments.com/ann-arbor-mi/"`
- Replace with ShareASale tracking link
- Format: `https://shareasale.com/r.cfm?b=XXXXX&u=XXXXX&m=XXXXX&urllink=apartments.com/ann-arbor-mi/`

**Expected Earnings:**
- 2% of housing visitors = 20 leads/month
- $15 average = **$300/month**

---

## 4️⃣ Instacart (Good Earning: $10-30/new customer)

**Why**: Food-insecure visitors may prefer delivery. First order bonuses convert well.

**Sign Up:**
1. Go to: https://www.impact.com
2. Create publisher account
3. Search for "Instacart" and apply
4. Wait for approval (2-5 days)
5. Get tracking link from Impact dashboard

**Add to Site:**
- Open `index.html`
- Find line ~327: `href="https://www.instacart.com"`
- Replace with Impact tracking link
- Save and redeploy

**Expected Earnings:**
- 1% of food section visitors = 10 signups/month
- $20 average = **$200/month**

---

## 💰 Total Potential Monthly Revenue

With 5,000 visitors/month:
- BetterHelp: $400
- Talkspace: $300
- Apartments.com: $300
- Instacart: $200
- **Total: $1,200/month**

At 10,000 visitors/month: **$2,400/month**
At 20,000 visitors/month: **$4,800/month**

---

## 📊 How to Track Performance

### 1. Google Analytics (Free)
Set up to see which pages get the most traffic:

```html
<!-- Add to <head> section of index.html -->
<script async src="https://www.googletagmanager.com/gtag/js?id=G-XXXXXXXXXX"></script>
<script>
  window.dataLayer = window.dataLayer || [];
  function gtag(){dataLayer.push(arguments);}
  gtag('js', new Date());
  gtag('config', 'G-XXXXXXXXXX');
</script>
```

Sign up: https://analytics.google.com

### 2. UTM Parameters
Track which traffic sources convert best:

**Example URLs to share:**
- Facebook: `annarbor.help?utm_source=facebook&utm_medium=social`
- Reddit: `annarbor.help?utm_source=reddit&utm_medium=social`
- Google Ads: `annarbor.help?utm_source=google&utm_medium=cpc`

Then check Analytics to see which sources drive affiliate clicks.

---

## 🔥 Pro Tips for Maximum Earnings

### 1. Add Affiliate Links to Resource Cards (Advanced)
You can also add BetterHelp as a resource in the Mental Health section:

```javascript
// In index.html around line 550, add to resources.mentalHealth.therapist:
{
    name: "BetterHelp - Online Therapy",
    desc: "Get matched with a licensed therapist online. Flexible scheduling, affordable rates.",
    website: "https://www.betterhelp.com/rpc/YOUR-ID",
    phone: "",
    address: "Online Service",
    isSponsored: true
}
```

### 2. Write Blog Posts (SEO)
Create a simple blog with posts like:
- "Top 5 Online Therapy Options in Michigan"
- "How to Find Affordable Housing in Ann Arbor"
- "Free Food Resources vs. Grocery Delivery Services"

Link to your affiliate offers naturally.

### 3. Email Capture
Add a simple form to collect emails, then send weekly resource updates with affiliate links.

**Tool**: Mailchimp (free up to 500 subscribers)

### 4. Retargeting Ads
Once you have traffic, use Facebook Pixel to retarget visitors with affiliate offers.

---

## ❓ FAQ

**Q: Do I need to disclose affiliate links?**
A: Yes! Already done - all cards say "SPONSORED" and links have `rel="sponsored"`.

**Q: When do I get paid?**
- BetterHelp: Net 30 (paid 30 days after signup)
- Talkspace: Net 30
- Apartments.com: Net 60
- Instacart: Net 30

**Q: What if I get rejected?**
- Apply again in 30 days
- Make sure your site has real traffic (even 10 visitors/day helps)
- Add more content (resource descriptions, etc.)

**Q: Can I use multiple affiliate programs at once?**
A: YES! That's the strategy - diversify income.

**Q: How do I test if links are working?**
- Open in incognito/private browser
- Click the affiliate link
- Check if URL has tracking parameters
- Cookie should be set (some programs pay for 30-90 day cookies)

---

## 🎯 Action Plan (This Week)

### Day 1: BetterHelp
- [ ] Sign up for BetterHelp Partners
- [ ] Wait for approval email

### Day 2: Talkspace
- [ ] Sign up for Impact.com or CJ Affiliate
- [ ] Apply to Talkspace program
- [ ] Wait for approval

### Day 3: Apartments.com
- [ ] Sign up for ShareASale
- [ ] Apply to Apartments.com
- [ ] Get tracking link

### Day 4: Instacart
- [ ] Sign up for Impact.com
- [ ] Apply to Instacart program

### Day 5: Implementation
- [ ] Get all approved tracking links
- [ ] Replace URLs in index.html
- [ ] Test all links in incognito mode
- [ ] Deploy: `vercel --prod`

### Day 6-7: Analytics
- [ ] Set up Google Analytics
- [ ] Add UTM parameters to social shares
- [ ] Post site in Ann Arbor Facebook groups

---

## 📈 Traffic Growth Strategy

Once affiliates are set up, focus on getting traffic:

**Week 1-2: Local Outreach**
- Email 20 Ann Arbor organizations asking them to link to you
- Post in r/AnnArbor (be helpful, not spammy)
- Share in 5 local Facebook groups

**Week 3-4: SEO**
- Submit to Google Search Console
- Get listed on local directories (Yelp, etc.)
- Add more resources (goal: 100+ total)

**Month 2: Paid Traffic (Optional)**
- Google Ads: $10/day budget
- Target: "ann arbor mental health", "homeless shelter near me"
- ROI: If 1 in 50 clicks converts to BetterHelp = profitable

---

## 🆘 Need Help?

**Common Issues:**
1. **Link not tracking**: Clear cookies, test in incognito
2. **Low conversions**: Add more trust signals (reviews, testimonials)
3. **Not approved**: Wait 30 days, reapply with more traffic

**Resources:**
- Affiliate marketing subreddit: r/affiliatemarketing
- ShareASale support: excellent email support
- Impact.com support: live chat available

---

**Ready to make money? Start with BetterHelp today!**

Sign up: https://www.betterhelp.com/partners/
