
# install python 3.11
```sh
brew install python3.11
```

# Clone Repository
```sh
# Move into a directory to store the project
cd ~/Developer
# Clone project
git clone https://github.com/aryajuanda/OpenCore-Legacy-Patcher
# Move into Project directory
cd ./OpenCore-Legacy-Patcher
# Install Python dependencies used by the project
pip3.11 install -r requirements.txt
```

# download or generate own dmg from https://github.com/aryajuanda/PatcherSupportPkg/releases/ Universal-Binaries.dmg and put in the OCLP dir

# build privilage helper 
```sh
cd ci_tooling/privileged_helper_tool
make debug
sudo ./install.sh
```

# back to OCLP dir
```sh
cd ../..
```

# Launch GUI
```sh
python3.11 OpenCore-Patcher-GUI.command
```