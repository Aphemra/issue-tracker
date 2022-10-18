# Fullstack Issue Tracker App

This repository stores the code for both the frontend and backend of this Issue Tracker portfolio piece.

The frontend is made in React.js and the backend is made in Express with a MongoDB database powered by Mongoose.

## Brief Project Description

This project will be a large portfolio piece looking to implement multiple features in a full stack workflow. Detailed feature list below, but a quick overview would be full authentication and account management using traditional username and password as well as authentication using Google, Github, and possibly other services.

It will also include a project-based database structure where all issues belong to a single project. Projects will be issue boards which includes the kanban workflow seen in services like Trello. I also want to include a lite form of sub-issues which will allow you to reference information from other issues within the definition of another issue. For example, you can create a checklist that references the completion state of other issues so that marking an issue complete (or the checkmark associated with the issue) will alter the state of the checkmark/issue respectively, making it easier to add or break down more complex issues into management pieces.

Another board view I will likely add is the Table View, also seen in services like Airtable or Notion. This view makes it easy to see all data at a glance and is useful for collating data into more convenient forms (like graphs)... Though the collation of data won't be a part of this app.

The last large feature I would like to add is a simple way to automate actions (similar to Trello). As an example, a custom action button that creates a new bug report would create a new issue and add the 'bug' tag to it.

## Planned Features

-   Full authentication and account management, including OAuth w/ Google and GitHub
-   Kanban board drag-and-drop support for issues
-   Project-based organization of issues, many issues under a project
-   Custom tags and fields for issues
-   Possibly other views besides Kanban (like table view)
-   Custom fields for issues/board views
-   Ability to add new board views to an existing project and issues auto-populate
