# Contact Form Setup Options

## Option 1: Formspree (Easiest - RECOMMENDED)

1. Go to https://formspree.io/
2. Sign up with your email
3. Create a new form
4. Get your form endpoint (looks like: `https://formspree.io/f/xxxxx`)
5. Update the form in `+page.svelte`:

```svelte
<form
  action="https://formspree.io/f/YOUR_FORM_ID"
  method="POST"
  class="bg-white border-2 border-black rounded-lg p-8 shadow-lg space-y-6"
>
```

**Pros:**
- No backend code needed
- Free tier: 50 submissions/month
- Automatic spam protection
- Email notifications

---

## Option 2: EmailJS (Free, No Backend)

1. Go to https://www.emailjs.com/
2. Sign up and create an email service
3. Get your Service ID, Template ID, and Public Key
4. Add EmailJS script and handle form with JavaScript

**Pros:**
- Free tier: 200 emails/month
- Client-side only
- More customization

---

## Option 3: SvelteKit Form Action (Most Control)

Create a SvelteKit server endpoint to handle the form and send emails via:
- Nodemailer
- SendGrid
- AWS SES

**Pros:**
- Full control
- No third-party limits
- Better security

**Cons:**
- Requires backend setup
- Email service configuration

---

## Quick Start: Use Formspree

For the fastest setup, I recommend **Formspree**. It takes 2 minutes:

1. Sign up at https://formspree.io
2. Create a form pointing to `teddy@stonewallmind.academy`
3. Copy your form endpoint
4. Let me know and I'll update the form!
