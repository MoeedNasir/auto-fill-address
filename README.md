# auto-fill-address
A portal feature that automatically fills user address details on the website, improving user experience and reducing  manual entry errors.

Overview:
The Auto-Fill Address Module enhances the Odoo website portal by automatically populating customer address details in forms. This improves the portal user experience, reduces manual input errors, and speeds up the checkout and profile update processes.

Features:
Automatic Address Population – Fetches and fills stored address data for portal users.
Website Portal Integration – Works directly with Odoo’s website and eCommerce forms.
Improved Data Accuracy – Eliminates repeated manual entry and reduces input errors.
Multi-User Support – Ensures each portal user sees their own saved address details.
Customizable Logic – Can be extended to include phone, email, and other contact details.

Module Structure
website_sale_autofill_address/
│── __init__.py
│── __manifest__.py
│── controllers/
│   └── __init__.py
    └── main.py

Installation:
Copy the module folder auto_fill_address into your Odoo addons directory.
Restart the Odoo server:
./odoo-bin -c odoo.conf -d <your_database_name> -u website_sale_autofill_address
Activate Developer Mode in Odoo.
Update the app list and install Auto-Fill Address.

Usage:
Log in as a portal user on the Odoo website.
Navigate to checkout or address forms.
The system will auto-fill saved address details.
Users can edit the pre-filled fields if updates are needed.

Configuration:
Ensure portal users have valid address information stored in their Odoo profile.
Modify portal_address_templates.xml to add or remove fields from the auto-fill logic.

Compatibility:
Odoo 18 Community & Enterprise
Python 3.10+
PostgreSQL 13+

Author:
Developed by Moeed Nasir
Role: Odoo Technical Developer
