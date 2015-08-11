In order to quickly and easily install the PMDCP server (and client!) code, you can use <a href="https://github.com/pmdcp/RaileyBuilder">this installer</a>, as long as you have both Git and MySQL installed. MySQL through xampp may or may not work, but the Windows installer for MySQL has been tested and works.<br>
Step 1: Download the installer from the link above.<br>
Step 2: Run it, select an install path, and click Install Server. Update Server can be used to apply commits that were created after installation, and is not needed immediately.<br>
Step 3: Input the creds for any MySQL account that has root access (root account is preferable for this, but realistically anything will work).<br>
Step 4: To bundle the client code for distribution to players, click Install Client. Otherwise, just git clone it and distribute its Release compile as created in Visual Studio.
