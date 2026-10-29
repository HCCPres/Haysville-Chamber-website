HAYSVILLE CHAMBER OF COMMERCE WEBSITE STARTER

Files
- index.html: responsive website prototype. Open it in a web browser to preview.
- README.txt: this setup and launch checklist.

WHAT IS INCLUDED
- Responsive homepage and navigation
- Business directory with search and category filter
- Events section
- Membership information
- Membership inquiry/application form that prepares an email in the visitor's email app
- News and photo gallery placeholders
- Contact form that prepares an email

IMPORTANT BEFORE PUBLISHING
1. Replace the sample directory listings in index.html with approved current members in good standing.
2. Review event dates, copy, Chamber mission, and all contact information.
3. Replace gallery tiles with approved photos.
4. Add the official Chamber logo and approved brand colors if available.
5. Add an actual secure online dues payment link from a payment processor. The current prototype does NOT collect card details or process payments.
6. Decide how online forms should be received and stored. The current forms open a visitor's email program and do not submit to a database.
7. Confirm the existing domain registrar, DNS access, and hosting plan before connecting the domain.
8. Add privacy policy, accessibility review, and any required terms before launch.

LOW-COST DEPLOYMENT
This is a static HTML starter, so it can be hosted on a low-cost or free static hosting service. The custom domain may have a separate renewal fee. Domain connection requires access to the domain's DNS settings. Keep the current domain registration active while setting up the replacement website.

DIRECTORY EDITING
Find `const businesses = [` near the bottom of index.html. Add one object per approved member, using:
{name:"Business Name",category:"Professional Services",description:"Short description",phone:"316-555-0100",website:"https://example.com"}

Allowed category labels in the current filter:
Professional Services, Food & Dining, Home & Construction, Health & Wellness, Retail, Community Organization, Other.

EVENTS
The event cards are currently written directly in the HTML. Update the date, title, description, and RSVP details as events are confirmed.

PAYMENTS
Do not ask visitors to enter payment card details into this website. Use a secure payment provider checkout page or invoice payment link and link to it from the Membership section after the Chamber chooses its provider.
