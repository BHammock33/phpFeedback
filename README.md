# phpFeedback
quick php app for practice with database queries
Made utilizing XAMPP and mysqli, had to work around local mysql workbench
clogging up the default port by digging into ini files and XAMPP config.

# To run
clone the repository, go live with live server plugin and serve the project through vscode.
You will need to activate a XAMPP MYSQL connection and Apache service. If it throws errors about
Database connection you will need to see what port it is trying to access, you may need to remove
the setting of mysqli.default port in config/database or change to a different port
You may also need to go into localhost/phpmyadmin to ensure the DB exists and the credentails are correct
