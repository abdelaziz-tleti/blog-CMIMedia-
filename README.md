# blog-CMIMedia


##  Environment Setup

This project is made with Symfony 6.1.

###  Needed tools

1. PHP 8.2 or higher;
2. Composer
3. Docker and docker-compose
4. and the [usual Symfony application requirements][2].
6. Clone this project: `git clone hhttps://github.com/abdelaziz-tleti/blog-CMIMedia-.git`
7. Move to the project folder: `cd blog-CMIMedia-`

### 🛠 Environment configuration

1. Create a local environment file (`cp .env .env.local`) if you want to modify any parameter

### Application execution

1. Install the backend dependencies: `composer install`.
2. Start data base and adminer containers : `docker-compose up` (http://localhost:8080/ ) 
3. Create database & tables with `php bin/console d:d:c` then `php bin/console make:migration`
   and `php bin/console migration:migrate` or force with `php bin/console d:s:u -f`
7. Start the server with Symfony: `symfony server:start`.
   Then access the application in your browser at the given URL (http://localhost:8000/micro-post).


![image](https://user-images.githubusercontent.com/3765550/215513046-5484295a-c158-4735-b7c6-ff9709c23039.png)
![image](https://user-images.githubusercontent.com/3765550/215513144-24f75fb3-53f6-4f92-8692-6791923b5447.png)
![image](https://user-images.githubusercontent.com/3765550/215513787-06e2ea47-bb9d-4414-abde-d4e5146d3a76.png)
![image](https://user-images.githubusercontent.com/3765550/215513230-a6d7588a-662b-40ca-bb71-c326d5270fab.png)
![image](https://user-images.githubusercontent.com/3765550/215513307-5cee170a-c857-4f65-a029-0b5311246045.png)
![image](https://user-images.githubusercontent.com/3765550/215513382-19129f44-6fb9-4c09-8f7e-c0f50ed999ea.png)
