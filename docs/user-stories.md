# User Stories

## US01 - Login
As a customer or admin, I want to login to the system using my valid user identification and password so that I can access the system according to my role. 

**Related Requirement:** FR01

### Acceptance Criteria
- Given valid credentials when the user logs in, then access is granted.
- Given invalid credentials when the user logs in, then access is denied.

## US02 - Select Cookies 
As a customer, I want to browse and select available cookies so that I can choose the products I want to purchase. 

**Related Requirements:** FR02

### Acceptance Criteria
- Given available cookie products when the customer views the product list, then the products are displayed.
- Given a selected product when the customer selects it, then it can be added to the order.

## US03 - View Receipt
As a customer, I want to view my receipt after successful payment so that I can confirm my purchase and keep a record of my transaction. 

**Related Requirements:** FR03

### Acceptance Criteria
- Given a successful payment when the customer views the receipt, then the transaction details are displayed.
- The receipt reflects the correct order and payment details.

## US04 - Add New Cookie Products
As an admin, I want to add new cookie products to the system so that customers can view and purchase the available cookies. 

**Related Requirements:** FR04

### Acceptance Criteria
- Given an authenticated admin when valid cookie details are submitted, then the new product is saved.
- The system rejects submissions with required details missing.

## US05 - Update Delivery Status
As an admin, I want to update the delivery status of customer orders so that customers can receive accurate information about their order progress. 

**Related Requirements:** FR05

### Acceptance Criteria
- Given an authenticated admin when a valid delivery status is selected, then the order status is updated.
- The updated status is stored and available for viewing.

## US06 - System Performance
As a customer or admin, I want the system pages to load within 3 seconds and checkout complete within 5 seconds so that I can use the system efficiently. 

**Related Requirements:** NFR01

### Acceptance Criteria
- Pages load within 3 seconds under the agreed test conditions.
- Checkout completes within 5 seconds under the agreed test conditions.

## US07 - Transaction Accuracy
As a customer, I want my order and payment information to be accurate and consistent so that I can avoid duplicate transactions and incorrect purchase records. 

**Related Requirements:** NFR02

### Acceptance Criteria
- Repeated submission of the same payment request does not create duplicate transactions.
- Order and payment records remain consistent after a successful transaction.

## US08 - Backup and Recovery
As an admin, I want the system to back up data daily and recover from failures wihtin 5 minutes without data loss so that important order and payment records remain protected. 

**Related Requirements:** NFR03

### Acceptance Criteria
- The system performs scheduled daily backups.
- Following a simulated failure, the system recovers within 5 minutes without losing data covered by the recovery requirements.