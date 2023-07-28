# FHIR2Cerner
 Code to connect to Cerner FHIR Testbed

TODO
Need to learn about using npm to pull fhir-client.js  to keep up to date


launch-patient.html
Let's create an app that can be called by a patient. (As opposed from an EHR)

index.html
After authentication this file will be called with everything required to run.


++ Set up ++
1. Process requires a publicly accessible web page. Lets use GitHub to Host:

    URL is https://github.com/BenHue/FHIR2Cerner

2. Next we need to setup Cerner FHIR to work with our application
        
    Code Central -> New Application
        Application Name: My FHIR2Cerner *Provider* App    
        Type of Access: Online
        Application Privacy: Public
        Redirect URL:https://github.com/BenHue/FHIR2Cerner/index.html
        Product Family: Millennium (note: can we use Millennium Bulk Data to pull metrics?)
        Select Products: Ignite APIs for Millenium: FHIR R4, All
        Use Product APIs: 
            Encounter: Select All
            Patient: Select All
            Practictioner: Select All
        Patient Prouct APIs:
            Encounter: Select All
            FamilyMemberHistory: Select All
            Immunization: Select All
            Observation: Select All
            Patient: Select All
            Procedure: Select All
            RelatedPerson: Select All

    Cerner responds with: (You have succesfully registered your application:)
    Application ID: 7733d374-f357-4806-8a44-95bf53413708
    Client ID: 050a37b7-119f-4567-8673-db5c21b0484f
    






    


