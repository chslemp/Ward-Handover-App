# Ward Handover App
A simple Dataverse for Teams-based canvas app for nurses on a ward to keep basic care information.

This app was born from the need to capture a set of data points about a patient, many of which are not updated hourly in the patient record, but need to be up to date for shift handovers. There is an admin UI for creating new wards, and setting which of the fields tracked in the database are used by each ward. Admins can also configure the beds on a ward, the names of nurse teams working the ward, and which beds are assigned to which teams.

Nurses can "bookmark" the wards they work on most for easy access on the home screen. When choosing a ward, patients are listed with key information at the ward view. When clicking a patient, they can see all the information tracked about patients on that ward. A nurse can transfer the information for a patient to another ward that's using the app because it will only provide options for beds that the app shows are empty.

Ward types and data field names can be changed in the Dataverse tables "Ward Types" and "Ward Fields". 

<img src="ward handover.jpg" alt="Ward Handover App">

<img src="ward handover tables.jpg" alt="Ward Handover Tables in Dataverse for Teams">

## Deployment
In the PowerApps Teams app, on the Build tab, choose the team you want to deploy to. Click "see all" in the list of apps, then click Import in the toolbar. Choose the .zip file you've downloaded from this repository. When import is complete, customize the UI and tables as needed.

## Legal notice
This app template is provided under the MIT License terms. In addition to these terms, by using this app template you agree to the following:

You, not Microsoft, will license the use of your app to users or organization.

This app template is not intended to substitute your own regulatory due diligence or make you or your app compliant with respect to any applicable regulations, including but not limited to privacy, healthcare, employment, or financial regulations.

You are responsible for complying with all applicable privacy and security regulations including those related to use, collection and handling of any personal data by your app. This includes complying with all internal privacy and security policies of your organization if your app is developed to be sideloaded internally within your organization. Where applicable, you may be responsible for data related incidents or data subject requests for data collected through your app.

Any trademarks or registered trademarks of Microsoft in the United States and/or other countries and logos included in this repository are the property of Microsoft, and the license for this project does not grant you rights to use any Microsoft names, logos or trademarks outside of this repository. Microsoft’s general trademark guidelines can be found here.

If the app template enables access to any Microsoft Internet-based services (e.g., Office365), use of those services will be subject to the separately-provided terms of use. In such cases, Microsoft may collect telemetry data related to app template usage and operation. Use and handling of telemetry data will be performed in accordance with such terms of use.

Use of this template does not guarantee acceptance of your app to the Teams app store. To make this app available in the Teams app store, you will have to comply with the submission and validation process, and all associated requirements such as including your own privacy statement and terms of use for your app.
