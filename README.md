# ✨ Aventura Textual Dinâmica ✨

### Um ChatBot educacional baseado na API do Google para Inteligência Artificial.

Este projeto é uma aventura textual interativa e educacional, impulsionada por um modelo de inteligência artificial generativa. Ele cria histórias dinâmicas com base em temas e níveis de dificuldade escolhidos pelo jogador, oferecendo uma experiência de aprendizado envolvente através da exploração e interação.

---

## Índice

* [📚 O Problema](#o-problema)

* [💡 A Solução](#a-solucao)

* [🔧 Como Configurar e Executar](#como-configurar-e-executar)

* [▶️ Como Jogar](#como-jogar)

* [🧠 Modelo de IA](#modelo-de-ia)

* [🛠️ Ferramentas](#ferramentas)

* [🚀 Possíveis Melhorias Futuras](#possiveis-melhorias-futuras)

* [📜 Licença](#licenca)

* [🙏 Créditos](#creditos)

---

## 📚 O Problema

Em muitos casos, aprender novos conceitos pode ser uma experiência passiva e pouco envolvente. Este projeto nasce da necessidade de tornar o aprendizado mais dinâmico e interativo. Ele resolve o problema do engajamento ao transformar o estudo de um tema específico em uma aventura lúdica, onde a compreensão do conceito é intrínseca à progressão no jogo. A utilidade reside em oferecer uma ferramenta educacional inovadora e uma demonstração prática do potencial da IA generativa para criar conteúdo personalizado e experiências de usuário ricas em tempo real.

## 💡 Solução

A solução proposta é uma aventura textual dinâmica onde a narrativa e o estado do jogo são gerados em tempo real por um modelo de IA (Gemini 2.5 Flash), oferecendo as seguintes funcionalidades e destacando-se pela sua criatividade:

* **Aventura Educacional:** O foco principal é ensinar um conceito específico dentro do tema escolhido através da narrativa e dos desafios do jogo.

* **História Dinâmica:** A narrativa e o estado do jogo são gerados em tempo real pelo modelo de IA, adaptando-se às ações do jogador.

* **IA como Mestre de Jogo Educacional:** O design do prompt instrui a IA a atuar não apenas como um narrador, mas como um guia educacional sutil, tecendo um conceito central no tema escolhido ao longo da aventura.

* **Seleção de Tema e Dificuldade:** Um chat inicial interativo permite que o jogador escolha o tema da aventura e defina um nível de dificuldade que se adapte à sua experiência.

* **Interface ipywidgets:** A interface do usuário é construída com `ipywidgets`, proporcionando uma experiência interativa rica diretamente em ambientes como o Google Colab, tornando a experiência mais acessível e interativa do que aplicações de console tradicionais.

* **Configuração por Chat:** O fluxo inicial de configuração do jogo é feito através de um chat interativo com a IA, adicionando uma camada de personalização elegante e conversacional.

* **Histórico e Paginação:** O jogo mantém um histórico das jogadas, permitindo que o jogador revise turnos anteriores (memória) através de botões de navegação.

* **Gerenciamento de Estado via JSON:** A comunicação estruturada com a IA via JSON para gerenciar o estado do jogo (localização, inventário, objetivos, etc.) demonstra uma solução técnica eficaz para manter a consistência em uma narrativa dinâmica, garantindo a consistência do jogo ao longo dos turnos.

* **Uso de Ferramentas (Google Search):** O modelo de IA pode utilizar a ferramenta de busca do Google (`search_google`) para obter informações relevantes enriquece a aventura com dados do mundo real, aumentando a precisão e o interesse do conteúdo educacional e permitindo a abordagem de temas modernos e atuais.

* **Indicador de Processamento:** Um indicador visual simples mostra quando a IA está processando a entrada do jogador.

A **eficácia** da solução é comprovada pela sua capacidade de gerar narrativas coerentes e adaptáveis, gerenciar um estado de jogo dinâmico e proporcionar uma transição suave entre as fases de configuração e jogo, garantindo uma experiência de usuário responsiva e envolvente impulsionada pela IA.

## 🔧 Como Configurar e Executar

1. **Ambiente:** Este projeto é projetado para ser executado em um ambiente Python que suporte `ipywidgets`, como Google Colab.

2. **Bibliotecas:** O projeto usa as bibliotecas padrão do Google Colab e instala, em seu primeiro comando, o `google-genai` e o `ipywidgets`

3. **Chave de API do Google:** Você precisará de uma Chave de API do Google Cloud com acesso à API Gemini. Configure-a como uma variável de ambiente chamada `GOOGLE_API_KEY`. No Google Colab, você pode usar a funcionalidade "Secrets" (`userdata.get('GOOGLE_API_KEY')`).

4. **Código:** Copie o arquivo `Text_Based_Adventure.ipynb` em seu Google Drive para criar um novo notebook Colab.

5. **Executar:** Execute as células em ordem e a última célula iniciará o jogo em si.

## ▶️ Como Jogar

1. Execute as células do notebook.

2. Uma interface de chat inicial aparecerá, guiando você na escolha do idioma, tema e da dificuldade da sua aventura.

3. Uma vez que as configurações forem finalizadas, a interface da aventura principal será exibida.

4. Leia a narrativa e insira seus comandos ou ações na caixa de texto. Seja você mesmo e tente aprender ao máximo com a sua aventura.

5. Use os botões "Prev" e "Next" para navegar pelo histórico de turnos e lembrar as ações passadas.

6. Digite `quit` a qualquer momento para sair do jogo e ver um resumo do seu progresso e como ele se conecta com conceitos chaves relacionado ao tema escolhido.

## 🧠 Modelo de IA

Este projeto utiliza o modelo **Gemini 2.5 Flash** para gerar a narrativa e o estado do jogo dinamicamente.

## 🛠️ Ferramentas

O modelo de IA tem acesso à ferramenta **Google Search** para buscar informações relevantes durante a configuração e o jogo.

## 🚀 Possíveis Melhorias Futuras

* Salvar/Carregar o estado do jogo.

* Interface de usuário mais rica com imagens ou elementos visuais.

* Mais ferramentas para a IA utilizar.

* Opções de acessibilidade.

## 📜 Licença

Este projeto está licenciado sob a Licença MIT. Consulte o arquivo `LICENSE` para mais detalhes.

## 🙏 Créditos

* Este projeto foi proposto como uma tarefa do curso de IA da **Alura**, a escola de tecnologia que proporcionou esta oportunidade de aprendizado e desenvolvimento. Agradecemos à Alura por esta iniciativa! Saiba mais em: <https://www.alura.com.br/>

* Desenvolvido com a assistência do modelo Gemini.

* Desenvolvido por [pekapa](https://github.com/pekapa).

---
