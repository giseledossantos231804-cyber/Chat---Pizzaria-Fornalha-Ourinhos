🍕 Chatbot para Pizzaria - Fornalha de Ourinhos

Este projeto é um chatbot interativo para pedidos de pizzas e bebidas, desenvolvido em HTML, CSS e JavaScript puro, com integração direta ao WhatsApp para envio automático dos pedidos.

🚀 Funcionalidades
💬 Interface de chat moderna e responsiva
🍕 Seleção de pizzas por:
Tamanho (Broto, Média, Grande), Quantidade de sabores e Ingredientes detalhados
🧀 Adição de bordas recheadas (doces e salgadas)
🥤 Inclusão de bebidas
🛒 Carrinho de compras com resumo do pedido
🎯 Promoções automáticas (dias da semana)
📝 Personalização de pedidos (ex: “sem cebola”)
📦 Escolhas entre: Entrega (com coleta de endereço) e Retirada no local
📱 Envio automático do pedido para o WhatsApp
📱 Integração com WhatsApp

O pedido é enviado automaticamente para o número configurado no código:

const ZAP_NUMBER = "5514996213939";

O chatbot gera uma mensagem formatada e abre o WhatsApp com o pedido pronto para envio.

🧠 Como funciona

O sistema utiliza uma máquina de estados (state) para controlar o fluxo da conversa, como por exemplo:

INIT → Início
TIPO_ENTREGA → Escolha entrega/retirada
MENU → Menu principal
PIZZA → Montagem da pizza
DONE → Finalização
🍕 Estrutura do Cardápio

O cardápio é definido diretamente no código JavaScript

O sistema aplica promoções automaticamente em dias úteis

Exemplo: Algumas pizzas grandes têm preço fixo promocional durante a semana

🎨 Interface
Design moderno (modo escuro 🌙)
Totalmente responsivo
Animações suaves
Simulação de “digitando...” do bot


Tudo está em um único arquivo:

HTML (estrutura)
CSS (estilo)
JavaScript (lógica)

⚙️ Possíveis melhorias
💳 Integração com pagamento online (Pix/cartão)
📊 Painel administrativo
🧾 Histórico de pedidos
🤖 IA para respostas automáticas mais avançadas
🔔 Notificações em tempo real
📌 Observações

Funciona melhor em dispositivos móveis
Não requer backend (100% front-end)
👨‍💻 Autor: Gisele dos Santos

Projeto desenvolvido para automatização de pedidos de pizzaria via WhatsApp.
