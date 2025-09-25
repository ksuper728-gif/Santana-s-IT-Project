# Minecraft Java Edition Server Setup

## Project Summary
This project is a step by step walkthrough for setting up and running a Minecraft Java Edition server on a personal computer in 2025. The purpose of the project is to demonstrate practical IT skills such as configuring software, editing configuration files, and working with networking concepts like port forwarding.  

Languages Used: 
- Java 
- Command Prompt (Windows Command Prompt)

Environments Used:  
- Windows 11  

Technology/Applications/Services Used:  
- Java Runtime Environment (latest version)  
- Minecraft Java Edition Server software (.jar file from official Minecraft site)  
- Localhost environment  
- Router configuration for port forwarding (port 25565) (had to use DECO App) 


 Demonstration

 1. Download the Server Software
- Download the latest Minecraft Java Edition server `.jar` file from the official Minecraft website.  
- Ensure the latest version of Java is installed.  

 2. Create a Server Folder
- Make a new folder (e.g., `Minecraft Server`).  
- Place the `.jar` file into this folder.  

 3. Run the Server (First Launch)
- Open a command prompt/terminal.  
- Navigate into the server folder using the `cd` command. Example:  
  ```bash
  cd path\to\Minecraft Server
  ```
- Start the server with:  
  ```bash
  java -Xmx1024M -Xms1024M -jar server.jar nogui
  ```
- On first launch, files will generate, and an error about the **EULA** will appear.  

 4. Agree to the EULA
- Open the newly created `eula.txt` file.  
- Change:  
  ```
  eula=false
  ```
  to:  
  ```
  eula=true
  ```
- Save the file.  

 5. Set Up Port Forwarding
- Log into your router and forward **port 25565** to your computer’s internal IP.  
- Each router has unique steps—refer to your router’s manual.  

 6. Have Friends Join
- Bsmity (Friend from Michigan) joined (I'm in North Carolina) 


Conclusion:
By following this tutorial, I successfully created a fully functional Minecraft server in 2025. This project demonstrates technical competency with Java applications, command line tools, configuration management, and networking fundamentals.

