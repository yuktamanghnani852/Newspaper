# Newspaper📰 Times of India – Newspaper Layout

📌 Project Overview

This project is a simple newspaper-style webpage created using HTML and CSS. It demonstrates how to create a newspaper layout with multiple columns, a scrolling news headline, headings, and text sections.

The design is inspired by a traditional newspaper layout.

✨ Features

- 📰 Newspaper-style heading: TIMES OF INDIA
- 📢 Scrolling latest-news announcement using "<marquee>"
- 📅 Displays the last updated news date
- 📰 Three-column newspaper layout
- 📏 Column borders using "column-rule"
- ↔️ Column spacing using "column-gap"
- 🎨 Beige background color
- 📝 Multiple article sections
- 🔤 Center-aligned section headings
- 📱 Basic responsive viewport setup

🛠️ Technologies Used

- HTML5
- CSS3
- CSS Multi-Column Layout
- HTML "<marquee>" element

📂 Project Structure

Times-of-India/
│
├── index.html
└── README.md

🚀 How to Run

1. Create a folder named "Times-of-India".
2. Create a file named "index.html".
3. Paste the provided HTML code into "index.html".
4. Save the file.
5. Open "index.html" in a web browser.

You can also open the project in VS Code and use the Live Server extension.

🎨 CSS Features Used

1. Three-Column Layout

The "column-count" property divides the content into three columns.

.three, .a {
    column-count: 3;
    column-rule: 3px solid black;
    column-gap: 40px;
}

2. Scrolling News

The "<marquee>" element is used to display a scrolling news update.

<marquee scrollamount="20">
    <h2>Last Updated News Date: 30 July 2026</h2>
</marquee>

3. Background Color

The webpage uses a beige background.

* {
    text-align: justify;
    background-color: beige;
}

4. Center Alignment

The main heading is centered using CSS.

h1 {
    text-align: center;
}

📚 Learning Objectives

This project helps in understanding:

- HTML page structure
- CSS styling
- CSS multi-column layouts
- "column-count"
- "column-rule"
- "column-gap"
- Text alignment
- Background colors
- Scrolling text
- Headings and paragraphs
- Basic webpage design

🖥️ Expected Output

The webpage displays:

1. TIMES OF INDIA as the main newspaper heading.
2. A scrolling Last Updated News Date banner.
3. News content arranged into three columns.
4. Additional article content divided into columns.
5. A simple beige newspaper-style appearance.

⚠️ Note

The article text in the provided code uses Lorem Ipsum placeholder text. It can be replaced with real news articles or other content.

The "<marquee>" element is an older HTML feature and is not recommended for modern production websites. CSS animations can be used as a modern alternative.

👨‍💻 Author

Your Name

📄 License

This project is created for educational and learning purposes.
