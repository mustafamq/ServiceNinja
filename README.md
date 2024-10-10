# Service Ninja Script

## Overview
This PowerShell script manages Windows services, enhancing system security and performance. It stops and disables unnecessary services, performs health checks, and ensures critical services are running.

## Features
- Stops and disables insecure and non-essential services.
- Performs system health checks and logs results.
- Automatically restarts critical services if needed.
- Detects and logs missing services.
- Supports log rotation to prevent excessive file size.

## Usage
1. Download or clone this repository.
2. Open PowerShell as an Administrator.
3. Navigate to the script location.
4. Run the script:
   ```powershell
   .\ServiceNinja.ps1
