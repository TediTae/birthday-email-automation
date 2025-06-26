# 📫 Birthday Email Automation
- Automatically send personalized birthday wishes via email using Python, CSV data, and pre-written letter templates.

###

## 📌 Features
- Reads birthday data from a CSV file.
- Matches today’s date with birthdays.
- Picks a random letter template and personalizes it.
- Sends a custom email through SMTP (e.g., Gmail, Yahoo).
- Simple, lightweight, and easy to configure.

###

## 🛠️ Requirements
- Python 3.x
- pandas
- smtplib (built-in)

###

## 📁 Project Structure

- ├── birthdays.csv
- ├── main.py
- ├── letter_templates
- │   ├── letter_1.txt
- │   ├── letter_2.txt
- │   └── letter_3.txt

###

## 🚀 Usage
1. Place your birthdays.csv file in the project root.
2. Add at least one or desired amount of  birthday template in /letter_templates
   (need to modify random.randint(1,3) part of code if you desided to change amount of letters).
3. Run the script: main.py

###

## 📬 Future Improvements
- Add support for multiple emails per day.
- Schedule script to run daily via cron or Windows Task Scheduler.
- Add GUI interface for non-technical users.
- Telegram or Discord bot integration for notifications.

###

## 🧑‍💻 Connection
- Email: tolgayilmaz1377@gmail.com
