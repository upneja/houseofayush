# Connect campneja.com to Your Netlify Site

Your Netlify site: **https://earnest-duckanoo-d41f2b.netlify.app/**

Let's connect your custom domain in 2 parts!

---

## PART 1: Add Domain in Netlify (5 steps)

### Step 1: Go to Your Site Settings
1. Go to: **https://app.netlify.com**
2. Click on your site: **earnest-duckanoo-d41f2b**
3. You should see your site dashboard

### Step 2: Add Custom Domain
1. Look for **"Domain settings"** or **"Set up a custom domain"** button
   - It's usually at the top or in the left sidebar under "Domain management"
2. Click **"Add custom domain"** or **"Add domain"**

### Step 3: Enter Your Domain
1. Type: **campneja.com** (without www)
2. Click **"Verify"** or **"Add domain"**
3. Netlify will say something like "This domain is already registered"
4. Click **"Yes, add domain"** or **"Add domain anyway"**

### Step 4: Also Add www Version (Optional but Recommended)
1. Click **"Add domain alias"** or **"Add another domain"**
2. Type: **www.campneja.com**
3. Click **"Add"**
4. Set one as primary (I recommend **campneja.com** without www)

### Step 5: Check DNS Instructions
Netlify will now show you DNS settings. You'll see something like:

**Option A: Netlify DNS (Easier)**
```
Use these nameservers:
dns1.p08.nsone.net
dns2.p08.nsone.net
dns3.p08.nsone.net
dns4.p08.nsone.net
```

**OR Option B: External DNS (Keep Porkbun DNS)**
```
Create an A record pointing to: 75.2.60.5
```

**I RECOMMEND OPTION A (Netlify DNS)** - it's simpler and handles everything automatically.

**COPY THOSE NAMESERVERS** - you'll need them for Porkbun!

---

## PART 2: Update Porkbun (4 steps)

### Step 1: Log into Porkbun
1. Go to: **https://porkbun.com/account/domain**
2. Log in with your Porkbun credentials

### Step 2: Find Your Domain
1. You should see **campneja.com** in your domain list
2. Click on **campneja.com** or click **"Details"** next to it

### Step 3: Update Nameservers
1. Look for **"Authoritative Nameservers"** section
   - It might be under "DNS" or "Nameservers" tab
2. You'll see current nameservers (probably Porkbun's like `curitiba.ns.porkbun.com`)
3. Click **"Edit"** or **"Change Nameservers"**
4. **DELETE** the existing Porkbun nameservers
5. **ADD** the Netlify nameservers you copied (should be 4 of them):
   ```
   dns1.p08.nsone.net
   dns2.p08.nsone.net
   dns3.p08.nsone.net
   dns4.p08.nsone.net
   ```
   *(Your actual nameservers might have different numbers - use what Netlify gave you!)*

### Step 4: Save Changes
1. Click **"Submit"** or **"Update"** or **"Save"**
2. Porkbun might ask you to confirm - click **"Yes"** or **"Confirm"**

---

## PART 3: Wait for DNS Propagation

### What Happens Now:
- DNS changes take **30 minutes to 48 hours** (usually works in 30-60 min)
- Netlify will automatically detect the change
- Netlify will automatically set up **HTTPS** (the padlock/secure connection)

### How to Check:
1. Wait 30 minutes
2. Try visiting: **campneja.com** and **www.campneja.com**
3. You can also check propagation at: **https://dnschecker.org**
   - Enter: `campneja.com`
   - Type: `A` or `NS`
   - Click "Search"

### Signs It's Working:
- ✅ campneja.com redirects to your site
- ✅ You see a padlock (HTTPS) in the browser
- ✅ Netlify shows "Domain is live" with a green checkmark

---

## 🆘 Troubleshooting

### "Domain verification failed" in Netlify
- This is normal! Just click "Add domain anyway" - you own it, so it's fine

### Images not showing on the Netlify URL
- Did you drag the whole `campneja-deploy` folder or just index.html?
- The folder should contain both `index.html` AND the `campnejapics` folder

### Domain not working after 2+ hours
- Double-check the nameservers in Porkbun match what Netlify gave you EXACTLY
- Make sure you saved the changes in Porkbun
- Try clearing your browser cache (Cmd+Shift+R)

### "Mixed content" or "Not secure" warnings
- Wait for Netlify to provision HTTPS (can take up to 24 hours, usually <1 hour)
- Check in Netlify under "Domain settings" → "HTTPS" → Should say "Certificate active"

---

## 📸 Visual Guide (Where to Click)

### In Netlify:
```
Site dashboard → Domain settings → Add custom domain →
Enter "campneja.com" → Add domain
```

### In Porkbun:
```
Domain list → campneja.com → Details →
Authoritative Nameservers → Edit →
Delete old nameservers → Add Netlify nameservers → Submit
```

---

## ✅ Success Checklist

- [ ] Added campneja.com in Netlify
- [ ] Copied Netlify nameservers
- [ ] Updated nameservers in Porkbun
- [ ] Saved changes in Porkbun
- [ ] Waited 30+ minutes
- [ ] campneja.com loads your site!
- [ ] HTTPS (padlock) is showing

---

## 🎉 Once It's Live

Your site will be at:
- **campneja.com** ← Main URL
- **www.campneja.com** ← Also works
- ~~earnest-duckanoo-d41f2b.netlify.app~~ ← Still works but use your domain!

---

**Need help with any step? Just ask! I'll walk you through it.** 🏰
