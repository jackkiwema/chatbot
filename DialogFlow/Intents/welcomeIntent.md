---
Welcome Intent
---

###### Text Response
```
Hello :-) Ask me about any of the items below. If at any point you want to come back to the main menu type exit.

Greetings :-) Ask me about any of the items below. If at any point you want to come back to the main menu type exit.
```


###### Welcome Intent
```
{
  "richContent": [
    [
      {
        "options": [
          {
            "text": "1. Branch Location"
          },
          {
            "text": "2. Account Queries"
          },
          {
            "text": "3. Bmobile Queries"
          },
          {
            "text": "4. Card Queries"
          },
          {
            "text": "5. Mpesa /Bill Payments"
          },
          {
            "text": "6. Chat with an Agent"
          },
          {
            "text": "7. Current Campaigns"
          },
          {
            "text": "8. Can I see your menu?"
          },
          {
            "text": "9. Can I book a table?"
          },
          {
            "text": "10. Do you deliver?"
          }, 
          {
            "text": "Click on name or number"
          }
        ],
        "type": "chips"
      }
    ]
  ]
}
```

###### Modified Welcome Intent
```
{
  "richContent": [
    [
      {
        "type": "list",
        "title": "Hello! Ask me about any of the items below.",
        "subtitle": "If at any point you want to come back to the main menu, type 'exit'.",
        "items": [
          {
            "optionInfo": {
              "key": "BRANCH_LOCATION",
              "synonyms": [
                "Branch Location"
              ]
            },
            "title": "1. Branch Location"
          },
          {
            "optionInfo": {
              "key": "ACCOUNT_QUERIES",
              "synonyms": [
                "Account Queries"
              ]
            },
            "title": "2. Account Queries"
          },
          {
            "optionInfo": {
              "key": "BMOBILE_QUERIES",
              "synonyms": [
                "Bmobile Queries"
              ]
            },
            "title": "3. Bmobile Queries"
          },
          {
            "optionInfo": {
              "key": "CARD_QUERIES",
              "synonyms": [
                "Card Queries"
              ]
            },
            "title": "4. Card Queries"
          },
          {
            "optionInfo": {
              "key": "MPESA_BILL_PAYMENTS",
              "synonyms": [
                "Mpesa / Bill Payments"
              ]
            },
            "title": "5. Mpesa / Bill Payments"
          },
          {
            "optionInfo": {
              "key": "CHAT_AGENT",
              "synonyms": [
                "Chat with an Agent"
              ]
            },
            "title": "6. Chat with an Agent"
          },
          {
            "optionInfo": {
              "key": "CURRENT_CAMPAIGNS",
              "synonyms": [
                "Current Campaigns"
              ]
            },
            "title": "7. Current Campaigns"
          }          
        ]
      }
    ]
  ]
}
```

