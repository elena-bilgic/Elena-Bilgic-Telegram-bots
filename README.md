# Telegram bot named wardrobe_brain_bot
## The bot was created for ladies to address once and going forward the so much hated girlish question **"What to put on today?!"** in a comfy, pleasant and fancy way. 

How the bot works:
* The user needs to provide 3 pics of tops, 3 pics of bottoms (skirts, pants) and at least 2 pairs of footwear. The Bot saves the photos received in the list  to be further used for daily looks generation.
* This particular Bot stores the data in the memory.
* On a daily basis within the next 7 days the Bot generates outfits using **generate_outfits** function and the photos provided by the user on a random basis.
* Task planning: The **schedule** module is used for scheduling messages to be sent out to the user. The **Thread** module initializes **schedule_checker** function that validates and processes the tasks scheduled.


![logo](https://st.depositphotos.com/1177973/3268/i/450/depositphotos_32684137-stock-photo-beautiful-girl-thinking-what-to.jpg)
