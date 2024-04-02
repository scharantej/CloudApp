## Flask Application Design for Google Cloud Consulting Website

### HTML Files
- **home.html:** Main landing page of the website, showcasing services and case studies.
- **services.html:** Comprehensive list of consulting services offered by Google Cloud Consulting.
- **case-studies.html:** Collection of successful implementation examples of Google Cloud services.
- **contact.html:** Contact form for potential clients to request consultations or additional information.

### Routes
- **/:** Home page (displays the content of `home.html`).
- **/services:** Services page (displays the content of `services.html`).
- **/case-studies:** Case Studies page (displays the content of `case-studies.html`).
- **/contact:** Contact page (displays the content of `contact.html`).
- **/submit_contact:** Route for handling contact form submissions, typically performing actions like sending an email or storing the data in a database.