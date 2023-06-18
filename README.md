# Destination Bucket List

Personal private destinations bucket list app, an user can add a private destination to his private bucket list or select a public destination from the public destinations pool which are added by an admin

## Technologies

- .NET (backend)
- React & Vite (frontend)

## Additional Information

### Backend

The backend part of the app uses the .NET framework, the app is running on https, the endpoint are authorized using JWT, except the login part of the app. The app uses a MySQL database using 2 tables: Destinations and Users. 

### Frontend

The frontend part of the app uses the React & Vite technologies, the login dto (username & JWT), are saved in the local storage in order to send requests to the backend part. The design part is made with bootstrap css, mainly icons and buttons, no fancy css moving, responsive.

