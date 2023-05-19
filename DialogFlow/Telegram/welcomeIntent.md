---
Welcome Intent
---

###### Text Response Header
```
{
    "telegram": {
        "text": "Hello! Ask me about any of the items below. If at any point you want to come back to the main menu type exit",
        "reply_markup": {
            "inline_keyboard": [
                [
                    {
                        "text": "1. Branch Location",
                        "callback_data": "branch_location"
                    }
                ],
                [
                    {
                        "text": "2. Account Queries",
                        "callback_data": "account_queries"
                    }
                ],
                [
                    {
                        "text": "3. Bmobile Queries",
                        "callback_data": "bmobile_queries"
                    }
                ],
                [
                    {
                        "text": "4. Card Queries",
                        "callback_data": "card_queries"
                    }
                ],
                [
                    {
                        "text": "5. Mpesa / Bill Payments",
                        "callback_data": "mpesa_bill_payments"
                    }
                ],
                [
                    {
                        "text": "6. Chat with an Agent",
                        "callback_data": "chat_agent"
                    }
                ],
                [
                    {
                        "text": "7. Current Campaings",
                        "callback_data": "current_campaings"
                    }
                ]
                ]
        }
    }
}
```