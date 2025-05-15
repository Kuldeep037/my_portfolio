# Kuldeep Sahu - Robotics Engineer Portfolio

A modern, responsive portfolio website showcasing my skills, experience, and projects as a robotics engineer. Built with Bootstrap 5.

## Features

- **Responsive Design**: Mobile-first design ensures compatibility across all devices
- **Modern UI**: Clean, professional layout with gradient accents
- **Multiple Pages**: 
  - Home page with introduction to my robotics expertise
  - Detailed resume highlighting my experience in robotics engineering
  - Projects showcase featuring autonomous systems and robotics solutions
  - Skills & Interests page to showcase additional skills and interests
  - Contact form for potential clients and collaborators

## Technologies Used

- HTML5
- CSS3
- Bootstrap 5
- JavaScript
- Google Fonts
- Bootstrap Icons

## Pages

1. **Home Page (index.html)**: Landing page introducing myself as a robotics engineer
2. **Resume (resume.html)**: Detailed professional experience in robotics, education, and technical skills
3. **Projects (projects.html)**: Portfolio of robotics projects including autonomous systems and robotic arms
4. **Skills & Interests (skills.html)**: Additional skills and interests beyond robotics, including artistic, physical, and mindfulness practices
5. **Contact (contact.html)**: Contact form for potential clients or employers

## Structure

```
my_portfolio/
├── assets/
│   ├── favicon.ico
│   ├── profile.png
│   ├── painting-1.jpg (to painting-6.jpg)
│   └── meditation-1.jpg (to meditation-3.jpg)
├── css/
│   └── styles.css
├── js/
│   └── scripts.js
├── projects/
│   ├── warehouse-robot.html
│   ├── robotic-arm.html
│   └── multi-robot.html
├── skills/
│   ├── painting.html
│   ├── meditation.html
│   └── (other skill pages will be added)
├── index.html
├── resume.html
├── projects.html
├── skills.html
├── contact.html
└── README.md
```

## Getting Started

### Local Development

1. Clone this repository:
   ```bash
   git clone https://github.com/kuldeepsahu/my_portfolio.git
   cd my_portfolio
   ```

2. Open `index.html` in your browser or use a local development server.

### Customization

- Replace the profile image in the `assets` folder with a professional photo
- Add more detailed robotics projects to `projects.html` with actual project images
- Update social media links with my actual profiles
- Integrate a functional contact form

## Deployment

This site can be deployed to any static site hosting platform:

- GitHub Pages
- Netlify
- Vercel
- Firebase Hosting
- Amazon S3

## Deployment on GitHub Pages

This portfolio is designed to be hosted on GitHub Pages. Follow these steps to deploy:

1. Create a GitHub repository named `username.github.io` (replace "username" with your GitHub username)
2. Push this project to the repository:
   ```bash
   git init
   git add .
   git commit -m "Initial commit"
   git remote add origin https://github.com/username/username.github.io.git
   git push -u origin main
   ```
3. Go to your repository settings on GitHub
4. Navigate to the "Pages" section
5. Select "main" branch as the source
6. Click "Save"
7. Your portfolio will be available at `https://username.github.io` within a few minutes

Alternatively, you can host this as a project site:

1. Create any repository for this project
2. Push the code
3. Go to repository settings > Pages
4. Set the branch to "main" and folder to "/ (root)"
5. Your site will be available at `https://username.github.io/repository-name`

## Important Notes

- To make the "Download Resume" button work, add your resume PDF file to the `assets` folder and name it `Kuldeep_sahu_resume.pdf`
- Add project images to enhance your portfolio:
  - Project thumbnails: Add images to the `assets` folder named:
    - `warehouse-robot-thumbnail.jpg`
    - `robotic-arm-thumbnail.jpg`
    - `multi-robot-thumbnail.jpg`
  - Detailed project images: Add full-sized images for each project:
    - Warehouse robot project: `assets/warehouse-robot-1.jpg`, `assets/warehouse-robot-2.jpg`, `assets/warehouse-robot-3.jpg`
    - Robotic arm project: `assets/robotic-arm-1.jpg`, `assets/robotic-arm-2.jpg`, `assets/robotic-arm-3.jpg`
    - Multi-robot project: `assets/multi-robot-1.jpg`, `assets/multi-robot-2.jpg`, `assets/multi-robot-3.jpg`, `assets/multi-robot-sim.jpg`
- Add research documents for each project (optional):
  - For warehouse robot: `assets/warehouse-robot-whitepaper.pdf`, `assets/warehouse-robot-presentation.pdf`
  - For robotic arm: `assets/robotic-arm-paper.pdf`, `assets/robotic-arm-technical-doc.pdf`
  - For multi-robot system: `assets/multi-robot-research.pdf`, `assets/multi-robot-design.pdf`
- Update YouTube video IDs in the project detail pages:
  - In each project's HTML file, replace `your-video-id` with actual YouTube video IDs
- Update social media links in `index.html` with your actual profiles

## Credits

- Template originally based on [Start Bootstrap - Personal](https://startbootstrap.com/template-overviews/personal)
- Icons from [Bootstrap Icons](https://icons.getbootstrap.com/)
- Fonts from [Google Fonts](https://fonts.google.com/)

## License

This project is licensed under the MIT License - see [StartBootstrap's License](https://github.com/StartBootstrap/startbootstrap-personal/blob/master/LICENSE) for details.

## Customization To-Do List

- [ ] Add actual profile photo
- [ ] Add screenshots of real robotics projects
- [ ] Set up contact form functionality
- [ ] Add links to GitHub repositories for open-source projects
- [ ] Add blog section for robotics insights and research
- [ ] Include downloadable resume file 