# Issue Tracker Backend

The backend portion of this fullstack issue tracker portfolio piece made with Express and a MongoDB using Mongoose.

## Database Plans

-   Database will be MongoDB, edited via a purpose built REST API
-   Users will be able to own multiple projects
-   Projects will be able to own multiple issues
-   Users will have a single account preferences object containing all account preferences
-   Projects will have a single project preferences object containing all project preferences
-   Projects will manage their own board views
-   Board Views will manage their issues with defined and custom fields

### Example API Routes

-   "/" : All users
-   "/:user" : Single specified user
-   "/:user/:project" : Specified project of specified user
-   "/:user/:project/:issue" : Specified issue of specified project of specified user
