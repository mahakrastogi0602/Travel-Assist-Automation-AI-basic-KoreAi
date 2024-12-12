Here’s a breakdown of what I implemented:
Travel Assistant App Key Features:
1. Greeting and Task Display – The bot warmly greets users and displays available options:
•Book a Flight
•Fetch Booking Details
•Modify Booking
2. Flight Booking Assistance – The bot collects essential travel details through a digital form, with validation to ensure booking dates are in the future. Confirmation is requested before saving, and a customized message reassures the user that their booking details have been successfully saved.
3. Booking Management – Users can:
•Retrieve booking details by providing their mobile number.
•Modify existing bookings, including options to change the date or location, or cancel if necessary, with backend updates (PUT/PATCH/DELETE API calls).
4. Enhanced ML Capabilities – I trained the bot’s ML engine with diverse utterances, synonyms, and patterns to handle varied user inputs, including short, idiomatic, and uniquely structured phrases, making the bot more intuitive and user-friendly.
5. Comprehensive FAQs – Added responses for commonly asked travel-related questions, ensuring users are informed at each step of their journey.
6. Testing and Publishing – Defined a batch test suite for intent and entity extraction accuracy, with live testing on an enabled channel for end-user evaluation.
