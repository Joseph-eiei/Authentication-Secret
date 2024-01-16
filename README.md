# Secret 🤫

A simple website built for learning authentication and security using bcrypt, passport, dotenv, Google OAuth, and PostgreSQL for the database.

## How it Works ❓

1. **Register:**
   - Create an account using email and password or sign up with Google.

2. **Access the Secret Page:**
   - After registration, you'll be redirected to the secret page.

3. **Submit Your Secret:**
   - New users can submit a secret by clicking 'Submit a Secret.'
 
4. **View Your Secret:**
   - Your submitted secret will be displayed on the secret page after submission.

## Tech Stack 🤖

- **Authentication:** bcrypt, passport, Google OAuth
- **Database:** PostgreSQL
- **Environment Variables:** dotenv

## Getting Started ✅

To run locally:

1. **Clone the Repository:**
```
git clone https://github.com/Joseph-eiei/Authentication-Secret.git
```

2. **Navigate to Project Directory:**
```
cd Authentication-Secret
```

3. **Install Dependencies:**
```
npm i
```

4. **Setup Your Environment Variable:**
- Create ```.env``` Then add
```
SESSION_SECRET=your_session_encrypt_key
```

5. **Setup Local Database:**
- Create a PostgreSQL database locally.
- Update the database connection settings in the ```.env``` file with your local database credentials.
```
PG_USER=your_pg_user
PG_HOST=your_pg_host
PG_DATABASE=your_pg_database
PG_PASSWORD=your_pg_password
PG_PORT=your_pg_port
```

6. **Add Google OAuth Credentials:**
- Obtain your Google OAuth 2.0 Client ID and Client Secret by creating a project on the [Google Cloud Console](#https://console.cloud.google.com/).
- Update the ```.env``` file with your Google Client ID and Client Secret:
```
GOOGLE_CLIENT_ID=your-client-id
GOOGLE_CLIENT_SECRET=your-client-secret
```

7. **Run the Website:**
```
node index.js
```

8. **Open in Your Browser:**
- Visit [localhost:3000](#http://localhost:3000) and share your secret!

**Feel free to use, share, and explore. Happy coding! 🚀**



