# Relatório de Pesquisa & Insights — Bolão CazéTV

Com base nos resultados das 15 perguntas aplicadas via YouTube Lives para quase 3.000 usuários por enquete, consolidamos os aprendizados para focar o desenvolvimento do **MVP do Bolão** com a LiveLike.

---

## 🚀 1. Motor de Adoção: Prêmios são o "Hook"
A grande isca de entrada para o usuário comum de YouTube no Bolão é a promessa de premiação. 
- **61%** relata que entraria no bolão gratuito imediatamente se houvesse prêmio.
- **41%** diz que é o *maior motivo* para jogar.
- **Conclusão para Produto/Vendas:** A busca por um Sponsor (iFood ou Bets) que consiga suprir esses prêmios não é só um capricho, é uma necessidade forte para atração no Brasil.

## 🤝 2. Retenção & Rotina: Ligas de Amigos ("Resenha")
Se prêmios atraem, os **amigos retêm**.
- Quando perguntados sobre o que torna o bolão rotineiro, **49%** escolhe a "resenha com amigos".
- **52%** criariam uma liga só para amigos, e **37%** preferem focar nessa disputa em vez do ranking geral (13%).
- **Insight para o MVP:** Ligas Privadas (com criação muito simples) devem ser priorizadas no MVP da LiveLike em relação ao Leaderboard Global. Sem amigos, o bolão esfria rápido no pós-cadastro. As mecânicas de compartilhamento rápido precisarão estar lisas.

## 🎙️ 3. O Fator "Fancentric": Elenco CazéTV nas Ligas
Cruzar a comunidade de criadores com a vida do torcedor é uma riqueza social.
- **59%** acha que poder inserir o elenco nas ligas pessoas seria "gigante!".
- **47%** gostaria de ver o seu ranking ou os do bolão integrados diretamente na transmissão ao vivo da CazéTV.
- **Insight:** O público não quer apenas o aplicativo do bolão como uma "segunda tela muda", eles querem que ele interaja com a Live. A LiveLike precisará providenciar APIs claras pra equipe de stream (produção) poder puxar o Top10 rapidamente na tela do YouTube.

## ⏱️ 4. O Comportamento de Carga: Server "Meltdown"
Isso valida 100% a discussão sobre infraestrutura da última reunião técnica do Kick-off:
- **40% vão fazer palpites minutos antes do jogo.** E outros **34% no dia do jogo**.
- Apenas 26% faria com muita antecedência.
- **Conclusão Crítica:** O tráfego do Bolão da CazéTV não será linear; a infraestrutura (SSO / Banco de Dados e App da LiveLike) vai sofrer um evento de DdoS natural (pico gigantesco) de 5 a 8 milhões de conexões num espaço de 15 minutos antes da bola rolar. Isso reforça a prioridade máxima técnica exigida nos fornecedores terceiros.

## 📲 5. Notificações e Gatilhos Sociais
Os usuários respondem bem à hierarquia social:
- A notificação favorita (44%) é a de **"Subiu no ranking!"**.
- A exposição de resultados também é forte: **36%** fariam sempre stories validando resultados no Instagram.
- **Insight Final:** O app precisará oferecer um mecanismo rápido e nativo de "Exportar Card (Meme) pro Instagram/WhatsApp" pra fomentar a viralidade e trazer esse público que quer se mostrar pro mundo.
