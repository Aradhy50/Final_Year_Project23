# Change into the directory
cd group-00-web

# Setup backend
cd server && npm install
npm run dev

# Setup frontend
cd client && npm install
npm run serve

## Visual Studio Code (VSCode)

Open the `server` and `client` in separate VSCode workspaces or open the combined [backend-frontend.code-workspace](./backend-frontend.code-workspace). Otherwise, workspace-specific settings don't work properly.

## System Definition (MS0)
This is a booking system for laundry rooms in an apartment building. The system aims to make laundry booking easier for users. A user can easily create, edit and cancel their bookings remotely on their computer or mobile. 

### Purpose

The purpose of this system is to allow registered users to book available laundry rooms remotely. 

### Pages

* Register and login: the user can register and then, with the log in can acces to the laundry system.

* Home: On the home page the user can get an overall view of the system and also view any current bookings. From the home page the user can easily navigate to other pages.  

* Profile: The user can view their details and notifications on the profile page. 

* Booking: On this page the user can view and manage their bookings, i.e create a new one, edit an existing or delete one. 

* Dashboard: The user can view, create and edit notes relevant to other users in the apartment building.
