
# VPN Control Script

[](https://github.com/luisleonardo/OpenVPN-Control-Script#vpn-control-script)

This is a simple Python script that allows you to easily interact with your VPN connection.

## Introduction

[](https://github.com/luisleonardo/OpenVPN-Control-Script#introduction)

Have you ever found yourself unsure if your VPN is running or struggling to locate the .ovpn file to start the connection? If so, this script is for you! With just a few simple commands, you can start and stop your VPN connection from anywhere in your system without hassle.

## Features

[](https://github.com/luisleonardo/OpenVPN-Control-Script#features)

-   Start and stop your VPN connection with ease.
-   No need to remember the location of your .ovpn file.
-   If placed in a directory included in the system's PATH, such as  `/usr/local/bin`, it can be executed from anywhere.

## Installation

[](https://github.com/luisleonardo/OpenVPN-Control-Script#installation)

1. **Download the Script to the System's Command Directory:**
	 - Open a terminal and execute the following command to download the `ovpn` file directly from your Git repository to `/usr/local/bin`: 
   
       `sudo wget -O /usr/local/bin/ovpn https://raw.githubusercontent.com/luisleonardo/OpenVPN-Control-Script/main/ovpn`
2. **Grant Execution Permissions (if necessary)**:
	 - If the script doesn't have execution permissions, you can grant them with the command: 
   
       `sudo chmod +x /usr/local/bin/ovpn`

3. **Verify Successful Installation**:
	 - To verify that the installation was successful, you can try executing the script from any directory using the command:: 
   
       `ovpn --help`

## Usage

[](https://github.com/luisleonardo/OpenVPN-Control-Script#usage)

1.  **Starting the VPN**:
    
    `ovpn start`
    
2.  **Stopping the VPN**:
    
    `ovpn stop`
    
3.  **Restarting the VPN**:
    
    `ovpn restart`
    
4.  **Checking VPN Status**:
    
    `ovpn status`
    
5.  **Help**:
    
    `ovpn --help`
    

## License

[](https://github.com/luisleonardo/OpenVPN-Control-Script#license)

This project is licensed under the Attribution 4.0 International (CC BY 4.0). You are free to use and modify the script as you see fit, as long as you provide attribution to the original author.
