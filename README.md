# 🍦 Sorveteria Gourmet - Web App

![Project Status](https://img.shields.io/badge/status-concluído-success)
![Type](https://img.shields.io/badge/tipo-Real%20World%20Solution-blue)
![Tech](https://img.shields.io/badge/tech-Vanilla%20JS-yellow)

> Uma Landing Page Mobile-First desenvolvida para automatizar pedidos e agilizar o atendimento via WhatsApp de um comércio local.

[![LinkedIn](https://img.shields.io/badge/LinkedIn-0077B5?style=for-the-badge&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/anajuliatoriani/)
[![GitHub](https://img.shields.io/badge/GitHub-100000?style=for-the-badge&logo=github&logoColor=white)](https://github.com/anajuliatoriani)
[![Portfólio](https://img.shields.io/badge/Portfólio-FF5722?style=for-the-badge&logo=&logoColor=white)](https://anajuliatorianipessoa.vercel.app/)
[![E-mail](https://img.shields.io/badge/-Email-D97706?style=for-the-badge&logo=gmail&logoColor=white)](mailto:anajuliatoriani@gmail.com)
[![Behance](https://img.shields.io/badge/Behance-1769ff?style=for-the-badge&logo=behance&logoColor=white)](https://www.behance.net/ajtp)

---

## Sobre o Projeto

Este projeto nasceu de uma necessidade real: **reduzir o atrito de vendas** de uma sorveteria de bairro. O atendimento via WhatsApp sofria com gargalos – clientes sem saber os preços, demora para somar totais e erros nos pedidos.

A solução foi criar um **Web App Leve** (sem necessidade de instalação) que funciona como um cardápio digital inteligente. O foco não foi apenas "mostrar produtos", mas **guiar a conversão** até o fechamento da venda.

###  Funcionalidades Principais
* **Carrinho Inteligente & Persistente:** Utiliza `localStorage` para salvar o pedido. Se o cliente fechar a aba ou ficar sem bateria, o pedido continua lá quando ele voltar.
* **Checkout via WhatsApp:** Gera automaticamente uma mensagem formatada com o resumo do pedido, total calculado e endereço de retirada, enviando direto para o app do vendedor.
* **Smart Status (Horário Real):** Lógica que valida se a loja está "Aberta" ou "Fechada" baseada no fuso horário local (São Paulo), prevenindo pedidos fora de hora.
* **Navegação Nativa (Deep Linking):** Botões de localização que abrem diretamente o app de GPS preferido do usuário (Waze/Google Maps), sem carregar mapas pesados na página.
* **UX Emocional:** Uso de efeitos de confete (`canvas-confetti`) na conclusão da compra para gerar recompensa visual (Dopamina) e *Empty States* ilustrados para reter usuários.

---

##  Tecnologias Utilizadas

O projeto foi construído com foco em **Performance** e **Acessibilidade**, sem o uso de frameworks pesados, garantindo carregamento instantâneo mesmo em 3G/4G.

* **HTML5 Semântico:** Estrutura acessível e otimizada para SEO local.
* **CSS3 Moderno:**
    * **Mobile First:** Todo o layout foi desenhado primeiro para telas verticais.
    * **Design System:** Uso de Variáveis CSS (`:root`) para consistência de cores (Paleta Appetizing).
    * **Layout:** Flexbox e Grid para responsividade fluida.
* **JavaScript (Vanilla ES6+):**
    * Manipulação eficiente do DOM.
    * Lógica de Carrinho (CRUD de itens em array de objetos).
    * Integração com APIs do navegador (`Date`, `Navigator`, `LocalStorage`).
* **Libs Leves:**
    * **GSAP:** Para animações de entrada e micro-interações suaves.
    * **Canvas Confetti:** Para o efeito visual de celebração na compra.
    * **Phosphor Icons:** Ícones vetoriais leves e modernos.

---

##  Decisões de UX/UI

Como Designer migrando para Front-End, cada linha de código teve uma intenção de design:

1.  **Bottom Sheet (Carrinho):** Em vez de levar o usuário para outra página, o carrinho abre como uma "gaveta" (padrão de apps como iFood/Uber), mantendo o contexto de navegação.
2.  **Cores & Apetite:** Substituição do vermelho padrão (que remete a erro/pare) por um **Rosa Framboesa** vibrante, que desperta desejo e mantém a energia da marca.
3.  **Redução de Carga Cognitiva:** Filtros de categoria no topo para que o usuário não precise rolar uma lista infinita para achar o que quer.
4.  **Feedback Visual:** O status da loja (Aberto/Fechado) muda de cor e texto automaticamente, dando feedback imediato sem o usuário precisar perguntar.

---

##  Como Rodar Localmente

1.  Clone este repositório:
    ```bash
    git clone [https://github.com/ajtoriani/sorveteria-gourmet.git](https://github.com/ajtoriani/sorveteria-gourmet.git)
    ```
2.  Abra a pasta do projeto.
3.  Abra o arquivo `index.html` no seu navegador.
    * *Dica:* Recomenda-se usar a extensão **Live Server** do VS Code para simular o ambiente real.

---

##  Estrutura de Pastas

```text
sorveteria/
├── index.html      # Estrutura, Lógica JS e CSS (Single File Component style)
├── img/            # Assets e Prints do projeto
└── README.md       # Documentação
```


## Contribuições
Contribuições são bem-vindas! Se você tiver sugestões ou melhorias, sinta-se à vontade para abrir uma _issue_ ou um _pull request_.

## Contato
Conecte-se comigo no LinkedIn:
Ana Julia


[![LinkedIn](https://img.shields.io/badge/LinkedIn-0077B5?style=for-the-badge&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/ajtp/)
[![GitHub](https://img.shields.io/badge/GitHub-100000?style=for-the-badge&logo=github&logoColor=white)](https://github.com/ajtoriani)
[![Behance](https://img.shields.io/badge/Behance-1769ff?style=for-the-badge&logo=behance&logoColor=white)](https://www.behance.net/ajtp)
[![E-mail](https://img.shields.io/badge/-Email-000?style=for-the-badge&logo=gmail&logoColor=AA42F7)](mailto:anajuliatoriani@gmail.com)
---
## Licença
Este projeto está sob a licença MIT.

---
Desenvolvido por Ana Julia Toriani Pessoa
