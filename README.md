HealthLink – Doctor Management Portal
The Doctor App is the counterpart to the Patient App, designed specifically for healthcare professionals to manage their practice, view patient lists, and issue digital prescriptions efficiently.

🚀 Key Features
1. Doctor Profile & Status
Professional Identity: Doctors can manage their own profile, including specialty, experience, and bio.

Availability Toggle: A simple switch to let patients know if the doctor is currently available for consultations.

2. Appointment Management
Patient Queue: A dedicated list showing all pending and confirmed appointments specifically for that doctor.

Actionable Appointments: Doctors can "Accept" or "Decline" appointment requests, which updates the patient's dashboard in real-time.

Status Tracking: Visual indicators (like Green for Confirmed, Orange for Pending) help doctors prioritize their day.

3. Digital Prescription Tools
Prescription Creator: An easy-to-use form where doctors enter medicine names, dosages, and instructions.

Instant Issuance: Once submitted, the prescription is instantly linked to the patient's ID and appears on their "My Prescriptions" page.

History Log: Doctors can view a history of all prescriptions they have issued to a specific patient.

4. Patient Records Access
Searchable Database: Doctors can search for patients by name or ID to review their medical history.

Confidential Access: Securely view patient details without compromising the data of patients not assigned to them.

🛠️ Technology Stack
Frontend: Flutter (Cross-platform for web and mobile).

Backend: Firebase Firestore (for real-time data syncing between doctor and patient).

Authentication: Firebase Auth (ensures only verified medical professionals can log in).

🛡️ Security Features
Role-Based Access: The system ensures that only users registered as "Doctors" can access the doctor-specific features.

Encryption: All communication between the doctor's device and the database is secured via SSL/TLS.

Audit Trail: Every prescription issued is timestamped and logged for medical record accuracy.

