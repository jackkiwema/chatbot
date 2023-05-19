---
Welcome Intent
---

###### Text Response Header
Hello :-) Ask me about any of the items below. If at any point you want to come back to the main menu type exit.

###### Welcome custom payload
{
  "telegram": {
    "text": "Choose an option:",
    "reply_markup": {
      "keyboard": [
        [
          "1. Branch Location",
          "2. Account Queries",
          "3. Bmobile Queries"
        ],
        [
          "4. Card Queries",
          "5. Mpesa / Bill Payments",
          "6. Chat with an Agent"
        ],
        [
          "7. Current Campaigns",
          "8. Can I see your menu?",
          "9. Can I book a table?"
        ],
        [
          "10. Do you deliver?"
        ]
      ]
    }
  }
}