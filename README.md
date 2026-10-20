# Open.mp Management Console (1.0.0)
Allows you to manage your Open.mp server with a text based UI

---

Edit "omc" and change the settings at the top if your Open.mp server is not in /home/openmpowner/Open.mp

You also need to have my Open.mp Startup Script installed.

I suggest you then add this to your /home/openmpowner/.bashrc file:

	export PATH=/home/openmpowner/bin:/home/openmpowner/OpenmpManagementConsole:$PATH

You will need to install the required perl modules (as root):

- /home/openmpowner/OpenmpManagementConsole/installdeps


After that you should log out and back in and now "omc" should work.
