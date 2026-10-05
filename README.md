# Greca Travel Concierge

Build and manage customized Greca travel packages.

Greca Travel Concierge is a connector (plugin) that brings Greca's travel services into your AI assistant. It helps users discover destinations, select locations and travel dates, find hotels, transfers, tickets, excursions, car rentals and other travel services, build a day-by-day itinerary, calculate package options, create customized travel packages, and manage existing bookings.

| | |
|---|---|
| **Developer** | Greca |
| **Category** | Travel |

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

## Use it

1. Install the Greca Travel Concierge plugin.
2. Open the plugin's **Connectors** tab, connect the Greca connector, and sign in with your Greca account.
3. Ask Claude about Greca trips, prices or your bookings in plain language. Claude builds and prices the package through Greca, shows you a summary, and books only after you confirm.

On Team and Enterprise plans, an Owner adds the connector for the organization, and members then connect with their own Greca account.

## Data

The plugin sends the details you provide for a trip (destinations, travel dates, number and type of passengers, hotel category, selected services) and booking or client lookup requests to your Greca account through Greca's MCP server at `https://aiplan.greca.co/mcp`. When you confirm a booking, the traveler and booking details needed to create it are sent to Greca. The plugin itself stores nothing; bookings and client records are kept in Greca's systems under [Greca's privacy policy](https://www.greca.co/en/privacy).

## Support

For questions about the connector, bookings or your account, contact Greca support through [greca.co](https://www.greca.co).

## License

This plugin is released under the MIT License.
