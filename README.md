## Laboratory work XI

Данная лабораторная работа посвещена изучению процесса создания сеансов совместной разработки с использованием инструмента **ngrok**

curl -s https://ngrok-agent.s3.amazonaws.com/ngrok.asc |       
sudo tee /etc/apt/trusted.gpg.d/ngrok.asc >/dev/null &&       
echo "deb https://ngrok-agent.s3.amazonaws.com buster main" |       
sudo tee /etc/apt/sources.list.d/ngrok.list &&       
sudo apt update && sudo apt install ngrok - installation of ngrok w/ apt

ngrok config add-authtoken 2F7Hohkwekkvzt0ZQDiyeuZwcbG_56KGJYxTg8o6sJhLxNxQ9 - adding to ngrok token of your account

apt install nginx - installing of http server

ngrok http 80 - making ngrok redirecting to your server
