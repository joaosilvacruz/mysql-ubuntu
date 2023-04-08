# Tutorial Instalação do MySQL Server e Workbench no UBUNTU 22.04
Tutorial para instalação do mysql server e mysql-workbench no ubuntu 22.04

Neste tutorial será utilizado o repositório de pacotes APT.

---

## Primeiro passo: Atualizar o gerenciador de pacotes APT

O primeiro passo é atualizar abrir o terminal que pode ser feito utilizando o comando Ctrl + Alt + T

Em seguida, é necessário atualizar as listas de pacotes do linux. Assim execute o comando no terminal:

```sudo apt update```

Caso possua atualizações pendentes será retornado no terminal uma lista dessas atualizações disponíveis, assim para atualizar execute o comando no terminal:

```sudo apt-get upgrade```

OBS.: Caso deseje verificar melhor quais pacotes possuem atualizações antes de atualizá-los, use o comando 

```apt list --upgradable```

---

## Passo 2: Instalar o MySQL SERVER

Com o APT atualizado, vamos iniciar a instalação do MySQL SERVER, para isso insira o seguinte comando no terminal:

```sudo apt install mysql-server```

Feito isso, parabéns você instalou o MySQL SERVER

---

## Passo 3: Verificar funcionamento do MySQL SERVER

Para que você possa verificar a sua conexão poderá utilizar os seguintes comandos:

- Saber a versão do mysql instalado:

    ```mysql --version ```

- Saber o status de conexão do servidor 

    ```service mysql status```

OBS.: Para reconhecer se está conectado, após ter digitado o comando acima verifique o parâmetro Active da mensagem no terminal se estiver 
<span style="color:green">active(running)</span> 
então o servidor está conectado, caso contrário estará desconectado.

- Iniciar a conexão do servidor MySQL

    ```sudo serice mysql start```

- Parar a conexão do servidor MySQL

    ```sudo service mysql stop ```

- Reiniciar a conexão do Servidor MySQL

    ```sudo service mysql restart ```



