# TrackIt : Project Tracking Made Easy 🚀

TrackIT is a robust Project Management Web Application designed to streamline the process of tracking team projects, assigning user stories, and providing detailed task analysis.

### 🚀 Technologies

![React](https://img.shields.io/badge/-React-61DAFB?logo=react&logoColor=white) ![Node.js](https://img.shields.io/badge/-Node.js-339933?logo=node.js&logoColor=white) ![MongoDB](https://img.shields.io/badge/-MongoDB-47A248?logo=mongodb&logoColor=white) ![Express](https://img.shields.io/badge/-Express-000000?logo=express&logoColor=white) ![Context API](https://img.shields.io/badge/-ContextAPI-5D4037?logo=react&logoColor=white) ![HTML5](https://img.shields.io/badge/-HTML5-E34F26?logo=html5&logoColor=white) ![CSS3](https://img.shields.io/badge/-CSS3-1572B6?logo=css3&logoColor=white) ![MUI](https://img.shields.io/badge/-MUI-007FFF?logo=mui&logoColor=white) ![Moment.js](https://img.shields.io/badge/-Moment-FFCA28?logo=javascript&logoColor=black) ![Chart.js](https://img.shields.io/badge/-Chart.js-FF6384?logo=chart.js&logoColor=white)

## User Requirements 📝

- **User Login/Register Page**
  - Register: User can create an account with username and password.
  - Login: Registered users can log in to their existing account.
  <div style="display: flex; align-items: center; justify-content: space-around;">
      <img alt="Register" src="./Demo/assets/Register.png" style="height: 130px; width: 120px;">
      <img alt="Login" src="./Demo/assets/Login.png" style="height: 130px; width: 120px;">
      <img alt="OTP" src="./Demo/assets/OTP.png" style="height: 130px; width: 120px;">
  </div>

- **Home Page**
  ![Projects](./Demo/assets/Projects.png)
  - View and create Project Groups.
  - Project Group admin can manage group details like adding or deleting members, updating project titles, deleting entire Project Group, etc.
  - Users can modify their profiles. By default, User will have access to groups he is part of
    <img alt="Projects CRUD" src="./Demo/assets/Projects_crud.png" height=“300” width=“480”>


- **Project Group Details Page**
  <div style="display: flex; flex-direction: column; align-items: center;">
      <img alt="Projects Tasks" src="./Demo/assets/Project_tasks.png" style="width: 500px; margin-bottom: 10px; height: 220px">
      <img alt="Task Detail" src="./Demo/assets/Task_detail.png" style="width: 500px; height: 190px">
  </div>

  - Display of user/project tasks.
  - Task management features and Dashboard Metrics.
  - Email notifications on task status changes.
  - Task filtering options. Users can view each task detail like task_status (Created, InProgress, Done), due_date, description, task_created_by, task_assigned_to, task_label (feature/bug)
  - Pie chart for task progress visualization in the Project Group
  <img alt="Pie Visualization" src="./Demo/assets/pie.png" height=“40” width=“40”>

## Features 🌟

1. **Efficient Project Group Management**: Create, update, and delete project groups with ease.
2. **Dynamic Task Handling**: Add, update, or delete tasks within project groups.
3. **User-Friendly Dashboard**: A dashboard offering comprehensive metrics and a pie chart visualization of task progress.
4. **Customizable Notifications**: Automated email alerts for task status updates.
5. **Advanced Filtering**: Filter tasks by status, due date, or group member name.

## Assumptions 📌

- A user can be a member of multiple Project Groups.
- Each Project Group requires at least one user.
- A user in a Project Group can be assigned multiple tasks, but each task is unique to one user.

## Team Members 👥

- Nikhil Reddy Karukonda - `karukonda.n@northeastern.edu`
- Venkatesha Matam - `matam.v@northeastern.edu`
- Naga Venkata Nishanth Sayana - `sayana.n@northeastern.edu`
- Rahul Chowdary Kalapala - `Kalapala.r@northeastern.edu`

## Domain Model Diagram 📊

<img alt="Project Tracking Domain Model" src="../Demo/../TrackIt_App/Demo/assets/project-tracking-domain-model.jpeg" height=“380” width=“680”>
