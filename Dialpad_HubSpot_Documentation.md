# Dialpad for HubSpot CRM by Sandeza

## Overview

Dialpad for HubSpot CRM is a CTI (Computer Telephony Integration) application that embeds Dialpad calling capabilities directly inside HubSpot CRM. The integration allows sales and support teams to place calls, manage contacts, view CRM data, and track call activities without leaving HubSpot.

## Key Features

### 1. Embedded Dialpad Softphone
- Make outbound calls directly from HubSpot
- Access recent calls and favorites
- View Dialpad contact directories
- Agent-specific call handling

### 2. HubSpot CRM Integration
- Synchronize HubSpot contacts
- Search CRM contacts inside the widget
- Display contact information during calls
- One-click click-to-call functionality

### 3. OAuth-Based Authentication
- Secure HubSpot OAuth 2.0 authentication
- Multi-account support
- Token management and refresh handling

### 4. Contact Management
- Search contacts by name or phone number
- Sync contacts from HubSpot CRM
- Quick access to customer information

### 5. Call Context
- Display customer details during active calls
- Associate calls with CRM records
- Improve agent productivity

### 6. Ticket & Activity Support
- View customer-related information
- Create tickets from within the widget
- Track customer interactions

---

## Application Workflow

### Initial Setup
1. Install the application.
2. Configure Dialpad credentials.
3. Select Dialpad environment.
4. Select Dialpad agent.
5. Connect HubSpot using OAuth.
6. Save configuration.

### Daily Usage
1. Open HubSpot CRM.
2. Launch the Dialpad widget.
3. Search for a contact.
4. Click the call button.
5. Handle the call directly within HubSpot.
6. Review customer details during the conversation.

---

## Main Screens

### Dialpad Home
Provides:
- Recent calls
- Favorites
- Contact directory
- Dialpad controls

### Settings Screen
Provides:
- Dialpad account configuration
- Agent selection
- HubSpot OAuth connection
- Pipeline and stage configuration

### CRM Dashboard
Provides:
- HubSpot contact search
- Contact synchronization
- Click-to-call actions
- Customer record access

### Active Call Screen
Provides:
- Caller information
- Call controls
- Customer context
- Ticket visibility

---

## Technical Architecture

### Frontend
- React
- TypeScript
- HubSpot CRM Extension SDK
- Responsive Widget UI

### Backend
- AWS Lambda
- API Gateway
- Serverless Framework
- OAuth Management APIs

### External Services
- Dialpad API
- HubSpot CRM API
- HubSpot OAuth 2.0

---

## Security

### Authentication
- HubSpot OAuth 2.0
- Secure token storage
- Refresh token support

### API Communication
- HTTPS only
- Authenticated requests
- Protected backend endpoints

---

## Benefits

### Sales Teams
- Faster outbound calling
- Reduced application switching
- Improved productivity

### Support Teams
- Customer context during calls
- Faster issue resolution
- Better customer experience

### Administrators
- Centralized configuration
- OAuth-based security
- Easy deployment

---

## Deployment

### Frontend
Can be hosted on:
- GitHub Pages
- Hostinger
- AWS S3
- Netlify
- Vercel

### Backend
Hosted on:
- AWS Lambda
- AWS API Gateway

---

## Future Enhancements

- Automatic call logging
- Call recording links
- Activity timeline synchronization
- Ticket creation automation
- Advanced analytics dashboard
- AI-powered call insights

---

## Support

Sandeza Intelligent Communications

For support, configuration assistance, or enterprise deployment inquiries, contact the Sandeza implementation team.
