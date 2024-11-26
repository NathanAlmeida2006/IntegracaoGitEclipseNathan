# Integração com IntelliJ IDEA

Este guia foi criado para ajudá-lo a integrar seu projeto ao IntelliJ IDEA, um dos ambientes de desenvolvimento mais populares e robustos para Java e outras linguagens.

## Pré-requisitos

Antes de começar, certifique-se de que:

1. O IntelliJ IDEA está instalado em sua máquina. Você pode baixá-lo [aqui](https://www.jetbrains.com/idea/download/).
2. Você possui o JDK configurado corretamente. Caso contrário, faça o download [aqui](https://www.oracle.com/java/technologies/javase-downloads.html).
3. O projeto que você deseja integrar está disponível localmente ou em um repositório Git.

---

## Passo a Passo

### 1. Abrir o Projeto
- **Opção 1:** Se o projeto já está em sua máquina:
    1. Abra o IntelliJ IDEA.
    2. Clique em `File > Open`.
    3. Navegue até o diretório do projeto e clique em **OK**.

- **Opção 2:** Se o projeto está em um repositório Git:
    1. Clique em `File > New > Project from Version Control`.
    2. Escolha o tipo de controle de versão, como Git.
    3. Insira a URL do repositório e o diretório onde deseja clonar o projeto.
    4. Clique em **Clone**.

---

### 2. Configuração do JDK
1. Vá para `File > Project Structure > SDKs`.
2. Clique no botão `+` e selecione **JDK**.
3. Escolha o diretório onde o JDK está instalado.
4. Certifique-se de que o JDK está selecionado no projeto.

---

### 3. Configuração do Build Tool (Maven/Gradle)
- Se o projeto utiliza **Maven**:
    1. Certifique-se de que o arquivo `pom.xml` está na raiz do projeto.
    2. O IntelliJ IDEA detectará automaticamente o Maven e importará as dependências.

- Se o projeto utiliza **Gradle**:
    1. Certifique-se de que o arquivo `build.gradle` está presente.
    2. Clique em `Import Gradle Project` quando solicitado.

---

### 4. Configuração do Ambiente de Execução
1. Vá para `Run > Edit Configurations`.
2. Clique no botão `+` para adicionar uma nova configuração.
3. Escolha **Application** para aplicações Java.
4. Preencha:
    - **Main class**: A classe principal do projeto.
    - **VM options** (opcional): Configurações adicionais para a JVM.
5. Clique em **OK**.

---

### 5. Testando o Projeto
- Use o atalho `Shift + F10` para executar o projeto.
- Confira a saída do console para verificar se tudo está funcionando corretamente.

---

### 6. Atalhos Úteis no IntelliJ IDEA
- **Alt + Insert**: Gera código automaticamente (getter, setter, etc.).
- **Ctrl + Shift + F10**: Executa a aplicação.
- **Ctrl + Shift + A**: Abre a ação ou configuração rapidamente.
- **Ctrl + N**: Busca classes.
- **Ctrl + Shift + N**: Busca arquivos.

---

## Suporte
Se você encontrar problemas durante a integração, consulte a [documentação oficial do IntelliJ IDEA](https://www.jetbrains.com/help/idea/) ou entre em contato com sua equipe de desenvolvimento.
