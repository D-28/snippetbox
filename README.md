## Snippetbox App

### Project Structure

- cmd
  - contains application-specific code for the executable applications
  - i.e., the executable web app in cmd/web
- internal
  - ancillary non-application-specific code used in the project
  - holds potentially reusable code like validation helpers and the SQL db models
- ui
  - contains user-interface assets used by the web app
  - i.e., the ui/html dir contains HTML templates, ui/static contains CSS/images
