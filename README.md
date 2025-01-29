# Investment Banking Website

A modern Next.js + TypeScript + Tailwind CSS project designed to convert potential clients for our investment banking firm. It includes pages like **About**, **Careers**, **Contact**, **Deal Room**, **Industry**, **Insights**, and **Services**, plus components for a smooth user experience.

## File Structure

    .
    ├─ components/
    │  ├─ ContactInfo.tsx
    │  ├─ EmbeddedAppBox.tsx
    │  ├─ Footer.tsx
    │  ├─ Header.tsx
    │  ├─ HeroSection.tsx
    │  ├─ Layout.tsx
    │  ├─ RecentDeals.tsx
    │  ├─ ServicesOverview.tsx
    │  └─ ValuationCalculator.tsx
    ├─ pages/
    │  ├─ about.tsx
    │  ├─ careers.tsx
    │  ├─ contact.tsx
    │  ├─ dealroom.tsx
    │  ├─ index.tsx
    │  ├─ industry.tsx
    │  ├─ insights.tsx
    │  └─ services.tsx
    ├─ public/
    │  └─ images/
    │     └─ (logo files, etc.)
    ├─ src/
    │  ├─ favicon.ico
    │  ├─ globals.css
    │  ├─ layout.tsx
    │  └─ page.tsx
    ├─ styles/
    │  ├─ global.css
    │  └─ tailwind.css
    ├─ eslint.config.mjs
    ├─ next-env.d.ts
    ├─ next.config.ts
    ├─ package.json
    ├─ package-lock.json
    ├─ postcss.config.mjs
    ├─ tailwind.config.ts
    └─ tsconfig.json

## Getting Started

1. **Install dependencies**:
    ```bash
    npm install
    # or
    yarn install
    ```

2. **Run the development server**:
    ```bash
    npm run dev
    # or
    yarn dev
    ```
    Open [http://localhost:3000](http://localhost:3000) to view the site.

3. **Build and Run for Production**:
    ```bash
    npm run build
    npm run start
    ```
    This compiles a production-ready build, served on [http://localhost:3000](http://localhost:3000).

## Deployment

- **Marketing Site**: Hosted on Hostinger (if using a static export or Node hosting).  
- **App**: Deployed on Azure and integrated with SharePoint for document management.

## License

*(Include your license details here if applicable.)*

## Contributing

1. Fork the repository.
2. Create a new branch for your feature/fix.
3. Commit your changes.
4. Open a pull request for review.
