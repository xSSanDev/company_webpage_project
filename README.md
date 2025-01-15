# FutureGrid Solutions

A comprehensive full-stack web application built with Django 5 and Bootstrap 5, featuring a modern agency website with an integrated blog system.

## 📝 Project Description

This project is a complete agency website built using Django 5 and Bootstrap 5, It demonstrates modern web development practices and provides a fully functional website with blog capabilities and admin controls.

### Key Learning Points
- Complete Django 5 fundamentals
- Frontend integration with Bootstrap 5
- CRUD operations
- Mobile-responsive design
- Database management
- Email integration
- Deployment workflows

## 🚀 Technologies Used

- **Frontend:** Bootstrap 5
- **Backend:** Django 5
- **Database:** SQLite/PostgreSQL
- **Deployment:** PythonAnywhere
- **Additional Tools:** 
  - pycharm
  - Git & GitHub
  - Rich Text Editor
  - Gmail Service Integration

## 📋 Features

# Django Agency Website with Blog

[Previous sections remain the same...]

## 📋 Features

### 1. Home Page
The landing page showcases the agency's main offerings and value proposition with a modern, responsive design. It includes:
- Hero section with call-to-action
- Overview of services
- Company highlights
- Latest blog posts

![Homepage Screenshot](https://github.com/xSSanDev/company_webpage_project/blob/master/images/Homepage.png?raw=true)

### 2. Services
Detailed presentation of the agency's service offerings:
- Comprehensive service descriptions
- Service categories
- Pricing information
- Service request functionality
[Screenshot placeholder]

### 3. Testimonials
Client feedback and success stories:
- Client reviews
- Success metrics
- Client logos and testimonials
- Rating system
[Screenshot placeholder]

### 4. FAQ
Interactive frequently asked questions section:
- Categorized questions and answers
- Search functionality
- Expandable/collapsible answers
[Screenshot placeholder]

### 5. Blog
Full-featured blog system with:
- Rich text editor integration
- Category filtering
- Search functionality
- Comment system
- Social sharing options
[Screenshot placeholder]

### 6. Contact
Interactive contact features:
- Contact form with email integration
- Location map
- Business hours
- Social media links
[Screenshot placeholder]

## 🛠️ Installation and Setup

1. Clone the repository
```bash
git clone [your-repository-url]
cd [repository-name]
```

2. Create a virtual environment
```bash
python -m venv venv
source venv/bin/activate  # On Windows use: venv\Scripts\activate
```

3. Install dependencies
```bash
pip install -r requirements.txt
```

4. Configure environment variables
```bash
# Create .env file and add:
SECRET_KEY=your_secret_key
DEBUG=True
EMAIL_HOST_USER=your_email@gmail.com
EMAIL_HOST_PASSWORD=your_email_password
```

5. Apply migrations
```bash
python manage.py migrate
```

6. Create superuser
```bash
python manage.py createsuperuser
```

7. Run the development server
```bash
python manage.py runserver
```

## 🌐 Deployment

This application is deployed on PythonAnywhere and can be accessed at: [https://xssandev.pythonanywhere.com/](https://xssandev.pythonanywhere.com/)

### Deployment Steps
1. Set up PythonAnywhere account
2. Configure virtual environment
3. Set up static files
4. Configure database
5. Update settings for production
6. Configure WSGI file

## 🤝 Contributing

Contributions are welcome! Please feel free to submit a Pull Request.

1. Fork the repository
2. Create your feature branch (`git checkout -b feature/AmazingFeature`)
3. Commit your changes (`git commit -m 'Add some AmazingFeature'`)
4. Push to the branch (`git push origin feature/AmazingFeature`)
5. Open a Pull Request

## 📄 License

This project is licensed under the MIT License - see the [LICENSE.md](LICENSE.md) file for details

## 👤 Contact

[Your contact information]

## 🔗 Additional Resources

- [Django Documentation](https://docs.djangoproject.com/)
- [Bootstrap Documentation](https://getbootstrap.com/docs/5.0/getting-started/introduction/)
- [PythonAnywhere Help Pages](https://help.pythonanywhere.com/)
