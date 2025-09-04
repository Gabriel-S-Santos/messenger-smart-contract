# 📩 Messenger Smart Contract

Um contrato inteligente simples em **Solidity** para armazenar e atualizar mensagens na blockchain.  
O contrato permite que apenas o dono (owner) modifique a mensagem, e cada alteração é registrada em um contador.  

---

## 🚀 Objetivo do Projeto
Este projeto foi criado como parte do meu aprendizado em Solidity, explorando conceitos fundamentais de contratos inteligentes, como:
- Declaração de variáveis públicas (`uint`, `address`, `string`)
- Uso do **constructor** para definir o dono do contrato
- Controle de acesso com `msg.sender`
- Persistência e atualização de dados on-chain
- Criação de um contador para rastrear mudanças

## ⚙️ Como Executar:

Abra o projeto no Remix IDE
Crie um novo arquivo chamado Messenger.sol e copie o código acima
Compile o contrato usando a versão 0.8.x
Faça o deploy utilizando o ambiente JavaScript VM
Teste as funções:
  sendMessenge("sua mensagem") → atualiza a mensagem
  message → retorna a mensagem atual
  changeCounter → mostra quantas vezes foi alterada
  owner → retorna o endereço do dono do contrato

