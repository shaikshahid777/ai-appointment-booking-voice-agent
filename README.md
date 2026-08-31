# AI Appointment Booking Voice Agent

A Retell AI + n8n appointment booking voice-agent project for a clinic use case.

## Demo

Loom: https://www.loom.com/share/3efd6ad5e9034d94831dd274dfda38e5

## Core capabilities

- Appointment booking
- Calendar availability checking
- Unavailable-slot handling with alternative slots
- Appointment rescheduling
- Appointment cancellation
- Confirmation notifications
- Professional call closure

## Architecture

Retell AI Voice Agent → n8n Webhook → Google Calendar → Availability Logic → Retell response

## Function tools

- `check_availability`
- `book_appointment`
- `reschedule_appointment`
- `cancel_appointment`
- `send_confirmation`

## Supporting document

See `docs/assessment-submission.md` for the assessment configuration summary, test scenarios, assumptions, and submission checklist.

## Assessment note

The unavailable-slot branch requires the availability tool to return `available: false` with alternative slots for demonstration. During development, the tested calendar path returned `available: true`.
