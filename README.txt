CULTIVARA WEBSITE
=================
Where freshness grows.

Cultivara is a controlled environment agriculture (CEA) farming company.
This is the company's commercial website. It lets business customers
browse crop categories and submit a bulk enquiry (quantity, crop category,
variety, packaging and quality requirements).


FILES
-----
cultivara-website.html   The complete website (single file: HTML, CSS, JS)
README.txt               This file
LICENSE.txt              Usage terms


HOW TO PUBLISH THE WEBSITE
--------------------------
1. Buy or use your domain (for example cultivara.co.in) and any normal
   web hosting plan.
2. Rename cultivara-website.html to index.html.
3. Upload index.html to the root (public_html / www) folder of your host.
4. Open your domain in a browser and test the page on mobile and desktop.

No build tools or installation are needed.


HOW TO UPDATE CONTACT DETAILS
-----------------------------
Open the file in a text editor and search for these items:

  sales@cultivara.co.in   Sales email (top bar, footer, enquiry buttons)
  +91 86182 69246         Phone number (top bar, footer)
  918618269246            WhatsApp number (digits only, with country code)
  NH-66, Karavali Bypass  Company address (footer)

The email, phone and WhatsApp values for the enquiry buttons are set on
one line near the end of the file, beginning with: var CONTACT=


HOW THE ENQUIRY FORM WORKS
--------------------------
- The customer fills in the form and clicks "Review my enquiry".
- A summary is shown. The customer can then send it using "Send by email"
  (opens their email app, addressed to sales@cultivara.co.in), "Send on
  WhatsApp", or "Copy enquiry".
- IMPORTANT: The form does not send anything to a server by itself.
  An enquiry is only received if the customer completes the email or
  WhatsApp step.

To receive enquiries automatically (recommended for live use), connect
the form to a form service such as Formspree, Web3Forms or Formsubmit,
or to a Google Apps Script that saves entries to a Google Sheet and
emails you. This needs a small change to the form's submit code.


CROP CATEGORIES AND VARIETIES
-----------------------------
Categories and varieties are listed in the CROPS block in the script.
Edit the names there to add, remove or rename crops; the website cards
and the form dropdowns update automatically.


DESIGN
------
Brand colours:
  Deep green  #0F3D2E
  Mid green   #2F9E6B
  Lime        #8CC63F
  Ivory       #F6F4EC
Font: Outfit (loaded from Google Fonts, so an internet connection is
needed to display it; the site falls back to Helvetica/Arial otherwise).
The site is fixed to a light theme to keep the brand colours consistent.


CONTENT NOTE
------------
Website text uses general claims (year-round supply, consistent quality,
custom packaging). Please confirm all claims match what Cultivara can
actually deliver before publishing, and add certifications only once held.


CONTACT
-------
Cultivara
NH-66, Karavali Bypass, Post Ambalapady,
Udupi, Karnataka - 576103
Email: sales@cultivara.co.in
Phone: +91 86182 69246
