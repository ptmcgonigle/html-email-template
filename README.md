# HTML Email Template

Basic HTML Email Template

## Directus Notifications

I mainly use this with Directus for sending email notifications. 

*Directus Form Fields to Tags*
- Name = {{$trigger.payload.name}}
- Email = {{$trigger.payload.email}}
- Phone = {{$trigger.payload.phone}}
- Message = {{$trigger.payload.mesage}}
