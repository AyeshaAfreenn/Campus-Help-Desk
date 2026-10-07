# Campus-Help-Desk
# User Stories - Campus Help Desk

## Group Information

* **Group Number:** G06
* **Module:** Campus Help Desk
* **Group Label:** team-06
* **Product Owner:** Ayesha
* **Story Writer:** Laiba
* **Task Planner:** Ayisha
* **Tester:** Hamd
* **Reviewer:** group

---

## US-01 - Create a Help Desk Request

### User Story

As a student, I want to create a help desk request so that I can report a problem with Wi-Fi, classroom equipment, projector, or the university portal.

### Acceptance Criteria

* [ ] The system displays a help desk request form.
* [ ] The student can enter a description of the problem.
* [ ] The student can submit the request successfully.
* [ ] The system displays a confirmation after the request is submitted.

### Technical Tasks

* [ ] Design the help desk request form.
* [ ] Implement the request submission function.
* [ ] Store the request in the database.
* [ ] Validate the required request information.
* [ ] Test the request submission process.

### Story Information

* **Priority:** High
* **Assignee:** member1-github-username
* **Status:** Backlog
* **Labels:** `type:user-story`, `team-06`

### Definition of Done

* [ ] All acceptance criteria are satisfied.
* [ ] The assigned tester has verified the story.
* [ ] Another group member has reviewed the work.
* [ ] The team has recorded the required evidence.

---

## US-02 - Select Problem Category

### User Story

As a student, I want to select a problem category so that my complaint can be sent to the appropriate support team.

### Acceptance Criteria

* [ ] The system displays the available problem categories.
* [ ] The student can select Wi-Fi, classroom, projector, or university portal.
* [ ] The selected category is saved with the help desk request.
* [ ] The system does not allow the request to be submitted without selecting a category.

### Technical Tasks

* [ ] Design the problem category selection.
* [ ] Add the available problem categories.
* [ ] Connect the category with the help desk request.
* [ ] Validate that a category is selected.
* [ ] Test all available categories.

### Story Information

* **Priority:** High
* **Assignee:** member2-github-username
* **Status:** Backlog
* **Labels:** `type:user-story`, `team-06`

### Definition of Done

* [ ] All acceptance criteria are satisfied.
* [ ] The assigned tester has verified the story.
* [ ] Another group member has reviewed the work.
* [ ] The team has recorded the required evidence.

---

## US-03 - View Request Priority

### User Story

As a student, I want to view the priority of my help desk request so that I know how urgent my reported problem is.

### Acceptance Criteria

* [ ] The system assigns a priority to each help desk request.
* [ ] The priority is displayed with the request.
* [ ] The student can see whether the request is High, Medium, or Low priority.
* [ ] The displayed priority matches the priority stored for the request.

### Technical Tasks

* [ ] Define the request priority levels.
* [ ] Implement priority assignment.
* [ ] Display the priority on the request details page.
* [ ] Connect the priority with the request record.
* [ ] Test High, Medium, and Low priority requests.

### Story Information

* **Priority:** Medium
* **Assignee:** member3-github-username
* **Status:** Backlog
* **Labels:** `type:user-story`, `team-06`

### Definition of Done

* [ ] All acceptance criteria are satisfied.
* [ ] The assigned tester has verified the story.
* [ ] Another group member has reviewed the work.
* [ ] The team has recorded the required evidence.

---

## US-04 - Track Request Status

### User Story

As a student, I want to track the status of my help desk request so that I know whether my problem is waiting, being worked on, or resolved.

### Acceptance Criteria

* [ ] The system displays the current status of the request.
* [ ] The student can see statuses such as Pending, In Progress, and Resolved.
* [ ] The status is updated when support staff work on the request.
* [ ] The student can view the updated status.

### Technical Tasks

* [ ] Define the request status values.
* [ ] Implement status updates.
* [ ] Display the current status to the student.
* [ ] Connect status updates with the request record.
* [ ] Test the complete status flow.

### Story Information

* **Priority:** High
* **Assignee:** member4-github-username
* **Status:** Backlog
* **Labels:** `type:user-story`, `team-06`

### Definition of Done

* [ ] All acceptance criteria are satisfied.
* [ ] The assigned tester has verified the story.
* [ ] Another group member has reviewed the work.
* [ ] The team has recorded the required evidence.

---

## US-05 - Provide Feedback After Resolution

### User Story

As a student, I want to provide feedback after my problem is resolved so that I can tell the university about my support experience.

### Acceptance Criteria

* [ ] The system allows the student to provide feedback after the request is resolved.
* [ ] The student can give a rating or comment.
* [ ] The system saves the submitted feedback.
* [ ] Feedback cannot be submitted for an unresolved request.

### Technical Tasks

* [ ] Design the feedback form.
* [ ] Implement the feedback submission function.
* [ ] Store feedback with the related request.
* [ ] Validate that the request is resolved.
* [ ] Test valid and invalid feedback submissions.

### Story Information

* **Priority:** Medium
* **Assignee:** member5-github-username
* **Status:** Backlog
* **Labels:** `type:user-story`, `team-06`

### Definition of Done

* [ ] All acceptance criteria are satisfied.
* [ ] The assigned tester has verified the story.
* [ ] Another group member has reviewed the work.
* [ ] The team has recorded the required evidence.

---

## Change Challenge Response

* **Affected User Story:** US-01
* **New Requirement:** The system should prevent a student from submitting the same complaint twice.
* **Updated Acceptance Criterion:** The system must detect a duplicate complaint from the same student and prevent the duplicate request from being submitted.
* **New or Updated Task:** Add duplicate complaint checking based on the student and complaint details before creating a new help desk request.

---

## Peer Review

* **Reviewed By Group:** G06
* **User role is clear:** Yes
* **User value is clear:** Yes
* **Acceptance criteria are testable:** Yes
* **Missing condition:** The stories should also consider duplicate complaint handling.
* **Recommended improvement:** Add duplicate request checking so that the same complaint is not submitted multiple times.
