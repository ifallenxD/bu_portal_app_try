
# bu_portal_app

A new Flutter project.

## Getting Started

This project is a starting point for a Flutter application.

A few resources to get you started if this is your first Flutter project:

- [Lab: Write your first Flutter app](https://flutter.dev/docs/get-started/codelab)
- [Cookbook: Useful Flutter samples](https://flutter.dev/docs/cookbook)

For help getting started with Flutter, view our
[online documentation](https://flutter.dev/docs), which offers tutorials,
samples, guidance on mobile development, and a full API reference.

## Setup
### Flutter Project
 1. Clone the repository: `git clone https://github.com/kennzmd/bu_portal_app.git`
 2. Go to the project folder: `cd bu_portal_app`
 3. Create the project: `flutter create .` **include the dot '.'*
 4. Install the app into your connected mobile with: `flutter install` or
 5. Build the apk with: `flutter build apk`
### XAMPP
#### php.ini file
1. In XAMPP Control Panel, click **Config** button of the Apache module, then **PHP (php.ini)** to open the configuration file of PHP.
2. Use `CTRL+F` then enter "dynamic extensions".
3. Scroll down and find `;extension=pdo_pgsql` and remove the semi-colon. It should be `extension=pdo_pgsql`.
4. **Save** the file then **Start** the Apache module.
#### htdocs
1. In XAMPP Control Panel, click **Explorer** to open the XAMPP installation directory.
2. Navigate to `htdocs` folder then paste the `bu_portal_api` folder that is found in the cloned repo inside the `#` folder.
### PostgreSQL (dummy data)
1. Restore the `database.sql`
