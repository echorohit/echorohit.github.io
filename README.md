# Rohit Kumar Choudhary - Personal Website

Welcome to my personal website and digital resume, built with [Hugo](https://gohugo.io/) and the [PaperMod](https://github.com/adityatelange/hugo-PaperMod) theme.

## 🚀 Live Site
Visit my website at: [https://echorohit.github.io](https://echorohit.github.io)

## 🛠️ Technologies Used
- **Hugo**: Static site generator
- **PaperMod Theme**: Clean and responsive Hugo theme
- **GitHub Actions**: Automated deployment to GitHub Pages
- **Markdown**: Content creation

## 📁 Site Structure
- `content/`: Contains all the page content in Markdown format
  - `about.md`: Personal information and professional summary
  - `experience.md`: Work history and achievements
  - `education.md`: Educational background
  - `skills.md`: Technical skills and expertise
- `hugo.toml`: Hugo configuration file
- `themes/PaperMod/`: Theme files (git submodule)
- `.github/workflows/hugo.yml`: GitHub Actions workflow for deployment

## 🏃‍♂️ Local Development

### Prerequisites
- [Hugo Extended](https://gohugo.io/installation/) (v0.112.0 or later)
- Git

### Running Locally
1. Clone the repository:
   ```bash
   git clone https://github.com/echorohit/echorohit.github.io.git
   cd echorohit.github.io
   ```

2. Initialize the theme submodule:
   ```bash
   git submodule update --init --recursive
   ```

3. Start the development server:
   ```bash
   hugo server --buildDrafts
   ```

4. Open your browser and visit `http://localhost:1313`

## 📝 Content Management

To update content:
1. Edit the relevant Markdown files in the `content/` directory
2. Commit and push your changes
3. GitHub Actions will automatically build and deploy the site

## 🎨 Customization

The site can be customized by:
- Editing `hugo.toml` for site configuration
- Modifying content files in the `content/` directory
- Customizing the theme (though it's recommended to avoid direct theme modifications)

## 📧 Contact
- **Email**: mrohitchoudhary@gmail.com
- **GitHub**: [@echorohit](https://github.com/echorohit)
- **Twitter**: [@Twittsrohit](https://twitter.com/Twittsrohit)

---

Built with ❤️ using Hugo and deployed with GitHub Pages
