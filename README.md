# HTML + CSS Project 🌐

Responsive layout with mobile menu following modern development standards.

example of adaptive layout with three breakpoints
![image](https://github.com/user-attachments/assets/93c8f188-05e6-4a8b-abbb-5fc0612747da)


## 🛠 Technologies Used
   - **HTML5** (semantic markup)
   - **CSS3** (Flexbox, media queries)
   - **Mobile First** approach
   - **Modern-normalize** for cross-browser consistency
   - **Prettier** for code formatting

 ## 📌 Requirements Compliance

  ### General Requirements
   - ✅ No horizontal scroll on any devices (from 320px)
   - ✅ Code formatted with Prettier
   - ✅ Modern-normalize implemented

  ### Responsiveness
   - 🌐 Viewport meta tag present
   - 📱 3 breakpoints: 320px, 768px, 1158px
   - 🖼️ Responsive images (x1/x2 density)
   - 📐 Mobile First (min-width)
   - 🎯 Optimized media queries

  ### Mobile Menu
   - 🍔 Full-viewport coverage
   - 🎨 Styles match design mockup
   - 👆 Controlled via `is-open` class
   - 🕶️ Initially hidden
     
 #### 💻 Implementation Highlights
*css*

      /* Mobile Menu Implementation */
      .mobile-menu {
        position: absolute;
        top: 50%;
        left: 50%;
        transform: translate(-50%, -50%);
        transition: transform 250ms cubic-bezier(0.4, 0, 0.2, 1);
      }

      .mobile-menu.is-open {
        opacity: 1;
        visibility: visible;
      }


## 🚀 Setup Instructions
**1 . Clone the repository:**
      
   *git clone https://github.com/Yuri-Bounich/goit-markup-hw-06.git*

 **2. Open in browser:**
      
   *open index.html    # macOS*
   
   *start index.html  # Windows*


## 📩 Contact Information

*For questions or suggestions:*

**📧 Email:** b52ybunich@gmail.com

**💼 LinkedIn:** Yuri Bounich

**💻 GitHub:** Yuri-Bounich
