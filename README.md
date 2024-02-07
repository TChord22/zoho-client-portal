# Client Portal - Zoho Creator
Creating a Client Portal within Zoho Creator is a simple process to follow. All the details provided for you is just to get you started.
Please note that this is based on the Beta Version of the current portal. Feel free to fork this repo and make modifications to your own code in order to expand your needed client portal requirments. 

## The Setup

This setup would assume you have already figured out how to create application on Zoho Creator. If not, feel free to check YouTube or contact zoho support to find out. As this is not really a beginners process.

1. Make sure that you have the following connections made in your Zoho Creator setup
   - Zoho CRM
   - Zoho Desk
   - Zoho Creator
  
Feel free to use Zoho Auth Connection to connect with Zoho Creator & Desk. CRM is provided as out of the box. Creator and Desk should be too, however in this use case we used Zoho Auth.
Please make sure to use the apps names "creator", "desk" and "crm" as your connection, as this will be so much easier to remember when setting up your invoke URL.
2. In this project we have the following
  - 2 Forms
  - 6 Pages
  
You can add whichever in your setup, but our setup covers 1 form for support, 1 form for project briefing, pages for quotes, invoices, profile, and 2 pages for the forms to display on.

The code provided and scripts can be adjusted according to your specific requirements. This is just basic sample coding for each page or workflow within Zoho Creator.

## Table Contents

Right, so you should by now have your pages created and forms. For each of pages, we used the HTML widget, which provided us with the option to customize the look and feel of our portal. I would love to know if you are making adjustments to the code in order to either better what has been provided or to try think outside the box.

1. Support Form Page
2. Breifing Form Page
3. Quotes Page
4. Invoices Page
5. Profile Page (including ticket history)
6. Workflow functions
