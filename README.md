

🛍 Next.js E-Commerce Category Page
🚀 Project Overview
This project is a Next.js-based E-Commerce Category Page that fetches and displays products from an API. The application is designed to showcase Men, Women, and Kids categories with an optimized user experience, lazy loading images, skeleton loaders, and error handling for API failures (including 404 errors).

🏗 Features
✔ Dynamic Product Fetching – Uses useEffect to fetch category-specific products.
✔ Error Handling – Displays a custom 404 error message if products fail to load.
✔ Skeleton Loaders – Shows placeholder UI while fetching data (5-8 seconds simulated delay).
✔ Lazy Loading Images – Improves page speed by only loading images when needed.
✔ Responsive Design – Styled with Tailwind CSS for a clean, modern UI.

📸 Preview

![Screenshot (22)](https://github.com/user-attachments/assets/b345cef4-cd66-4613-97ae-b31c102d9c1d)
![Screenshot (23)](https://github.com/user-attachments/assets/a6ae771f-fce3-4486-b827-9e64948d3cf6)
![Screenshot (27)](https://github.com/user-attachments/assets/339099c5-4ef2-478e-86cb-851d77e68664)
![Screenshot (28)](https://github.com/user-attachments/assets/9985e26c-6b6d-42f3-847d-962d20e9ddbe)




🛠 Tech Stack
Framework: Next.js

Styling: Tailwind CSS

State Management: React useState and useEffect hooks

API: FakeStore API

🏗 Project Structure

📦 my-nextjs-project
 ┣ 📂 src
 ┃ ┣ 📂 app
 ┃ ┃ ┣ 📂 men  # Men Category Page
 ┃ ┃ ┣ 📂 women  # Women Category Page
 ┃ ┃ ┣ 📂 kids  # Kids Category Page
 ┃ ┃ ┣ 📜 globals.css  # Tailwind CSS Global Styles
 ┃ ┃ ┣ 📜 layout.js  # Global Layout
 ┃ ┃ ┗ 📜 page.js  # Home Page
 ┣ 📂 public  # Static Assets
 ┣ 📜 tailwind.config.js  # Tailwind Configuration
 ┣ 📜 next.config.js  # Next.js Configuration
 ┣ 📜 package.json  # Dependencies
 ┣ 📜 README.md  # Project Documentation
🔧 Installation & Setup
⿡ Clone the Repository
git clone https://github.com/your-username/nextjs-ecommerce.git
cd nextjs-ecommerce
⿢ Install Dependencies
npm install
⿣ Run the Development Server
npm run dev
Your application will run at http://localhost:3000
