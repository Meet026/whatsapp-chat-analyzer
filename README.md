WhatsApp Chat Analyzer
=======================

This is a Streamlit web application that analyzes exported WhatsApp chats.
It supports both group and solo chats and provides various visual insights.

------------------------------------------
Features:
------------------------------------------

- Automatically detects group or solo chats.
- Displays key statistics: total messages, words, media, and links.
- Identifies the most active users (for group chats).
- Monthly and daily message timelines.
- Activity heatmap for days and hours.
- Word cloud for most frequently used words.
- Common words and emoji usage breakdown.

------------------------------------------
How to Use:
------------------------------------------

1. Export a WhatsApp chat:
   - Open the chat in WhatsApp.
   - Tap the three dots (menu) > More > Export chat.
   - Choose "Without media".
   - Save the `.txt` file.

2. Run the App:

   a. Clone the repository:
      git clone https://github.com/Meet026/whatsapp-chat-analyzer
      cd whatsapp-chat-analyzer

   b. Install the requirements:
      pip install -r requirements.txt

   c. Launch the app:
      streamlit run app.py

3. Upload the exported chat `.txt` file in the app.

------------------------------------------
Files in the Project:
------------------------------------------

- app.py              : Main Streamlit app interface.
- helper.py           : Utility functions for data analysis.
- preprocessor.py     : Text preprocessing logic.
- stop_hinglish.txt   : Stopwords for filtering chat words.

------------------------------------------
Requirements:
------------------------------------------

- Python 3.7 or higher
- Libraries: streamlit, pandas, matplotlib, seaborn, emoji

------------------------------------------
Notes:
------------------------------------------

- This app processes data locally. No uploaded chat data is stored.
- Only English WhatsApp chat exports are currently supported.

------------------------------------------
Contact:
------------------------------------------

GitHub Repo: https://github.com/Meet026/whatsapp-chat-analyzer
