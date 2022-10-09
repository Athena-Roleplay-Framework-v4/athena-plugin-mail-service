# Athena Plugin - Mail Service

An email service plugin for the Athena Framework compatible with `3.9.0` of the [Athena Framework](https://athenaframework.com/).

## Installation

1. Open a command prompt in your main Athena Directory.
2. Navigate to the plugins folder.

```ts
cd src/core/plugins
```

3. Copy the command below.

**SSH**

```
git clone git@github.com:Stuyk/athena-plugin-mail-service.git
```

**HTTPS**
```
git clone https://github.com/Stuyk/athena-plugin-mail-service
```
4. `npm install nodemailer`
5. You need a domain (.com, .org, whatever) registered under you.
6. Utilize https://sendgrid.com/
7. Setup Sender Authentication https://app.sendgrid.com/settings/sender_auth
8. Go through the steps to verify your domain with sendgrid.
9. Create an API key https://app.sendgrid.com/settings/api_keys
10. In `server/src/config.ts` fill in the information.
   6a. Leave username alone if using SendGrid
   6b. Only fill in password with API key.
11. Send a test email by writing some code to double check everything is okay. :)