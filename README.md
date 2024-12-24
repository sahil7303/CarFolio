# CarFolio

The CarFolio website is a platform to explore and filter various car types. Built with modern web technologies, it leverages **Next.js** for server-side rendering, ensuring an exceptional user experience with smooth performance and responsive design.

## 🚀 Tech Stack

- **Next.js**: Enables server-side rendering for enhanced performance.
- **TypeScript**: Ensures robust typing and improved code quality.
- **Tailwind CSS**: Provides utility-first styling for responsive and visually appealing designs.

---

## 🌟 Features

### Home Page
A visually appealing homepage showcasing a variety of cars fetched from a third-party API, offering a captivating introduction to available vehicles.

### Exploration and Filtering
Explore a wide range of cars globally using advanced filters based on:
- **Model**
- **Manufacturer**
- **Year**
- **Fuel Type**
- **Make**

### Transition to Server-Side Rendering (SSR)
Seamlessly transitions from client-side rendering to server-side rendering for:
- Improved performance
- Faster page load times
- A smoother browsing experience

### Pagination
Effortless navigation through large datasets of cars with pagination support, allowing users to browse multiple pages conveniently.

### Metadata Optimization and SEO
Optimize metadata for each car listing, enhancing **SEO** and ensuring better visibility on search engine results pages.

### TypeScript Types
Robust typing provided by TypeScript enhances code quality and improves the overall development experience.

### Responsive Design
The website is fully responsive, ensuring an optimal user experience across devices of all sizes.

---

## 📂 Project Structure

The project follows a modular and reusable architecture for scalability and maintainability. Key directories include:

- **`components/`**: Reusable UI components.
- **`pages/`**: Next.js pages for routing and server-side rendering.
- **`styles/`**: Tailwind CSS configuration and global styles.
- **`utils/`**: Utility functions and API calls.

---

## 🛠️ Installation & Setup

**Cloning the Repository**

```bash
git clone {url}
cd {directory}
```

**Installation**

Install the project dependencies using npm:

```bash
npm install
```

**Set Up Environment Variables**

Create a new file named `.env` in the root of your project and add the following content:

```env
NEXT_PUBLIC_RAPID_API_KEY=
NEXT_PUBLIC_IMAGIN_API_KEY=
```

Replace the placeholder values with your actual credentials. You can obtain these credentials by signing up on the corresponding websites from [Rapid API](https://www.youtube.com/redirect?event=video_description&redir_token=QUFFLUhqbmI1TlE1NHFGZ1JLdHU3dnAxSTU5a2R5UUM4QXxBQ3Jtc0tsUDY0aW8xMFhUZVdxMUNzSUlKUExRTG5UaDZoR3hWVFprN2tJV0k2dnk4MXo2NVFMVkk0NWhGS19Nd0g5cGRfN2JjcTdaSlJJRHJKYzlfT3lSS1M4TDVNVTV5Wl91c1lIR2VPZUYzbHJ2Tll2QkJ0aw&q=https%3A%2F%2Frapidapi.com%2Fapininjas%2Fapi%2Fcars-by-api-ninjas%3Futm_source%3Dyoutube.com%2FJavaScriptMastery%26utm_medium%3Dreferral%26utm_campaign%3DDevRel&v=pUNSHPyVryU) to [Imagin Cars](https://www.imagin.studio/solutions/api)

**Running the Project**

```bash
npm run dev
```