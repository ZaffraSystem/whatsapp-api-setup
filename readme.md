# INSTALAÇÃO WHATSAPP API

01. ABRA A VM LINUX DEBIAN EM SSH

02. DIGITE OS SEGUINTES COMANDOS

		A) 👉sudo su root
		
		B) 👉apt update
		
		C) 👉apt upgrade
	
		D) 👉sudo apt install -y curl nano gconf-service libasound2 libatk1.0-0 libc6 libcairo2 libcups2 libdbus-1-3 libexpat1 libfontconfig1 libgcc1 libgconf-2-4 libgdk-pixbuf2.0-0 libglib2.0-0 libgtk-3-0 libnspr4 libpango-1.0-0 libpangocairo-1.0-0 libstdc++6 libx11-6 libx11-xcb1 libxcb1 libxcomposite1 libxcursor1 libxdamage1 libxext6 libxfixes3 libxi6 libxrandr2 libxrender1 libxss1 libxtst6 ca-certificates fonts-liberation libappindicator1 libnss3 lsb-release xdg-utils wget build-essential apt-transport-https libgbm-dev
	
		E) 👉sudo apt-get install -y git
	
		F) 👉curl -fsSL https://deb.nodesource.com/setup_14.x | sudo -E bash -
	
		G) 👉sudo apt-get install -y nodejs
	
		H) 👉git clone https://github.com/ZaffraSystem/whatsapp-api-setup.git
		
		I) 👉cd whatsapp-api-setup
		
		J) 👉npm install
		
		K) 👉npm run start:dev


# INICIAR APLICAÇÃO API

01. ABRA A VM LINUX DEBIAN EM SSH

02. DIGITE OS SEGUINTES COMANDOS
	
		A) 👉sudo su root
	
		B) 👉cd whatsapp-api-setup
	
		C) 👉npm run start:dev
	
