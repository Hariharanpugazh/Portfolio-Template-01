# Modern Portfolio Template

A clean, modern, and fully responsive portfolio template built with Next.js 13, TypeScript, and Tailwind CSS. Perfect for developers, designers, and professionals looking to showcase their work and skills.

## ✨ Features

- **Modern Design** - Clean and professional UI with smooth animations
- **Responsive Layout** - Optimized for all device sizes
- **Dark/Light Theme** - Toggle between themes with persistent storage
- **Contact Form** - Functional email contact form using Resend API
- **Smooth Animations** - Framer Motion animations and scroll effects
- **SEO Optimized** - Built with Next.js 13 for optimal performance
- **Type Safe** - Full TypeScript implementation
- **Fast Loading** - Optimized images and performance

## 🛠️ Tech Stack

- **Framework:** Next.js 13 (App Router)
- **Language:** TypeScript
- **Styling:** Tailwind CSS
- **Animations:** Framer Motion
- **Email:** Resend API + React Email
- **Icons:** React Icons
- **Deployment:** Vercel Ready
- **Analytics:** Vercel Analytics

## 🚀 Quick Start

### Prerequisites

- Node.js 18.0 or later
- npm, yarn, or pnpm

### Installation

1. **Clone the repository**
   ```bash
   git clone https://github.com/your-username/portfolio-template.git
   cd portfolio-template
   ```

2. **Install dependencies**
   ```bash
   npm install
   ```

3. **Set up environment variables**
   ```bash
   cp .env.example .env.local
   ```
   Add your Resend API key:
   ```
   RESEND_API_KEY=your_resend_api_key_here
   ```

4. **Run the development server**
   ```bash
   npm run dev
   ```

5. **Open your browser**
   Navigate to [http://localhost:3000](http://localhost:3000)

## 🎨 Customization

### Personal Information

Edit the following files to add your personal information:

- **`lib/data.ts`** - Update projects, skills, experience, and navigation
- **`components/Intro.tsx`** - Modify introduction text and social links
- **`public/`** - Replace profile image and project screenshots
- **`public/Resume.pdf`** - Add your resume/CV

### Styling

- **Colors:** Modify `tailwind.config.js` for custom color schemes
- **Fonts:** Update `app/layout.tsx` for different font families
- **Layout:** Adjust spacing and sizing in component files

### Contact Form

1. Sign up for a [Resend](https://resend.com) account
2. Get your API key and add it to `.env.local`
3. Update the recipient email in `components/actions/sendEmail.ts`

## 🚀 Deployment

### Vercel (Recommended)

1. Push your code to GitHub
2. Connect your repository to [Vercel](https://vercel.com)
3. Add environment variables in Vercel dashboard
4. Deploy automatically

### Other Platforms

This template works with any platform that supports Next.js:
- Netlify
- Railway
- DigitalOcean App Platform
- AWS Amplify

## 📁 Project Structure

```
├── app/                    # Next.js 13 app directory
│   ├── globals.css         # Global styles
│   ├── layout.tsx          # Root layout
│   └── page.tsx           # Home page
├── components/            # React components
│   ├── About.tsx          # About section
│   ├── Contact.tsx        # Contact form
│   ├── Experience.tsx     # Experience timeline
│   ├── Projects.tsx       # Projects showcase
│   ├── Skills.tsx         # Skills section
│   └── ThemeSwitch.tsx    # Dark/light toggle
├── context/               # React context providers
├── lib/                   # Utilities and data
│   ├── data.ts           # Portfolio content
│   ├── hooks.ts          # Custom hooks
│   └── types.ts          # TypeScript types
└── public/               # Static assets
```

## 🌐 Browser Support

- Chrome (latest)
- Firefox (latest)
- Safari (latest)
- Edge (latest)

## 📄 License

This project is open source and available under the [MIT License](LICENSE).

## 🤝 Contributing

Contributions are welcome! Please feel free to submit a Pull Request.

## ⭐ Support

If you found this template helpful, please give it a star on GitHub!

---

**Made with Next.js and Tailwind CSS**