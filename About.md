# 🗂️ Project Management Platform

A full-stack Project Management Platform built with PostgreSQL, Express.js, React.js, and Node.js (PERN Stack) that helps organizations manage their projects, tasks, and team members efficiently.

# 🚀 Overview

This platform allows users to create and manage multiple organizations, handle projects within each organization, assign tasks, and collaborate with team members in real time. The application is designed to streamline organizational workflow, enhance productivity, and maintain smooth communication across teams.

# 🧩 Features

* 👥 Organization Management

 - Create and manage multiple organizations.

 - Invite and manage team members via email.

 - Assign different roles and permissions to members.

* 📁 Project Management

 - Create, update, and delete projects under an organization.

 - Add detailed project descriptions, timelines, and status updates.

* ✅ Task Management

 - Create and assign tasks to team members.

 - Track task progress, set due dates, and add task notes.

 - Get email notifications when a new task is assigned.

 - Automatic reminder emails on task due dates.

* 🔐 Authentication & Access Control

 - Integrated Clerk for secure user authentication and organization management.

 - Role-based access to protect sensitive organizational data.

* 📬 Email Notifications & Background Jobs

 - Managed using Inngest for background processing.

 - Handles:

   - Automated email notifications

   - Task reminder emails

   - Clerk webhooks management

* 🗄️ Database

 - Neon PostgreSQL is used as the primary database.

 - Stores user, organization, team member, project, and task information efficiently.