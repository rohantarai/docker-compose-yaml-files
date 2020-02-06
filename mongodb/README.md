# Docker-MongoDB
Docker based MongoDB with web-based Client interface

## Setup
1. Make sure **Docker** is running in your system.

2. Clone the repository and change directory by executing command **`cd Docker-MongoDB/<mongo or mongo-replicaset>`**

3. For **Mac/Linux** users, skip **`Step 4 and 5`**

4. For Windows users, Open PowerShell by pressing **`Left-Shift Key + Right-Mouse-Click`** inside repo directory and select **`Open PowerShell window here`**

5. If no PowerShell then Open CMD and change directory to Docker-MongoDB by executing command **`cd "C:\Users\<Account-name>\Desktop\Docker-MongoDB"`** (assuming that you have cloned the repository to Desktop)

6. Execute the command **`docker-compose -f <filename.yml> up`**

7. Next time when you want to start the containers, execute the command **`docker-compose -f <filename.yml> start`**, and never run the **up** command twice or else it will reset your containers.

8. Wait for the setup to complete.

9. If you see any success message then the setup is completed else wait few more minutes.

10. You can also share your MongoDB server in your LAN network by sharing `<your-IPv4-address>:27017`

**NOTE:** for more information, open the .yml files in an editor and check the instructions.
