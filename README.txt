Country Offer PWA — GA4 FIXED

Google Analytics 4 Measurement ID:
G-88HKRVYB4R

Target Netlify site:
asiadeals.netlify.app

What was fixed:
1. The Google tag is now installed directly inside <head>, using the standard Google Analytics installation.
2. The previous dynamic GA loader was removed to avoid tag-detection problems.
3. offer_click tracking is preserved for Malaysia, Singapore and Bangladesh.
4. The PWA service-worker cache was bumped/cleaned so an older cached index.html is less likely to hide the new tag.
5. Existing offer links were NOT changed.

After deployment:
- Open https://asiadeals.netlify.app
- Test a few pages/buttons.
- In GA4, open Reports > Realtime.
- Google notes that data collection can take up to about 30 minutes to begin.

Important:
The GA4 Web Stream URL shown in Google Analytics should match the actual website domain. If the stream currently says publisherhufb.netlify.app while the live site is asiadeals.netlify.app, edit the web stream details in Google Analytics to use the actual live URL.
