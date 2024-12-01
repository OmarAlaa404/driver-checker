
# Driver License Checker

A simple Bash script to check driver's license eligibility based on age and vision rate. It also maintains a log of results for future reference.

---

## Features

- Check eligibility based on age and vision rate.
- Retrieve eligibility status for specific users.
- List all logged eligibility results.

---

## Installation

1. Clone the repository:
   ```bash
   git clone https://github.com/OmarAlaa404/driver-checker.git
2. Move the script to /bin:
      ```bash
      sudo cp driver-checker /bin/
3. Make the script executable:
      ```bash
      sudo chmod +x /bin/driver-checker
4. Create and configure the log file:
      ```bash
      sudo touch /var/log/driver_checker.log
      sudo chmod 666 /var/log/driver_checker.log
