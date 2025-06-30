# Air-Ticket-Booking-Automation

This Selenium automation script performs a flight booking simulation on the [Rahul Shetty Academy flight booking demo site](https://rahulshettyacademy.com/dropdownsPractise/). It automates selecting source/destination, date, number of passengers, currency, and applies a student discount before clicking the search button.

## 📌 Features

- Auto-suggest dropdown selection (e.g., typing "ind" selects "India")
- Round-trip booking mode
- Source and destination airport selection
- Date picker interaction for return date
- Passenger count configuration (adds 5 adults)
- Currency selection from dropdown
- Student discount checkbox handling
- Flight search button interaction

## 🧪 Automation Flow

1. Launch Chrome browser and navigate to the flight booking site.
2. Enter partial country name and select "India" from suggestions.
3. Select round-trip and choose:
   - From: BLR (Bangalore)
   - To: MAA (Chennai)
4. Enable student discount.
5. Pick a return date (e.g., 13th of the month).
6. Add 5 adult passengers.
7. Select currency (e.g., INR).
8. Submit the search.
9. Close the browser.

## 📁 Project Structure

```bash
Air-Ticket-Booking-Automation/
├── src/
│   └── main/
│       └── java/
│           └── Test.java
├── pom.xml
└── README.md
```
## ⚙️ Setup Instructions

### Clone the repository

```bash
git clone https://github.com/amit-rakib/Air-Ticket-Booking-Automation.git
cd Air-Ticket-Booking-Automation
```

### Install dependencies
Make sure you have Maven and Java 17+ installed.

```bash
mvn clean install
```

Run the test
You can run the test using your IDE or via command line:

``` bash
mvn exec:java -Dexec.mainClass="Test" -Dexec.classpathScope=compile

```
## 🔧 Prerequisites

- Google Chrome browser 
- ChromeDriver in your system PATH
- Java 17 or above
- Maven
- Internet connection
  
## ✍️ Author

Md. Amit Hasan Rakib

Email: mdamithasanrakib11@gmail.com
