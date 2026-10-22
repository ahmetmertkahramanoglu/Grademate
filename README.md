# GradeMate

AI-assisted grading and feedback for Google Classroom. Instructors create assignments
in GradeMate; student submissions are evaluated against a rubric, and proposed grades
and feedback are returned to students only after instructor approval.

## Team 5
- Sude Yılmaz – Infrastructure and integration lead
- Ahmet Mert Kahramanoğlu – AI evaluation lead
- Zeynep Şüheda Kaya – UI, reporting and test data lead

## Tech stack
Python 3.11, Streamlit, Google Classroom & Drive APIs, SQLite, LLM API, Docker

## Setup
Under development. Setup steps will be added in Week 6.
API keys and tokens are kept in a local `.env` file, which is never committed.

## Workflow
- `main` is protected: it always contains a working version; no direct pushes.
- `develop` collects finished features during a sprint; merged into `main` at each sprint review.
- One branch per task, named by issue: `feature/12-classroom-auth`, `fix/27-json-validation`.
- Every pull request references its issue and is approved by one member other than its author.
- Tasks are tracked on the GitHub Projects board.

## Documents
- `Team5_D1_SDP.pdf` – Software Development Plan
