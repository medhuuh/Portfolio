Portfolio Website Implementation Plan
The objective is to create a single-page portfolio for Midhun Sha, featuring a dark neumorphic design (Inbio theme) and an interactive "Anti-Gravity" mode using Matter.js.

Proposed Changes
[Component] Portfolio Sections
Hero: Introduce Midhun Sha as a Final Year BCA Student & Creative Developer.
Education: Show BCA at Srinivas University and UI/UX Designing Course.
Projects: Grid of project cards (E-Commerce).
Resume: Dedicated section toggled via navigation, showing the resume image and a download button.
Certifications: Dedicated section toggled via navigation, showing thumbnails of certifications.
[Component] UI/UX & Design System
Theme: Dark mode (#212428) with neumorphic cards and pink accents (#ff014f).
Navigation: Single-page structure with hash-based or JS-based section switching.
Matter.js Physics:
A "Break Portfolio" button that transforms standard DOM elements into Matter.js physics bodies.
Elements will fall under gravity and be draggable/throwable.
Verification Plan
Automated Tests
Not applicable for this vanilla HTML/CSS/JS project, but manual browser testing is priority.
Manual Verification
Verify that nav links correctly switch between "Home", "Resume", and "Certifications".
Verify that "Break Portfolio" triggers the Matter.js simulation and elements react to gravity.
Verify that the resume image and download link function as expected.
Check responsiveness on different screen sizes.