# Project-1-Personal-AI-Content-Assistant
This is my first project for the class Advanced Web Design

**Product Brief**

The Field Hockey Training Generator addresses a significant challenge faced by field hockey players and coaches: the time-consuming process of designing personalized, skill-appropriate training exercises. Traditional practice planning requires extensive knowledge of drill progressions, understanding of different skill levels, and the ability to scale exercises for varying group sizes. Players who want to practice independently or coaches preparing for sessions with limited time often struggle to create effective, targeted drills that match their specific needs. This results in generic training that may not address individual skill gaps or utilize available player numbers effectively.
Our target users span the entire field hockey community. Primary users include individual players at all levels, from beginners learning fundamental stick skills to advanced athletes refining specific techniques, who need solo practice exercises. Secondary users are coaches at high school, club, and collegiate levels who require fresh drill ideas for practice sessions with different team sizes. The tool serves anyone seeking efficient, quality training content without spending hours researching drill libraries.
The approach's effectiveness lies in its intelligent personalization combined with immediate actionability. By capturing three critical parameters: skill level, number of participants, and target skill, the AI generates exercises specifically calibrated to the user's context. The output format prioritizes clarity and speed: concise equipment lists, straightforward setup descriptions, and numbered steps that players can follow immediately without interpretation. The regeneration feature provides variation. This combination of personalization, simplicity, and speed transforms what typically takes 15-30 minutes of planning into a 30-second process, democratizing access to quality training design for the entire field hockey community.

**How to Use**
1.	Select your skill level from the dropdown menu: choose from Beginner (learning fundamentals), Average (comfortable with basics), Advanced (competitive player), or Pro (elite level training)
2.	Enter the number of players who will participate in this exercise: input "1" for individual practice, or any number from 2-30 for partner or team drills
3.	Specify the skill you want to develop in the text field: be specific (examples: dribbling under pressure, aerial passes, penalty corner defense, 3D skills, reverse stick, elimination moves)
4.	Click "Generate Training Exercise" to receive your personalized drill: the AI will create a complete exercise with equipment list, setup instructions, and step-by-step actions
5.	Review the generated exercise carefully: note the equipment needed, understand the setup layout, and read through all steps before starting
6.	Click "Generate Different Exercise" if you want an alternative drill using the same parameters: perfect for getting variety or finding an exercise that matches your available equipment
7.	Click "Clear" to reset all fields and start over with completely different parameters: use this when switching focus to a different skill or changing player count

**Tech Stack**

AI Coding Assistant Used:
•	Claude
•	Used extensively for component architecture design, React state management implementation, UI/UX iteration, and API integration debugging. Claude assisted in creating the custom SVG crossed hockey sticks icon, implementing responsive design with Tailwind CSS, and refining the prompt engineering to achieve optimal exercise output format.
Deployment Platform:
•	GitHub Pages
•	Chosen for its free hosting, seamless GitHub repository integration, reliable uptime, and global CDN for fast loading times across all geographic locations.
Design:
•	Color Scheme - Syracuse University brand colors: Orange (#F76900) and Navy Blue (#000E54)
•	Responsive Design - Mobile-first approach ensuring full functionality on smartphones, tablets, and desktop computers

**Reflection**

Using AI to build this project made everything much faster and easier. Claude created the basic code structure right away, so I could focus on making the tool user-friendly instead of writing complicated code from scratch. The AI quickly made different design options for me to choose from and was really helpful when creating the crossed hockey sticks logo, adjusting it based on my feedback. This project taught me how to clearly explain what I want to AI tools to get the best results.
The hardest part was getting the exercise format right. At first, the AI created exercises that were way too long with lots of bold text and special formatting that looked messy. It took several tries to get the clean, simple format with just six steps that I wanted. I also had to learn how to properly connect to the Claude API and handle things like loading states and error messages, which was confusing at first.
For version 2.0, I would add a "Save" button so users can keep their favorite exercises, a way to print exercises as PDFs for using on the field, and filters to find exercises based on what equipment you have available. Adding simple diagrams showing where to set up cones and players would make instructions even clearer.
