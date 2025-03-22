# Module 3: Remote Connection and SSH

## Overview
- **Remote connection** simplifies IT support by allowing access to multiple machines from anywhere in the world.
- **Scenario 1**: Forgetting a presentation on a desktop but accessing it remotely via a remote connection.
- **Scenario 2**: Getting tech support through remote connection instead of waiting for a physical store to open.

## Remote Connection
- **SSH (Secure Shell)**: A protocol for securely accessing one computer from another.
- **Components Needed**:
  - SSH **client**: Installed on the machine initiating the connection.
  - SSH **server**: Software running in the background on the remote machine that accepts and authenticates connection requests.

## Popular SSH Programs:
- **Linux**: OpenSSH is commonly used.
- **Windows**: PuTTY is a widely used open-source program.

## How SSH Works:
1. **Login to Remote Machine**: Requires:
   - An account on the target computer.
   - Host name or IP address of the remote computer.
2. **First Connection**: A message may appear saying the authenticity of the host can't be established (since you’ve never connected to that machine before). After verifying, you type "yes" to proceed.
3. **Known Hosts**: Once verified, the remote machine gets saved as a "known host" for future connections.
4. **Secure Commands**: After logging in, all text commands are securely sent to the SSH server.

## Advanced SSH Features:
- **GUI Applications**: SSH allows launching graphical applications from the command line (learn more in supplemental reading).

## Authentication Methods:
1. **Passwords**: Standard, but not the most secure.
2. **SSH Keys**: More secure.
   - **Private and Public Key Pair**: Like physical keys to a safe:
     - The public key locks (encrypts) the safe.
     - The private key unlocks (decrypts) it.

## VPN (Virtual Private Network)
- **VPN**: A more advanced remote connection method compared to SSH.
  - Allows connection to a private network (e.g., work network) over the internet.
  - Provides access to resources like shared file servers as if you were connected locally.
  

**Next Steps**:
- Learn more about SSH setup and remote connection tools for both Windows and Linux in the system administration course.
- Further details on **SSH keys** and **VPN** will be covered in the IT Security course.
