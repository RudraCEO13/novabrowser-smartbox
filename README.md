# NovaBrowser - Smart Omnibox (Beta v1.0) 🚀

Welcome to **NovaBrowser Smart Box**, a clean, minimalist, and lightweight temporary browser interface designed specifically for developers during testing phases. Inspired by modern "Big Tech" UI layouts, this tool combines URL navigation and search capabilities into a single, intuitive input field.

---

## Key Features 🌟

* **Smart Omnibox:** Automatically detects whether the input is a web URL or a general search term. If it's a search term, it routes via Google Search with iframe-rendering parameters.
* **Automatic Protocol Handling:** No need to type `https://` every time; the engine appends it automatically for direct links.
* **Sleek Big-Tech UX:** A clean, distraction-free environment utilizing modern typography and sharp transitions.
* **Dynamic Full-Screen Workspace:** The top control panel automatically hides when you scroll down to maximize viewable space, and reappears smoothly when scrolling up.
* **Mobile Optimized:** Auto-focus blur logic ensures the virtual keyboard dismisses cleanly upon hitting 'Enter'.

---

## Technical Architecture 🛠️

This is a pure frontend implementation built with zero external dependencies:
* **Structure:** Semantic HTML5
* **Styling:** Vanilla CSS3 (featuring fixed layouts and transform-based animations)
* **Logic:** Native JavaScript (Touch/Wheel event tracking and RegEx-based URL routing)

---

## Developer Contribution & Guidelines 👨‍💻

This project is currently in its **Testing Phase**. Since it utilizes `<iframe>` architecture for quick testing, please note:
> ⚠️ **Note on Cross-Origin Policies:** Some high-security domains (like YouTube or standard Facebook) enforce `X-Frame-Options: SAMEORIGIN` which restricts them from rendering inside an iframe. Google Search functions flawlessly due to specific embedded query parameters (`&igu=1`). 

Feel free to fork this repository, optimize the scrolling logic, or experiment with native wrapper components!

---

## License 📄

This project is open-source and available under the [MIT License](LICENSE). Created with a vision to build clean digital utilities.
