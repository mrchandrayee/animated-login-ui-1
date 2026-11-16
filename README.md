# Animated Login UI

[![Live Demo](https://img.shields.io/badge/Live%20Demo-GitHub%20Pages-blue?style=for-the-badge&logo=github)](https://mrchandrayee.github.io/animated-login-ui-1/)
[![HTML](https://img.shields.io/badge/HTML5-E34F26?style=for-the-badge&logo=html5&logoColor=white)](https://developer.mozilla.org) [![CSS](https://img.shields.io/badge/CSS3-1572B6?style=for-the-badge&logo=css3&logoColor=white)](https://developer.mozilla.org) [![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?style=for-the-badge&logo=javascript&logoColor=black)](https://developer.mozilla.org)
[![License: MIT](https://img.shields.io/badge/License-MIT-green?style=for-the-badge)](./LICENSE)

Responsive, dependency-free login screen recreated from the uploaded screen recording.

## Run
Open `index.html` in a modern browser. No build tools or npm packages are required.

Optional local server:
```bash
python3 -m http.server 8000
```
Then visit http://localhost:8000.

## Included
- Animated organic / morphing circular outline with neon-green glow
- Dark navy login panel
- Username and password fields with floating labels
- Show / hide password control
- Sign in form validation and demo feedback
- Forgot Password and Signup placeholder interactions
- Responsive layout and reduced-motion support

## Source extraction note
The video visibly shows the title “Animated Login UI” and these CSS declarations:
- `.square`: relative positioning, 500px width/height, flex centering
- `.square i`: absolute positioning, `inset: 0`, 1px solid white border, 0.5s transition
- `.square i:nth-child(1)`: `border-radius: 38% 62% 63% 37% / 41% 44% 56% 59%`, `animation: animate 6s linear infinite`, `background-color: rgb(4, 35, 84)`

The rest of the UI and interactions are implemented as a runnable reconstruction because the recording does not show the complete original HTML, CSS, or JavaScript source. Login is frontend-only; no authentication backend is connected.

## 👨‍💻 Author

**mrchandrayee** · [GitHub](https://github.com/mrchandrayee)

## 📄 License

[MIT License](./LICENSE)
