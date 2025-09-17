# AWS Cloud Club · CCT College Dublin

This repository contains the source code for the official website of the **AWS Cloud Club at CCT College Dublin**.  
It is a simple, modern, and responsive site intended to give the Club a public presence while keeping the implementation lightweight, fully debuggable, and transparent.

---

## Purpose

The site was built with three priorities in mind:

1. **Visibility** – Provide a clear identity for the Cloud Club that can be shared with students, staff, and external partners.  
2. **Accessibility** – Fully open source, mobile-friendly, and simple enough to be extended by any student with basic web development knowledge.  
3. **Professionalism** – Serve as a showcase of how to deliver a minimal but production-ready project, in line with academic and industry expectations.

---

## 🛠 Tech Stack

- **HTML5 / CSS3 / JavaScript** – No heavy frameworks, so everything is transparent and easy to debug.  
- **Responsive Design** – Sidebar on desktop, hamburger toggle on mobile.  
- **Background Video** – Fixed looping `.webm` / `.mov` asset with a subtle overlay for readability.  
- **Animations** – Sections fade in on scroll using the Intersection Observer API.  
- **Branding** – AWS dark slate + AWS orange for consistency with Cloud Club guidelines.

---

## Structure

website/
├── index.html # Main page
├── favicon.png # Tab icon
├── images/ # Logos, banners
└── assets/
└── bg/ # Background video (webm/mp4)


- `index.html` is fully commented for educational purposes (students can read it line by line).  
- All styling is inline in `<style>` for simplicity, but could be modularised later.  
- JavaScript is embedded at the bottom of the page to handle animations and menu toggle.

---

## Features

- **Fixed video background** with light overlay.  
- **Smooth scrolling navigation** with active link highlighting.  
- **Animated content** (fade + upward motion).  
- **Responsive layout** with hamburger menu for mobile users.  
- **Slack Invite CTA** – Call-to-action button on hero section links directly to Slack community:  
  [Join us in Slack →](https://join.slack.com/t/awsclubie/shared_invite/zt-36rnw9sja-XpcRWmJsQmgzL~DZCnYoTA)  

---

## How to Run Locally

1. Clone the repository:

   ```bash
   git clone https://github.com/<your-org>/<your-repo>.git
   cd website

2. Open index.html in a browser directly or use a simple development server (recommended):
`# Python 3`
`python3 -m http.server 5500`
`# then open` http://127.0.0.1:5500