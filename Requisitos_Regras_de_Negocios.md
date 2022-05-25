# Business Rules and Requirements
**Project:** Sprint Manager
**Autor:** Jairo Koning
**Last Update:** 12/01/2022

---

## Organizations

#### Create Organization

**Functional Requirements**

- It should be able to create a new Organization

**Rules**

- It should NOT be able to create a duplicated Organization

#### Show Organization

**Functional Requirements**

- It should be able to show all data details of organization

**Rules**

- Just User that are linked with Organization should be able to show data

#### Update Organization

**Functional Requirements**

- It should be able to update Organization data

**Rules**

- Just Admin User or PO User should be able to change the data

#### Delete Organization

**Functional Requirements**

- It should be able to delete Organization

**Rules**

- Just Admin User should be able to delete Organization

---
## Users

#### Create User Account

**Functional Requirements**

- It should be able to create a new User Account
- It should be able to link to a Organization

**Rules**

- It should NOT be able to create a duplicated User Account

#### Show User Account Profile

**Functional Requirements**

- It should be able to show User Account Profile

**Rules**

- User should be authenticated to show Account Profile

#### Update User Account

**Functional Requirements**

- User should be able to update Account

**Rules**

- User should be authenticated to update Account

#### Delete User Account

**Functional Requirements**

- User should be able to delete self Account

**Rules**

- User should be authenticated

___

## Change linked Organization

## Workspace

## Projects

#### Create Project

**Functional Requirements**
- It should be able to create new Project

**Rules**
- Project needs to be linked with a previous created Workspace

#### List Projects

- **Requirements**
  - It should be able to list all created Projects of a Workspace
  - It should be able to filter active/inactive Projects
 

#### Show Project
- **Requirements**
  - It should be able to show Project details

#### Show Project Epics
- **Requirements**
  - It should be able to show all Epics of a Project

#### Show Project Tasks
- **Requirements**
  - It should be able to show all Tasks of a Project

#### Update Project
- **Requirements**
  - It should be able to update Project

#### Delete Project
- **Requirements**
  - It should be able to delete Project

---
## Epics

#### Create Epic
- **Requirements**
  - It should be able to create new Epic
- **Rules**
  - Epic should be linked to a Project
  - User should be authenticated

#### List Epics of Project
- **Requirements**
  - It should be able to list all Epics of a Project
- **Rules**
  - User should be authenticated

#### Show Epic
- **Requirements**
  - It should be able to show Epic details
- **Rules**
  - User should be authenticated

#### Update Epic
- **Requirements**
  - It should be able to update Epic
- **Rules**
  - User should be authenticated

#### Delete Epic
- **Requirements**
  - It should be able to delete Epic
- **Rules**
  - User should be authenticated

---
## Tasks
#### Create Task
- **Requirements**
  - It should be able to create new Task
  - It should be able to link Task with Epic
  - It should be able to link Task with Sprint
- **Rules**
  - Task should be linked to a Project
  - User should be authenticated

#### Show Task
- **Requirements**
  - It should be able to show Task details
- **Rules**
  - User should be authenticated

#### Update Task
- **Requirements**
  - It should be able to update Task
- **Rules**
  - User should be authenticated

#### Delete Task
- **Requirements**
  - It should be able to delete Task
- **Rules**
  - User should be authenticated

---
## Sprints
#### Create Sprint
- **Requirements**
  - It should be able to create new Sprint
- **Rules**
  - Just Admin/PO User should be able to create Sprint
  - User should be authenticated

#### Show Sprint
- **Requirements**
  - It should be able to show Sprint details
- **Rules**
  - User should be authenticated

#### Show Sprint Tasks
- **Requirements**
  - It should be able to show Sprint Tasks
- **Rules**
  - User should be authenticated

#### Update Sprint
- **Requirements**
  - It should be able to update Sprint
- **Rules**
  - User should be authenticated

#### Start Sprint
- **Requirements**
  - It should be able to start Sprint
- **Rules**
  - User should be authenticated

 #### Close Sprint
- **Requirements**
  - It should be able to close Sprint
- **Rules**
  - User should be authenticated
#### Delete Sprint
- **Requirements**
  - It should be able to delete Sprint
- **Rules**
  - User should be authenticated