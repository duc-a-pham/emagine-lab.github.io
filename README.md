# EMAGINE Laboratory Website

This is a static GitHub Pages website for Prof. Duc Pham's EMAGINE Laboratory at the University of Cincinnati.

## Maintained Pages

- `index.html`: Home page with the EMAGINE welcome statement, News list, and visitor counters.
- `pi.html`: Principal investigator biography, education, experience, services, peer review, honors, and awards.
- `members.html`: Lab members and recruiting information.
- `research.html`: Research interests and figures.
- `publications.html`: Journal publications.
- `conferences-and-talks.html`: Research talks and conference publications.
- `contact.html`: Email, office, directions, and map.

## Maintained Assets

Local images are stored in `assets/` so the website does not depend on Google Sites after launch:

- `uc-logo.png`: Browser tab favicon.
- `emagine-header.png`: Header logo.
- `emagine-hero.png`: Original Home hero/concept image.
- `emagine-hero-cropped.png`: Cropped Home hero/concept image used on `index.html`.
- `duc-pham-profile-emagine.jpg`: PI profile photo used in the sidebar.
- `emagine-members.png`: Members page graphic.
- `research-ris.png`: Reconfigurable intelligent surface figure.
- `research-rf-security.png`: RF hardware cybersecurity figure.
- `research-ntn-antenna-systems.png`: Non-terrestrial networks antenna figure.
- `research-rf-sensors-wearable-rfid.png`: RF sensors wearable/RFID figure.
- `research-rf-sensors-intermodulation.png`: RF sensors intermodulation figure.

## How To Edit

Open the relevant `.html` file and edit the text directly. Common updates:

- Add News items in `index.html` inside `<ul class="news-list">`.
- Update the Welcome text in `index.html` inside `<div class="page-section intro-section">`.
- Add journal papers in `publications.html` inside `<ol class="pub-full-list">`.
- Add talks or conference papers in `conferences-and-talks.html`.
- Update office, phone, email, or address details in the sidebar blocks shared across pages and in `contact.html`.
- Replace images by keeping the same filename in `assets/`, or update the corresponding `src="assets/..."` reference.

## Preview Locally

From this folder, run a static server and open `http://127.0.0.1:8000/index.html`.

```powershell
python -m http.server 8000 --bind 127.0.0.1
```

## Publish On GitHub Pages

Upload the contents of this folder to a GitHub repository. In GitHub, go to Settings, Pages, and set the deployment source to the branch containing `index.html`.