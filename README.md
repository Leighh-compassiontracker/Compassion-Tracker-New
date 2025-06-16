# Compassion Tracker

A comprehensive caregiver support application designed to simplify health management through intuitive, secure, and compassionate digital tools.

## Features

- **Medication Management** - Track medications, schedules, and inventory with automated reminders
- **Health Monitoring** - Record blood pressure, glucose, insulin, and other vital metrics
- **Bodily Function Tracking** - Monitor bowel movements and urination patterns
- **Meal & Sleep Tracking** - Log meals and sleep patterns for comprehensive care
- **Appointment Management** - Schedule and track medical appointments
- **Emergency Information** - Secure storage of critical medical information with PIN protection
- **Doctor & Pharmacy Management** - Maintain contact information for healthcare providers
- **Notes & Supplies** - Daily notes and supply inventory management
- **Multi-Care Recipient Support** - Manage care for multiple family members

## Technology Stack

- **Frontend:** React, TypeScript, Tailwind CSS, shadcn/ui
- **Backend:** Express.js, Node.js
- **Database:** PostgreSQL with Drizzle ORM
- **Authentication:** Passport.js with session management
- **Security:** Helmet, rate limiting, password hashing
- **Notifications:** SendGrid (email), Twilio (SMS)
- **Deployment:** Docker, Render-ready

## Quick Start

### Development
```bash
npm install
npm run dev
```

### Production Build
```bash
npm run build
npm start
```

### Database Setup
```bash
npm run db:push
npm run db:seed
```

## Deployment

This application is ready for deployment on Render. See `DEPLOYMENT.md` for detailed instructions.

## Security Features

- Password strength validation
- Rate limiting on API endpoints
- Secure session management
- PIN-protected emergency information
- Helmet security headers

## Test Account

For testing purposes:
- Username: `Leigh Hacker`
- Password: `555`

## License

MIT License