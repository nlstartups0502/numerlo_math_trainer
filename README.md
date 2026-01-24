# Updated Legal Documents for Numerlo - Math Trainer

## What's Included

This package contains 4 updated legal documents for your app with subscription features:

1. **privacy-policy.md** - Updated Privacy Policy (Markdown)
2. **terms-of-service.md** - Updated Terms of Service (Markdown)
3. **privacy.html** - Updated Privacy Policy (HTML)
4. **terms.html** - Updated Terms of Service (HTML)

## What's Changed

### Privacy Policy Updates:
✅ Added section on local data storage (games, streaks, subscription status)
✅ Added section on subscription verification with Apple
✅ Clarified that payment info goes to Apple, not you
✅ Added explanation of Free vs Premium tiers
✅ Updated date to January 24, 2026

### Terms of Service Updates:
✅ Added complete subscription terms section
✅ Added pricing details ($4.99/month, $49.99/year)
✅ Added 7-day free trial terms
✅ Added payment and renewal terms
✅ Added cancellation and refund policies
✅ Added promotional offers section
✅ Added service tiers (Free vs Premium) details
✅ Updated license to use section (no circumventing subscription)
✅ Updated date to January 24, 2026

## Where to Place These Files

### In Your GitHub Repository:

**Markdown Files (for GitHub):**
```
/legal/privacy-policy.md  ← Replace with new privacy-policy.md
/legal/terms-of-service.md  ← Replace with new terms-of-service.md
```

**HTML Files (for website/app hosting):**
```
/docs/privacy.html  ← Replace with new privacy.html
/docs/terms.html  ← Replace with new terms.html
```

## How to Update

### Option 1: Manual Upload
1. Go to your GitHub repository
2. Navigate to `/legal/` folder
3. Click on `privacy-policy.md`
4. Click "Edit" (pencil icon)
5. Delete all content
6. Copy and paste content from new `privacy-policy.md`
7. Commit changes
8. Repeat for all 4 files

### Option 2: Git Command Line
```bash
# Navigate to your repo
cd numerlo_math_trainer-main

# Copy new files
cp /path/to/privacy-policy.md legal/privacy-policy.md
cp /path/to/terms-of-service.md legal/terms-of-service.md
cp /path/to/privacy.html docs/privacy.html
cp /path/to/terms.html docs/terms.html

# Commit and push
git add legal/privacy-policy.md legal/terms-of-service.md docs/privacy.html docs/terms.html
git commit -m "Update legal documents for subscription features"
git push origin main
```

## After Updating GitHub

### Update App Store Connect:

1. Go to App Store Connect
2. Click on your app
3. Go to "App Information"
4. Verify these URLs are correct:
   - Privacy Policy URL: `https://yourusername.github.io/numerlo_math_trainer-main/docs/privacy.html`
   - Terms & Conditions URL: `https://yourusername.github.io/numerlo_math_trainer-main/docs/terms.html`
5. Save changes

### Update In-App Links:

Make sure your app links to the updated documents:
- Settings page should link to Privacy Policy
- Subscription page should link to Terms of Service
- Both should open the HTML versions from your GitHub Pages

## Important Notes

### Apple Review:
- Apple reviews your Terms & Privacy Policy during app review
- Make sure the policies match your app's actual functionality
- Subscription apps are scrutinized more closely
- Having accurate, complete policies helps avoid rejection

### Required Disclosures:
✅ Subscription pricing clearly stated
✅ Auto-renewal clearly stated
✅ Cancellation process clearly stated
✅ Free trial terms clearly stated
✅ What data you collect (or don't collect)
✅ How payments are processed (through Apple)

### Legal Compliance:
- These documents are templates and should be reviewed by a lawyer if:
  - Your app generates significant revenue
  - You're targeting specific regulated markets
  - You want extra legal protection
- For a small indie app, these templates are sufficient for App Store approval

## URLs You'll Need

### For App Store Connect:
Replace `yourusername` with your actual GitHub username:

**Privacy Policy URL:**
```
https://yourusername.github.io/numerlo_math_trainer-main/docs/privacy.html
```

**Terms of Service URL:**
```
https://yourusername.github.io/numerlo_math_trainer-main/docs/terms.html
```

### For In-App Links:
Use the same URLs in your app's Settings page and Subscription page.

## Testing

After uploading, test that:
1. ✅ GitHub Pages are serving the HTML files correctly
2. ✅ Links in App Store Connect work
3. ✅ Links in your app open correctly
4. ✅ Documents display properly on mobile devices
5. ✅ All sections are present and readable

## Questions?

If you have questions about these documents:
- Legal questions: Consult a lawyer
- Technical questions: Contact freelance.actuary.nl@gmail.com
- App Store questions: Check Apple's App Store Review Guidelines

## Last Updated

All documents updated: January 24, 2026

These documents reflect the current app features:
- Freemium model (Free tier: 3 games/day)
- Premium subscription ($4.99/month or $49.99/year)
- 7-day free trial
- Apple In-App Purchases
- No personal data collection
- Local data storage only

---

**Ready to upload? Follow the steps above and you're good to go!**
