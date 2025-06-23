# 🧠 MINECHAT

**Jogo Suave e Lutas Interativas Entre Inscritos em uma Live no YouTube**

MINECHAT é um jogo interativo transmitido ao vivo em formato vertical no YouTube, onde crianças e adolescentes podem digitar comandos no chat para entrar em batalhas 1x1 com criaturas estilo Minecraft. O jogo mistura elementos de RPG, sorte, colecionáveis e batalhas estratégicas, oferecendo uma experiência imersiva e divertida em tempo real.

---

## 📺 Público-Alvo

* Crianças e adolescentes que assistem lives no YouTube.
* Jogadores casuais que gostam de batalhas estilo Pokémon ou RPG.
* Idioma do jogo: **Inglês** (para maior alcance internacional).

---

## ⚔️ Como Funciona o Jogo

### Entrada no jogo:

* O jogador digita `!Join` no chat da live para entrar na fila.
* Quando dois jogadores estão prontos, eles são convocados para batalha.

### Regras da Batalha:

* Batalhas 1x1.
* Cada jogador tem 20 segundos para digitar `!Ready` e escolher sua criatura.
* Se não responder, outro jogador entra no lugar.
* A batalha dura até 2 minutos ou até um jogador ficar com 0 de HP.

### Sistema de Combate:

* Cada criatura possui 4 ataques únicos.
* O ataque 1 tem chance de crítico (dano dobrado) e 0.5% de chance de **hit kill** instantâneo (chamado "Appart").
* Criaturas possuem defesa natural que reduz o dano recebido entre 25% a 75%, variando conforme o tipo.
* Itens ilimitados: podem curar, dar buffs de dano, entre outros efeitos.

### Comandos Disponíveis:

* `!entrar` → Entra na fila de batalha
* `!Ready` → Confirma prontidão para lutar
* `!atack` → Executa ataque padrão
* `!atack (1, 2, 3, 4)` → Executa ataque específico
* `!ataque aleatorio` → Sorteia ataque aleatório da criatura
* `!item (1, 2, 3, 4)` → Usa item específico
* `!escape` → Desiste da batalha
* `!bet` → 50% de chance de matar o inimigo ou morrer instantaneamente

### Criaturas Iniciais:

* Zumbi
* Esqueleto
* Pé grande
* Olho mágico flutuante
* Homem quadrado estilo Minecraft

### Bots automáticos:

* Se o chat da live ficar sem comandos por **4:40 minutos**, bots entram em batalha automática.

### Interface Visual na Live:

* Tela dividida: jogador 1 à esquerda, jogador 2 à direita.
* Nome do jogador aparece acima da criatura.
* Comandos digitados aparecem no topo da tela.
* Barra de vida animada de cada criatura.
* Layout responsivo e adaptado para formato vertical 1080x1920.

### Ranking e Dados:

* Ranking exibido na interface (canto inferior esquerdo).
* Histórico completo de batalhas vencidas por jogador.
* Dados armazenados e salvos periodicamente em arquivos JSON.

---

## 💰 Monetização

* Jogadores compram **moedas no site oficial**.
* Com as moedas, podem adquirir:

  * Skins (visuais e com habilidades novas)
  * Itens (cura, buffs, suporte)
  * Ataques especiais
* Skins são obtidas via **lootboxes** e influenciam estética e poder da criatura.
* Planejado suporte a **LivePix** para doações na live.

---

## 🌐 Site Oficial

O site será o centro de controle do jogador:

* Cadastro e login de conta
* Escolha de criatura e ataques antes da batalha
* Loja com compra de moedas, skins, itens e ataques
* Visualização do inventário do jogador
* Histórico de batalhas anteriores
* Ranking global de jogadores

---

## 🛠️ Stack Tecnológica

* **Linguagem:** Python
* **Renderização:** Pygame (formato vertical 1080x1920)
* **Chat da live:** API oficial YouTube Data v3 (Google API)
* **Banco de dados:** (a definir: SQLite, PostgreSQL ou Firebase)
* **Site:** HTML/CSS/JS ou frameworks modernos (Next.js, Flask + React)
* **Streaming:** OBS Studio

---

## 🧑‍💼 Liderança e Equipe

* Projeto liderado por **Lucas Heitor** (Product Owner, Dev Principal e gestor).
* Equipe atual com 3 integrantes multidisciplinares.
* Meta: crescer o time e evoluir o MINECHAT para um jogo RPG completo no futuro.

---

## 🔮 Futuro: RPG Completo

O projeto MINECHAT serve como MVP e base técnica para um jogo completo estilo RPG:

* Inspirado em criaturas do universo Minecraft
* Com mapa, fases, evolução e habilidades desbloqueáveis
* Inventário persistente e jogabilidade contínua
* Loja integrada com sistema de progressão
* Disponível em web, desktop e possivelmente mobile

---

## 🤝 Como Contribuir

1. Fork este repositório.
2. Crie uma branch com sua feature: `git checkout -b feature-nova`
3. Commit suas mudanças: `git commit -m 'Adiciona nova feature'`
4. Push na branch: `git push origin feature-nova`
5. Crie um Pull Request explicando suas mudanças

---

## ⚖️ Licença

Este projeto está licenciado sob a [Licença Apache 2.0](https://www.apache.org/licenses/LICENSE-2.0).

```
Copyright 2025 Lucas Heitor

Licensed under the Apache License, Version 2.0 (the "License");
you may not use this file except in compliance with the License.
You may obtain a copy of the License at

   http://www.apache.org/licenses/LICENSE-2.0
```

---
