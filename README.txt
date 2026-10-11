CapDeck website
===============

Open index.html in a browser to view the site. To publish it, upload all
the files and the assets folder to any web host.

Pages
- index.html      homepage
- apply.html      full application: six steps (funding, business, revenue,
                  owner, bank, review and sign), a confirmation, and a
                  reviews section underneath
- signin.html     customer sign-in
- approvals.html  approvals from lending partners, with sorting and
                  offer selection
- assets/         your logo and the hero photo

The application, sign-in and approvals pages are a prototype
----------------------------------------------------------
They look and behave like the real thing in the browser, but nothing is
saved or sent, and each page says so in a bar at the top.

- Application: answers stay in the browser tab. Only the amount, purpose
  and first name are passed to the approvals page, for that tab only.
  The password, Social Security number and EIN are never stored.
- The three review cards are placeholders. Paste in real customer
  reviews (for example from your Google listing) before going live.
- "Connect securely" does not contact a bank, and uploaded statements do
  not leave the visitor's computer.
- Sign-in accepts any email and password.
- The lenders and offers on the approvals page are examples.

To make these work for real customers, a developer needs to add a
server: accounts and passwords, storing applications, a bank-connection
provider such as Plaid, secure document upload, and the link to your
lending partners. Social Security numbers, EINs and bank details must be
sent over HTTPS and stored encrypted. Remove the prototype bar once that
is done.

Before going live
- Replace every item in [SQUARE BRACKETS] with your real text.
- Add your consent and credit-check wording on the last application step.
- Footer and some menu links are placeholders (#about, #privacy and so on).
- Fonts load from Google Fonts, so they need an internet connection.
- To change the blue on the homepage, edit --accent near the top of
  index.html.
