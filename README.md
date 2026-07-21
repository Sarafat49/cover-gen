# 📄 Academic Assignment Cover Page Generator

A lightweight, single-page web application that allows students to dynamically generate formal academic assignment cover pages matching standard university layouts. Users can preview their changes live and automatically attach/merge the generated cover page directly to the front of their assignment PDF.

---

## ✨ Features

* **Live Interactive Preview:** See real-time formatting updates as you type.
* **Dual Layout Modes:** Supports both **Individual** and **Group** assignment submissions.
* **Flexible Instructor Layout:** 
  * Automatically centers a single teacher block when 1 instructor is entered.
  * Dynamically aligns 2 instructors side-by-side when both fields are filled.
* **Seamless PDF Merging:** Upload your existing assignment PDF, and the app compiles the cover page as Page 1 and appends your uploaded document into a single download.
* **Client-Side Processing:** Built using lightweight browser-based JS libraries (`html2canvas`, `jsPDF`, `pdf-lib`). No backend server needed—your documents stay private on your local machine.

---

## 🛠️ Built With

* **HTML5 / CSS3 / JavaScript (ES6)**
* **[Tailwind CSS](https://tailwindcss.com/):** For UI styling.
* **[html2canvas](https://html2canvas.hertzen.com/):** For capturing high-resolution DOM element renders.
* **[jsPDF](https://github.com/parallax/jsPDF):** For constructing standard A4 PDF pages.
* **[pdf-lib](https://pdf-lib.js.org/):** For merging multiple PDF binary streams in the browser.

---

## 🚀 Live Demo

Access the live generator hosted on GitHub Pages:
**[https://Sarafat49.github.io/cover-gen/](https://Sarafat49.github.io/cover-gen/)**

---

## 💻 Local Setup & Usage

Since this is a client-side static application, running it locally requires no build step:

1. Clone the repository:
   ```bash
   git clone https://github.com/Sarafat49/cover-gen.git
   ```

If anyone wants to improve this project, feel free to send a PR and I’ll merge it.