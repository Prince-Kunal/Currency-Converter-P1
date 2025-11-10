# Currency-Converter-P1

A simple web-based currency converter that lets you convert any amount between different currencies in real-time. I built this project to practice working with APIs, DOM manipulation, and clean UI layout using HTML, CSS, and JavaScript.

---

## **Features**

* Convert currency values between any two countries
* Real-time exchange rates fetched through API
* Automatic flag updates when changing currency selections
* Input validation for stable conversions
* Clean and responsive UI

---

## **Tech Stack**

| Area                 | Technology                           |
| -------------------- | ------------------------------------ |
| Frontend Structure   | HTML                                 |
| Styling              | CSS                                  |
| Logic & API Handling | JavaScript                           |
| Exchange Rate API    | Free Currency API (via jsDelivr CDN) |
| Flags                | flagsapi.com                         |

---

## **How It Works**

1. Select the **From** and **To** currencies from dropdowns.
2. Enter the amount to convert.
3. Click **Get Exchange Rate**.
4. The app fetches the latest exchange rate and displays the result instantly.

The conversion formula used:

```
finalAmount = inputAmount ✕ exchangeRate
```

---

## **Project Structure**

```
index.html      → UI Structure
style.css       → Styling and layout
app.js          → Logic, API calls and DOM updates
codes.js        → Currency list and flag mapping
```

---

## **Run This Project**

No installation needed.

Just **open `index.html` in your browser**.

---

## **What I Learned**

* How to fetch data from an external API
* Updating UI dynamically with JavaScript
* Handling user input and events
* Connecting data with visual elements (flags + dropdowns)

---

## **Future Improvements (Optional ideas)**

* Dark mode
* Add “Swap currencies” button animation
* Show past conversion history
* Add country search in dropdowns

---