# how_to_install_matlab_ubuntu

## Download installtion file

The downloaded file should have a name as `matlab_Rxxxx_glnxa64.zip`, let's call it `matlab_xx.zip`

## Install

Unzip the installaiton file using following command:

```bash
sudo unzip -X -K matlab_xx.zip -d matlab_<version>_installer
```

Then go to `matlab_<version>_installer` folder an install MATLAB using following command:

```bash
xhost +SI:localuser:root
sudo ./install
```

Select your desired packages and make sure to select the “Create symbolic links to MATLAB scripts in” option during the
installation process

## Run

Open a terminal and run following command:

```bash
matlab
```