# Welcome to your Lovable project

## Project info

**URL**: https://lovable.dev/projects/95ed7559-129a-4b7e-813e-7580e9891349

## How can I edit this code?

There are several ways of editing your application.

**Use Lovable**

Simply visit the [Lovable Project](https://lovable.dev/projects/95ed7559-129a-4b7e-813e-7580e9891349) and start prompting.

Changes made via Lovable will be committed automatically to this repo.

**Use your preferred IDE**

If you want to work locally using your own IDE, you can clone this repo and push changes. Pushed changes will also be reflected in Lovable.

The only requirement is having Node.js & npm installed - [install with nvm](https://github.com/nvm-sh/nvm#installing-and-updating)

Follow these steps:

```sh
# Step 1: Clone the repository using the project's Git URL.
git clone <YOUR_GIT_URL>

# Step 2: Navigate to the project directory.
cd <YOUR_PROJECT_NAME>

# Step 3: Install the necessary dependencies.
npm i

# Step 4: Start the development server with auto-reloading and an instant preview.
npm run dev
```

**Edit a file directly in GitHub**

- Navigate to the desired file(s).
- Click the "Edit" button (pencil icon) at the top right of the file view.
- Make your changes and commit the changes.

**Use GitHub Codespaces**

- Navigate to the main page of your repository.
- Click on the "Code" button (green button) near the top right.
- Select the "Codespaces" tab.
- Click on "New codespace" to launch a new Codespace environment.
- Edit files directly within the Codespace and commit and push your changes once you're done.

## What technologies are used for this project?

This project is built with:

- Vite
- TypeScript
- React
- shadcn-ui
- Tailwind CSS

## How can I deploy this project?

Simply open [Lovable](https://lovable.dev/projects/95ed7559-129a-4b7e-813e-7580e9891349) and click on Share -> Publish.

## Can I connect a custom domain to my Lovable project?

Yes, you can!

To connect a domain, navigate to Project > Settings > Domains and click Connect Domain.

Read more here: [Setting up a custom domain](https://docs.lovable.dev/tips-tricks/custom-domain#step-by-step-guide)


<!-- Tasks for affiliate integration -->
1. User create the account with login with google 
    i. Generate the unique code there only linkedin with email.
    ii.
2. Create the unique ref id if exists
    i. Check the ID
    ii. Store it in the local storage
    iii. If in the locakstorage, read it wheile making the paymnet
    iv. Make the paymnet status initiated here only
3. Store it in the back-end db when user initiate the payment  
    i. Afther the paymnet while verifygn the payment, if it's done then only update
4. Create GET back-end request to display it at the front-end


affiliate Schema

email
uid
refferals {
    "plan_id1":count",
    "plan_id2":count",
    "plan_id3":count",
    "plan_id4":count",
}
total_earnings:0 // Will make it 0 once we make payment to the users
lifetime_earnings:0
joined_on