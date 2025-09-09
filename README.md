# Messanger
download this: https://aka.ms/vs/17/release/vc_redist.x64.exe

# Composer
installer link: https://getcomposer.org/Composer-Setup.exe

# After installation
download: https://github.com/sabrina-ahmad/Cardify-2
open with vscode: Cardify-2

# Install Node js:
  ## Option 1:
        - go to https://nodejs.org/en/download/ and download nodejs-xx.msi 
  ## Option 2:
        ```bash
        # Download and install Chocolatey:
        powershell -c "irm https://community.chocolatey.org/install.ps1|iex"
        
        # Download and install Node.js:
        choco install nodejs --version="22.19.0"
        
        # Verify the Node.js version:
        node -v # Should print "v22.19.0".
        
        # Verify npm version:
        npm -v # Should print "10.9.3".
      ```

open terminal:
```bash
npm install
```
then
```bash
composer install
```
