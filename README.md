# Quiz Master V1

A comprehensive quiz management system built with Flask, allowing administrators to create and manage quizzes while users can take quizzes and track their progress.

## Features

- User Authentication (Admin/User roles)
- Quiz Management
  - Create, edit, and delete quizzes
  - Add questions and options
  - Set time limits and pass percentages
- Subject and Chapter Organization
- Quiz Attempt Tracking
- Performance Analytics
- Responsive Design

## Technologies Used

- Python 3.x
- Flask
- SQLAlchemy
- Bootstrap 5
- Font Awesome
- SQLite Database

## Installation

1. Clone the repository:
```bash
git clone https://github.com/yourusername/quiz_master.git
cd quiz_master
```

2. Create and activate a virtual environment:
```bash
python -m venv venv
source venv/bin/activate  # On Windows: venv\Scripts\activate
```

3. Install dependencies:
```bash
pip install -r requirements.txt
```

4. Initialize the database:
```bash
python main.py
```

5. Run the application:
```bash
python main.py
```

## Default Admin Account

- Email: admin@example.com
- Password: admin123

## Project Structure

```
quiz_master/
├── static/
│   ├── css/
│   └── js/
├── templates/
│   ├── admin/
│   ├── auth/
│   └── user/
├── main.py
├── models.py
├── forms.py
├── utils.py
└── requirements.txt
```

## Contributing

1. Fork the repository
2. Create your feature branch (`git checkout -b feature/AmazingFeature`)
3. Commit your changes (`git commit -m 'Add some AmazingFeature'`)
4. Push to the branch (`git push origin feature/AmazingFeature`)
5. Open a Pull Request

## License

This project is licensed under the MIT License - see the LICENSE file for details.

## Author

K Ramakrishna

## Acknowledgments

- Flask Documentation
- Bootstrap Team
- Font Awesome Team 