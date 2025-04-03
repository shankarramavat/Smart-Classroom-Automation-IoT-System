# Smart-Classroom-Automation-IoT-System
Revolutionize classroom management with our intelligent IoT automation solution that detects occupancy and controls appliances to maximize energy efficiency.
# Smart Classroom Automation System

An intelligent IoT-based classroom automation system that uses computer vision and sensors to automatically control classroom appliances (lights, AC, fans) based on occupancy detection.

## 🌟 Features

- **Intelligent Occupancy Detection**: Uses OpenCV with MobileNet SSD model to detect people in the classroom
- **Automated Appliance Control**: Turns on/off lights, AC, and fans based on classroom occupancy
- **Energy Savings**: Reduces electricity consumption by preventing appliances from running in empty classrooms
- **Manual Override**: Allows teachers to override automatic controls when needed
- **Real-time Monitoring**: Dashboard shows current classroom status, occupancy, and appliance states
- **Analytics Dashboard**: Visualizes energy savings, occupancy patterns, and system events over time
- **Secure Access**: User authentication with different permission levels
- **Event Logging**: Comprehensive logging of all system events for audit and analysis

## 📋 Technology Stack

### Backend
- **Flask**: Python web framework
- **SQLAlchemy**: ORM for database interactions
- **PostgreSQL**: Robust relational database
- **Gunicorn**: WSGI HTTP Server

### Frontend
- **Next.js**: React framework for modern UI
- **Material UI**: Component library with pre-styled elements
- **Chart.js/Recharts**: Data visualization libraries

### Computer Vision
- **OpenCV**: Image processing and person detection
- **MobileNet SSD**: Neural network model for object detection

### IoT Simulation
- **Threading**: For concurrent hardware operations
- **MQTT Simulation**: For IoT device communication

## 📊 Dashboard Features

- Real-time occupancy status
- Current temperature and humidity readings
- Appliance control status (with override options)
- Energy savings in kWh and Indian Rupees (₹)
- Occupancy patterns visualization
- System event logs with filtering

## 📱 Responsive Design

The application is fully responsive and works on:
- Desktop computers
- Tablets
- Mobile phones

## 🔐 Security Features

- Secure user authentication
- Password hashing
- Role-based access control
- Session management

## 💻 Installation Instructions

### Prerequisites
- Python 3.9+
- Node.js 18+
- PostgreSQL database

### Setup Steps

1. **Clone the repository**
   ```bash
   git clone https://github.com/yourusername/classroom-automation.git
   cd classroom-automation
   ```

2. **Set up the backend**
   ```bash
   # Install Python dependencies
   pip install -r requirements.txt
   
   # Set up environment variables (copy from .env.sample)
   cp .env.sample .env
   
   # Configure your database URL in .env
   ```

3. **Set up the frontend**
   ```bash
   # Install Node.js dependencies
   npm install
   ```

4. **Run the application**
   ```bash
   # Start the Flask backend
   python main.py
   
   # In a separate terminal, start the Next.js frontend
   npm run dev
   ```

5. **Access the application**
   - Backend: http://localhost:5000
   - Frontend: http://localhost:3000

## 🚀 Deployment

This application consists of two parts that need to be deployed separately:

1. **Backend (Flask)**: Deploy to a Python-supporting platform like Heroku, Render, or Railway
2. **Frontend (Next.js)**: Deploy to Vercel

See [VERCEL_DEPLOYMENT_GUIDE.md](./VERCEL_DEPLOYMENT_GUIDE.md) for detailed deployment instructions.

## 📝 License

This project is licensed under the MIT License - see the LICENSE file for details.

## 🙏 Acknowledgements

- OpenCV for computer vision capabilities
- Material UI for the responsive interface components
- Next.js team for the fantastic React framework
- Flask team for the lightweight web framework
