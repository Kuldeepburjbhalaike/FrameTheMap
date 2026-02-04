# FrameTheMap 🗺️🎨

**FrameTheMap** is a browser-based tool for creating stunning, high-resolution artistic maps using OpenStreetMap data. It combines the aesthetic discovery of tools like *city-roads* with the precision control of professional mapping software.

[**Tool Link**](https://kuldeepburjbhalaike.github.io/FrameTheMap/)

## ✨ Features

* **🔍 Instant Search:** "Search-as-you-type" functionality using the Photon API (no API keys required).
* **✏️ Precision Selection:**
    * **Visual Frame:** Use fixed aspect ratios (A4 Portrait, Landscape, Square, Full Screen).
    * **Draw Custom Box:** Click and drag to define the exact export area.
* **🎨 Artistic Themes:**
    * **Cartography:** Clean, modern look with cased roads.
    * **City Lights:** Dark mode with high contrast.
    * **Old Paper:** Vintage aesthetic.
    * **Blueprint:** Architectural style.
    * **Minimalist:** Clean light mode.
* **🛠️ Customization:** Toggle visibility for Roads, Water, Buildings, and Street Names.
* **🖨️ High-Res Export:** Generate PNGs in Standard, HD (2x), or Ultra Print (4x) quality.
* **🔒 Privacy First:** Runs entirely in the browser. No tracking, no backend database.

## 🚀 Getting Started

### Prerequisites
You don't need `npm`, `node`, or a backend server. This is a standalone web application.

### Installation
1.  **Clone the repository:**
    ```bash
    git clone [https://github.com/Kuldeepburjbhalaike/FrameTheMap.git](https://github.com/Kuldeepburjbhalaike/FrameTheMap.git)
    ```
2.  **Open the file:**
    Simply double-click `index.html` to open it in your web browser.

### Usage
1.  **Search** for a location (e.g., "Kyoto, Japan" or "Burj Bhalaike").
2.  **Define your area** by moving the map or drawing a custom box.
3.  **Click "Generate Map"** to fetch vector data from the Overpass API.
4.  **Customize** your map style using the sidebar controls.
5.  **Export** your masterpiece as a PNG image.

## 🛠️ Built With

* **[Leaflet.js](https://leafletjs.com/)** - Interactive maps.
* **[Overpass API](https://overpass-api.de/)** - Fetching raw OpenStreetMap vector data (nodes/ways).
* **[Photon API](https://photon.komoot.io/)** - Instant search/geocoding.
* **HTML5 Canvas** - High-performance client-side rendering.
* **Vanilla JS** - No heavy frameworks, lightweight and fast.

## 🤝 Contributing

Contributions are welcome! Please feel free to submit a Pull Request.

1.  Fork the Project
2.  Create your Feature Branch (`git checkout -b feature/AmazingFeature`)
3.  Commit your Changes (`git commit -m 'Add some AmazingFeature'`)
4.  Push to the Branch (`git push origin feature/AmazingFeature`)
5.  Open a Pull Request

## 👏 Acknowledgments & Inspiration

This project was inspired by the amazing work of the open-source community:
* **[Render MyMap](http://render.osmtippek.hu/)** - For the logic behind high-quality export and layer control.
* **[city-roads](https://github.com/anvaka/city-roads)** by anvaka - For the concept of artistic road rendering.
* **[OpenStreetMap](https://www.openstreetmap.org/)** - For the incredible open data.

## 📄 License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

Data © [OpenStreetMap contributors](https://www.openstreetmap.org/copyright).

---
Made with ❤️ by [Kuldeep](https://meta.wikimedia.org/wiki/User:Kuldeepburjbhalaike)
