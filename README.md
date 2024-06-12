# Raily Clone - Landing Page

## Overview

This project is a recreation of the Raily.app landing page using the PHP/Laravel framework. The design is matched as closely as possible up to page 5 (smartwatch as social circle).

## Setup Instructions

### Prerequisites

1. **PHP**: Ensure PHP is installed and added to your system's PATH.
2. **Composer**: Install Composer for dependency management.
3. **Node.js and npm**: Required for running frontend assets.

### Step-by-Step Setup

1. **Enable `zip` Extension in PHP**:
   - Open your `php.ini` file, located at `C:\xampp\php\php.ini`.
   - Find the line that says:
     ```ini
     ;extension=zip
     ```
   - Remove the semicolon (;) at the beginning to uncomment it:
     ```ini
     extension=zip
     ```
   - Save the `php.ini` file and restart your command prompt.

2. **Install 7-Zip**:
   - Download and install [7-Zip](https://www.7-zip.org/).
   - Ensure the path to `7z.exe` is added to your system's PATH environment variable:
     - Open System Properties (Right-click on My Computer/This PC > Properties > Advanced system settings).
     - Click on the `Environment Variables` button.
     - Under `System variables`, find the `Path` variable, select it, and click `Edit`.
     - Click `New` and add the path to `7z.exe` (e.g., `C:\Program Files\7-Zip`).

3. **Generate GitHub Token**:
   - Go to [GitHub's token generation page](https://github.com/settings/tokens/new?scopes=&description=Composer).
   - Click on "Generate token".
   - Copy the generated token.

4. **Create Laravel Project**:
   - Open Command Prompt and run:
     ```sh
     composer create-project --prefer-dist laravel/laravel raily_clone
     ```
   - Enter the generated GitHub token when prompted.

5. **Navigate to the Project Directory**:
   ```sh
   cd C:\Users\DELL\Documents\Projects\InterviewProjects\Tripcel\raily_clone
