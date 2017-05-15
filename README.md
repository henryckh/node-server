# Node Server Example
An Express, Node, Mongoose production server structure suggestion.
> Based on reviewing of numerous large scale GitHub repositories framework
  with balance of complexity.  
> Planned to integrate with angular 4.0, webpack, ES6, gulp

## Project Structure

### Server Level
* config - Application configurations, domain, header, IP, HTTP, or docker
* database - Databases for storage, sessions
* deploy - Process for application deployment
* log - System access logs
* scripts - Grunt, gulp, or other tools
* tests - Test individual modules, setup, or api
* worker - Scheduled task like scraping or push notification
* www - API and website exposing

### API Level /WWW
* app - Sever, model, views, controllers
* assets - Public images, text, html, styles
* helpers - Library and utilities helpers
* locales - Support for multiples languages
* routes - Website and API routes
* api.js - Api server 
* web.js - Web server