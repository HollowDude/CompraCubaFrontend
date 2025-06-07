# 🛍️ MiPyme E-Commerce Frontend — Angular

[Live Demo](https://github.com/tuusuario/mipymeecomerc-frontend#readme)

## 📌 Description

This project is **the frontend for a Cuban MiPyme e-commerce platform**, built with **Angular**. Inspired by Amazon’s clean, user-friendly aesthetic, it enables individual business owners to manage their storefronts and customers to browse, add to cart, and purchase products online.

No backend logic here—just a responsive, SPA interface that consumes RESTful APIs to power:

- Vendor dashboards (product CRUD, order overview)  
- Customer storefront (category browsing, search, filters)  
- Shopping cart & checkout workflows  

## 🛠️ Technologies

- **Angular 15+** (CLI, RxJS)  
- **TypeScript**  
- **Angular Material** (UI components & theming)  
- **NgRx** (state management)  
- **Angular Router** (navigation & guards)  
- **SCSS** (custom theming & responsive layouts)

👉 Check out the code here:  
[🔗 github.com/tuusuario/mipymeecomerc-frontend](https://github.com/tuusuario/mipymeecomerc-frontend)

## 🎨 Why Is It Interesting?

- **Amazon-style UX**: polished product grids, detail pages, and persistent cart.  
- **Vendor self-service**: each MiPyme can fully manage inventory and view sales stats.  
- **Modular architecture**: feature modules for products, cart, checkout, and admin.  
- **State-driven**: NgRx ensures predictable state and easier testing.  
- **Responsive & accessible**: mobile-first design with ARIA compliance.

Ideal as a boilerplate for any multi-vendor marketplace or as a showcase of advanced Angular patterns.

---

## 🚀 How to Run It

1. **Clone the repo**  
   ```bash
   git clone https://github.com/tuusuario/mipymeecomerc-frontend.git
   cd mipymeecomerc-frontend

2. **Install dependencies**

   ```bash
   npm install
   ```

3. **Configure environment**

   * Copy `src/environments/environment.example.ts` → `src/environments/environment.ts`
   * Set your API base URL, e.g.:

     ```ts
     export const environment = {
       production: false,
       apiUrl: 'https://api.mipymeecomerc.cu'
     };
     ```

4. **Run the development server**

   ```bash
   npm start
   ```

5. **Open in browser**
   Navigate to [http://localhost:4200](http://localhost:4200)

---

## 📣 Note

This frontend expects a matching Django DRF backend at `environment.apiUrl`. Make sure the API endpoints for products, vendors, authentication, cart, and orders are up and running.

---

## 📌 Author

Developed by **HollowDude**.
Feedback, issues, and contributions are welcome—feel free to fork or open an issue!
