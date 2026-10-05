# Greca Travel Concierge

Build and manage customized Greca travel packages.

Greca Travel Concierge is a connector (plugin) that brings Greca's travel services into your AI assistant. It helps users discover destinations, select locations and travel dates, find hotels, transfers, tickets, excursions, car rentals and other travel services, build a day-by-day itinerary, calculate package options, create customized travel packages, and manage existing bookings.

| | |
|---|---|
| **Developer** | Greca |
| **Category** | Travel |
| **App configuration** | [`.app.json`](./.app.json) |

---

## What it does

Greca Travel Concierge helps users discover available Greca travel products, review itineraries and destinations, configure travel dates, passengers, hotel categories and available options, calculate authoritative package prices, create bookings after explicit confirmation, and manage existing booking information.

## Capabilities

- **Discover products** – Browse available Greca travel products.
- **Review details** – View product itineraries, destinations and details.
- **Configure a trip** – Set travel dates, passengers, hotel categories and available options.
- **Calculate pricing** – Get authoritative product prices directly from Greca.
- **Create bookings** – Create confirmed Greca bookings.
- **Retrieve booking information** – Look up existing booking and transfer details.
- **Get document and update links** – Retrieve document-upload and booking-update links for an existing booking.
- **Look up clients and currency rates** – Find client records and current currency rates.

## Example requests

- "What Greca trips are available to Greece in June?"
- "Show me the day-by-day itinerary for this package."
- "Price this trip for 2 adults and 1 child, departing July 10, with a 4-star hotel."
- "Add an airport transfer and a boat excursion, then recalculate the price."
- "Book this package." *(the connector asks for explicit confirmation first)*
- "What are the transfer details for my booking?"
- "Send me the link to upload my travel documents."

## How booking works

1. **Discover** – The user browses products and reviews itineraries and destinations.
2. **Configure** – Dates, passengers, hotel category and optional services are selected.
3. **Price** – The connector requests an authoritative price from Greca's systems. Prices are always calculated by Greca, never estimated by the assistant.
4. **Confirm** – The full summary (trip, travelers, options, total price) is shown to the user.
5. **Book** – A booking is created **only after the user explicitly confirms**.
6. **Manage** – Booking and transfer details, document-upload links and booking-update links can be retrieved at any time.

## Installation

1. Add the Greca Travel Concierge connector to your AI assistant or workspace.
2. Sign in with your Greca account when prompted.
3. Start asking about Greca trips and bookings.

## Support

For questions about the connector, bookings or your account, contact Greca support through the Greca website.

---

© Greca. All rights reserved.
