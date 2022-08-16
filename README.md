# Ward Handover App
A simple Dataverse for Teams-based canvas app for nurses on a ward to keep basic care information.

This app was born from the need to capture a set of data points about a patient, many of which are not updated hourly in the patient record, but need to be up to date for shift handovers. There is an admin UI for creating new wards, and setting which of the fields tracked in the database are used by each ward. Admins can also configure the beds on a ward, the names of nurse teams working the ward, and which beds are assigned to which teams.

Nurses can "bookmark" the wards they work on most for easy access on the home screen. When choosing a ward, patients are listed with key information at the ward view. When clicking a patient, they can see all the information tracked about patients on that ward. A nurse can transfer the information for a patient to another ward that's using the app because it will only provide options for beds that the app shows are empty.

Ward types and data field names can be changed in the Dataverse tables "Ward Types" and "Ward Fields". 

<img src="ward handover.jpg" alt="Ward Handover App">

<img src="ward handover tables.jpg" alt="Ward Handover Tables in Dataverse for Teams">

## Deployment
In the PowerApps Teams app, on the Build tab, choose the team you want to deploy to. Click "see all" in the list of apps, then click Import in the toolbar. Choose the .zip file you've downloaded from this repository. When import is complete, customize the UI and tables as needed.
