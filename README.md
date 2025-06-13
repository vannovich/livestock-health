# Welcome to your Lovable project

## Project info

**URL**: https://lovable.dev/projects/9b99e53c-7180-461f-af94-385b5ff08347

## How can I edit this code?

There are several ways of editing your application.

**Use Lovable**

Simply visit the [Lovable Project](https://lovable.dev/projects/9b99e53c-7180-461f-af94-385b5ff08347) and start prompting.

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

Simply open [Lovable](https://lovable.dev/projects/9b99e53c-7180-461f-af94-385b5ff08347) and click on Share -> Publish.

## Can I connect a custom domain to my Lovable project?

Yes, you can!

To connect a domain, navigate to Project > Settings > Domains and click Connect Domain.

Read more here: [Setting up a custom domain](https://docs.lovable.dev/tips-tricks/custom-domain#step-by-step-guide)


### 🚀 DEVELOPER PROMPT: Build MVP for *Livestock HealthConnect* (Dummy Data Version)

**GOAL:**
Build a functional prototype of the *Livestock HealthConnect* platform—a system to connect livestock farmers in Buea with veterinarians. This is **a frontend+backend prototype (no real database)** using **dummy data** to simulate core flows.

---

### 🛠️ Stack to Use

* **Frontend**: React.js 
* **Backend**: Node.js with Express.js (no DB needed; use in-memory data or JSON files)
* **State/Data**: Store data in memory or mock JSON objects
* **Optional**: Include comments where database calls would normally go

---

### 📱 Must-Have Core Features (with Dummy Data)

#### 1. **User Roles**

* **Farmer**
* **Veterinarian**
* **Admin**
  Each role has its own dashboard and access controls. Simulate authentication with hardcoded user credentials.

---

#### 2. **Farmer Features**

* **Dashboard**

  * View nearby veterinarians (list from dummy JSON)
  * Request consultation (submit form → adds to dummy array)
  * Receive consultation responses (simulate with dummy replies)
*Profile page*

  * View/edit profile details (dummy only)
Health Tips

  * Show 3–5 health tips in English and Pidgin (hardcoded JSON)

---

3. **Veterinarian Features**

* **Dashboard**

  * See incoming consultation requests
  * Respond to consultations (form + dummy response state)
  * Manage schedule (time slots from dummy JSON)
* **Prescription History**

  * List past dummy consultations and prescriptions


#### 4. **Admin Features**

* **Dashboard**

  * View registered vets and farmers (from dummy JSON)
  * “Approve” new vets (toggle a boolean `isVerified`)
  * View platform stats (e.g., "Total Consultations: 42" – dummy values)


 💬 Communication Simulation

* **Simulate Chat**:

  * Simple textarea input to send/receive messages (use dummy message array)
* **Simulate Video/Call Option**:

  * Add a “Start Video” button (non-functional placeholder)
  * Label based on internet strength (simulate offline with toggle)



🧩 System Features

* Language Toggle (English)
* Role-based navigation and views
* Notifications (basic alerts/popups for new consultations)



🔐 Security Simulation

* Use role-based routing logic
* Show where token-based auth or PIN login would be implemented in real system
* Comment where HTTPS, encryption, or biometric login would be added



🎯 Success Criteria

* Navigable UI for each user type
* Dummy data flows simulate real operations
* Developer includes `// TODO` markers where API or DB integration would go
* Fully testable and deployable without external dependencies
