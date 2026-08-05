# 🍽️ Sistema de Gestão para Restaurantes (Autoatendimento por QR Code)

> Plataforma completa desenvolvida para gerenciar todas as operações de um restaurante de forma integrada, oferecendo autonomia para os clientes na mesa e controle total em tempo real para a administração e a cozinha.

---

## 🛠️ Tecnologias Utilizadas

Este projeto foi estruturado com foco em performance, controle de fluxo e separação de permissões por perfil de usuário:

*   **Backend:** PHP / Laravel
*   **Banco de Dados:** MySQL
*   **Interface:** Tailwind CSS / Blade
*   **Controle de Versão:** Git & GitHub

---

## 💡 Sobre o Projeto

O sistema automatiza o ecossistema interno e externo de um estabelecimento gastronômico. Ele elimina a fila de espera para atendimento tradicional ao permitir que o próprio cliente faça o pedido direto da mesa via QR Code, integrando instantaneamente o salão, a cozinha e o controle administrativo/financeiro.

---

## 👥 Perfis de Acesso (Roles)

O sistema possui uma arquitetura baseada em múltiplos papéis, garantindo que cada usuário acesse apenas o que é necessário para a sua função:

*   👨‍💼 **Administrador:** Visão geral do negócio, relatórios financeiros, controle de estoque (entradas, saídas e insumos), gerenciamento completo de funcionários, cardápio e auditoria de caixa.
*   🤵 **Garçom:** Apoio ao salão, acompanhamento de mesas ativas e suporte aos clientes caso seja necessário atendimento presencial.
*   🍳 **Cozinha (KDS - Kitchen Display System):** Painel em tempo real para os cozinheiros visualizarem os pedidos que chegam do salão/mesas, organizados por ordem de prioridade e com status de preparo.
*   📱 **Cliente (Mesa via QR Code):** Interface mobile responsiva onde o cliente lê o código da mesa, visualiza o cardápio digital, realiza e acompanha o status do seu próprio pedido sem depender de intermediários.

---

## ⚙️ Principais Módulos e Funcionalidades

*   📊 **Painel Administrativo & Estoque:** Métricas de vendas diárias, fluxo de caixa, produtos mais vendidos e baixa automática de insumos e estoque gerenciada pelo próprio painel do admin.
*   📲 **Cardápio Digital por QR Code:** Cada mesa possui um QR Code único vinculado; o cliente acessa instantaneamente pelo celular para pedir e acompanhar a comanda.
*   🛎️ **Fluxo de Pedidos em Tempo Real:** Comunicação instantânea entre o pedido feito pelo cliente na mesa e a tela de exibição da cozinha.
*   🍔 **Gestão de Produtos:** Cadastro flexível de categorias, pratos, ingredientes, adicionais e preços.
*   🔒 **Controle de Acessos e Segurança:** Autenticação robusta e proteção contra acessos indevidos a rotas administrativas usando os recursos nativos do Laravel.

---

## 📈 Arquitetura

O sistema foi estruturado seguindo o padrão **MVC (Model-View-Controller)** do Laravel, garantindo código limpo, fácil manutenção e escalabilidade para adicionar novas funções, caixas ou terminais de atendimento.
