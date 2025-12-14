DemocraTechSystem Storyboard

## Entry Points
```
index.html → Landing page
    ↓
login.html → User authentication
register.html → New user registration
```

---

## Admin Flow

**Dashboard**
- [admin-dashboard.html](web/admin-dashboard.html) - Main admin control panel

**Election Management**
- [manage-elections.html](web/manage-elections.html) - Create and manage elections
- [manage-candidates.html](web/manage-candidates.html) - Manage candidate registrations
- [election-results.html](web/election-results.html) - View and publish election results

**User Management**
- [manage-users.html](web/manage-users.html) - Manage student and admin accounts

---

##  Student Flow

**Dashboard**
- [student-dashboard.html](web/student-dashboard.html) - Main student portal

**Voting Process
1. [view-elections.html](web/view-elections.html) - Browse active elections
2. [voting-page.html](web/voting-page.html) - Cast votes
3. [vote-history.html](web/vote-history.html) - View voting history

**Election Results**
- [election-results-student.html](web/election-results-student.html) - View election results

**Candidacy**
- [apply-candidate.html](web/apply-candidate.html) - Apply to become a candidate

---

## 🔧 Common Pages

- [profile.html](web/profile.html) - User profile management
- [help.html](web/help.html) - Help and support documentation

---

## Project Structure

```
web/
├── index.html              # Landing page
├── login.html              # Login page
├── register.html           # Registration page
│
├── Admin Pages
│   ├── admin-dashboard.html
│   ├── manage-elections.html
│   ├── manage-candidates.html
│   ├── manage-users.html
│   └── election-results.html
│
├── Student Pages
│   ├── student-dashboard.html
│   ├── view-elections.html
│   ├── voting-page.html
│   ├── vote-history.html
│   ├── apply-candidate.html
│   └── election-results-student.html
│
└── Common Pages
    ├── profile.html
    └── help.html
```

### Admin Journey
1. Login → Admin Dashboard
2. Manage Elections (Create/Edit/Delete)
3. Manage Candidates (Approve/Reject)
4. Manage Users (Add/Remove/Edit)
5. View Results

### Student Journey
1. Register/Login → Student Dashboard
2. View Available Elections
3. Apply as Candidate (Optional)
4. Cast Vote
5. View Vote History
6. Check Election Results

## Getting Started

1. Start with [index.html](web/index.html)
2. Login or register a new account
3. Access role-based dashboard (Admin or Student)
4. Navigate through the system based on user role
