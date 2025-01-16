Script Documentation:

1. Usage:
   - Run the script with the -s option followed by a quoted list of server addresses or hostnames.
     Example: ./update_servers.sh -s 

2. Features:
   - Connects to specified remote servers via SSH.
   - Performs system updates and installs Apache2 and Nginx.
   - Restarts both web services to ensure proper configuration.

3. Error Handling:
   - Validates input parameters.
   - Logs success or failure for each server.

4. Requirements:
   - Ensure SSH access is configured for the specified servers.
   - The script requires sudo privileges on the remote servers.

5. Testing:
   - Test the script on virtual machines or test servers before using it in production.

