# airvat-admin-db-seed

This repository will allow you to seed the firebase realtime database with realistic airvat like data including users, receipts, trips etc. 

1. Once cloned, run ```npm i``` in the root directory. 

2. Update the firebase-config.js file with your credentials from firebase for adminConfig. 

3. Update any of the following constants to match your needs: 
```
const MAX_TRIPS_PER_USER = 3; 
const MAX_RECEIPTS_PER_TRIP = 10;
const MAX_RECEIPT_ITEMS_PER_RECEIPT = 10;
const USERS_TO_CREATE = 2;
```

4. Run ```npm start``` to start seeding your db.
