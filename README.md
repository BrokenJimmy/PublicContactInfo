# Luke's NFC Contact Card

A mobile-friendly contact landing page with a downloadable vCard, designed for GitHub Pages.

## Publish

1. Upload `index.html` and `luke-simmons.vcf` to the root of `BrokenJimmy/PublicContactInfo` on the `main` branch.
2. In repository **Settings → Pages**, choose **Deploy from a branch**, branch **main**, folder **/(root)**, and **Save**.
3. Once deployment finishes, visit https://brokenjimmy.github.io/PublicContactInfo/ .
4. Program the NFC tag with a **URL/URI** record pointing to that same URL (not the GitHub repository URL).
5. Test on iPhone and Android. The visitor must confirm importing/saving the contact. Browsers may download the VCF first; opening it should present the contact import flow.

## Update

Edit `index.html` and `luke-simmons.vcf` together when contact details change. The NFC URL stays the same.

## Privacy

The email address and phone number are public and can be indexed or collected by bots.
