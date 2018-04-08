# GenerateMenu

Windows console application that prints a menu structure from an XML file 

## Getting Started

To run the application, simply provide the XML file path, and the menu item that needs to be shown as active.

```
c:\GenerateMenu\bin> GenerateMenu.exe “c:\schedAeroMenu.xml” “/Requests/OpenQuotes.aspx”

Home, /Default.aspx
Trips, /Requests/Quotes/CreateQuote.aspx ACTIVE
        Create Quote/Trip, /Requests/Quotes/CreateQuote.aspx
        Open Quotes, /Requests/OpenQuotes.aspx ACTIVE
        Scheduled Trips, /Requests/Trips/ScheduledTrips.aspx
Company, /mvc/company/view
         Customers, /customers/customers.aspx
         Pilots, /pilots/pilots.aspx
         Aircraft, /aircraft/Aircraft.aspx
```
