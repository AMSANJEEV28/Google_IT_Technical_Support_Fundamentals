### Notes for Module 3: Remote Connections on Windows

1. **PuTTY Overview**: 
   - **PuTTY** is a free, open-source software for making remote connections through multiple network protocols like **SSH**. 
   - You can download PuTTY from the official website in a **Microsoft installer (MSI)** format or as an executable file (**PuTTY.EXE**).
   - The PuTTY GUI allows you to input the **hostname** or **IP address** of the remote computer, and the default port for SSH is **22**.

2. **Starting an SSH Session**:
   - In PuTTY, once the connection details are filled (hostname/IP), click **Open** to start the SSH session.
   - You can also use PuTTY from the command line (e.g., PowerShell) by typing:
     ```bash
     putty.exe -ssh user@IPaddress -P 22
     ```

3. **Using Plink (PuTTY Link)**:
   - **Plink** is a command-line tool included with PuTTY that also supports remote SSH connections. 

4. **Remote Desktop Protocol (RDP)**:
   - **RDP** is another method to connect to Windows computers remotely, providing a **graphical user interface (GUI)**.
   - To enable RDP on your computer:
     - Right-click on **This PC**, select **Properties**, then **Remote settings**.
     - Enable RDP connections under the **Remote Desktop** section.
   - The **mstsc.exe** client is used to initiate RDP connections. You can launch it via the Start Menu or command line:
     ```bash
     mstsc /admin
     ```

5. **Security Considerations**:
   - Only trusted users should be allowed to connect remotely to your computer as remote connections pose **security risks**.
   - In organizational settings, system administrators typically configure remote connection settings.

6. **RDP Documentation**: More details about RDP usage can be found in the linked supplementary reading for additional features like setting up RDP clients on **Linux** or **Mac** systems (e.g., **RealVNC** and **Microsoft RDP** for Mac).

These are the key points for **Remote Connections on Windows**, focusing on using PuTTY and RDP.