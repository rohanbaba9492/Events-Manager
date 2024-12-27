# **Events Manager**  

### **Overview**
The Events Manager project is a web-based application designed to manage and display events from an RSS feed. Built using HTML, CSS, and JavaScript, the app supports responsive design, filtering functionality, and deployment on AWS EC2. This project is part of the **CSE 4234/5234 Web Applications** course.  

---

### **Features**
- **Dynamic Event Rendering**: Reads and processes an RSS XML file to dynamically populate event cards using JavaScript.  
- **Event Filtering**: Supports filtering events by title, date, and description with multiple filter combinations.  
- **Responsive Design**: Flexbox-based layout adapts to different screen sizes with a maximum of 5 cards per row for larger screens and 1 card per row for smaller screens.  
- **Interactive Elements**: Includes a "Learn More" button to toggle event descriptions.  
- **Cloud Hosting**: Deployed on AWS EC2 for online access.  
- **Pagination** (Bonus): Allows navigation through events with configurable items per page (25, 50, 100, or all).  

---

### **Technologies Used**
- **Frontend**: HTML5, CSS3, JavaScript (Strict Mode)  
- **Responsive Design**: CSS Flexbox  
- **RSS Parsing**: JavaScript `fetch` and XML parsing techniques  
- **Hosting**: AWS EC2  

---

### **Installation**
1. **Clone the Repository**  
   ```bash
   git clone https://github.com/your-username/events-manager.git
   cd events-manager
   ```
2. **Host on a Local Web Server**  
   You can use a simple Python HTTP server:
   ```bash
   python -m http.server 8080
   ```
   Navigate to `http://localhost:8080` in your web browser.  

3. **Deploy on AWS EC2**  
   - Launch an EC2 instance with a suitable AMI (e.g., Ubuntu).  
   - Install and configure a web server like Apache or NGINX.  
   - Copy project files to the web server's root directory (e.g., `/var/www/html`).  

---

### **License**
This project is licensed under the MIT License. See the [LICENSE](LICENSE) file for details.  
