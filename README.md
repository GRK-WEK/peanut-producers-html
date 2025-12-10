# 🥜 Peanuts & Companies Worldwide

A single-page HTML project providing information about different types of peanuts, the work of George Washington Carver, and a look at major companies in the global peanut industry.

## ✨ Features

* **Header Navigation:** A simple dropdown menu for site links.
* **George Washington Carver Section:** Information and links related to the "plant doctor."
* **Peanut Varieties:** Cards detailing the characteristics of Virginia, Spanish, and Valencia peanuts.
* **Global Companies:** Cards highlighting key peanut and commodity companies like J.M. Smucker (Jif), Hormel Foods (Skippy), ADM, and more.
* **Interactive Map:** Utilizes the Google Charts API to visualize the worldwide locations of the featured peanut companies.
* **Contact Form:** A basic contact form for user inquiries.
* **Responsive Footer:** Includes copyright and social media links.

## 🛠️ Technologies Used

* **HTML5:** For the structure and content of the page.
* **JavaScript:** Primarily for loading and displaying the Google Maps visualization.
* **Google Charts API:** Specifically the `map` package, to plot company locations using coordinates.

## 🗺️ Map Data

The map uses the following hardcoded latitude and longitude data to mark company locations:

| Latitude | Longitude | Location Name | Company/Brand |
| :---: | :---: | :--- | :--- |
| $40.0269$ | $-75.2160$ | Jif Ohio | J.M. Smucker |
| $43.2320$ | $-93.2080$ | Hormel Minnesota | Hormel Foods |
| $42.5525$ | $-70.8820$ | Teddie Massachusetts | Leavitt Corporation |
| $41.8781$ | $-93.0977$ | ADM Illinois | ADM |
| $1.3521$ | $103.8198$ | Olam Singapore | Olam International |
| $-33.8688$ | $151.2093$ | PCA Australia | PCA – Australia |

***

## 🚀 Getting Started

To view this project locally:

1.  **Clone the repository** (if hosted in one).
2.  **Open `index.html`** in your web browser.

**Note:** The Google Map will only load if you replace the placeholder API key in the `<head>` section with a valid Google Maps JavaScript API key. The current key is likely inactive or a placeholder:

```javascript
'mapsApiKey': 'AIzaSyDhv-B5OKiU7Q1BDMpA9ahqe14tqsxDuU8'
```

## File Structure

├── index.html            # Main HTML file
├── peanut.css            # Stylesheet (referenced but not included)
├── peanut.js             # Javascript for interactive elements (referenced but not included)
└── images/               # Directory for local images (smucker.png, hormel-foods.png, etc.)