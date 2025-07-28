# 🌱 Plant Store Dashboard

A beautiful, responsive dashboard for managing a plant store business with real-time analytics, order management, and customer communication features.

<div align="center">
  
![Plant Store Dashboard](https://img.shields.io/badge/Plant%20Store-Dashboard-green?style=for-the-badge&logo=leaf&color=4CAF50)
![HTML](https://img.shields.io/badge/HTML-E34F26?style=for-the-badge&logo=html5&logoColor=white)
![CSS](https://img.shields.io/badge/CSS-1572B6?style=for-the-badge&logo=css3&logoColor=white)
![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?style=for-the-badge&logo=javascript&logoColor=black)
![Bootstrap](https://img.shields.io/badge/Bootstrap-563D7C?style=for-the-badge&logo=bootstrap&logoColor=white)
![Chart.js](https://img.shields.io/badge/Chart.js-FF6384?style=for-the-badge&logo=chart.js&logoColor=white)

</div>

## ✨ Features

- 📊 **Real-time Analytics** - Track revenue, orders, customers, and growth metrics
- 📈 **Interactive Charts** - Sales trends and product category distribution
- 📋 **Order Management** - View and manage recent orders with status tracking
- 💬 **Customer Communication** - Direct messaging system for customer support
- 📱 **Responsive Design** - Works perfectly on desktop, tablet, and mobile
- 🎨 **Modern UI** - Clean, professional interface with smooth animations

## 🚀 Quick Start

### Prerequisites

Before you begin, ensure you have the following installed:
- [Git](https://git-scm.com/downloads)
- A modern web browser (Chrome, Firefox, Safari, or Edge)

### Step 1: Clone the Repository

```bash
# Clone the repository
git clone https://github.com/quangcaptian26-3/git_test.git

# Navigate to the project directory
cd git_test
```

### Step 2: Open the Application

#### Option 1: Direct Browser Opening
Simply open the `index.html` file in your browser:

```bash
# On Windows
start index.html

# On macOS
open index.html

# On Linux
xdg-open index.html
```

#### Option 2: Using a Local Server (Recommended)
For the best experience, use a local server:

```bash
# Using Python (if installed)
python -m http.server 8000
# Then visit: http://localhost:8000

# Using Node.js (if installed)
npx serve .
# Then visit: http://localhost:3000

# Using PHP (if installed)
php -S localhost:8000
# Then visit: http://localhost:8000
```

### Step 3: Explore the Dashboard

Once opened, you'll see the beautiful plant store dashboard with:

1. **Sidebar Navigation** - Easy access to all sections
2. **Dashboard Overview** - Key metrics at a glance
3. **Interactive Charts** - Sales trends and product categories
4. **Recent Orders** - Latest customer orders with status
5. **Customer Communication** - Send messages to customers

## 📁 Project Structure

```
git_test/
├── index.html          # Main HTML file
├── style.css          # Custom styles
├── script.js          # JavaScript functionality
├── README.md          # This file
└── assets/            # Images and other assets (if any)
```

## 🛠️ Technologies Used

- **HTML5** - Semantic markup and structure
- **CSS3** - Modern styling with flexbox and grid
- **JavaScript** - Interactive functionality and charts
- **Bootstrap 5** - Responsive design framework
- **Chart.js** - Beautiful and interactive charts
- **Font Awesome** - Icons and symbols

## 🎯 Usage Guide

### Dashboard Overview
- **Revenue**: Total sales amount
- **Orders**: Number of orders received
- **Customers**: Unique customers served
- **Growth**: Percentage increase in sales

### Charts
- **Sales Over Time**: Line chart showing monthly sales trends
- **Product Categories**: Pie chart displaying product distribution

### Order Management
- View recent orders with customer details
- Track order status (Shipped, Processing, Pending)
- Quick identification with color-coded badges

### Customer Communication
- Select customers from dropdown
- Send personalized messages
- Keep track of customer interactions

## 🎨 Customization

### Colors
The dashboard uses a green color scheme that can be customized in `style.css`:
```css
:root {
  --primary-color: #4CAF50;
  --secondary-color: #45a049;
  --background-color: #f8f9fa;
}
```

### Charts
Charts can be customized in `script.js`:
```javascript
// Modify chart colors, data, and labels
const salesChart = new Chart(ctx, {
  data: {
    labels: ['Jan', 'Feb', 'Mar'], // Your custom labels
    datasets: [{
      data: [100, 200, 300], // Your custom data
      backgroundColor: ['#FF6384', '#36A2EB', '#FFCE56'] // Custom colors
    }]
  }
});
```

### Adding New Products
To add new products, modify the product categories in `script.js`:
```javascript
labels: ['Ferns', 'Succulents', 'Cacti', 'Your New Category']
```

## 📞 Contact & Support

<div align="center">

**📧 Email**: [phamminhquang2603@gmail.com](mailto:phamminhquang2603@gmail.com)

**💼 LinkedIn**: [linkedin.com/in/minhquang2604](https://linkedin.com/in/minhquang2604)

**🐙 GitHub**: [github.com/quangcaptian26-3](https://github.com/quangcaptian26-3)

</div>

## 🤝 Contributing

Contributions are welcome! Feel free to:

1. Fork the repository
2. Create a feature branch (`git checkout -b feature/AmazingFeature`)
3. Commit your changes (`git commit -m 'Add some AmazingFeature'`)
4. Push to the branch (`git push origin feature/AmazingFeature`)
5. Open a Pull Request

## 📄 License

This project is open source and available under the [MIT License](LICENSE).

## 🙏 Acknowledgments

- [Chart.js](https://www.chartjs.org/) for beautiful charts
- [Bootstrap](https://getbootstrap.com/) for responsive design
- [Font Awesome](https://fontawesome.com/) for icons

---

<div align="center">
  
**⭐ Star this repository if you found it helpful!**

Made with ❤️ by [Minh Quang](https://linkedin.com/in/minhquang2604)

</div>
