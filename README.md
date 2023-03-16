# Medicare [![MIT License](https://img.shields.io/apm/l/atomic-design-ui.svg?)](https://github.com/tterb/atomic-design-ui/blob/main/LICENSE)
### Stack we used
![Python](https://img.shields.io/badge/python-3670A0?style=for-the-badge&logo=python&logoColor=ffdd54)
![HTML5](https://img.shields.io/badge/html5-%23E34F26.svg?style=for-the-badge&logo=html5&logoColor=white)
![JavaScript](https://img.shields.io/badge/javascript-%23323330.svg?style=for-the-badge&logo=javascript&logoColor=%23F7DF1E)
![CSS3](https://img.shields.io/badge/css3-%231572B6.svg?style=for-the-badge&logo=css3&logoColor=white)


![meditate](https://user-images.githubusercontent.com/79878896/124366069-65f10000-dc66-11eb-84c0-e548883fbb1c.JPG)

Medicare - An Online Medicine Ordering System Built with Django

## About
Medicare is an open-source online medicine ordering system built with Python Django. The system features separate logins for NGO and customers, allowing customers to browse through a list of medicines, place orders, and pay for them online, while NGOs can manage their inventory and process the received orders. 

## Features
- Separate Sign in & Sign up for NGOs and customers

![sign](https://user-images.githubusercontent.com/79878896/124366070-67bac380-dc66-11eb-93c4-310e0db01788.JPG)

![signup](https://user-images.githubusercontent.com/79878896/124366073-68ebf080-dc66-11eb-8ecc-0e83231c587b.JPG)

- Customer can browse medicines, add them to cart, and place orders
- NGOs can manage their inventory, process orders, and track delivery status
- Payment gateway integration
- Secure user authentication and authorization system
- Responsive web design

## Installation
1. Clone the repository:
    ```
    git clone git@github.com:Hassanali4/Medicare.git
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
