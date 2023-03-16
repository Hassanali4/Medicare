# MediCare [![MIT License](https://img.shields.io/apm/l/atomic-design-ui.svg?)](https://github.com/tterb/atomic-design-ui/blob/master/LICENSEs)
### Stack we used
![Python](https://img.shields.io/badge/python-3670A0?style=for-the-badge&logo=python&logoColor=ffdd54)
![HTML5](https://img.shields.io/badge/html5-%23E34F26.svg?style=for-the-badge&logo=html5&logoColor=white)
![JavaScript](https://img.shields.io/badge/javascript-%23323330.svg?style=for-the-badge&logo=javascript&logoColor=%23F7DF1E)
![CSS3](https://img.shields.io/badge/css3-%231572B6.svg?style=for-the-badge&logo=css3&logoColor=white)


![meditate](https://user-images.githubusercontent.com/79878896/124366069-65f10000-dc66-11eb-84c0-e548883fbb1c.JPG)

MediCare - An Online Medicine Ordering System Built with Django

## About
MediCare is an open-source online medicine ordering system built with Python Django. The system features separate logins for NGO and customers, allowing customers to browse through a list of medicines, place orders, and pay for them online, while NGOs can manage their inventory and process the received orders. 

## Features
- Separate login for NGOs and customers
- Customer can browse medicines, add them to cart, and place orders
- NGOs can manage their inventory, process orders, and track delivery status
- Payment gateway integration
- Secure user authentication and authorization system
- Responsive web design

## Installation
1. Clone the repository:
    ```
    git clone git@github.com:abrehman90/MediCare.git
    ```
2. Navigate into the project directory:
    ```
    cd UOS_med
    ```
3. Run database migrations:
    ```
    python manage.py migrate
    ```
4. Create a superuser:
    ```
    python manage.py createsuperuser
    ```
5. Start the development server:
    ```
    python manage.py runserver
    ```
6. Visit `http://localhost:8000` to see the application in action

## Contributors
- Hassan Ali
- Yousaf Sarwar

## License
This project is licensed under the terms of the MIT license.
