ZACKHICKS.COM — PUBLISH TODAY

FILES
Upload this entire folder exactly as provided. Do not upload only index.html.

CLOUDFLARE PAGES — DIRECT UPLOAD
1. Create or sign in to a Cloudflare account.
2. In the dashboard, open Workers & Pages.
3. Choose Create application, then Pages, then Direct Upload.
4. Name the project zackhicks.
5. Upload the ZIP file named zackhicks-standalone-site.zip, or drag the unzipped site folder if the dashboard asks for a folder.
6. Choose Deploy site.
7. Cloudflare will provide a temporary address similar to zackhicks.pages.dev.
8. Open that address and verify the page, images, links, and mobile layout.

CONNECT ZACKHICKS.COM
1. In the Cloudflare Pages project, open Custom domains.
2. Select Set up a domain.
3. Enter zackhicks.com.
4. Cloudflare requires the apex domain to be a Cloudflare zone. Follow the prompts to add zackhicks.com to Cloudflare.
5. Cloudflare will display two assigned nameservers.
6. Sign in to Porkbun.
7. Open Domain Management for zackhicks.com.
8. Replace the current authoritative nameservers with the two Cloudflare nameservers.
9. Save the change.
10. Return to Cloudflare and wait for the domain to become Active.
11. In the Pages project, also add www.zackhicks.com as a custom domain.

IMPORTANT EMAIL CHECK
Changing nameservers moves DNS management to Cloudflare. Before changing them, make sure Cloudflare imported any existing MX and TXT records used by your email. Compare the Cloudflare DNS records with the current Porkbun DNS records. Do not continue until the email records are present.

AFTER THE SITE IS LIVE
1. Test zackhicks.com and www.zackhicks.com.
2. Test the LinkedIn button and every article/video link.
3. Open the site on a phone.
4. Add zackhicks.com to your LinkedIn contact information.
5. Set up Google Search Console and submit:
   https://zackhicks.com/sitemap.xml
6. Set up Bing Webmaster Tools and submit the same sitemap.

MONTHLY PERSPECTIVE UPDATE
1. Duplicate the existing file in the perspectives folder.
2. Rename it with a short descriptive URL.
3. Replace the title, date, description, article text, question, canonical URL, and Article JSON-LD.
4. Add a preview and link on index.html.
5. Add the new URL to sitemap.xml and update its date.
6. Upload the updated site as a new Cloudflare Pages deployment.

The site does not display an email address. Contact is directed to LinkedIn.
