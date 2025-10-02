# Sprint 2 Retrospective

## What went well in the previous sprint?
- I implemented `Login/Signup` feature with "firebase authentication". So, users can now create accounts and log in securely. I use form components to submit user credentials and created custom hooks for auth and error handling. My form follows HTML standard, so user can use "Enter" key to submit the form.
- I implemented Modal component to display `Add Form` and `Delete Form` on our main page. The Modal component is reusable and can be used for various purposes in the future.
- I refactored the Add Form and Delete Form into HTML standard forms. This improves accessibility and allows users to submit the forms using the "Enter" key.
- I converted json files' format. This simplifies data structure and makes it easier to manage and update songs.

## What could have gone better in the previous sprint, or went poorly?
- Now, our project is bigger and bigger. So, I am struggling to manage CSS. We need to select better way to manage CSS such as SASS.
- Although I created `Login/Signup` feature with firebase authentication, I created weak regulation for password such as password must be at least 6 characters long. So, users can create weak passwords. In the future, I will add regulation for strong passwords such as requiring a mix of uppercase, lowercase, numbers, and special characters.

## What can be done in the next sprint to do better?
- I will refactor the CSS to use SASS for better organization and maintainability.
- I will create `Repository` pattern to CRUD operations of songs with Test data.
- I will add regulation for strong passwords in the `Signup` form to enhance security such as requiring a mix of uppercase, lowercase, numbers, and special characters.