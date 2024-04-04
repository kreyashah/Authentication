# Authentication
This is the node JS application that provides the functionality for signin, signup, signout, forget password, reset password & google signin.

# Features
  1.  **Sign Up**: User can create the account using name, email & password.
  2.  **Sign In**: User can login into the system using email & password.
  3.  **Sign Out**: User can signout from their account.
  4.  **Reset Password**: User can change their password using reset password option.
  5.  **Encrypt password**: Password will be stored in the encrypted format in the database.
  6.  **Google signIn**: User can sign in in the system using the google account.
  7.  **Forgot password**: If user forget their password then by entering the email Id they can get the new password.
  8.  **Reset Password**: User can change their password.
  9.  **ReCAPTCHA Integration**: reCAPTCHA for both sign in & sign up.

# Environment Variable
  1. PORT
  2. DB_URL
  3. CLIENT_ID
  4. CLIENT_SECRET
  5. EMAIL
  6. PASSWORD
  7. CLIENT_URL
  8. CALLBACK_URL

# Installation
  1. First clone the repository.
  2. In the terminal write npm install command
  3. Run npm app.js
  4. In the browser open HTTP://localhost:3000

# Dependencies
  1. bcrypt
  2. body-parser
  3. cookie-session
  4. dotenv
  5. ejs
  6. express
  7. express-ejs-layouts
  8. express-session
  9. mongoose
  10. nodemailer
  11. passport
  12. passport-google-oauth2
  13. path

