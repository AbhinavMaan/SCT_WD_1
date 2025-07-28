🎨 Dynamic Background Styling Webpage
A mini front-end project that allows users to switch between multiple gradient background styles using a clean navigation interface. Built using HTML, CSS, and JavaScript — no frameworks, just pure front-end magic.

🚀 Features
Five buttons to toggle different background themes:

Style 1 to Style 4: Gradient color themes

Clear: Resets background to default

Smooth background transitions

Hover effects for buttons

Fully responsive with media queries for mobile and tablet screens

🛠️ Tech Stack
HTML5

CSS3 (Gradients, Transitions, Media Queries)

JavaScript (DOM Manipulation, Event Listeners)

📱 Responsiveness
The layout is responsive:

On larger screens: Horizontal navigation bar with buttons

On smaller screens (tablets & phones): Vertical stack of buttons for easy interaction

📂 Project Structure
css
Copy
Edit
index.html       --> Main HTML file
(style inside <style> tag)
No external JS/CSS files needed — all code is embedded in the HTML file for simplicity.

✨ How It Works
Each button adds a background class to the <body> element using JavaScript, which triggers a corresponding gradient style via CSS. A "Clear" button removes all background styles.

javascript
Copy
Edit
document.body.classList.add("style1"); // Applies gradient style 1
document.body.classList.remove("style2", "style3", ...); // Removes others

🧠 What I Gained
Deeper understanding of DOM manipulation

Clean JavaScript event handling

Hands-on CSS gradient creation

Importance of writing responsive, user-friendly layouts

📌 Future Improvements
Add dark/light theme toggle

Store selected style using localStorage

Animate background transitions more smoothly

✅ Try It Out
Clone or download the repo and open index.html in your browser.
No dependencies required!
