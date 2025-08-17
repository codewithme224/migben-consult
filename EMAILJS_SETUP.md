# EmailJS Setup Guide for Migben Consultancy Contact Form

This guide will help you set up EmailJS to enable the contact form to send emails directly to migbenconsultancy@gmail.com.

## Step 1: Create EmailJS Account

1. Go to [https://www.emailjs.com/](https://www.emailjs.com/)
2. Sign up for a free account (allows 200 emails/month)
3. Verify your email address

## Step 2: Add Email Service

1. In your EmailJS dashboard, go to **Email Services**
2. Click **Add New Service**
3. Choose **Gmail** (recommended for Gmail accounts)
4. Follow the OAuth setup to connect your Gmail account
5. Set the **Service ID** (e.g., `service_migben`)
6. Save the service

## Step 3: Create Email Template

1. Go to **Email Templates** in your dashboard
2. Click **Create New Template**
3. Set the **Template ID** (e.g., `template_contact`)
4. Use this template content:

```
Subject: New Contact Form Submission from {{from_name}}

Hello,

You have received a new contact form submission from the Migben Consultancy website:

**Contact Details:**
- Name: {{from_name}}
- Email: {{from_email}}
- Phone: {{phone}}
- Service Interest: {{service}}

**Message:**
{{message}}

Please respond to this inquiry at your earliest convenience.

Best regards,
Migben Consultancy Website Contact Form
```

5. Save the template

## Step 4: Get Your Public Key

1. Go to **Account** → **General**
2. Find your **Public Key** (looks like: `user_xxxxxxxxxx`)
3. Copy this key

## Step 5: Update Configuration

1. Open `src/config/email.ts`
2. Replace the placeholder values with your actual EmailJS credentials:

```typescript
export const emailConfig = {
  serviceId: 'service_migben', // Your actual service ID
  templateId: 'template_contact', // Your actual template ID
  publicKey: 'user_xxxxxxxxxx', // Your actual public key
  recipientEmail: 'migbenconsultancy@gmail.com'
}
```

## Step 6: Test the Contact Form

1. Build and run your application
2. Fill out the contact form with test data
3. Submit the form
4. Check migbenconsultancy@gmail.com for the email

## Troubleshooting

### Common Issues:

1. **"Template not found" error**: Check that your template ID matches exactly
2. **"Service not found" error**: Check that your service ID matches exactly
3. **"Invalid public key" error**: Make sure you copied the full public key
4. **Emails not receiving**: Check Gmail spam folder, verify email service setup

### Testing Tips:

- Use browser developer tools to check console for errors
- Start with the EmailJS test feature in their dashboard
- Verify all configuration values match your EmailJS account

## Security Notes

- The public key is safe to use in client-side code
- EmailJS handles the secure transmission to your email service
- Consider implementing rate limiting for production use
- Monitor your EmailJS usage to stay within limits

## Upgrading EmailJS

If you need more than 200 emails/month, consider upgrading to a paid plan:
- Personal: $15/month (2,000 emails)
- Professional: $50/month (10,000 emails)

For questions or support, contact EmailJS at support@emailjs.com
