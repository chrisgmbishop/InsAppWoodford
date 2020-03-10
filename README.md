# InsAppWoodford

Repository for Woodford Inspection application development

## How does it work
Connect to your CRM server and start Woodford. Create an app project (= a customization, i.e., the way you want the mobile app to look and work). Once you save the changes you make, these are saved on the backend server in custom Resco entities, which are created at the first start of Woodford.

When you publish the project, the customization becomes active and available to be downloaded to Resco mobile apps. When the app synchronizes with your backend system (be it Microsoft Dynamics, Salesforce, Resco Cloud), it downloads the project, available for the user’s security role and downloads/uploads data.

## Key concepts
Develop once – deploy everywhere
The development of mobile apps is platform-agnostic. The apps are configured once and the same configuration is used for all platforms and devices.
## Adaptable UI
The user interface adapts automatically to different screen sizes, formats, and aspect ratios. It looks great on a phone, on a tablet, or even in your browser. Everything is managed by Resco app and no manual customization is needed.
## Availability and installation
An HTML version of Woodford is available on all major platforms and browsers, including Mac OS and the Safari web browser. Former stand-alone application is no longer updated.

Using Woodford requires a SuperUser (Administrator) license.

## Microsoft Dynamics
### If you are using Microsoft Dynamics:

Go to Woodford download page: www.resco.net/woodford-overview.
1. Depending on your Dynamics version, download the appropriate solution file:
2. If you are using Microsoft Dynamics CRM 2011, click Woodford for Dynamics 2011 Download (direct link).
3. If you are using a newer version, click Woodford for Dynamics Download (direct link).
4. Log in to your Dynamics CRM as a system administrator.
5. Go to the Solutions section of your CRM server settings.
6. Click Import and select the downloaded Woodford zip file.
7. Finish the import wizard.
8. Publish all customizations.
9. Reload the Dynamics webpage (often, this can be accomplished by pressing F5).
10. Woodford is now available in the CRM Settings, under MobileCRM section.

Please see your Dynamics documentation if you need more information about how to upload solution packages or publish customizations.

## Updating Woodford
If you need to update your Woodford solution to a new version, we recommend the following:

**First, back up your Woodford projects.**
Use the procedure for new installation; however, you need to perform an additional step during the solution import wizard. Dynamics detects that the solution package contains an update for a solution that is already installed. Select Maintain customizations (recommended).
