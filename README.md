# Portfolio Website

A modern, responsive portfolio website showcasing projects and professional information. Built with HTML/CSS/JavaScript frontend and a Node.js backend server.

## Features

- **Responsive Design**: Mobile-friendly layout that works on all devices
- **Project Showcase**: Display your projects with images and descriptions
- **Professional Layout**: Clean and modern interface
- **Backend Integration**: Node.js server for handling requests and data
- **Email Support**: Nodemailer integration for contact forms

## Project Structure

```
portfolio-website/
├── index.html              # Homepage
├── projects.html           # Projects showcase page
├── resume.pdf              # Resume document
├── assets/
│   └── images/             # Project and profile images
├── backend/
│   ├── server.js           # Express server entry point
│   ├── package.json        # Node.js dependencies
│   └── node_modules/       # Installed packages
└── README.md               # This file
```

## Technologies Used

- **Frontend**: HTML5, CSS3, JavaScript
- **Backend**: Node.js, Express.js
- **Email**: Nodemailer
- **Dependencies**: CORS, Body Parser, and more

## Installation

### Prerequisites
- Node.js (v14 or higher)
- npm or yarn

### Setup

1. **Clone the repository**
   ```bash
   git clone https://github.com/skulk2545/Portfolio.git
   cd portfolio-website
   ```

2. **Install backend dependencies**
   ```bash
   cd backend
   npm install
   ```

3. **Configure environment variables** (if needed)
   - Create a `.env` file in the `backend` folder
   - Add any necessary configuration variables

## Usage

### Running the Frontend
Simply open `index.html` in your web browser or serve the static files through the backend.

### Running the Backend Server
```bash
cd backend
node server.js
```

The server will start and listen on a configured port (typically 3000 or 5000). Check `server.js` for the specific port.

## Deployment

### Frontend
- Deploy static files to services like Vercel, Netlify, or GitHub Pages
- Or serve through the Node.js backend

### Backend
- Deploy to platforms like:
  - Heroku
  - Railway
  - Render
  - AWS/Azure
  - DigitalOcean

## Features to Customize

1. **Update Personal Information**
   - Edit `index.html` with your name, bio, and contact info
   - Replace profile image in `assets/images/`

2. **Add Your Projects**
   - Edit `projects.html` to showcase your work
   - Add project images to `assets/images/`

3. **Configure Backend**
   - Set up email configuration in `backend/server.js` for contact forms
   - Adjust CORS settings as needed

4. **Add Your Resume**
   - Replace `resume.pdf` with your own resume

## Contributing

Feel free to fork this repository and customize it for your own portfolio!

## License

This project is open source and available under the MIT License.

## Contact

For questions or suggestions about this portfolio template, feel free to reach out through the contact form on the website.

---

**Repository**: [github.com/skulk2545/Portfolio](https://github.com/skulk2545/Portfolio)

*Last updated: January 26, 2026*
