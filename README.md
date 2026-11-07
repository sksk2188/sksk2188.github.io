# OpenMausBot Drive Output — OAuth information site

A public **static informational site** for the owner's private OpenMausBot Google Drive OAuth integration.

**This is not the OpenMausBot server, a Google login page, or a public Drive endpoint.**

## Public pages
- [Homepage](https://sksk2188.github.io/)
- [Privacy policy](https://sksk2188.github.io/privacy.html)
- [Terms of use](https://sksk2188.github.io/terms.html)

## GitHub Pages configuration (owner)
In **Settings → Pages**, select **Deploy from a branch**, branch **main**, folder **/(root)**, then Save.

## Google OAuth setup (owner)
1. Check all three pages are publicly reachable over HTTPS.
2. In Google Search Console, add a **URL-prefix property** for https://sksk2188.github.io/ and use the **HTML file** verification method. Commit the exact Google-provided HTML verification file to the repository root; do not post the verification token in chat.
3. In Google Auth Platform → Branding, provide the verified homepage, privacy and terms links and authorized domain if accepted by Console.
4. In Audience, attempt **In production** publishing. Read the actual Console messages and do not bypass additional Google requirements.
5. After the publishing change is confirmed by Google, complete new OAuth consent using the existing private OMB Desktop PKCE workflow and install the new refresh token.

Never commit Google OAuth credentials, tokens, NAS paths, private OpenMausBot code, or operational evidence.

This site uses no JavaScript, forms, analytics, authentication or Google OAuth callback.
