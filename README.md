Install basic resources to develop using node on ubuntu.

```bash
sudo apt update && sudo apt upgrade &&
echo -e '\n\n'

echo -e 'Installing Curl\n\n' &&
sudo apt install curl -y &&
echo -e '\n\n'

echo -e 'Installing NodeJS 12.x\n\n' &&
curl -sL https://deb.nodesource.com/setup_12.x -o nodesource_setup.sh &&
sudo bash ./nodesource_setup.sh &&
sudo apt install nodejs -y &&
echo -e '\n\n' &&

echo -e 'Installing VS Code\n\n' &&
sudo snap install --classic code &&
echo -e '\n\n'

echo -e 'Installing Git\n\n' &&
sudo apt install git -y &&
echo -e '\n\n'

echo -e 'Installing Fira Code Font\n\n' &&
sudo apt install fonts-firacode -y &&

echo -e 'Finished... Lets code'
``
