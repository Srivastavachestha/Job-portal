# JOB_PORTAL - Modern Job Search Platform

A fully responsive job portal website built with HTML, CSS, and JavaScript. Connect job seekers with top companies across multiple industries, offering a seamless experience for browsing and applying to job opportunities.

## 🌟 Features

### For Job Seekers
- **Advanced Job Search**: Real-time search functionality with dynamic filtering across 17+ job listings
- **Multiple Categories**: Browse jobs from leading companies including Google, Meta, Apple, LinkedIn, Uber, Yahoo, WordPress, and Instagram
- **Detailed Job Pages**: Each job listing includes comprehensive information including:
  - Company details and location
  - Salary range and working hours
  - Employment type (Full-time, Part-time, Freelance)
  - Workplace preferences (Remote, Hybrid, On-site)
  - Education and experience requirements
  - Detailed job descriptions
- **Responsive Design**: Fully optimized for desktop, tablet, and mobile devices
- **Interactive UI**: Smooth transitions and hover effects for better user experience

### For Employers
- **Contact Form**: Functional contact form with PHP backend for direct communication
- **Company Showcase**: Feature multiple job openings from the same company
- **Professional Presentation**: Clean, modern interface that reflects your brand

## 🛠️ Tech Stack

- **Frontend**: HTML5, CSS3, JavaScript (Vanilla)
- **Backend**: PHP (for contact form)
- **Icons**: Boxicons
- **Fonts**: Google Fonts (Poppins)
- **Design**: Custom CSS with mobile-first approach

## 📚 Learning & Inspiration

This project was developed as part of my web development learning journey.
I followed a YouTube tutorial series to understand the implementation and
then customized the project with my own content, links, styling, and modifications.

**Learning Resource:** [YouTube Tutorial Series](https://youtube.com/playlist?list=PL9bD98LkBR7ONxaKGJjcP0aWXgTNbOwno&si=Kaxge1_UFpNgpjsi)

## 📁 Project Structure
```
JOB_PORTAL/
├── index.html              # Homepage
├── contact.html            # Contact page
├── style.css              # Main stylesheet
├── script.js              # Main JavaScript file
├── toggle.js              # Mobile menu toggle
├── send_email.php         # Contact form handler
├── README.md              # Project documentation
├── jobs/
│   ├── job.html           # Job listings page
│   ├── job-details.html   # Individual job details
│   ├── job-list.js        # Job data array
│   └── jobSearch.js       # Search functionality
└── images/
    ├── logo.png           # Site logo
    ├── hero.PNG           # Hero section image
    ├── hero1.png          # Alternative hero image
    ├── contact.svg        # Contact page illustration
    ├── google.png         # Company logos
    ├── facebook.png
    ├── linkedin.png
    ├── uber.png
    ├── apple.png
    ├── yahoo.png
    ├── wordpress.png
    ├── instagram.png
    ├── vacancy.png        # Job info icons
    ├── hour.png
    ├── salary.png
    ├── date.png
    ├── fe 1.png          # Feature icons
    ├── fe 2.png
    ├── fe 3.png
    ├── fe 4.png
    ├── fl-1.png          # Freelancer icons
    ├── fl-2.png
    ├── fl-3.png
    ├── fl-4.png
    └── t1.png - t6.png   # Team/trust images
```

## 🚀 Getting Started

### Prerequisites
- Web browser (Chrome, Firefox, Safari, Edge)
- Local server (XAMPP, WAMP, or Live Server extension for VS Code)
- PHP installed (for contact form functionality)

### Installation

1. **Clone the repository**
```bash
   git clone https://github.com/Srivastavachestha/Job-portal.git
   cd Job-portal
```

2. **Update email configuration**
   Open `send_email.php` and replace the email address:
```php
   $to = "your-email@gmail.com";  // Replace with your email
```

3. **Start local server**
   - **Using XAMPP/WAMP**: Place project in `htdocs` folder and access via `localhost`
   - **Using VS Code**: Install Live Server extension and click "Go Live"

4. **Open in browser**
```
   http://localhost/JOB_PORTAL
```

## 💻 Usage

### For Job Seekers

1. **Browse Jobs**: Visit the homepage and click "Browse Jobs" to see all available positions
2. **Search**: Use the search bar to filter jobs by title, company, or keywords
3. **View Details**: Click on any job card to see full job description and requirements
4. **Apply**: Click "Apply Now" button on job details page to get started
5. **Contact**: Use the contact form for any inquiries

### For Developers

**Adding New Jobs:**
Edit `jobs/job-list.js` and add new job objects to the `jCategory` array:
```javascript
{
    index: 17,
    image: "../images/company.png",
    title: "Job Title",
    rate: "Salary Range",
    av: "Employment Type",
    companyName: "Company Name",
    location: "City, India",
    vacancy: "Number",
    hours: "Hours / Week",
    workplace: "Work Type",
    education: "Degree Required",
    experience: "Years Required",
    description: "Full job description..."
}
```

**Customizing Styles:**
- Main colors: Edit CSS variables in `style.css`
- Primary color: `#51a995`
- Secondary color: `#1f4a40`
- Accent color: `#edcfee`

## 📱 Responsive Breakpoints

- **Desktop**: 1200px and above
- **Tablet**: 700px - 1199px
- **Mobile**: Below 699px

## 🎨 Color Palette
```css
Primary Green: #51a995
Dark Green: #1f4a40
Light Green: #c1e1d9
Background: #f8fcfa
Accent Purple: #edcfee
Text Dark: #333333
Text Light: #666666
```

## 🔧 Configuration

### Contact Form Setup

1. Ensure PHP is installed and running
2. Update SMTP settings if needed
3. Test form submission locally before deployment
4. For production, consider using services like:
   - Formspree
   - EmailJS
   - Netlify Forms

### Google Maps Integration

The contact page includes an embedded Google Map. To customize the location:
1. Go to [Google Maps](https://maps.google.com)
2. Search for your location
3. Click "Share" → "Embed a map"
4. Copy iframe code and replace in `contact.html`

## 🌐 Browser Support

- Chrome (latest)
- Firefox (latest)
- Safari (latest)
- Edge (latest)
- Opera (latest)

## 📈 Future Enhancements

- [ ] User authentication system
- [ ] Employer dashboard
- [ ] Job application tracking
- [ ] Resume upload functionality
- [ ] Email notifications
- [ ] Advanced filtering options
- [ ] Saved jobs feature
- [ ] Company review system

## 🤝 Contributing

Contributions are welcome! If you'd like to improve this project:

1. Fork the repository
2. Create a feature branch (`git checkout -b feature/AmazingFeature`)
3. Commit your changes (`git commit -m 'Add some AmazingFeature'`)
4. Push to the branch (`git push origin feature/AmazingFeature`)
5. Open a Pull Request

## 📄 License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.
## 👨‍💻 Author

**Chestha Srivastava**
- GitHub: [@Srivastavachestha](https://github.com/Srivastavachestha)
- Email: srivastavachestha@gmail.com

## 🙏 Acknowledgments

- Job data and company information for demonstration purposes only
- Icons provided by [Boxicons](https://boxicons.com)
- Fonts from [Google Fonts](https://fonts.google.com)
- Inspired by modern job portal platforms

## 📞 Support

For support, email srivastavachestha@gmail.com or open an issue in the GitHub repository.

---

**⭐ If you found this project helpful, please consider giving it a star!**

Made with ❤️ by Chestha Srivastava