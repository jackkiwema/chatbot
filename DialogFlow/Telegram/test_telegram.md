---
test telegram Intent
---
###### test
```
{
  "telegram": {
    "text": "You can read about *entities* [here](/docs/concept-entities).",
    "parse_mode": "Markdown"
  }
}
```

###### Color
```
{
  "telegram": {
    "text": "Pick a color",
    "reply_markup": {
      "inline_keyboard": [
        [
          {
            "text": "Red",
            "callback_data": "Red"
          }
        ],
        [
          {
            "text": "Green",
            "callback_data": "Green"
          }
        ],
        [
          {
            "text": "Yellow",
            "callback_data": "Yellow"
          }
        ],
        [
          {
            "text": "Blue",
            "callback_data": "Blue"
          }
        ],
        [
          {
            "text": "Pink",
            "callback_data": "Pink"
          }
        ]
      ]
    }
  }
}
```