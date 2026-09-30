ASA TUK website (plain HTML, CSS and JavaScript, no build step)

VIEW:   double-click index.html
EDIT:   open this folder in VS Code and edit the .html files
PUBLISH: drag this whole folder onto netlify.com/drop, or upload it to GitHub Pages

PAGES
  index, about, events, projects, gallery, news, leadership, join, faq, contact
  thanks.html (shown after a form is sent) and 404.html (page not found)

FORMS AND EMAIL NOTIFICATIONS (Join + Contact)
  Both forms post to Formspree (https://formspree.io/f/xgavdqkb) and work on any host,
  including Netlify, GitHub Pages and an opened local file.
  Every registration or message is emailed to the address on your Formspree account and is
  also stored in the Formspree dashboard (Submissions, exportable to CSV).
  Registrations arrive with the subject "ASA TUK website: new membership registration";
  replying goes straight to the person who signed up.
  The first submission may ask you to confirm the form in Formspree. To change who gets the
  emails, edit the recipients in the Formspree form settings (no code change needed).
  If a visitor's connection fails, the form offers to open their email app instead.

EMAIL: replace asatuk@students.tukenya.ac.ke in the pages, and in the data-mailto
  attribute of the two forms (join.html, contact.html), with your real address.

CONTENT TO REPLACE (all marked TBC / sample)
  events.html      dates for each event
  leadership.html  names of the committee (duplicate a card for more people)
  projects.html    project cards
  news.html        posts (copy an <article class="post"> block)
  gallery.html     photos: put files in assets/photos/ and swap in an <img> (comment shows how)
  faq.html         answers, e.g. membership fee

FILES
  assets/style.css  base styles     assets/extra.css  nav, forms, new pages, animations
  assets/site.js    menu, animations, forms, lightbox     assets/search.js  site search
  Animations switch off automatically for visitors who prefer reduced motion.
