# Subindo-o-Seu-Projeto-Flutter-no-GitHub

Vou te guiar através do processo de subir um projeto Flutter no GitHub em módulos.

### Módulo 1: Preparação do Ambiente
**Objetivos**:
1. Instalar o Flutter.
2. Configurar o ambiente de desenvolvimento.

**Passos**:
1. **Download do Flutter SDK**: Acesse o [site oficial do Flutter](https://flutter.dev) e faça o download do SDK do Flutter para o seu sistema operacional.
2. **Extração do SDK**: Extraia o arquivo baixado em uma pasta de sua escolha (por exemplo, `C:\src\flutter` no Windows).
3. **Atualização do Path**: Adicione o caminho da pasta `flutter\bin` ao PATH do seu sistema operacional.
4. **Verificação da instalação**: Abra o terminal e execute `flutter doctor` para verificar se está tudo certo com a instalação.

### Módulo 2: Criação do Projeto
**Objetivos**:
1. Criar um novo projeto Flutter.
2. Testar o projeto em um emulador ou dispositivo físico.

**Passos**:
1. **Criação do projeto**: No terminal, navegue até a pasta onde deseja criar o projeto e execute `flutter create nome_do_projeto`.
2. **Execução do projeto**: Entre na pasta do projeto criado e execute `flutter run` para iniciar o app no emulador ou dispositivo conectado.

### Módulo 3: Subindo o Projeto no GitHub
**Objetivos**:
1. Inicializar um repositório Git.
2. Conectar com o GitHub.
3. Subir o projeto no GitHub.

**Passos**:
1. **Inicialização do Git**: Dentro da pasta do projeto, execute `git init` para inicializar um repositório Git.
2. **Adição dos arquivos**: Adicione os arquivos ao repositório com `git add .`.
3. **Commit inicial**: Faça o primeiro commit com `git commit -m "Primeiro commit"`.
4. **Criação do repositório no GitHub**: Vá até o [GitHub](https://github.com) e crie um novo repositório.
5. **Conexão do repositório local com o GitHub**: Execute `git remote add origin url_do_repositório_no_github`.
6. **Subida dos arquivos**: Envie os arquivos para o GitHub com `git push -u origin master`.

Lembre-se de verificar o `.gitignore` para não subir arquivos desnecessários, como as pastas `build/` e `.dart_tool/`. Pronto! Seu projeto Flutter agora está no GitHub e pronto para colaborações! 🚀

https://flutter.dev/
