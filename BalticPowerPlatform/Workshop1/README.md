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
    ![Adding Env Variable](https://github.com/365CornerDavid/PowerPlatform/blob/master/BalticPowerPlatform/Workshop1/images/2022-11-23_14h43_07.png "Adding Env Variable")
    * Leave LIST (SPO_List_BPP_Wnioski) Environment Variable empty
After successfull import

### Creation of the "Wnioski" list
* Go to the CreateSPO_Wnioski_list cloud flow
* Make sure it is Turn On
* Run the Flow
* Check if the list has been created

### Update of Environment Variabl
*   Select SPO_List_BPP_Wnioski Env Variable and start editing
*   Select freshly created list (Wnioski) as Current value
![Adding List to Env Variable](https://github.com/365CornerDavid/PowerPlatform/blob/master/BalticPowerPlatform/Workshop1/images/2022-11-23_14h49_23.png "Adding List to Env Variable")

### Run the App
* After adding the List Env Variable you can run the application
* Initally you will see blank screen
* Click + icon to create new test item

## Job done ^^

Hope we will see you at the second Workshop.

Next event is scheduled for 25.11.2022.
### [Register here](https://www.eventbrite.com/e/baltic-power-platform-community-event-tickets-468290588757?aff=erelexpmlt)



