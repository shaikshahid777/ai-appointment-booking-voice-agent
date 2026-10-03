<!-- SHOWCASE_START --><div align="center">[![Typing](https://readme-typing-svg.demolab.com?font=Fira+Code&weight=700&size=22&duration=2800&pause=900&color=58A6FF&center=true&vCenter=true&width=900&lines=ai%20appointment%20booking%20voice%20agent;AI%20%7C%20Automation%20%7C%20Engineering;Explore%20the%20project%20%F0%9F%9A%80)](https://github.com/shaikshahid777/ai-appointment-booking-voice-agent)<img src="https://capsule-render.vercel.app/api?type=waving&color=0:0D1117,50:161B22,100:58A6FF&height=110&section=header&text=ai-appointment-booking-voice-agent&fontSize=26&fontColor=FFFFFF&animation=twinkling&fontAlignY=65" width="100%" alt="Animated project banner"/>

[![Repository](https://img.shields.io/badge/Repository-181717?style=for-the-badge&logo=github&logoColor=white)](https://github.com/shaikshahid777/ai-appointment-booking-voice-agent) [![Issues](https://img.shields.io/badge/Report-Issue-red?style=for-the-badge&logo=github)](https://github.com/shaikshahid777/ai-appointment-booking-voice-agent/issues/new) [![Stars](https://img.shields.io/github/stars/shaikshahid777/ai-appointment-booking-voice-agent?style=for-the-badge&logo=github)](https://github.com/shaikshahid777/ai-appointment-booking-voice-agent/stargazers) [![Fork](https://img.shields.io/github/forks/shaikshahid777/ai-appointment-booking-voice-agent?style=for-the-badge&logo=github)](https://github.com/shaikshahid777/ai-appointment-booking-voice-agent/fork) [![Profile](https://img.shields.io/badge/Profile-Visit-0A66C2?style=for-the-badge&logo=github)](https://github.com/shaikshahid777)</div>

> ✨ **Project Showcase Mode:** animated banner • interactive navigation • live repository actions

[🚀 Repository](https://github.com/shaikshahid777/ai-appointment-booking-voice-agent) · [🐞 Report Issue](https://github.com/shaikshahid777/ai-appointment-booking-voice-agent/issues/new) · [⭐ Star](https://github.com/shaikshahid777/ai-appointment-booking-voice-agent/stargazers) · [🔱 Fork](https://github.com/shaikshahid777/ai-appointment-booking-voice-agent/fork) · [👤 Profile](https://github.com/shaikshahid777)

<!-- SHOWCASE_END -->

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
