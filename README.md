Smart-Attend Mobile App

SDLC & DevOps Fundamentals Assignment

Project Overview:

Smart-Attend is a mobile application designed to automatically record student attendance when they enter a classroom. The system uses Geo-fencing to detect when a student is within the classroom boundary and marks attendance automatically.

During development, a new requirement was introduced by the university administration: Biometric (Face ID) verification must be added to prevent proxy attendance.
To handle this change efficiently, the project adopts the Agile Scrum framework with iterative development through sprints.

CI/CD (Continuous Integration and Continuous Deployment) is used to ensure that new updates from each sprint are delivered quickly and reliably.

1. Continuous Integration

Whenever developers push new code changes to the repository, the CI pipeline automatically:

Builds the application

Runs automated tests

Checks for errors or integration issues

This ensures that the system remains stable even when multiple developers contribute code.

2. Continuous Deployment

After successful testing, the deployment pipeline automatically releases the updated version of the application.
This allows students and teachers to receive the latest features without manual updates.

For example:

After Sprint 1, the MVP version of the attendance app becomes available.

After Sprint 2, the system automatically updates to include Face ID verification and improved dashboards.

Benefits of Using CI/CD

Faster delivery of new features

Reduced human errors during deployment

Immediate availability of sprint updates

Early detection of bugs through automated testing

Continuous improvement of the application
