# Quick Shift Kampala — Image Folders

Drop your real photos into the subfolders below.
All images in `public/` are served at the root URL, e.g. `/images/team/john.jpg`.

## Folder guide

### `/images/team/`
Photos of the Quick Shift crew.
- Suggested filenames: `crew-1.jpg`, `manager-david.jpg`, etc.
- Recommended size: 800×800px, square crop, JPEG 80% quality

### `/images/trucks/`
Photos of the branded moving trucks / vehicles.
- Suggested filenames: `truck-1.jpg`, `truck-loading.jpg`
- Recommended size: 1200×800px, JPEG 80% quality

### `/images/projects/`
Before/after photos of completed office moves.
- Suggested filenames: `nakasero-office-move.jpg`, `kololo-ngo-relocation.jpg`
- Recommended size: 1200×800px, JPEG 80% quality

### `/images/clients/`
Client logos (PNG with transparent background preferred).
- Suggested filenames: `client-acme.png`, `client-ngo-name.png`
- Recommended size: 400×200px, PNG

---

## How to replace the Unsplash placeholders

Every page currently uses Unsplash URLs like:
`https://images.unsplash.com/photo-xxx?w=1600&q=80`

Once you have real photos, replace those URLs in the `.astro` files with local paths:
`/images/projects/nakasero-office-move.jpg`

Search for `images.unsplash.com` across the `src/pages/` folder to find every instance.
