# Blank Template for ASP.NET MVC 5 and Agility
This is a blank template for Agility MVC5 .NET Framework sites that is based off the vanilla MVC5 template that Microsoft provides.

# Setup
1. Replace the values in the web.config for `{WebsiteName}` and `{SecurityKey}` as well as set the UGC API key and password in `<appSettings>` please contact support@agilitycms.com to get the required fields
2. In your Agility instance, create a Homepage Template, go to Settings -> Page Templates -> New
3. Enter 'Homepage Template' for the <b>Name</b>
4. Select <b>Digital Channel Type</b> as 'Website'
5. Leave <b>Output Type</b> as 'Relative URL'
6. Enter '~/Views/Templates/HomepageTemplate.cshtml' for the <b>Relative URL</b>
7. Add 'CustomContentZone' as a <b>Module Zones</b>
8. In your Agility instance, create a new Page, got to Pages -> + (click to add new page)
9. Select 'Homepage Template' as <b>Page Template</b>
10. Enter 'homepage' as <b>Menu Text</b> and click 'Save'
11. Start the project in Visual Studio

<i>Note: When running the project, if you receive any template errors you can either add the missing templates or remove/update the pages that are using the missing templates. If you chose to remove the templates do not remove the home page just drill down to page's settings and change the selected template</i>
