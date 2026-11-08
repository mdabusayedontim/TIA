# THE IGNITE ACADEMY — UI Design Specification

## Brand
- Primary: `#101A35` (Navy)
- Secondary: `#192844`
- Accent: `#F5A623` (Gold)
- Background: `#F4F6FA`
- Surface: `#FFFFFF`
- Success: `#16A36A`
- Error: `#DC3545`
- Bengali font: Hind Siliguri
- English font: Inter

## Android Student navigation
Bottom navigation (5 items):
1. Home
2. Courses
3. Exam
4. Notice
5. Profile

Student screens:
Splash, Onboarding, Login, Registration, Dashboard, Courses, Course Details,
Chapter Details, Learning Center, Material Viewer, Class Routine, Attendance,
Exam List, Exam Instructions, MCQ Exam, Written Exam Info, Submission Result,
Results, Performance Analytics, Assignments, Assignment Details, Submission,
Fees, Invoice Details, Payment History, Live Classes, Notice Board, Notice Details,
Doubt Solving, Leaderboard, Parent Linking, Profile, Settings, Support.

## Teacher screens
Dashboard, My Batches, Batch Details, Student List, Student Details, Routine,
Class Sessions, Attendance Taking, Attendance History, Exam Creator, Question
Editor, Marks Entry, Result Review, Assignment Creator, Submission Review,
Material Upload, Live Class Management, Student Performance, Notifications,
Profile.

## Parent screens
Dashboard, Linked Children, Child Profile, Attendance, Results, Routine,
Fee Invoices, Payment History, Notices, Notifications, Profile.

## Web Admin screens
Login, Dashboard, Admissions, Admission Details, Students, Student Details,
Teachers, Teacher Details, Parents, Courses, Subjects, Chapters, Batches,
Enrollments, Routine, Class Sessions, Attendance, Exams, Question Bank,
Results, Assignments, Materials, Live Classes, Fee Invoices, Payments,
Expenses, Notices, Notifications, Reports, Staff Permissions, Audit Logs,
Settings.

## UI rules
- Use 8dp spacing grid.
- Cards: 14–16dp radius.
- Inputs: 10–12dp radius, visible labels and validation.
- Buttons: minimum 48dp height.
- Every screen must have loading, empty, error and success states.
- Use Bengali labels by default, with English language option.
- Use responsive layouts and accessible contrast.
- Do not hardcode sample figures in production.

## Data and security reminders
- Enforce role permissions in backend/Firestore Rules, not only UI.
- Students can only read their own private records.
- Parents can only read linked children's records.
- Teachers can only access assigned batches.
- Payment verification must be server-authoritative.
- Exam scoring and answer release must be controlled by trusted backend logic.
