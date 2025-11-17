# Physioactif Schema.org Structured Data

This repository hosts Schema.org JSON-LD structured data for the Physioactif website.

## 📁 Structure

```
/fr/          - French language schemas (430 files)
/en/          - English language schemas (430 files)
```

## 🔗 Usage

These schemas are served via GitHub Pages and referenced by the Physioactif Webflow site through registered hosted scripts.

Example URL format:
```
https://USERNAME.github.io/physioactif-schemas/fr/homepage.json
https://USERNAME.github.io/physioactif-schemas/fr/clinique/chomedey.json
```

## 🚀 Deployment

1. Schemas are committed to this repository
2. GitHub Pages automatically serves them
3. Webflow API registers these as hosted scripts
4. Scripts are applied to individual pages

## 📝 Maintenance

Update schemas by:
1. Modifying JSON files in this repository
2. Committing changes
3. GitHub Pages will auto-update (usually within 1-2 minutes)

## ⚙️ Technical Details

- **Format**: JSON-LD
- **Schema vocabulary**: https://schema.org
- **Validation**: All schemas validated before upload
- **CDN**: Served via GitHub Pages CDN
- **HTTPS**: Automatically enabled

## 📄 License

These schemas are proprietary to Physioactif.
