# Open Graph Images

These are the preview images shown when pages are shared on WhatsApp, Facebook, LinkedIn etc.

## Required files

| Filename | Used on |
|---|---|
| `home.jpg` | Homepage (default fallback for all pages too) |
| `office-relocation.jpg` | /services/office-relocation |
| `corporate-moving.jpg` | /services/corporate-relocation |
| `after-hours-moving.jpg` | /services/after-hours-moving |
| `furniture-moving.jpg` | /services/office-furniture-moving |
| `decommissioning.jpg` | /services/office-decommissioning |
| `home-moving.jpg` | /services/home-moving |
| `nakasero.jpg` | /service-areas/kampala/nakasero |
| `kololo.jpg` | /service-areas/kampala/kololo |
| `ntinda.jpg` | /service-areas/kampala/ntinda |

## Spec
- **Size:** 1200 × 630 px (required — WhatsApp/Facebook crop to this exactly)
- **Format:** JPEG, 85% quality
- **Content:** Brand logo + page title text + a relevant photo background
- **Text on image:** Keep it short — company name + page topic

## How to add them
Save each file here, then update the `image` prop in each page's `<BaseLayout>` call:
```astro
<BaseLayout
  title="..."
  description="..."
  image="/og/office-relocation.jpg"   ← add this line
>
```
