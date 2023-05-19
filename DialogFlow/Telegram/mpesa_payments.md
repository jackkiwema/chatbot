---
Mpesa/bill payments
---

###### Mpesa Payments Headers
```
{
    "telegram": {
        "text": "5. Mpesa Payments",
        "reply_markup": {
            "inline_keyboard": [
                [
                    {
                        "text": "BOA Paybill",
                        "callback_data": "paybill"
                    }
                ],
                [
                    {
                        "text": "Mpesa Limits",
                        "callback_data": "mpesa_limits"
                    }
                ],
                [
                    {
                        "text": "Erroneous Payments",
                        "callback_data": "erroneous_payments"
                    }
                ],
                [
                    {
                        "text": "Chat with an Agent",
                        "callback_data": "chat_agent"
                    }
                ]
            ]
        }
    }
}
```