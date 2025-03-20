# AI Anime Art Generator

Welcome to the codebase of the wonderful tool AI Anime Generator!

AI Anime Generator is a deep learning-powered tool that creates high-quality anime-style artwork from sketches, descriptions, or real images. Using advanced neural networks like GANs (Generative Adversarial Networks) and diffusion models, the AI generates unique anime characters, backgrounds, and illustrations. This project is ideal for artists, content creators, and anime enthusiasts who want to explore AI-generated anime art.

## Use Cases

### Character Design for Anime

Create detailed and unique character designs for your anime series or manga. Customize every aspect to fit your story's needs and bring your characters to life with vibrant colors and dynamic expressions.

### Custom Avatars for Social Media

Generate personalized avatars for your social media profiles. Stand out with unique, AI-created anime artwork that reflects your personality and style.

### Art Inspiration and Exploration

Use the AI Anime Art Generator to explore new artistic styles and ideas. Experiment with different designs and color schemes to find inspiration for your next big project.

## Tech Stack

AI Anime Art Generator is built on the following stack:

- Next.js – Frontend/Backend
- TailwindCSS – Styles
- Google Analytics
- Vercel - Hosting
- Replicate - Image Generation
- CloudFlare R2 - Image Storage
- Clerk - User Login

## Deployment

Clone the codebase to your local machine.

```bash
git clone https://github.com/dtoyoda10/anime-gen.git
cd anime-gen
```

Initialize your local postgres database or use remote Supabase database.

```bash
export DATABASE_URL=your_local_postgres_connstr
npx prisma migrate dev
```

Copy the .env.example file to .env.local, fill in the environment variables.

Then you can run the project locally:

```bash
npm run dev
```

Open your local website: http://localhost:3000.

## Acknowledgements

This project heavily references another project [Landing page boilerplate](https://landingpage.weijunext.com/), and we are very grateful for their support.
