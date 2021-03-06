### Minecraft AI Poject:  Sirius-3                                      https://jiacheh4.github.io/Sirius-3/index.html ### 
![Image](docs/image/img.jpg)

### Overview ###
The main idea of the project is to kill random spawning zombies in order to minimize the loss of villagers. By performing enforcement learning on the agent, the agent is able to learn/identify the nearest threat to a villager and eliminate the threat as quick as possible. The goal of the project is to let the agent protects as many villagers as possible by performing actions such as moving to and attacking zombies.

Input information: The map, where the agent and zombies can walk around. The objects on the map and their positions, such as agent, villagers and zombies. The algorithm will guide the agent to perform desired tasks, for example attacking, moving, etc.

Output information: Time survived so far, zombies killed so far, and score received so far. Three possible outcome: 1. Agent was killed by zombies 2. All villagers were killed by zombies 3. Both agent and villagers survived in limited time frame (ex. 2 mins)

### Prerequisites ###
Note: Please install Malmo to run this program. 

      pip3 install malmo 

In order to run this program there are some environment and OS dependency requirements that have to be met:

1. Java 8 must be installed and the JAVA_HOME environment variable set up for Java8.

2. git should be installed and on your shell search path.

3. MALMO_XSD_PATH must be set to where the XSD schema files are located.

4. There are a few OS specific dependencies that must be pre-installed.

For more details on how to install go to [Malmo](https://github.com/jiacheh4/malmo)


### Getting Started ###

Pip install for Malmo. Once installed, the malmo Python module can be used to download source and examples and start up Minecraft with the Malmo game mod.

NOTE: If you encounter this error "ImportError: No module named MalmoPython" try put the file below in your project directory.
      
      MalmoPython.iso 
     
Download this project and save it in this path Malmo/Sirius-3

### Running the Program ###

Once Malmo is installed on your machine, go the Malmo/Minecraft/launchClient.sh or Malmo/Minecraft/launchClient.bat to lunch the actual Minecraft game

      cd Minecraft
      
      launchClient (On Windows)
      
      ./launchClient.sh (On Linux or MacOSX)
      
Once the game finish loading, open up another terminal and type 
      
      cd Malmo/Sirius-3
      
      python3 main.py

