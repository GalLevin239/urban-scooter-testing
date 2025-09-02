# Requirements — Task 3 (Backend API: Couriers)

The following requirements were tested for the **Urban Scooter API**.  
Only requirements **highlighted in yellow** from the specification are included here.

## Add Courier
- **Endpoint:** `POST /api/v1/courier`
- Registers a courier in the system.  
- The request body must include:  
  - `username`  
  - `password`  
  - `name`  
- After a successful POST call:  
  - A **new courier** should be created.  
  - Response status code: **201 Created** (confirmation that courier was created).

## Delete Courier
- **Endpoint:** `DELETE /api/v1/courier/:id`
- Deletes a courier account by ID.  
- After a successful DELETE call:  
  - Response status code: **200 OK** (confirmation that courier was deleted).  
  - Linked orders are also removed.
