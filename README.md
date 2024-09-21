# PostgreSQL Guide

## #Install PostgreSQL

### Step 1: Download PostgreSQL Installer
1. Visit the official PostgreSQL download page: [https://www.postgresql.org/download/windows/](https://www.postgresql.org/download/windows/)
2. Click on **"Download the installer"**, which will direct you to the EnterpriseDB website.
3. Choose the appropriate installer for your operating system (Windows) and download the latest version.

### Step 2: Run the Installer
1. Once the download is complete, navigate to the folder where the installer is saved.
2. Double-click the `.exe` file to launch the PostgreSQL Setup Wizard.
3. Click **Next** to start the installation process.

---

## #Configuring PostgreSQL

### Step 1: Select Installation Directory
1. Choose the directory where PostgreSQL will be installed.
   - Default directory: `C:\Program Files\PostgreSQL\<version>`
2. Click **Next**.

### Step 2: Select Components to Install
1. Make sure to select only the **PostgreSQL Server**.
   - You can deselect **pgAdmin 4** and **Stack Builder** since they won't be needed.
2. Click **Next**.

### Step 3: Choose Data Directory
1. Select the folder where PostgreSQL will store its database data.
   - Default directory: `C:\Program Files\PostgreSQL\<version>\data`
2. Click **Next**.

### Step 4: Set PostgreSQL Superuser Password
1. Create a password for the PostgreSQL `postgres` superuser account.
2. Ensure you remember this password, as you will need it to log into PostgreSQL.
3. Click **Next**.

### Step 5: Specify the Port Number
1. PostgreSQL listens on a specific port. By default, this is `5432`.
2. If `5432` is in use, select another port, or leave the default.
3. Click **Next**.

### Step 6: Choose Locale Settings
1. Select the locale to set language, formatting, and currency standards for PostgreSQL.
   - Default is typically fine for most users.
2. Click **Next**.

### Step 7: Start the Installation
1. Review the setup options you’ve chosen.
2. Click **Next** to begin installing PostgreSQL. This may take a few minutes.

### Step 8: Complete Installation
1. After installation finishes, the Setup Wizard will notify you.
2. Click **Finish**.

---