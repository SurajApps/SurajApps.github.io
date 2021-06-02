# Welcome to SurajApps

This is the official site of all SurajApps products. Links to the complete range of products can be found here.

## Products

- [WhatsApp Web for Tablet](https://github.com/SurajApps/WhatsApp-WebTab)
- [SysExpose](https://github.com/SurajApps/SysExpose/)

This website contains the installation instructions and links for all products.

### WhatsApp Web for Tablet: Installation Instructions

1. Download the latest release from [here](https://github.com/SurajApps/WhatsApp-WebTab/releases/).
2. Click on the downloaded ```*.apk``` file.
3. Click allow wherever it mentions install apps from unknown sources.
4. The app should be installed on the device.

### SysExpose: Installation Instructions

#### Easy Mode:
1. You can easily get setup by using the latest production version in the releases page, [here](https://github.com/SurajApps/SysExpose/releases).
2. Run the following command, where $FILE is the latest wheel from the releases page:
    ```
    pip install $FILE
    ```
3. Create a python file which will contain the following.
    ```
    from SysExpose import Expose
    Expose()
    ```
4. Run the python file you created with -h as the argument. This will display the help dialog.
5. Use the commands in the help dialog to use the functions provided.

#### Run from Source

1. If you choose not to use the packaged wheel from the releases page, then you can choose to run the py file alone.
2. Clone the repository, using git:
    ```
    git clone https://github.com/SurajApps/SysExpose
    ```
3. Run the SysExpose.py file and use steps 4-5 from the easy installation above to continue.
