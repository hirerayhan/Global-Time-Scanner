Create a fully functional single-file HTML website that shows the current time and date of any country when the user searches by country name.

Core Features:
1. User can type any country name (example: United States, Bangladesh, Japan, UK, Canada, Australia, Germany, France, UAE, Saudi Arabia, India etc.)
2. The website will automatically detect the correct timezone of that country.
3. Show:
   - Current Time (live updating every second)
   - Current Date
   - Timezone name (example: GMT+6, EST, PST etc.)
4. Show result instantly after clicking search button or pressing Enter.
5. Must support 200+ countries.
6. Use JavaScript timezone database (Intl API or timezone list).
7. No external paid API required.
8. Everything must work offline except timezone logic.
9. Code must be clean and under 4000 lines.

Design Requirements (Cyber Theme):
1. Cyberpunk / hacker style UI
2. Dark background (#020617 or #000000)
3. Neon glow colors (cyan, green, purple)
4. Futuristic font style
5. Glowing search box
6. Animated gradient border
7. Neon button hover effect
8. Digital clock style numbers
9. Smooth animation transitions
10. Responsive mobile friendly layout

UI Sections:
1. Title: "Global Time Scanner"
2. Subtitle: "Search any country to view live time"
3. Search Input Box
4. Search Button
5. Result Card showing:
   - Country Name
   - Current Time (large digital font)
   - Current Date
   - Timezone
6. Footer text: "Cyber Time System"

Technical Requirements:
1. Use HTML + CSS + JavaScript only
2. Must be single .html file
3. Do not use frameworks
4. Use modern CSS (flexbox or grid)
5. Add glowing animation using CSS keyframes
6. Use Intl.DateTimeFormat for timezone detection
7. Include mapping of country to timezone
8. Add fallback message if country not found

Extra Features:
1. Typing animation effect on title
2. Neon glowing border animation
3. Loading animation while searching
4. Auto focus cursor on input field
5. Press Enter triggers search
6. Show multiple timezone countries properly (example USA)
7. Add placeholder example text in search box

Output:
Provide complete working code in one HTML file.
