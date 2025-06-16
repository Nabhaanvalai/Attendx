# Employee Attendance Management System

A web-based application for tracking employee attendance, managing leave requests, and providing dashboards for employees, managers, and administrators.

## Features

### Authentication
- Username/password login
- Biometric authentication simulation
- Role-based access (Employee, Manager, Admin)

### Employee Dashboard
- Clock in/out functionality
- Real-time attendance tracking
- View attendance history
- Submit leave requests
- View leave request status

### Manager Dashboard
- Team overview with real-time status
- Leave request management (approve/reject)
- Employee status monitoring

### Admin Dashboard
- Employee management
- Department overview
- Organization-wide metrics

## Technology Stack

- HTML5
- JavaScript (Vanilla)
- TailwindCSS
- Simulated REST API (for demonstration purposes)

## Usage

### Accessing Different Roles

The system includes three user roles with different capabilities:

1. **Employee**
   - Username: `employee`
   - Password: `password`
   - Access to: attendance tracking, leave requests

2. **Manager**
   - Username: `manager`
   - Password: `password`
   - Access to: team overview, leave request approvals

3. **Admin**
   - Username: `admin`
   - Password: `password`
   - Access to: employee management, department metrics

You can switch between roles using the user dropdown menu in the top-right corner after logging in.

### Biometric Authentication

The system includes a simulated biometric authentication feature. Click on the fingerprint scanner to simulate a successful authentication.

## Implementation Details

- Single-page application architecture
- Client-side data storage (for demonstration)
- Responsive design using TailwindCSS
- Mock API services simulating server responses

## Development

### Simulated API

The application uses simulated API calls with timeouts to mimic server communication. In a production environment, these would be replaced with actual API endpoints.

### Data Persistence

Currently, all data is stored in memory during the session. In a production environment, this would be replaced with server-side storage.

## Future Enhancements

- Real database integration
- Real biometric authentication
- Reporting features
- Mobile application
- Email notifications
- Calendar integration 