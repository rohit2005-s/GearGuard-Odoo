# GearGuard-The Ultimate Management System

A comprehensive equipment management system built with Odoo integration, designed to streamline asset tracking, maintenance scheduling, and inventory management.

## 📋 Overview

GearGuard-Odoo is a modern equipment management solution that combines the power of Odoo ERP with custom functionality to provide robust gear and equipment tracking capabilities. The system helps organizations maintain control over their assets, schedule preventive maintenance, and optimize resource allocation.

## ✨ Features

- **Equipment Tracking**: Comprehensive asset management and tracking system
- **Maintenance Scheduling**: Automated maintenance reminders and tracking
- **Inventory Management**: Real-time equipment inventory monitoring
- **User Dashboard**: Intuitive frontend interface for easy access
- **Odoo Integration**: Seamless integration with Odoo ERP modules
- **Custom Workflows**: Tailored business process automation

## 🛠️ Tech Stack

- **Backend**: Python, Flask Framework
- **Frontend**: Modern JavaScript framework
- **Database**: SQLite (development)
- **Version Control**: Git

## 📦 Project Structure

```
GearGuard-Odoo/
├── app/                    # Backend application code
├── frontend/              # Frontend application files
├── instance/              # Instance-specific configuration
├── venv/                  # Python virtual environment
├── requirements.txt       # Python dependencies
├── run.py                # Application entry point
├── LICENSE               # MIT License
└── README.md             # Project documentation
```

## 🚀 Getting Started

### Prerequisites

- Python 3.8 or higher
- pip (Python package manager)
- Git
- Virtual environment (recommended)

### Installation

1. **Clone the repository**
   ```bash
   git clone https://github.com/anash56/GearGuard-Odoo.git
   cd GearGuard-Odoo
   ```

2. **Create and activate virtual environment**
   ```bash
   # Windows
   python -m venv venv
   venv\Scripts\activate

   # macOS/Linux
   python3 -m venv venv
   source venv/bin/activate
   ```

3. **Install dependencies**
   ```bash
   pip install -r requirements.txt
   ```

4. **Configure the application**
   - Update configuration files in the `instance/` directory
   - Set up database connections
   - Configure Odoo integration parameters

5. **Run the application**
   ```bash
   python run.py
   ```

## 🔧 Configuration

Configuration files are located in the `instance/` directory. Make sure to:

- Set up your database credentials
- Define environment-specific variables
- Set up security keys and tokens

## 📚 Usage

1. **Access the application**
   - Navigate to `http://localhost:5000` (or configured port)
   - Log in with your credentials

2. **Equipment Management**
   - Add new equipment entries
   - Track equipment location and status
   - Schedule maintenance tasks

3. **Maintenance Tracking**
   - View upcoming maintenance schedules
   - Log maintenance activities
   - Generate maintenance reports

## 🤝 Contributing

Contributions are welcome! Please follow these steps:

1. Fork the repository
2. Create a feature branch (`git checkout -b feature/AmazingFeature`)
3. Commit your changes (`git commit -m 'Add some AmazingFeature'`)
4. Push to the branch (`git push origin feature/AmazingFeature`)
5. Open a Pull Request


## 📝 License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

## 🐛 Bug Reports

If you encounter any bugs or issues, please create an issue on the [GitHub repository](https://github.com/anash56/GearGuard-Odoo/issues).

## 📧 Contact

For questions or support, please contact the project maintainers through the GitHub repository.
