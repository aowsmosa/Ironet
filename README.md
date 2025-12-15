# Ironet
Smart Web System For Calculating And Ordering Construction Materials
# Ironet – Smart Construction Materials Ordering System

Ironet is a web-based system that helps contractors and private customers calculate required construction materials
(rebar, concrete, and blocks) and place orders through a simple interface. The project includes an admin panel for
inventory and order status management.

## Tech Stack
- Backend: PHP
- Frontend: HTML, CSS, JavaScript
- Database: MySQL
- Charts: Chart.js (reports & dashboards)

## Key Features
- Rebar quantity estimation by area + floor type + geographic location factors
- Rebar mix calculation (8/10/12/16mm) and kg split by mix
- Server-side payment form validation (card number, expiry, CVV, holder name)
- Secure password reset with token validation
- Role-based access control (Admin / Customer) with server-side protection
- Admin order status flow (pending/approved/cancelled/delivered) + live-updating statistics (AJAX)
- Material estimation: blocks + concrete (by slab thickness)

## Example Algorithms (high level)
- Base rebar: 80 kg/m² with modifiers:
  - floor type: basement +15%, upper +10%
  - location: coastal +10%, mountain +5%
- Rebar mix adjustment by floor/location + normalization

## Project Info
- Final project grade: 100
