# 📊 Financial Pulse: Professional Expense Tracker

A sophisticated, client-side financial management dashboard engineered for real-time transaction tracking, balance calculation, and persistent data storage.

  * **Live Demo Link:** https://sk-reyad.github.io/02-Expense-Tracker/

-----

# 📝 Project Overview

**Financial Pulse** is a high-performance budgeting utility designed to give users a transparent view of their financial health. Built with a focus on seamless interactivity and localized formatting, the application allows users to manage income and expenditures through a clean, high-contrast interface.

The core logic focuses on mathematical precision, ensuring that the total balance, total income, and total expenses are updated instantaneously as transactions are added or removed. By leveraging browser storage, the application provides a "sticky" experience, retaining all financial records even after the browser is closed or refreshed, making it a reliable tool for daily fiscal monitoring.

-----

# ✨ Key Features

  * **Dynamic Ledger Management:** Add and delete transactions with immediate UI updates. The system automatically categorizes entries based on numerical polarity (positive for income, negative for expenses).
  * **Real-Time Analytics Dashboard:** A centralized summary card that calculates the net balance and breaks down total cash flow using JavaScript's `reduce` and `filter` methods.
  * **Persistent Data Storage:** Integrated `localStorage` engine that serializes the transaction array into JSON, ensuring user data is saved locally without the need for a backend database.
  * **Smart Currency Formatting:** Uses the `Intl.NumberFormat` API to display values in **BDT (৳)**, providing a localized and professional financial aesthetic.
  * **Intuitive UX Feedback:** Features a reverse-chronological transaction feed (newest first) with color-coded indicators—green for income and red for expenses—for instant visual scanning.
  * **Animated Interactions:** Smooth CSS keyframe animations (`slideIn`) that trigger when new transactions are added, providing a polished, modern feel.

-----

# 🧠 Technical Highlights (Skills Showcase)

This project serves as a comprehensive demonstration of vanilla JavaScript proficiency and modern CSS architecture, focusing on clean code and efficient state management:

### Advanced JavaScript Logic

  * **Functional Data Processing:** Eschewing basic loops for more declarative patterns, the `updateSummary` function utilizes the `.reduce()` accumulator pattern to compute totals. This demonstrates an understanding of Big O efficiency when handling data arrays.
  * **DOM Reconciliation & Template Literals:** The `createTransactionElement` function dynamically constructs complex HTML structures using ES6 Template Literals. It intelligently assigns CSS classes using ternary operators based on the `transaction.amount` state.
  * **State Persistence Logic:** Implemented a robust data sync cycle where the internal `transactions` state is mirrored to `localStorage` during every Create and Delete operation, preventing data loss.
  * **Event Delegation & Management:** Utilizes `e.preventDefault()` within form submission handlers to manage the request-response cycle entirely on the client side, resulting in a "Single Page Application" feel.

### Modern CSS3 Architecture

  * **Advanced Layout Engines:** A hybrid approach using **CSS Grid** for the high-level dashboard structure (`grid-template-columns: 1fr 1fr`) and **Flexbox** for alignment within transaction items and form groups.
  * **Glassmorphism & Depth:** Leverages complex linear gradients and multi-layered box shadows (`0 12px 24px rgba(0, 0, 0, 0.3)`) to create visual hierarchy and depth.
  * **Responsive Design System:** Uses sophisticated Media Queries to refactor the layout from a multi-column desktop view to a stacked mobile view, ensuring usability on devices as small as 480px.
  * **Custom UI Components:** Completely customized the browser's native scrollbar using `::-webkit-scrollbar` pseudo-elements to match the application's aesthetic.

### Semantic HTML5

  * **Accessible Forms:** Proper use of `<label>` for attribute binding and semantic input types (`type="number"`) to ensure mobile devices trigger the correct keyboard layout.

-----

# 🛠️ Tech Stack

  * **HTML5:** Semantic document structure and form validation.
  * **CSS3:** Flexbox, CSS Grid, Keyframe Animations, and Custom Scrollbars.
  * **JavaScript (ES6+):** LocalStorage API, Intl API, Array Methods (filter, reduce, map), and DOM Manipulation.
  * **Google Fonts:** "Lato" for a professional, highly readable typography.

-----

# 🚀 Quick Start

  * **Clone the repository:**

<!-- end list -->

```bash
git clone https://github.com/sk-reyad/expense-tracker.git
```

  * **Navigate to the project directory:**

<!-- end list -->

```bash
cd expense-tracker
```

  * **Run the application:**
    Simply open the `index.html` file in your preferred web browser. No installation or dependencies required\!

-----

# 📬 Let's Connect
  * **📧 Email:** skreyad2016@gmail.com
  * **💼 LinkedIn:** https://www.linkedin.com/in/sk-reyad/
