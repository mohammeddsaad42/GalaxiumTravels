# Galaxium Travels — Interplanetary Booking System

A demo multi-service application for booking interplanetary space travel. Its purpose is to **showcase challenges agents face in a real enterprise-style codebase** — three polyglot services, cross-service workflows, a dual REST + MCP backend, and intentional architectural constraints that make it interesting to work with.

## 🌟 Features

- 🚀 **Book flights across the solar system** — search routes between Earth, Mars, the Moon, Venus, Jupiter, Europa, and Pluto
- 💺 **Three seat classes** — Economy, Business, and Galaxium, each with independent seat counters and their own pricing multipliers
- ⏳ **Quote & hold workflow** — reserve a seat with a time-limited hold before committing to a booking, powered by a dedicated Java microservice
- 🤖 **Dual REST + MCP backend** — every booking operation is accessible as a standard REST endpoint *and* as an MCP tool, so AI agents can interact with the system natively
- 📡 **Live seat availability** — sold-out classes don't block other classes; availability updates in real time as bookings and holds are created or cancelled
- 🗓️ **Full booking lifecycle** — create, view, and cancel bookings; holds auto-expire after 15 minutes if not confirmed
- 🌍 **10 demo travellers, 10 routes, 20 pre-seeded bookings** — ready to explore the moment you start the app
- ☁️ **Deployable everywhere** — one-command local start, Docker Compose, AWS ECS + Terraform, and IBM Code Engine

Mirrored from [IBM/galaxium-travels](https://github.com/IBM/galaxium-travels).
