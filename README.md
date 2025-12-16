# Contractor Website Template

AstroJS template for generating contractor websites. This template is used by Tightcraft to create static websites for contractors.

## Templates

This template supports two visual styles:

- **classic**: Clean, traditional layout with white background and simple styling
- **bold**: Modern design with navy/orange accents, card-based services, and gradient sections

Set the template in `data.json` using the `template` field.

## Data Structure

Edit `data.json` to customize the website content:

```json
{
  "template": "classic",
  "company_name": "Company Name",
  "tagline": "Your tagline here",
  "phone": "(555) 123-4567",
  "email": "info@example.com",
  "address": "123 Main St, City, ST 12345",
  "trade": "painting",
  "services": [
    { "name": "Service 1", "description": "Description..." }
  ],
  "about": "About text...",
  "cta_text": "Get Your Free Estimate"
}
```

## Development

```bash
npm install
npm run dev
```

## Build

```bash
npm run build
```

Output will be in the `dist/` directory.
