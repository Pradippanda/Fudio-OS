API Documentation

Base URL

https://your-domain.com/api

---

Authentication

Protected endpoints require user authentication.

---

Orders

Get Orders

GET /api/orders

Create Order

POST /api/orders

Update Order

PUT /api/orders/:id

Delete Order

DELETE /api/orders/:id

---

Menu

GET /api/menu
POST /api/menu
PUT /api/menu/:id
DELETE /api/menu/:id

---

Inventory

GET /api/inventory
POST /api/inventory

---

Customers

GET /api/customers
POST /api/customers

---

Analytics

GET /api/analytics

---

Responses

Successful requests:

{
  "success": true,
  "data": {}
}

Error responses:

{
  "success": false,
  "message": "Error description"
}
