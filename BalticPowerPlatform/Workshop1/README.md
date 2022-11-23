# Workshop 1 Assets

Assets form the Workshop 1.

Here you will find the Solution package with the following assets:
  * Cloud Flow which after running will Create "Wnioski" list for you
  * Power Apps which has been configured during workshop
  * Supporting items
    * Environment variables
    * Connection Reference

### How to install Solution

* Download Solution package file
* Go to your tenant - office.com
* Import Solution - How to do it [click here](https://learn.microsoft.com/en-us/power-apps/maker/data-platform/import-update-export-solutions)
    * During the process provide your Connection for Connection Reference
    ![Adding connection references](https://github.com/365CornerDavid/PowerPlatform/blob/master/BalticPowerPlatform/Workshop1/images/2022-11-23_14h35_54.png "Adding connection references")
    * During the process add SharePoint Site URL where you want the list to be created
    * Leave LIST Environment Variable empty
After successfull import

### "Wnioski" list creation
    * Go to the CreateSPO_Wnioski_list cloud flow
    * Make sure it is Turn On
    * Run the Flow
    * Check if the list has been created

### Update of Environment Variabl
*   Select SPO_List_BPP_Wnioski Env Variable and start editing
*   Select freshly created list (Wnioski) as Current value




