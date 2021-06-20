# Home Control Discord Bot
This Discord bot can control your home!

Prerequisite
--

Services needed:
- [IFTTT](https://ifttt.com)
- [Discord](https://discord.com)

Applications needed (for Windows anyway):
- [PyCharm (Community Edition works fine)](https://www.jetbrains.com/pycharm/download/#section=windows)
- [Anaconda (Individual Edition works fine)](https://www.anaconda.com/products/individual)

Make sure you install PyCharm and Anaconda and have the accounts for Discord and IFTTT.

Set Up the Environment
--

Open up PyCharm and let everything load. Then, click on new project. At the top, you'll see a file path. You can change the end of it to whatever you want the project to be named.

![Image showing file path](https://raw.githubusercontent.com/offsec64/Home-Control-Discord-Bot/main/images/1ProjectName.PNG)

Then, click on 'New Environment Using' and choose conda from the drop down.

![Image of the environment selection with Conda chosen](https://raw.githubusercontent.com/offsec64/Home-Control-Discord-Bot/main/images/2Environment.PNG)

Press 'Create' and let everything load.

Install the Packages
--

Open up the 'Anaconda Prompt' app.

To select/activate the environment, type `activate <ENVIRONMENT NAME>`. Remember, the environment is what you chose in the file path when creating the environment.

Now, install the Discord package by typing `pip install discord`. After that finishes, you might want to install another package called requests which will be used later: `pip install requests`.

Start the Code
--


