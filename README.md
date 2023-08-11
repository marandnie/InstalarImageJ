# InstalarImageJ
Cómo instalar ImageJ en una chromebook



    sudo cp /etc/apt/sources.list sources.list

    sudo echo deb https://deb.debian.org/debian stretch main  | sudo tee -a /etc/apt/sources.list

    sudo apt update

    sudo apt install openjdk-8-jdk imagej

    sudo mv sources.list /etc/apt/sources.list

    sudo apt update
