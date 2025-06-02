# adds Kali Linux GPG key to your system so APT can verify the authenticity of Kali packages.

sudo apt-key adv --keyserver keyserver.ubuntu.com --recv-keys 827C8569F2518CC677FECA1AED65462EC8D5E4C5

curl -fsSL https://archive.kali.org/archive-key.asc | sudo gpg --dearmor -o /etc/apt/trusted.gpg.d/kali.gpg
