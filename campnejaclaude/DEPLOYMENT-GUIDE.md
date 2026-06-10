# 🚀 Deploy CampNeja.com - Step by Step

Your site is ready to go live! All files are in the `campneja-deploy/` folder.

---

## ✅ PART 1: Deploy to Netlify (5 minutes)

### Step 1: Go to Netlify
1. Open: **https://app.netlify.com**
2. Click **"Sign up"** (you can use GitHub, Google, or email)
3. No credit card needed!

### Step 2: Deploy Your Site
1. Once logged in, you'll see the dashboard
2. Look for **"Add new site"** or drag-and-drop area
3. **DRAG the entire `campneja-deploy` folder** onto the page
   - Location: `/Users/upneja/Projects/houseofayush/campnejaclaude/campneja-deploy`
   - Just drag the whole folder from Finder!

4. Netlify will upload and deploy automatically
5. In ~30 seconds, you'll get a live URL like: `random-name-12345.netlify.app`

### Step 3: Test Your Site
1. Click the live URL Netlify gives you
2. Verify:
   - ✅ All images load
   - ✅ RSVP button goes to Partiful
   - ✅ Airbnb link works
   - ✅ Navigation works

---

## ✅ PART 2: Connect Your Domain (campneja.com)

### Step 4: Add Custom Domain in Netlify
1. In Netlify, click on your site
2. Go to **"Domain settings"** or **"Set up a custom domain"**
3. Click **"Add custom domain"**
4. Type: `campneja.com`
5. Click **"Verify"** (Netlify will say it's not yours yet - that's OK!)
6. Click **"Add domain"**

### Step 5: Get Your Netlify DNS Info
Netlify will show you something like:
```
Primary DNS: dns1.p03.nsone.net
Secondary DNS: dns2.p03.nsone.net
```
**WRITE THESE DOWN** or leave the page open!

### Step 6: Update Porkbun DNS
1. Go to **https://porkbun.com** and log in
2. Find **campneja.com** in your domain list
3. Click **"DNS"** or **"Domain Management"**
4. Look for **"Nameservers"** section
5. Change from Porkbun's nameservers to Netlify's:
   - Delete the existing nameservers
   - Add the two Netlify DNS servers you wrote down

**Example:**
```
dns1.p03.nsone.net
dns2.p03.nsone.net
```

6. Click **"Save"** or **"Update"**

### Step 7: Wait for DNS Propagation
- DNS changes take **5 minutes to 48 hours** (usually ~30 min)
- Netlify will automatically set up HTTPS for you
- You can check status at: https://dnschecker.org

---

## 🎉 YOU'RE DONE!

Once DNS propagates, **campneja.com** will show your beautiful site!

### What You Get:
- ✅ Free hosting forever
- ✅ Automatic HTTPS (secure)
- ✅ Instant updates (just drag new files)
- ✅ Custom domain (campneja.com)

---

## 📝 Quick Reference

**Your deployment folder:** `campneja-deploy/`
**Netlify:** https://app.netlify.com
**Porkbun:** https://porkbun.com
**Your Partiful:** PARTIFUL_URL_HERE

---

## 🆘 Troubleshooting

**Images not loading?**
- Make sure you dragged the whole `campneja-deploy` folder, not just index.html

**Domain not working yet?**
- DNS takes time! Check back in 30 minutes
- Verify nameservers are correct in Porkbun

**Need to update the site?**
1. Make changes to files in `campneja-deploy/`
2. Drag the folder to Netlify again (it will update automatically)

---

## 🎯 Next Steps After It's Live

1. Test all links on mobile
2. Share campneja.com with friends!
3. Monitor RSVPs on Partiful

Need help? Let me know! 🏰
