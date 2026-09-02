1. Navigate to https://console.cloud.google.com/.  and from the left hamburger menu go to `API & Service` => `Enabled APIs & services` . Playstore will ask to create prject: Create a project named `Naya Sahar`


2. Now Search for `Google Play Android Developer API`, click it and Enable it 
<img width="1364" height="622" alt="Screenshot 2026-09-02 at 07 46 53" src="https://github.com/user-attachments/assets/a7e4b76e-f016-4f9c-adf6-0ae8771761d9" />



3. Click on Left menu and go inside `IAM & Admin` => `Service Account`
<img width="1217" height="614" alt="Screenshot 2026-09-02 at 07 54 19" src="https://github.com/user-attachments/assets/2785732d-8e45-4e70-ad56-6e9809fe1066" />

Here, Create a service account . No need for any Permission or role here

<img width="903" height="614" alt="Screenshot 2026-09-02 at 07 55 12" src="https://github.com/user-attachments/assets/6456b25e-1df5-4f96-98ef-d22a22d74033" />



4. Still in Google Cloud Console:

- Click the service account you just created (in the list).
- Go to the Keys tab.
- Add key → Create new key → key type: JSON → Create.
- A `.json` file downloads — this is the file EAS needs. Save it now; you can create a new key later but can't re-download this exact one.

<img width="1209" height="651" alt="Screenshot 2026-09-02 at 08 00 21" src="https://github.com/user-attachments/assets/0fe0837c-90a2-4a69-a4a7-e2f555dcb06e" />

Also, copy the newly auto created service email address as it's needed in step 5

<img width="1038" height="656" alt="Screenshot 2026-09-02 at 08 18 25" src="https://github.com/user-attachments/assets/30ae3ead-af92-4c9e-aa1b-fc31a99073ff" />

5. Go to play console.  https://play.google.com/console/
- And go to `Users and permisssions` => Invite User
- Enter the email address you copied in Step 4.
- Grant permissions. Use the "Account permissions" tab and check `Admin` for `App Access` and then Invite User

<img width="1506" height="819" alt="Screenshot 2026-09-02 at 21 48 35" src="https://github.com/user-attachments/assets/f398d929-1307-43c2-b841-3e6d7d19e33f" />


7. 
