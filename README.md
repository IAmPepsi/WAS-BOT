
# ✨✨WhatsApp_Simple_Bot✨✨


A WhatsApp bot that can answer simple pre-entered questions using python.
## Usage/Examples

The Bot use the following python libraries to be able to move the mouse and click the right and left buttons to copy the received messages and reply for it
```
import pyautogui as pt
import pyperclip as pc
```

The bot checks received messages every certain period of time


```

delay = 10
last_message = ''

sleep(3)
    ]
```

If there is any new messages, the bot gonna copy it and check if it exist in the given questions and will reply for it also from the given answer that belongs to this question using if else statements.
```

def process_message(msg):
    raw_msg = msg.lower()

    if raw_msg == 'hello':
        return 'hello'
    elif raw_msg == 'how are you ?':
        return 'i am good and you ?'
    else:
        return 'I do not understand'
```



## Requirements

WhatsApp Desktop-App is required for the Bot cause its working about checking new notifications for new messages and copy it to check out if its in the given Q&A or not.




## Updates

The Bot can easily be connected to a database like firebase to add the responses in there and make it LIVE 24/7
