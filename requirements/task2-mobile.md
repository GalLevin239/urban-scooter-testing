# Requirements — Task 2 (Mobile App)

The following requirements were tested for the **Urban Scooter** Android app (API level 31 emulator).  
Only requirements **highlighted in yellow** from the specification are included here.

## Notifications
1. When there are **2 hours left** to complete an order, the user receives a notification.  
   - Example: Order due May 8 by 11:59 p.m. → at 9:59 p.m. notification is sent.  
2. Notification text format:  
   `"2 hours to the end of the order. The order <Address> must be completed before <time X>. If you can't make it in time, alert support: 0101."`  
3. Tapping the notification opens the **"My orders" tab** in the app.

## Lack of Internet Connection
1. If no Internet connection is available and the user taps an active button → a **"No Internet connection"** pop-up appears.  
   - The pop-up disappears only when the user taps **"OK"**.  
2. If the user taps **"OK"** but there is still no Internet → the pop-up reappears on the next interaction with any active button.  
