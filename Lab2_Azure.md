# Lab 2: Putty/PuttyGen, acesse via Windows sua VM Linux na Azure

Você vai conectar uma máquina virtual Linux na Azure a partir da sua máquina Windows local.

## 1. Acesse `www.portal.azure.com`

Empregue seu e-mail *mackenzista.br*.

## 2. Check os seus créditos 

```
> Página inicial > Gerenciamento de custo + cobrança | Visão geral 
```

acesse sua inscrição (Azure for Students) e acesse o link,

```
Para verificar o crédito restante, ...
```

*Se estiver sem o acesso faça com um colega e verifique depois com o help-desk o seu acesso ao portal-azure.* 

## 3. Download `Putty` e `PuttyGen`

Acesse https://www.chiark.greenend.org.uk/~sgtatham/putty/latest.html 

## 4. Converta a sua chave `.pem` para `.pk`

- Empregue o programa `PuttyGen`
- Faça load da chave `.pem`
- Salve a chave `.ppk` correspondente

## 5. Conecte-se a sua VM Linux

- Empregue o programa `Putty`
- Forneça o IP ou hostname público
- Em `SSH > Auth > Private key file for authentication` forneça sua chave `.ppk`
- Execute, `Open`

 


