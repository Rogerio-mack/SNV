# Lab EC2 `nginx`

Neste laboratório você vai criar um webserver `nginx` criando uma página com um conteúdo de seu interesse.

Siga os seguintes passos:

1. Crie uma instância **EC2 Linux 2** com uma chave privada `.ppk`. Você vai criar um webserver, não deixe, portanto, de liberar o tráfego `http` e `https`.
2. Você fará o acesso via outra máquina Linux (ou PowerShell) via linha comando. Para isso você irá precisar de uma chave privada no formato openSSH. 
Empregue o programa `puttygen` para converter o formato da sua chave `.ppk`.
3. Acesse uma máquina Linux, PowerShell do Windows ou Cloud Shell da AWS* e conecte-se à sua instância EC2.
> Para Cloud Shell da AWS, faça o upload da chave no Cloud Shell e altere a permissão do arquivo `chmod 400 suachave.ppk`
5. Instale o `nginx`

```
sudo yum update -y
sudo amazon-linux-extras install nginx1 -y
sudo amazon-linux-extras enable nginx1
sudo systemctl start nginx
```

5. Empregue o comando `curl` e acesso via browser para verificar o conteúdo da página inicial do seu webserver 
6. Pesquise e altere a página padrão do `nginx`
