# Automated-Exam-Timetable-Invigilation-Planner Using UiPath
Automate exam timetable generation, room allocation, faculty invigilation scheduling, and conflict detection using UiPath RPA and Excel.
An automated examination scheduling solution built using **UiPath RPA and Microsoft Excel**. The project streamlines exam timetable generation, room allocation, faculty invigilation assignment, and scheduling conflict detection.

## Overview

Manually preparing examination timetables requires coordinating student subject groups, exam dates, room availability, faculty availability, and invigilation duties. This project automates key scheduling tasks using a UiPath workflow and structured Excel data.

## Key Features

- **Automated Timetable Generation:** Generates examination schedules from subject data and configured exam rules.
- **Room Allocation:** Assigns rooms to examinations using available room information.
- **Invigilation Scheduling:** Generates faculty invigilation assignments.
- **Conflict Detection:** Includes checks for overlapping student examinations and faculty invigilation duties.
- **Excel Integration:** Reads input data from Excel workbooks and writes the generated schedules to output workbooks.
- **Execution Logging:** Records processing information and scheduling counts.

## Technology Stack

- UiPath Studio
- UiPath Excel Activities
- Microsoft Excel
- Visual Basic expressions in UiPath workflows
- Robotic Process Automation (RPA)

## Project Structure

```text
AutomatedExamTimetableInvigilationPlanner/
├── Main.xaml
├── project.json
├── Input/
│   ├── StudentData.xlsx
│   ├── FacultyData.xlsx
│   ├── Subjects.xlsx
│   ├── Rooms.xlsx
│   └── ExamRules.xlsx
├── FinalExamTimetable.xlsx
└── FinalInvigilationSchedule.xlsx
```

## Workflow

1. Read student, faculty, subject, room, and examination-rule data from Excel.
2. Generate an examination schedule from the subject records and configured rules.
3. Check for overlapping examination assignments involving students.
4. Allocate rooms to scheduled examinations.
5. Generate faculty invigilation assignments and check for overlapping duties.
6. Export the final timetable and invigilation schedule to Excel.

## How to Run

1. Install UiPath Studio with a compatible Windows project configuration.
2. Clone or download this repository.
3. Open the project using its `project.json` file in UiPath Studio.
4. Restore the required UiPath activity dependencies.
5. Verify that all input Excel files exist in the expected `Input/` directory.
6. Review the scheduling rules and file paths.
7. Run `Main.xaml` and inspect the generated output workbooks.

## Project Goals

- Reduce manual effort in examination administration.
- Improve consistency in timetable preparation.
- Make scheduling conflicts easier to identify.
- Demonstrate practical RPA workflow design and Excel automation.

## Limitations

This is an academic automation project. The scheduling logic should be tested with different datasets and edge cases before real institutional use. Room capacity, faculty workload limits, availability constraints, and student conflicts should be validated against institutional requirements.

## Future Enhancements

- Add stronger room-capacity and faculty-availability validation.
- Improve timetable optimization to reduce conflicts and uneven workloads.
- Add automated notifications for faculty and students.
- Generate a dashboard with scheduling summaries and conflict reports.
- Add automated test cases and validation reports.

## License

Choose an appropriate open-source license before redistributing the project. If this project incorporates third-party assets or code, review their licenses first.
