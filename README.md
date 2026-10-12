# Lunare

Lunare is a simple Angular-based Progressive Web App (PWA) that calculates and displays the current lunar day based on traditional lunar calendar rules.

## Live Demo
https://etordev.github.io/lunare

## Tech Stack
- Angular 21 (`@angular/core` ^21.2.x)
- TypeScript ~5.9
- RxJS ~7.8
- ngx-translate (i18n)
- HTML5 / CSS3
- GitHub Pages (static deployment from the `gh-pages` branch)

## Local Development
1. Clone the repository  
   `git clone https://github.com/etordev/lunare.git`
2. Navigate into the project folder  
   `cd lunare`
3. Install dependencies  
   `npm install`
4. Run the development server  
   `npm start` (or `ng serve`)
5. Open in browser  
   http://localhost:4200/

## Notes
- Implemented as a lightweight PWA
- Deployed as a static web application
- Focus on simplicity and clarity
- Production build: `npm run build:prod` (output in `dist/lunare/browser/`, `baseHref` `/lunare/`)
