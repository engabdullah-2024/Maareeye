# Maareeye — School Management System (MVP‑01)

*A concise, non‑technical guide for administrators*

---

## What is Maareeye?

Maareeye helps schools stay organized. In this first release (MVP‑01), there are two roles:

* **SuperAdmin** – the single top‑level administrator who sets up each school and assigns its School Admin.
* **School Admin** – the per‑school administrator who manages their own school (in MVP‑01: teachers can be created by School Admins).

> There is **no self‑registration**. The SuperAdmin account is provided by the Maareeye team.

---

## Quick Links

* **SuperAdmin login:** `/login`
* **School Admin login:** `/school/login`

> If you cannot access these pages or forgot your credentials, contact the Maareeye team (see Support below).

---

## SuperAdmin — What you can do

* Create a **School** with a unique name.
* Assign a **School Admin** (name, username, email, password).
* Edit school details and the assigned School Admin’s details.
* Delete a school (this also removes its School Admin and their data).
* View a list of all schools and all school admins.

### Typical SuperAdmin workflow

1. **Sign in** at `/login`.
2. Open **Dashboard** and click **Create School**.
3. Enter the school’s name, then the School Admin’s name, username, email, and password.
4. Save. Share the School Admin’s credentials securely with that admin.

> If a School Admin forgets their password, the SuperAdmin can **update/rotate** it from the dashboard.

---

## School Admin — What you can do

* **Sign in** at `/school/login`.
* See your **School Dashboard**.
* **Create Teachers** for your school (basic create flow in MVP‑01).

### Typical School Admin workflow

1. **Sign in** at `/school/login`.
2. From your dashboard, use **Create Teacher** to add staff.
3. Review your list of teachers.

---

## Security & Privacy (plain‑language)

* Sign‑in is required. Your access is limited to your role.
* SuperAdmin sees and manages all schools; School Admins see **only their own** school.
* Passwords are stored safely; avoid sharing credentials over chat or email. Use a secure method to deliver or change them.
* Logging out on shared devices is recommended.

---

## Troubleshooting

* **“Access denied” or redirected to login:** You’re not signed in or do not have permission. Sign in with the correct role.
* **Duplicate school name:** Use a different school name.
* **Username/email already in use:** Choose a different username/email for the School Admin.
* **Forgotten School Admin password:** Ask the SuperAdmin to set a new one.

---

## Roadmap (next steps)

* School Admin: edit/delete teachers, search & filtering.
* Student management (enrollment, guardians).
* Classes/timetables and attendance.
* Improved activity logs and notifications.

---

## Support

* If you need help, reach out to the Maareeye team contact provided to you.
* Please include your **role** (SuperAdmin or School Admin) and **school name** (if applicable) when asking for assistance.
