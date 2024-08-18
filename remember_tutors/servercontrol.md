##### Создать судо юзера 

> useradd -m <любое имя пользователя>

> passwd <имя созданного ранее пользователя>

> usermod -aG sudo <имя созданного ранее пользователя>

> sudo chsh -s /bin/bash <имя созданного ранее пользователя>


##### Накатить докер 

> curl -fsSL https://get.docker.com -o get-docker.sh && sudo sh get-docker.sh




