Wedding Desk (demo)

A single-page wedding planning dashboard: vendor replies and deadlines, a cost comparison with totals, a "what is sorted" checklist, a document list and an email writer with a recipient picker. Colour themes and collapsible sections are built in.

All data is fictional. The couple, vendors, email addresses, phone numbers, address and prices are made up for demonstration.

Run it

It is one static file with no build step and no dependencies.

Open index.html in a browser, or
Host it on GitHub Pages: repository Settings > Pages > Deploy from a branch > main / root.
How it works
Plain HTML, CSS and JavaScript in index.html.
Ticks, amounts and uploaded documents are saved in your browser's localStorage (documents up to 1.5 MB each), so they stay on your device and nothing is sent anywhere.
"Write an email" builds a draft from your key points offline. Nothing is sent from the page.
The same page also runs inside Claude as a published artifact, where state is shared and Claude can write the email in full sentences. The small shim at the top of the file only activates when Claude is not present.
Fonts load from Google Fonts; the page works with fallback fonts if they are blocked.
