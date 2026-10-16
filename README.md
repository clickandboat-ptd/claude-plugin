# Click&Boat

Search available boat rentals worldwide on [Click&Boat](https://www.clickandboat.com) with real-time prices, inspect full boat details, and generate pre-filled checkout links from a conversation with Claude.

## Use it

Ask Claude to find a boat to rent by sharing your destination, rental dates, and number of guests. You can also filter by boat type (catamaran, sailboat, motorboat, RIB, yacht, houseboat, gulet, or jet ski), skipper preference, licence-free boats, budget, cabins, length, instant booking, or flexible cancellation.

Claude searches live Click&Boat inventory through the bundled `clickandboat` MCP connector, displays matching boats in an interactive carousel with photos and total prices, retrieves detailed specifications (equipment, cancellation policy, security deposit, mandatory extras, and verified reviews) when you ask about a specific boat, and generates a pre-filled checkout link when you are ready to book on Click&Boat.

## Tools included

- `search_boats`: Search available boats for rent with total period price in EUR.
- `show_boats`: Display selected boats in a visual carousel with photos, prices, badges, and booking links.
- `get_boat_details`: Get the full description, photo gallery, equipment, cancellation policy, deposit, mandatory extras, and top reviews for a boat.
- `get_booking_link`: Generate a pre-filled Click&Boat checkout link for a chosen boat and date range.

## Data and privacy

The plugin connects only to `https://www.clickandboat.com/mcp` over HTTPS. It sends only the search criteria, boat IDs, rental dates, guest count, and language code needed to answer your boat rental request. No authentication or API key is required, and the plugin stores nothing on your machine and requests no local file or shell access.

Use of the Click&Boat service is governed by the [Click&Boat Terms & Conditions](https://www.clickandboat.com/en/terms-conditions) and [Privacy Policy](https://www.clickandboat.com/en/privacy-policy).
