# OCA Website

This repository contains **16** OCA packages for website.

## Packages Included (16 packages)

- **odoo-bringout-oca-website-website_analytics_matomo** - From website: website_analytics_matomo
- **odoo-bringout-oca-website-website_cookiebot** - From website: website_cookiebot
- **odoo-bringout-oca-website-website_cookiefirst** - From website: website_cookiefirst
- **odoo-bringout-oca-website-website_crm_privacy_policy** - From website: website_crm_privacy_policy
- **odoo-bringout-oca-website-website_crm_quick_answer** - From website: website_crm_quick_answer
- **odoo-bringout-oca-website-website_form_require_legal** - From website: website_form_require_legal
- **odoo-bringout-oca-website-website_forum_subscription** - From website: website_forum_subscription
- **odoo-bringout-oca-website-website_google_tag_manager** - From website: website_google_tag_manager
- **odoo-bringout-oca-website-website_legal_page** - From website: website_legal_page
- **odoo-bringout-oca-website-website_menu_by_user_status** - From website: website_menu_by_user_status
- **odoo-bringout-oca-website-website_odoo_debranding** - From website: website_odoo_debranding
- **odoo-bringout-oca-website-website_recaptcha_v2** - From website: website_recaptcha_v2
- **odoo-bringout-oca-website-website_require_login** - From website: website_require_login
- **odoo-bringout-oca-website-website_snippet_country_dropdown** - From website: website_snippet_country_dropdown
- **odoo-bringout-oca-website-website_snippet_country_phone_code_dropdown** - From website: website_snippet_country_phone_code_dropdown
- **odoo-bringout-oca-website-website_whatsapp** - From website: website_whatsapp


## Installation

Install any package from this category:

```bash
# Install from local directory
pip install packages/oca-website/PACKAGE_NAME/

# Install in development mode  
pip install -e packages/oca-website/PACKAGE_NAME/

# Using uv (recommended for speed)
uv add packages/oca-website/PACKAGE_NAME/
```

## Repository Structure

Each package in this repository follows the standard Odoo addon structure:

```
oca-website/
├── odoo-bringout-oca-PROJECT-ADDON/
│   ├── ADDON_NAME/           # Complete addon code
│   │   ├── __init__.py
│   │   ├── __manifest__.py
│   │   └── ... (models, views, etc.)
│   ├── pyproject.toml        # Python package configuration
│   └── README.md            # Package documentation
└── ...
```

## Contributing

These packages are maintained as part of the [OCA (Odoo Community Association)](https://github.com/OCA) ecosystem.

## License

Each package maintains its original license as specified in the OCA repositories.
