Realization

SOBI 2 is not based on SOBI 1, but it is build up new from the bottom. This was necessary because the table structure of SOBI 1 was not suited for the features "sub-categories", "one entry in multi-categories" and "user definable fields". SOBI 2 uses a relational database structure. The table layout was designed graphically using the Clay Database Modeling UI.
SOBI 2 is build up almost object oriented, but still runs under PHP4 and MySQL4.
Front-end and back-end are separated. For example there are two separate language files available. This simplifies changing only the front-end texts.

Unfortunately, with this SOBI 2 isn't compatible to SOBI 1.
We have realized a lot of the whishes. Some of them are not yet ready in the first release of SOBI 2, such as the promotion feature. We haven't seized all ideas because we have the opinion, that some of them go beyond the scope of this component. Indeed, SOBI 2 isn't longer only a business index, but also a directory component for almost everything, but we had to come to a compromise between possible features and complexity of the configuration.
Category function

  * Multi-Level Categories. That is, each sub-category may have sub-categories. Unlimited nesting depth.
  * One entry can be entered in up to five categories.
  * Fee required for categories is adjustable, with price scaling.
  * Entries can be entered optionally only in the lowest or in all categories.

Entries

  * Adding an image/logo, which will be shown in the V-Card and/or in the Details View.
  * Adding an icon/symbol, which will be shown by default in the upper right corner of the V-Card and/or in the Details View.
  * Meta-Keywords and Meta-Description can be set up by the user.
  * Entries can be published immediately or not before an administrator has checked them.
  * Within the back-end it is selectable which fields are obligatory.
  * Standard fields can be switched off and own fields can be defined (Custom Fields).

Front-End-View

SOBI 2 is divided into three views: the General View (SOBI2 mainpage), the Category View and the Details View. A category view shows all subcategories and entries of a category. A Details View shows only one entry.
The views are almost entirely configurable within the back-end and additionally by changing the view templates.

  * In the General View all main categories can be shown together with an image and a short description.
  * Already in the general view all entries can be shown as V-Cards.
  * A Category View shows the corresponding sub categories and the entries within the category as V-Card.
  * The sorting order of the categories is adjustable within the back-end.
  * The sorting order of the fields is also adjustable (e.g. to change postal code and city for some countries).
  * For each entry two images can be added. One small picture (icon/symbol), which will be shown by default in the V-Cards and the logo image, which will be shown by default in the Details View.
  * The sorting order of the entries is adjustable in the back-end.
  * Templates, editable within the back-end, for Details View and V-Card to design the appearance individually.
  * CSS file, editable within the back-end, for changing the layout easily.
  * Connection to Google Maps possible and routing function.
  * Details View can be configured to be shown only to registered users.

User Edit Function

  * Edit and delete functions for the user.
> > If a user is logged in, he can edit and delete his own entries. Also he is able to move his entry to another category. This functionality can be switched off within the back-end.
  * The user is able to add his entry afterwards to additional categories.
  * If the user selects additional paid options while editing his entry, these fees will be charged.
  * It is adjustable within the back-end, if the delete function really deletes an entry or sets it only to unpublish.

Fee Requirement and Payment

  * All fields (besides the title field) can be set for free or not.
  * Base fee for whole entry.
  * Adding an entry in more than one category can be set for free or not.
  * Currency unit and currency separator are adjustable.
  * Summary of the prices of all selected options at the end of adding an entry.
  * Payment via Paypal and/or showing bank account info.
  * Confirmation email for paid entries.

Email Processing

  * Optional sending of different emails to the user/author depending on the action (on add entry, on change entry, on approve by administrators).
  * Sending an email with payment terms to the user/author and optional to the administrators.
  * Optional sending of different emails to the administrators depending on the action (on add entry, on change entry).
  * User group for system emails selectable.
  * Defining email texts via templates within the back-end.
  * Individualized emails using placeholders.
  * Separate emails for all installed SOBI2 languages.

Search

  * Extended search function using one single search field.
  * Drop Down Lists with all already entered values for all fields possible.
  * Separate drop down lists also for user defined custom fields.
  * Searching within a specific category possible
  * Search parameters are saved within a cookie.
  * Auto search with parameters given in the URL.
  * Searchbot (Plugin) for Standard Mambo/Joomla! search function.

Back-End

The back-end layout of SOBI 2 is divided into several areas, which can be chosen using the left-sided menu. One area is the "Category and Entry Manager". Other areas are the Configuration menu, the Plugins and the About section.

Configuration Menu

  * Fields Manager, which can be used for the following functions:
> > o Seven different field types: textfield, textarea, checkbox, checkbox group, select list, calendar and text code.
> > o Adjusting the length and type of a field: inputbox or textarea, textarea w/o Wysiwig.
> > o Field content as standard text or URL, Email address, linked image or linked media file (video/audio).
> > o Setting up fields in that manner, that they are only shown in the add/edit function but not visible for the visitors. This is for example for statistic functions or for a contact form.
> > o Administrative field. Only the administrator may add content.
> > o Setting up which fields are obligatory.
> > o Adjusting the sorting order of the fields (e.g. to change postal code and city for some countries).
> > o Adjusting, in which view a field should be shown (Category View (V-Card) and/or Details View).
  * The language is selectable (independent of the language setting of the CMS or use the setting of the CMS).
  * The background and the border color for the V-Cards is selectable.
  * Entries may have an expiration date.
  * User IP addresses of set up and changing will be saved.
  * Selectable, if user may choose its background for the entry.

Category and Entry Manager

Selection of category being edited is done via a tree view of all categories. The Manager shows all sub categories and entries of the selected category. If an entry is being edited, it will be checked out. The following can be done using the Manager:

  * Separate listing of all entries
  * Copying and moving categories and entries
  * Adding multiple subcategories at once
  * Adding new categories and entries
  * Editing categories and entries
  * Deleting categories and entries
  * Removing all or single entries from one category
  * Changing the order of categories and entries
  * Setting categories and entries to publish/unpublish
  * Setting entries to approve/unapprove (verification)

Further Functionality

  * Possibility to uninstall the SOBI2 tables from the database. Uninstalling of the component (without tables) will be done using the standard Mambo/Joomla! uninstall function.
  * Version checker to check for the newest SOBI2 version.
  * Possibility to set a debug mode on. In this case all warnings and notices are written to a file or to the screen. The file will be displayed in the back-end. Possibility to delete the log file.

Requirements

  * Joomla! 1.0.12+, 1.5 RC2 or Mambo 4.6.2+, PHP4, MySQL4
  * Save Mode off
  * GD Library installed
  * Java Script activated

Modules available

  * Module showing all categories in tree view or all main categories in flat view.
  * Module showing the latest entries.

Mambots available

  * Expiration plugin.
  * Searchbot.

Plugins available

  * SOBI Gallery - a plugin to show an "unlimited" number of uploaded images in Details View (horizontally or vertically) with Lightbox effect.
  * SOBI Review & Rating - a plugin to vote and comment an entry.
  * SOBI Media - a plugin to show audio or video files (Youtube support).
  * SOBI Radius Search - a plugin to search within a radius of cities.
  * SOBI Download - a plugin to upload and download files.