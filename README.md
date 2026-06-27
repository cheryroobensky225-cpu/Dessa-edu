
# DessaEdu
#### Video Demo: <https://youtu.be/ajdeo41aeww?si=cuds0rMJH2nE3Vo5>
#### Description:
What is DessaEdu?

DessaEdu is a free educational web platform designed for students in the NS1 (Niveau Secondaire 1) grade level in Haiti. The name is inspired by Jean-Jacques Dessalines, the founding father of Haiti, as a symbol of strength, independence, and the fight for a better future — which is exactly what education represents for Haitian youth today.

The core idea behind DessaEdu is simple: many students in Haiti do not have access to quality educational resources, whether due to limited internet connectivity, lack of books, or the high cost of private tutoring. DessaEdu aims to bridge that gap by providing a clean, easy-to-navigate website where students can find free video lessons in Mathematics, Physics, and Chemistry — all aligned with the Haitian NS1 curriculum.

The platform was built entirely with HTML, CSS, and JavaScript, and is hosted for free using GitHub Pages, making it accessible to anyone with a browser and an internet connection.


Files and Structure

index.html

This is the main homepage of the website. It displays all available lessons from every subject in a card-based layout. Each card shows a thumbnail image (pulled from YouTube), the subject category, the lesson title, and a link to watch the video. The page also includes a filter bar at the top that allows students to browse by subject (All, Maths, Physique, Chimie) without having to reload the page — this filtering is handled dynamically with JavaScript.

math.html

This page displays only the Mathematics lessons. It follows the same card layout as the homepage but is pre-filtered to show Maths content only. This makes it easier for a student who specifically wants to study math to go directly to the relevant content without scrolling through other subjects.

physics.html

Similar to math.html, this page is dedicated to Physics (Physique) lessons. It lists all available physics videos in the same clean card format.

chimie.html

This page contains the Chemistry (Chimie) lessons. Having separate pages per subject was an intentional design decision to make navigation simple and intuitive, especially for younger students who may not be very comfortable with technology.

style.css (or inline styles)

The styling of DessaEdu was designed to be minimal and clean. The color palette uses bright tones to give the site a modern, professional feel while remaining easy to read. The layout is fully responsive so that it works well on both desktop computers and mobile phones — an important consideration since many students in Haiti access the internet primarily through smartphones. Cards are displayed in a responsive grid that adapts to different screen sizes.



Design Choices

One major design decision was to use YouTube video embeds rather than hosting videos directly. Hosting video files would be expensive and slow, while YouTube already hosts high-quality educational content (such as Khan Academy videos) for free. By curating the best existing videos and organizing them under one platform aligned with the Haitian curriculum, DessaEdu adds real value without needing to reinvent the wheel.

Another choice was to keep the site as lightweight as possible — no heavy frameworks, no databases, no backend. This was deliberate: a simple HTML/CSS/JS site loads fast even on slow connections, which is critical in Haiti where internet speeds can be limited. It also means the site can be hosted entirely on GitHub Pages at no cost.

I also considered building a search feature but decided against it for now, as the number of lessons is small enough that filtering by subject is sufficient. As the platform grows, a search bar could be added in a future version.


Personal Motivation

I am a NS1 student in Haiti, and I built this project because I know firsthand how difficult it can be to find good study resources. I wanted to create something that would genuinely help my classmates and other students across the country. Haiti has an enormous amount of talented young people — they just need access to tools and knowledge.

DessaEdu is my small contribution to that effort. It is named after Dessalines not just for the historical reference, but because building this site felt like a personal act of independence: taking what I learned from CS50 and using it to create something real, useful, and lasting for my community.


Technology Stack


HTML5 — structure and content of all pages
CSS3 — styling, responsive grid layout, card design
JavaScript — dynamic subject filtering on the homepage
GitHub Pages — free hosting
YouTube — video content (Khan Academy and other educational channels)



Future Improvements

If I continue developing DessaEdu, I would like to add:


More subjects History, Biology, French, etc.
A quiz or exercise section so students can test their knowledge
A search bar to find lessons quickly
Support for offline use (Progressive Web App)
A Haitian Creole (Kreyòl) version of the interface



 — Built with passion by Chery Roobensky, NS1 student in Haiti. Inspired by Jean-Jacques Dessalines.