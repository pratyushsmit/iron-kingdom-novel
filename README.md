# The Iron Kingdom - Digital Novel

This repository contains the source code for the interactive digital novel **The Iron Kingdom**. It was originally deployed via Surge (`turning-point-v6-video.surge.sh`) and has been restructured for clean deployment via GitHub Pages.

## 🏗️ Architecture & Implementation

This project is built using **Vanilla Web Technologies** to ensure maximum performance, avoiding the heavy overhead of frameworks like React.

*   **HTML5**: Semantic structure.
*   **CSS3 & Tailwind CSS**: Tailwind is used via CDN for rapid utility styling. Custom complex animations (like pulses and glows) are written in `css/styles.css`.
*   **Vanilla JavaScript (ES6)**: No bundlers necessary. The core logic for animations and particle physics lives in `js/main.js`.
*   **GSAP & ScrollTrigger**: Handles high-performance cinematic animations and scroll-linked text reveals.
*   **HTML5 Canvas**: Powers the "Theme Showers"—a custom 2D particle engine simulating fire embers and ash that react dynamically to the user's mouse.

## 📂 Project Structure

A clean, modularized structure separates concerns:

\`\`\`
iron-kingdom-digital-novel/
├── index.html       # The main entry document referencing external resources.
├── css/
│   └── styles.css   # Custom CSS keyframes, 3D shifts, and pulse animations.
├── js/
│   └── main.js      # Core logic (GSAP timelines, Proximity glow, Canvas Engine).
└── README.md        # Documentation and deployment instructions.
\`\`\`

## 🚀 How to Deploy to GitHub Pages (No Code Required)

Since this project uses plain HTML/CSS/JS with no build steps required, deploying it on GitHub is incredibly simple. You don't even need Git installed on your local computer to do it!

### Step 1: Create a GitHub Repository
1. Go to [GitHub](https://github.com) and log into your account.
2. Click the **+** icon in the top right and select **New repository**.
3. Name it `iron-kingdom-digital-novel` (or anything you prefer).
4. Make it **Public** and check the box that says **Add a README file**.
5. Click **Create repository**.

### Step 2: Upload Files
1. In your new GitHub repository, click on the **Add file** button, then select **Upload files**.
2. Open the `c:\prompt_rachna\iron-kingdom-digital-novel\` folder on your local computer.
3. Drag and drop the `index.html`, `css` folder, and `js` folder directly into the GitHub upload area.
4. Scroll down and click **Commit changes**.

### Step 3: Enable GitHub Pages
1. In your GitHub repository, click the **Settings** tab at the top.
2. On the left sidebar, click **Pages** (under the "Code and automation" section).
3. Under **Build and deployment**, find the **Source** dropdown and make sure it says **Deploy from a branch**.
4. Under the **Branch** section, click the dropdown that says `None`, swap it to `main`, and click **Save**.
5. Wait ~1 to 2 minutes, refresh the page, and GitHub will provide you with a live URL (e.g., `https://yourusername.github.io/iron-kingdom-digital-novel/`).

Your cinematic digital novel is now live on the internet!
