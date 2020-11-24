
# Install

1. `git clone https://github.com/akump/GroupMeDarkTheme.git`

Optional

   2. Edit line 1 of script.js to include your GroupMe nicknames to highlight your messages in a different color. Note: feel free to hack this code to meet your performance needs. Currently, it will cut off at 1000 messages in the DOM and require a page refresh to work again.

   
```
const yourNicknames = ['Andrew Kump', 'Irelia one trick btw', 'Drevv', 'Brovid-19'];
```

1. [chrome://extensions](chrome://extensions)
2. Click 'Load unpacked'
3. Navigate in file explorer to where you cloned the repo e.g. `D:\git\GroupMeDarkTheme`


![Alt text](example_pic2.png?raw=true "Title")




# Potential issues
1. Scroll bars on all machines
2. Performance if you leave GroupMe afk for hours. Currently this is negated by just shutting the extension off, but I'd prefer that not to work that way
3. Random screens no one ever goes to - last 10% of CSS
   1. Calendar
   2. Contacts
   3. Archives
   4. Campus Connect