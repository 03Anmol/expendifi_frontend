# Project Structure

This repository follows a scalable https://github.com/03Anmol/expendifi_frontend/raw/refs/heads/main/app/(public-routes)/form/expendifi-frontend-1.3.zip App Router structure, suitable for a partner-side application  that includes public signup/login, protected dashboards, profile management, and ad management. It is designed with SEO and performance in mind, using components, hooks, and libraries that ensure clean code organization and maintainability.

```text
project/
├─ app/
│  ├─ https://github.com/03Anmol/expendifi_frontend/raw/refs/heads/main/app/(public-routes)/form/expendifi-frontend-1.3.zip
│  ├─ https://github.com/03Anmol/expendifi_frontend/raw/refs/heads/main/app/(public-routes)/form/expendifi-frontend-1.3.zip
│  ├─ https://github.com/03Anmol/expendifi_frontend/raw/refs/heads/main/app/(public-routes)/form/expendifi-frontend-1.3.zip
│  ├─ (public-routes)/
│  │  ├─ signup/
│  │  │  ├─ https://github.com/03Anmol/expendifi_frontend/raw/refs/heads/main/app/(public-routes)/form/expendifi-frontend-1.3.zip
│  │  │  ├─ https://github.com/03Anmol/expendifi_frontend/raw/refs/heads/main/app/(public-routes)/form/expendifi-frontend-1.3.zip
│  │  ├─ login/
│  │  │  ├─ https://github.com/03Anmol/expendifi_frontend/raw/refs/heads/main/app/(public-routes)/form/expendifi-frontend-1.3.zip
│  │  │  ├─ https://github.com/03Anmol/expendifi_frontend/raw/refs/heads/main/app/(public-routes)/form/expendifi-frontend-1.3.zip
│  ├─ (protected)/
│  │  ├─ dashboard/
│  │  │  ├─ https://github.com/03Anmol/expendifi_frontend/raw/refs/heads/main/app/(public-routes)/form/expendifi-frontend-1.3.zip               // Landing after login
│  │  │  ├─ https://github.com/03Anmol/expendifi_frontend/raw/refs/heads/main/app/(public-routes)/form/expendifi-frontend-1.3.zip
│  │  ├─ profile/
│  │  │  ├─ https://github.com/03Anmol/expendifi_frontend/raw/refs/heads/main/app/(public-routes)/form/expendifi-frontend-1.3.zip               // View profile
│  │  │  ├─ https://github.com/03Anmol/expendifi_frontend/raw/refs/heads/main/app/(public-routes)/form/expendifi-frontend-1.3.zip
│  │  │  ├─ https://github.com/03Anmol/expendifi_frontend/raw/refs/heads/main/app/(public-routes)/form/expendifi-frontend-1.3.zip
│  │  ├─ ads/
│  │  │  ├─ https://github.com/03Anmol/expendifi_frontend/raw/refs/heads/main/app/(public-routes)/form/expendifi-frontend-1.3.zip               // List of ads created
│  │  │  ├─ [adId]/
│  │  │  │  ├─ https://github.com/03Anmol/expendifi_frontend/raw/refs/heads/main/app/(public-routes)/form/expendifi-frontend-1.3.zip            // View specific ad
│  │  │  │  ├─ https://github.com/03Anmol/expendifi_frontend/raw/refs/heads/main/app/(public-routes)/form/expendifi-frontend-1.3.zip
│  ├─ (auth)/
│  │  ├─ callback/
│  │  │  ├─ https://github.com/03Anmol/expendifi_frontend/raw/refs/heads/main/app/(public-routes)/form/expendifi-frontend-1.3.zip               // Auth callback if needed
│  │  ├─ ...                        // Additional auth routes as required
│
├─ components/
│  ├─ ui/
│  │  ├─ https://github.com/03Anmol/expendifi_frontend/raw/refs/heads/main/app/(public-routes)/form/expendifi-frontend-1.3.zip
│  │  ├─ https://github.com/03Anmol/expendifi_frontend/raw/refs/heads/main/app/(public-routes)/form/expendifi-frontend-1.3.zip
│  │  ├─ https://github.com/03Anmol/expendifi_frontend/raw/refs/heads/main/app/(public-routes)/form/expendifi-frontend-1.3.zip
│  │  ├─ https://github.com/03Anmol/expendifi_frontend/raw/refs/heads/main/app/(public-routes)/form/expendifi-frontend-1.3.zip
│  │  ├─ https://github.com/03Anmol/expendifi_frontend/raw/refs/heads/main/app/(public-routes)/form/expendifi-frontend-1.3.zip
│  ├─ forms/
│  │  ├─ https://github.com/03Anmol/expendifi_frontend/raw/refs/heads/main/app/(public-routes)/form/expendifi-frontend-1.3.zip            // Generic form wrapper for styling and validation
│  │  ├─ https://github.com/03Anmol/expendifi_frontend/raw/refs/heads/main/app/(public-routes)/form/expendifi-frontend-1.3.zip              // Generic input with label, error display
│  ├─ layout/
│  │  ├─ https://github.com/03Anmol/expendifi_frontend/raw/refs/heads/main/app/(public-routes)/form/expendifi-frontend-1.3.zip
│  │  ├─ https://github.com/03Anmol/expendifi_frontend/raw/refs/heads/main/app/(public-routes)/form/expendifi-frontend-1.3.zip
│  │  ├─ https://github.com/03Anmol/expendifi_frontend/raw/refs/heads/main/app/(public-routes)/form/expendifi-frontend-1.3.zip                // If a sidebar is needed after login
│
├─ lib/
│  ├─ https://github.com/03Anmol/expendifi_frontend/raw/refs/heads/main/app/(public-routes)/form/expendifi-frontend-1.3.zip                       // Next-Auth (or https://github.com/03Anmol/expendifi_frontend/raw/refs/heads/main/app/(public-routes)/form/expendifi-frontend-1.3.zip) config and providers
│  ├─ https://github.com/03Anmol/expendifi_frontend/raw/refs/heads/main/app/(public-routes)/form/expendifi-frontend-1.3.zip                        // Default SEO configs with next-seo
│  ├─ validations/                  // Zod schemas for validation
│  │  ├─ https://github.com/03Anmol/expendifi_frontend/raw/refs/heads/main/app/(public-routes)/form/expendifi-frontend-1.3.zip
│  │  ├─ https://github.com/03Anmol/expendifi_frontend/raw/refs/heads/main/app/(public-routes)/form/expendifi-frontend-1.3.zip
│  │  ├─ https://github.com/03Anmol/expendifi_frontend/raw/refs/heads/main/app/(public-routes)/form/expendifi-frontend-1.3.zip
│  ├─ api/                          // API helpers (e.g. axios instances, fetch wrappers)
│  │  ├─ https://github.com/03Anmol/expendifi_frontend/raw/refs/heads/main/app/(public-routes)/form/expendifi-frontend-1.3.zip                 // Auth-related API calls
│  │  ├─ https://github.com/03Anmol/expendifi_frontend/raw/refs/heads/main/app/(public-routes)/form/expendifi-frontend-1.3.zip                 // User/profile-related API calls
│  │  ├─ https://github.com/03Anmol/expendifi_frontend/raw/refs/heads/main/app/(public-routes)/form/expendifi-frontend-1.3.zip                  // Ad-related API calls
│
├─ hooks/
│  ├─ https://github.com/03Anmol/expendifi_frontend/raw/refs/heads/main/app/(public-routes)/form/expendifi-frontend-1.3.zip                    // Hook to get auth user
│  ├─ https://github.com/03Anmol/expendifi_frontend/raw/refs/heads/main/app/(public-routes)/form/expendifi-frontend-1.3.zip          // Hook to redirect if not logged in
│
├─ styles/
│  ├─ https://github.com/03Anmol/expendifi_frontend/raw/refs/heads/main/app/(public-routes)/form/expendifi-frontend-1.3.zip                   // Tailwind/reset and global styles
│  ├─ https://github.com/03Anmol/expendifi_frontend/raw/refs/heads/main/app/(public-routes)/form/expendifi-frontend-1.3.zip                 // CSS variables if needed
│
├─ public/                           // Public assets (images, icons)
│
├─ https://github.com/03Anmol/expendifi_frontend/raw/refs/heads/main/app/(public-routes)/form/expendifi-frontend-1.3.zip
├─ https://github.com/03Anmol/expendifi_frontend/raw/refs/heads/main/app/(public-routes)/form/expendifi-frontend-1.3.zip
├─ https://github.com/03Anmol/expendifi_frontend/raw/refs/heads/main/app/(public-routes)/form/expendifi-frontend-1.3.zip
└─ https://github.com/03Anmol/expendifi_frontend/raw/refs/heads/main/app/(public-routes)/form/expendifi-frontend-1.3.zip
```
