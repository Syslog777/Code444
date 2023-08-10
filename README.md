# Code444

Business Requirements (Why make this app?)
Client needs this app to coordinate communication between drivers and passengers
This app is similar to Uber but different in payment structure. Driver pays a monthly fee instead of a fee for every ride.
This business model is much more attractive than pay-per-match.

User Requirements (Who needs this app?)
People who want to save money need this app. The name of the app is not yet final.

System Requirements (How to make this app?)
We will use FlutterFlow and Firebase to make a mock-up version of the app. In the future we will use Flutter and Firebase for the commercial version of the app.

Product Requirements (What does this app need to be able to do?)
Focus on the UX/UI for now. We will do backend later.
1. Login page: users should be able to login using google or apple account
2. Passenger or Driver? page. Two button, user chooses one and it takes them to the app store if press choose driver button. Passenger button simply takes them to the next app view
3. Choose a payment method page. We will accept credit via Stripe/debit via Stripe/google pay/Paypal
4. The next view will ask for their location and will use autocomplete, implement this with googl. The backend will integrate Google Maps. Of course the app will need to ask the user for location permissions if it does not have those already. It should check every time the app opens.
5. Ask user for destination. Again, the backend will have autocomplete. Use this: https://developers.google.com/maps/documentation/javascript/place-autocomplete
6. Find the nearest driver ( that will require backend programming, dont worry about it right now.
7. alculate distance, then charge the user total miles/2. Ask user if they want to complete the transaction.
8. Send the ride info to the nearest non-busy driver first, then to all drivers. This is beyond the scope of this mockup so dont worry about it for now.
   




