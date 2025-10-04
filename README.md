# 🛡️ SafeResQ – MVP  

SafeResQ is a safety and support platform that empowers victims of abuse to seek help anonymously, trigger emergency alerts, and access professional counseling.  

---

## 📌 Project Overview  

SafeResQ provides a mobile-first experience that allows users to:  
- Register securely and set up emergency details.  
- Trigger a panic alert in seconds to notify trusted contacts.  
- Report incidents quickly and anonymously.  
- Access professional or AI-driven counseling.  
- Learn about self-help resources and legal support in Nigeria.  

---

## ⚡ Features  

- 📝 **User Registration & Profile Setup**  
  - Collects: First/Last Name, Email, Phone Number, Emergency Contact, Address, State/City  
  - Set a 4-digit panic cancel PIN  
  - Consent checkbox for emergency dispatch  

- 🔑 **Login & Verification**  
  - Login with email + password  
  - Email/OTP verification (default demo: `1234`)  
  - Password reset (updates via localStorage for now)  

- 📊 **User Dashboard**  
  - Greeting with user’s name + profile picture  
  - Quick actions: USSD Mode, Emergency Call, Quick Report  
  - Big red Panic Button (press to trigger emergency)  
  - Snapshot of recent reports  
  - Footer navigation bar (Home, Resources, Report, Profile)  

- 🚨 **Panic Mode**  
  - Confirmation modal: “Are you in danger?”  
  - Cancel with PIN, or send alert  
  - “Help is on the way” placeholder screen (backend integration planned)  

- 📞 **Emergency Call Page**  
  - One-tap emergency contacts: Police (112), Ambulance (911), Fire Service (113), OVH Rescue (114)  

- 📱 **USSD Mode**  
  - Instructions to dial `*123#` when offline (placeholder, backend planned)  

- 🕵️ **Anonymous Help**  
  - Self-help resources: Warning signs, What to do, Support system, Legal help  
  - AI chat counseling (placeholder, backend/AI integration planned)  

- 📝 **Incident Reporting**  
  - Form for type, location, description, urgency level  
  - Submitted reports show in dashboard snapshot  

- 👤 **Profile Page**  
  - View/edit all user details (via localStorage for demo)  
  - Update emergency contact & panic PIN  
  - Change profile picture  
  - Logout option  

---

## 🧭 User Flow  

1. **Splash Screen → Onboarding (3 pages)**  
2. **Sign Up** (Basic info → Emergency details → Password)  
3. **Email Verification + OTP** (default OTP = `1234`)  
4. **Complete Profile Setup** (Address, State/City, PIN)  
5. **Login Page** → Forgot Password available  
6. **Dashboard/Homepage**  
   - USSD Mode  
   - Emergency Call  
   - Quick Report  
   - Panic Button  
   - Speak Out section  
   - Top Agencies section  
   - Report Snapshot  
   - Footer nav (Home, Resources, Report, Profile)  
7. **Resources Page** (Self-help + Talk to a Professional)  
8. **Report Page** (Submit incidents)  
9. **Profile Page** (Edit details, Logout)  

---

## 🛠️ Tech Stack  

- **Frontend:** HTML5, CSS3, JavaScript  
- **Storage:** LocalStorage (demo purposes)  
- **Designs:** Figma (UI/UX from product designers)  
- **Future Integration:** Backend APIs for OTP, Panic Alerts, AI Chat, Emergency Dispatch  

---

## 🚀 Setup Instructions  

### 🔗 Live View  
👉 [SafeResQ Live Demo]( https://inventorsdev.github.io/NGB-Team-Alpha-Force-frontend-updated/ )  

### 💻 Local Setup  
1. Download this repository as a ZIP file.  
2. Extract the ZIP file to your computer.  
3. Open the folder and double-click `index.html` (or right-click → open in browser).  

---

## 🔮 Future Improvements  

- Real-time OTP verification via backend  
- Panic alert integration with SMS/WhatsApp/email APIs  
- Live location tracking for emergency dispatch  
- AI-powered counseling chat (OpenAI / Rasa integration)  
- Database support (MongoDB / SQL) for persistent user data  
- Admin dashboard for reports and analytics  

---

## 👥 Team Roles  

- **Frontend Development:** HTML, CSS, JS, LocalStorage setup  
- **Backend Development (Planned):** APIs for authentication, OTP, panic alert, chat, reports storage  
- **Product Design:** UI/UX mockups and Figma assets  
- **Team Collaboration:** GitHub, Pitch Decks, and MVP testing  
