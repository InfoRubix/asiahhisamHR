# HR Feedback and Complaints System

**Built by RUBIX TECHNOLOGY**

A web system that makes it easy for employees to send feedback and complaints to the HR department with a user-friendly interface and admin panel for management.

## Key Features

### User Portal (index.html)
- ✅ Dual-function form (Feedback & Complaints)
- ✅ Responsive interface with Tailwind CSS
- ✅ Submit data to Google Sheets via Google Apps Script
- ✅ Real-time feedback for users
- ✅ Bahasa Malaysia support

### Administrator Panel (admin.html)
- 🔐 Email-based login system
- 📊 Dashboard with summary statistics
- 🔍 Data search and filtering functionality
- 👁️ Detailed view in popup modal
- 📈 Automatic sentiment analysis (Positive/Negative)
- 🔄 Real-time data from Google Sheets

## Tech Stack

- **Frontend**: HTML5, CSS3, JavaScript (Vanilla)
- **Styling**: Tailwind CSS, Font Awesome Icons
- **Backend**: Google Apps Script
- **Database**: Google Sheets
- **Font**: Inter (Google Fonts)

## File Structure

```
asiahhisamHR/
├── index.html      # Main portal for users
├── admin.html      # Admin panel for HR
└── README.md       # System documentation
```

## How to Use

### For Users
1. Open index.html in a web browser
2. Select the "Feedback" or "Complaint" tab
3. Fill in the subject and message
4. Click the send button

### For HR Admins
1. Open `admin.html` in a web browser
2. Log in with an authorized email
3. View dashboard with statistics
4. Use search and filtering to find data
5. Click on any item to see full details

## System Requirements

- Modern web browser (Chrome, Firefox, Safari, Edge)
- Active internet connection
- Properly configured Google Apps Script

## Configuration

This system requires a properly configured Google Apps Script to:
- Receive data from forms
- Store data in Google Sheets
- Authenticate admins based on email
- Provide API for panel admins

The Google Apps Script URL needs to be updated in both HTML files:
```javascript
const GOOGLE_SCRIPT_URL = 'YOUR_GOOGLE_SCRIPT_URL_HERE';
```

## Security

- Admin authentication via email and session token
- Data validation on both client and server sides
- Automatic session expiration for security

## Support

For any technical questions or issues, contact **RUBIX TECHNOLOGY**.

---

*This system is specifically designed to facilitate communication between employees and the HR department in an efficient and secure manner.*

---

## License & Terms

This software is proprietary to RUBIX TECHNOLOGY. Unauthorized reproduction, distribution, or modification is prohibited. For licensing inquiries, please contact RUBIX TECHNOLOGY directly.

---

**© 2025 RUBIX TECHNOLOGY. All right reserved.**