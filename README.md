# CMPG-323-Overview-36627399
This repository will hold information about the due dates of assignment and time taken to complete them

### Repositories that will be created for each projects
1) CMPG 323 Overview-36627399: is the respository for first project which is Agile and Scrum
2) CMPG 323 Project 2-36627399: is the repository for the second project which is API Development
3) CMPG 323 Project 3-36627399: is the repository for the third project which is Standards and Patterns
4) CMPG 323 Project 4-36627399: is the repository for the fourth project which is Testing and RPA
5) CMPG 323 Project 5-36627399: is the repository for the fifth project which is Reporting and Monitoring

### Digram showing how the project will be broken down
```mermaid
graph TB;
    <a href CMPG-323Overview(Repositiory)>-->Code</a>;
    CMPG-323Overview(Repositiory)-->Issues;
    CMPG-323Overview(Repositiory)-->Projects;
    Code-->READMEFILE;
    Code-->LICENCE;
    Issues-->Lables;
    Issues-->Millstones;
    Projects-->Project1;
    Project1-->TabularView;
    Project1-->StatusView;
    Project1-->LinkedAssignmentView;
    Project1-->SprintView;
    Project1-->DueDateView
    TabularView-->AddColumns;
    TabularView-->PopulateTheTask
    PopulateTheTask-->LinkRepositoryToTheProject;
    StatusView-->GroupTheTaskByStatus;
    LinkedAssignmentView-->GroupTheTastByLinkedAssignment;
    SprintView-->GroupTheTaskBySprint;
    DueDateView-->GroupTheTaskByDueDate;
```
