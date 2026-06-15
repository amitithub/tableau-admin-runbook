**Installation**

**Linux**: Run the initialization script after installing the .rpm/.deb package.
sudo ./initialize-tsm --accepteula --activation-service --<optional_parameters>

**Install and Initialize TSM**
https://help.tableau.com/current/server-linux/en-us/setup.htm#install-tableau-server

**Windows: Run the executable installer silently.**

TableauServer-64bit-<version>.exe /silent ACCEPTEULA=1 ACTIVATIONSERVICE="1"

**Install and Initialize TSM**
https://help.tableau.com/current/server/en-us/setup.htm#install-tableau-server

**Upgrade**

**Linux:** Navigate to the scripts folder of the new version and run the upgrade script.

sudo /opt/tableau/tableau_server/packages/scripts.<version_code>/upgrade-tsm --accepteula

Upgrading from 2018.1 and Later (Linux)
https://help.tableau.com/current/server-linux/en-us/sug_plan.htm

**Windows:** Open a command prompt as administrator, navigate to the new scripts folder, and execute the script.

upgrade-tsm

Upgrading from 2018.2 and Later (Windows)
https://help.tableau.com/current/server/en-us/sug_plan.htm
