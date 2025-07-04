# 🚀 UNIESP Online

Bem-vindo(a) ao repositório do **Site Institucional da UNIESP**! Este não é apenas mais um site; é a prova viva de que o **Frontend Avançado** pode ser fascinante, dinâmico e cheio de possibilidades. Criado com paixão para a disciplina do **Prof. Kelson**, este projeto demonstra como construir uma experiência web de verdade, do zero e com as ferramentas mais quentes do mercado.

---

## ✨ O Que Você Vai Encontrar Aqui?

Imagine um portal universitário moderno, que conversa com você e se adapta a qualquer tela. É exatamente isso que este projeto entrega! Meu objetivo foi simular um site institucional completo, com:

* **Notícias Fresquinhas:** Uma seção dedicada a manter a comunidade UNIESP atualizada, consumindo dados de uma API (simulada, mas com cara de verdade!).
* **Navegação Sem Complicações:** Chega de recarregar a página! Com um sistema de rotas inteligente, você pula de uma seção para outra de forma fluida e instantânea.
* **Design que se Adapta:** Seja no computador, tablet ou celular, o site fica lindo e funcional. Graças ao poder do **Bootstrap**, a responsividade é garantida.
* **Muita Interatividade:** O coração do projeto bate com **React**, garantindo uma experiência de usuário rica e reativa, onde tudo acontece como mágica na tela.

---

## 🛠️ O Arsenal Tecnológico por Trás da Mágica

Para construir algo tão bacana, eu contei com um time de peso. Aqui estão as estrelas que fazem este projeto brilhar:

* **React:** A base de tudo! Com ele, construir interfaces se torna um quebra-cabeça divertido de componentes reutilizáveis.
* **React Router DOM:** Nosso guia de viagens! Ele nos leva de uma página à outra sem perder o ritmo, criando uma verdadeira experiência de aplicativo.
* **Axios:** Nosso mensageiro confiável! É ele que busca os dados da API para que você sempre veja as informações mais recentes.
* **Bootstrap & React-Bootstrap:** A dupla dinâmica para estilo e responsividade. Layouts impecáveis e componentes prontos para usar, tudo isso adaptado para o React.
* **JSON Server:** O "backend de mentirinha" que todo desenvolvedor front-end ama! Ele transforma um simples arquivo JSON em uma API REST completa, perfeita para testar e desenvolver sem dores de cabeça.
* **Vite:** O foguete do desenvolvimento! Com ele, seu projeto inicia em segundos e as mudanças aparecem na tela num piscar de olhos. Diga adeus aos longos tempos de compilação!

---

## 🚀 Colocando o Projeto Para Rodar (É Mais Fácil do Que Parece!)

Curioso(a) para ver a UNIESP online em ação? Siga estes passos simples e você estará navegando em minutos!

### Pré-requisitos

Antes de começar, certifique-se de ter o **Node.js** (recomendo a versão 18 ou superior) e o **npm** (que vem com o Node.js) instalados na sua máquina.

### É Hora de Codar!

1.  **Pegue o código:** Comece clonando este repositório ou baixando os arquivos para o seu computador.
2.  **Entre na pasta:** Abra o seu terminal e navegue até a raiz do projeto:
    ```bash
    cd site-uniesp
    ```
3.  **Instale as dependências:** Deixe o npm fazer o trabalho pesado para você:
    ```bash
    npm install
    ```
4.  **Ligue o "Backend Falso":** Em um terminal **separado** (sim, dois terminais!), inicie o JSON Server:
    ```bash
    npm run server
    ```
    Isso vai ligar nossa API simulada em `http://localhost:3000`, pronta para entregar os dados. Mantenha este terminal aberto!

5.  **Suba o Frontend:** Agora, no **primeiro terminal** (ou em um novo), é hora de ver a mágica acontecer:
    ```bash
    npm run dev
    ```
    O Vite vai ligar o servidor de desenvolvimento e, em alguns segundos, seu navegador abrirá o site, provavelmente em `http://localhost:5173`. Se a porta for diferente, o terminal te avisará!

---

O site precisa do **JSON Server rodando** para buscar as notícias e outros dados. Então, mantenha ambos os terminais ativos!

---