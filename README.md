# Inteli - Instituo de Tecnologia e liderança

<p align="center">
  <img src="https://i.imgur.com/aIfBsxk.png" alt="Inteli logo" border="0" width="312px">
</p>

# Proposta de Arquitetura de Software

## Grupo X - Nome do Grupo

### 🚀 Integrantes
- <a href="">Abner Silva</a>
- <a href="">Abner Silva</a>
- <a href="">Abner Silva</a>
- <a href="">Abner Silva</a>
- <a href="">Abner Silva</a>
- <a href="">Abner Silva</a>

## 🔍 Sumário

* [Descrição](#descrição)
* [Estrutura de pastas](#-estrutura-de-pastas)
* [Documentação do sistema atual](#-documentação-do-sistema-atual)
* [Documentação do sistema novo](#-documentação-do-sistema-novo)
* [Documentação da simulação](#-documentação-da-simulação)
* [Instalação](#-instalação)
  * [Tecnologias](#tecnologias)
  * [Implementações](#implementações)
  * [Demo](#demo)
* [Histórico de lançamentos](#-histórico-de-lançamentos)
* [Licença/License](#-licençalicense)
* [Referências](#referências)


## 📜Descrição

A solução de arquitetura desenvolvida para a Meta foi projetada para aprimorar requisitos funcionais específicos, visando proporcionar uma abordagem inovadora para obter informações atualizadas sobre tópicos relevantes para empresas. Ao integrar interações de voz e texto, os usuários podem realizar buscas precisas sobre as discussões das empresas em relação a temas específicos. Por exemplo, é possível explorar o que empresas do setor financeiro estão debatendo sobre otimização e planejamento financeiro. Além disso, o robusto mecanismo de IA por trás dessa solução é capaz de compreender não apenas as perspectivas da Meta, mas também de outras empresas de tecnologia sobre esses temas, identificando quais tecnologias da Meta estão relacionadas, oferecendo assim um acesso conveniente a insights de mercado, tendências e informações competitivas.

**Principais melhorias da arquitetura:**

- **Busca por comandos de voz e texto:** É possível a utilização de comandos de voz ou texto para fazer perguntas em linguagem natural, como "O que as empresas do ramo financeiro estão falando sobre otimização e planejamento financeiro?"

- **Busca inteligente:** A aplicação utiliza tecnologias avançadas de Inteligência Artificial (IA) e Processamento de Linguagem Natural (NLP) para buscar informações relevantes em documentos e fontes confiáveis.

- **Resultados abrangentes:** Além de informações do mercado em geral, o motor de IA também fornece insights sobre o que a IBM e outras empresas de tecnologia estão dizendo sobre o tema, destacando as tecnologias da IBM envolvidas.

- **Interoperabilidade:** A solução é compatível com uma variedade de dispositivos e sistemas operacionais, incluindo integração com dispositivos de hardware em diferentes ambientes.

- **Privacidade e segurança:** A coleta e o uso de dados dos usuários estão em conformidade com as regulamentações de privacidade, garantindo a segurança e a proteção dos dados pessoais.

- **Protótipo funcional:** A solução é entregue como um protótipo funcional, demonstrando as principais funcionalidades que podem ser refinadas e expandidas conforme necessário.

Este projeto visa melhorar a capacidade de tomada de decisões informadas e manter os profissionais de vendas e clientes da IBM atualizados com informações cruciais sobre o mercado e tópicos relevantes. 

## 📁 Estrutura de pastas


- 📂 __Projeto5M2__
   - 📄 [README.md](README.md)
   - 📂 __[.vscode](.vscode/)__
      - <a href="https://emoji.gg/emoji/8009-java-js"><img src="https://cdn3.emoji.gg/emojis/8009-java-js.png" width="16px" height="16px" alt="Java_Js"></a> sttings.js
   - 📂 __[documentos](documentos/)__
      - <a href="https://github.com/2022M2T3/Projeto4/blob/main/documentos/WAD%20-%20Yamaha%20Planning%20System.pdf"><img src="https://user-images.githubusercontent.com/99209356/174968401-abc5cae1-7a1e-4f06-aca6-c859c993c038.svg" width="18px" height="18px"></a> Manual de Administrador
      - <a href="https://github.com/2022M2T3/Projeto4/blob/main/documentos/WAD%20-%20Yamaha%20Planning%20System.pdf"><img src="https://user-images.githubusercontent.com/99209356/174968401-abc5cae1-7a1e-4f06-aca6-c859c993c038.svg" width="18px" height="18px"></a> Manual do Utilizador
      - <a href="https://github.com/2022M2T3/Projeto4/blob/main/documentos/WAD%20-%20Yamaha%20Planning%20System.pdf"><img src="https://user-images.githubusercontent.com/99209356/174968401-abc5cae1-7a1e-4f06-aca6-c859c993c038.svg" width="18px" height="18px"></a> WAD Grupo 5 - Intech
   - 📁 __[imagens](imagens/)__
   - 📂 __[src](src/)__
      - 📂 __[Backend](src/Backend)__
          - 📁 controllers
          - 📁 database
          - 📁 models
          - 📁 Routes
      - 📂 __[Frontend](src/Frontend)__ 
          - 📁 fonts
          - 📁 images (imagens utilizadas na aplicação web)
          - 📁 script (arquivos em javascript)
             - 📁 tagInputs
             - <a href="https://emoji.gg/emoji/8009-java-js"><img src="https://cdn3.emoji.gg/emojis/8009-java-js.png" width="16px" height="16px" alt="Java_Js"></a> adm
             - <a href="https://emoji.gg/emoji/8009-java-js"><img src="https://cdn3.emoji.gg/emojis/8009-java-js.png" width="16px" height="16px" alt="Java_Js"></a> api-localidades
             - <a href="https://emoji.gg/emoji/8009-java-js"><img src="https://cdn3.emoji.gg/emojis/8009-java-js.png" width="16px" height="16px" alt="Java_Js"></a> dashboard-recruit
             - <a href="https://emoji.gg/emoji/8009-java-js"><img src="https://cdn3.emoji.gg/emojis/8009-java-js.png" width="16px" height="16px" alt="Java_Js"></a> dashboard-user
             - <a href="https://emoji.gg/emoji/8009-java-js"><img src="https://cdn3.emoji.gg/emojis/8009-java-js.png" width="16px" height="16px" alt="Java_Js"></a> forms
             - <a href="https://emoji.gg/emoji/8009-java-js"><img src="https://cdn3.emoji.gg/emojis/8009-java-js.png" width="16px" height="16px" alt="Java_Js"></a> showhideSenhas
             - <a href="https://emoji.gg/emoji/8009-java-js"><img src="https://cdn3.emoji.gg/emojis/8009-java-js.png" width="16px" height="16px" alt="Java_Js"></a> vaga-descricao
          - 📂 styles (arquivos CSS da aplicação web)
             - 📁 styleADM 
             - 📁 styleRecruiter
             - 📁 styleUsers
             - <a href="https://emoji.gg/emoji/8517-css"><img src="https://cdn3.emoji.gg/emojis/8517-css.png" width="24px" height="24px" alt="css"></a> login
             - <a href="https://emoji.gg/emoji/8517-css"><img src="https://cdn3.emoji.gg/emojis/8517-css.png" width="24px" height="24px" alt="css"></a> main
             - <a href="https://emoji.gg/emoji/8517-css"><img src="https://cdn3.emoji.gg/emojis/8517-css.png" width="24px" height="24px" alt="css"></a> recuperacaoSenha
             - <a href="https://emoji.gg/emoji/8517-css"><img src="https://cdn3.emoji.gg/emojis/8517-css.png" width="24px" height="24px" alt="css"></a> telaCadastro
          - 📁 views (arquivos em HTML)
             - 📁 ADM
             - 📁 Recruiter
             - 📁 Users
             - <a href="https://emoji.gg/emoji/GoogleChrome"><img src="https://cdn3.emoji.gg/emojis/GoogleChrome.png" width="24px" height="24px" alt="GoogleChrome"></a> index
             - <a href="https://emoji.gg/emoji/GoogleChrome"><img src="https://cdn3.emoji.gg/emojis/GoogleChrome.png" width="24px" height="24px" alt="GoogleChrome"></a> recuperacaoSenha1
             - <a href="https://emoji.gg/emoji/GoogleChrome"><img src="https://cdn3.emoji.gg/emojis/GoogleChrome.png" width="24px" height="24px" alt="GoogleChrome"></a> recuperacaoSenha2
             - <a href="https://emoji.gg/emoji/GoogleChrome"><img src="https://cdn3.emoji.gg/emojis/GoogleChrome.png" width="24px" height="24px" alt="GoogleChrome"></a> telaCadastro
             - <a href="https://emoji.gg/emoji/GoogleChrome"><img src="https://cdn3.emoji.gg/emojis/GoogleChrome.png" width="24px" height="24px" alt="GoogleChrome"></a> testelogin
 
<br>

Dentre os arquivos e pastas presentes na raiz do projeto, definem-se:

- <b>README.md</b>: arquivo que serve como guia e explicação geral sobre o projeto (o mesmo que você está lendo agora).

- <b>assets</b>: aqui estão os arquivos relacionados a parte gráfica do projeto, ou seja, as imagens e links de vídeos que os representam (o logo do grupo pode ser adicionado nesta pasta).

- <b>docs</b>: aqui estão todos os documentos do projeto. Há também uma pasta denominada <b>outros</b> onde estão presentes outros documentos complementares, além de um arquivo README para o grupo registrar a localização de cada artefato.

- <b>src</b>: Todo o código fonte criado para o desenvolvimento do projeto, incluindo backend e frontend se aplicáveis.

src: todo o código fonte criado para o desenvolvimento do projeto, incluindo os blocos de código do circuito, backend e frontend se aplicáveis.

## 📄 Documentação do sistema atual
  - <a href=""><img src="https://user-images.githubusercontent.com/99209356/174968401-abc5cae1-7a1e-4f06-aca6-c859c993c038.svg" width="18px" height="18px"> Exemplo.md</a> 

## 📄 Documentação do sistema novo
  - <a href=""><img src="https://user-images.githubusercontent.com/99209356/174968401-abc5cae1-7a1e-4f06-aca6-c859c993c038.svg" width="18px" height="18px"> Exemplo.md</a> 

## 📄 Documentação da simulação
  - <a href=""><img src="https://user-images.githubusercontent.com/99209356/174968401-abc5cae1-7a1e-4f06-aca6-c859c993c038.svg" width="18px" height="18px"> Exemplo.md</a> 

## 🔧 Instalação

Para a instalação desse projeto, é necessário ter alguns recursos instalados na máquina que irá executar. Nota-se que além das instalações necessárias, também destaca-se que é relevante a versão de cada uma dessas tecnologias, haja vista que podem ocorrer falhas na execução, devido a configuração do projeto.

### Tecnologias
- React Native 0.64.2
- Flutter 2.2.3
- Python 3.9.6
- Rabbit MQ 3.9.7
- Docker 20.10.8
- Type Script 4.3.5
- Node 14.17.6

### Implementações
- Passo a Passo de como incicializar as implmentações localmente ( Recomenda-se para facilitar a documentação e a propria instalação utilizar docker compose).

Exemplo :

```bash
  git clone ***
  cd my-project
```

### Demo
- Passo a Passo de como incicializar a demo localmente ( Recomenda-se para facilitar a documentação e a propria instalação utilizar docker compose)

Exemplo :

```bash
  git clone ***
  cd my-project
```

## 🗃 Histórico de lançamentos

**1.0 — 11/08/2023 (Sprint I)**

* Entendimento do Negócio

* Entendimento do Design

* Entendimento da Arquitetura do Sistema


**2.0 — 25/08/2023 (Sprint II)**

* Sistema de NLP

* Documentação da Sprint


**3.0 — 06/09/2023 (Sprint III)**

* Construção do Backend da Solução

* Documentação da Sprint


**4.0 — 22/09/2023 (Sprint IV)**

* Construção do Frontend da Aplicação

* Documentação da Sprint
  

**5.0 — 06/10/2023 (Sprint V)**

* Elaboração da Documentação Final do Projeto

* Apresentação Final


## 📋 Licença/License

<p xmlns:cc="http://creativecommons.org/ns#" xmlns:dct="http://purl.org/dc/terms/"><a property="dct:title" rel="cc:attributionURL" href="#">Kepler</a> by <a rel="cc:attributionURL dct:creator" property="cc:attributionName" href="#">Inteli, Abner Silva Barbosa, Daniel da Silva Cunha, Emanuel Costa, Gabriel Nascimento, Livia Coutinho, Mateus Neves, Priscila Falcão</a> is 
licensed under <a href="http://creativecommons.org/licenses/by/4.0/?ref=chooser-v1" target="_blank" rel="license noopener noreferrer" style="display:inline-block;">Attribution 4.0 International<img style="height:22px!important;margin-left:3px;vertical-align:text-bottom;" src="https://mirrors.creativecommons.org/presskit/icons/cc.svg?ref=chooser-v1"><img style="height:22px!important;margin-left:3px;vertical-align:text-bottom;" src="https://mirrors.creativecommons.org/presskit/icons/by.svg?ref=chooser-v1"></a></p>

## 🎓 Referências

IBM. Encontre respostas rapidamente com documentos e soluções Cloud. Disponível em: <https://cloud.ibm.com/docs?locale=pt-BR>. Acesso em: set. 2023.

IBM. Speech to text. Disponível em: <https://cloud.ibm.com/apidocs/speech-to-text>. Acesso em: ago. 2023.

ADZLANI, Nasri. RabbitMQ on Docker and python. Disponível em: <https://nasriadzlani.medium.com/rabbitmq-on-docker-and-python-300e449fcc8c>. Acesso em: set. 2023.

PALLETS, Flask. API. Disponível em: <https://flask.palletsprojects.com/en/3.0.x/api/>. Acesso em: set. 2023.

_Alguns textos foram baseados em pesquisas no ChatGPT._ Disponível em: <https://chat.openai.com/>.

