markdown
 Copy
# Light Yagami

![Banner](https://telegra.ph/file/24a9dcdbf99b94c26dc66.jpg)

A Death Note themed bot that can guard the group 24/7 with additional fun and useful features.

## Deployment

To deploy the bot locally or on a VPS, follow these steps:

1. Install tmux to keep your bot running when you close the terminal:
 
 
sudo apt install tmux && tmux
 

 Copy

2. Upgrade and update your system:
 
 
sudo apt-get update && sudo apt-get upgrade -y
 

 Copy

3. Install FFmpeg:
 
 
sudo apt-get install python3-pip ffmpeg -y
 

 Copy

4. Install required packages:
 
 
sudo apt install python3-pip
 

 Copy

5. Clone the repository:
 
 
git clone https://github.com/SeiryuXD/Light-Yagami
 

 Copy

6. Enter the repository:
 
 
cd Light-Yagami
 

 Copy

7. Install requirements:
 
 
pip3 install -U -r requirements.txt
pip3 install --upgrade pip setuptools
pip install -U "pip < 22" setuptools wheel && pip install -U -r requirements.txt
pip install pyopenssl
sudo pip install -U pyopenssl
 

 Copy

8. Copy the sample environment file:
 
 
cp sample.env .env
 

 Copy

9. Edit the .env file:
 
 
vi .env
 

 Copy
Press "i" to start editing, make your changes, then press Ctrl + C, type ":wq" to save or ":qa" to exit editing.

10. Finally, run the bot:
 ```
 python3 -m Light-Yagami
 ```

For updating your bot with the latest commit, use:
 
 
git pull
 

 Copy

Make sure to follow these steps carefully to deploy the Light Yagami bot successfully. Enjoy using the bot!
 
