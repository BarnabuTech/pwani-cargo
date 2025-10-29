# Technical Documentation - Project Structure

## Core Components

### 1. Django Project Configuration (`pwani/`)
- `settings.py`: Core Django settings and configurations
- `urls.py`: Main URL routing configuration
- `wsgi.py` & `asgi.py`: Web server configurations
- `emailAlerts.py`: Email notification system

### 2. User Management (`signup/`)
- User authentication and registration
- Role-based access control
- User profile management
- Models:
  - `Customer`: End-user profile management
  - `Supplier`: Supplier account management
  - `ShippingCompany`: Shipping company profiles
  - `OilTankerCompany`: Oil tanker operations
  - `PortAuthority`: Port authority accounts
  - `CustomAuthority`: Customs official accounts

### 3. Customer Module (`Customer/`)
- Order placement and management
- Product browsing and cart management
- Order tracking and history
- Models:
  - `Order`: Core order management
  - `ExcelSheet`: Cargo details tracking

### 4. Supplier Module (`Supplier/`)
- Product listing management
- Order fulfillment
- Shipping coordination
- Custom documentation handling
- Models:
  - `Product`: Product catalog management

### 5. Shipping Operations (`ShippingCompany/`)
- Shipping cost management
- Vessel tracking
- Cargo pickup and delivery
- Documentation (manifests, bills of lading)

### 6. Oil Tanker Operations (`OilTanker/`)
- Tank filling operations
- Vessel information management
- Loading/unloading coordination
- Technical specifications tracking

### 7. Port Management (`PortAuthority/`)
- Vessel clearance
- Port entry/exit management
- Cargo dispatch authorization
- Documentation verification

### 8. Customs Processing (`CustomAuthority/`)
- Custom tax calculation
- Documentation verification
- Export/Import clearance
- Tax payment processing

### 9. Notification System (`notification/`)
- Real-time status updates
- Event-triggered notifications
- Stakeholder communications
- Alert management

### 10. Static Files (`static/`)
- CSS stylesheets
- JavaScript files
- Media assets
- Notification scripts

### 11. Templates (`templates/`)
- HTML templates for all modules
- Base templates for consistent UI
- Dashboard templates
- Form templates

## Technical Features
- Modular architecture
- Role-based access control
- Document management system
- Real-time notification system
- Secure file uploads
- Session management
- Database migrations
- Form validation
- Error handling

## Dependencies
- Django 5.2.7
- Python 3.13
- Bootstrap 5.3.2
- Font Awesome 4.7.0