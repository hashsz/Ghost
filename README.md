### Menos procura. Mais acesso ao que você usa todos os dias.

Ghost é uma central de produtividade portátil para Windows que reúne prompts, arquivos Markdown, sites, procedimentos e aplicativos em um só lugar. Organize seu conteúdo por categorias, encontre o que precisa pela busca global e acesse suas ferramentas pelo notch na borda da tela.

**Windows x64 · Portátil · Dados locais · Interface personalizável**

[⬇️ Download]([https://github.com/SEU-USUARIO/ghost/releases/latest/download/Ghost-Portable.zip](https://drive.google.com/file/d/1zZu0Pie0yuEKfx-Dxh8Ku2iZHMlJwd8p/view?usp=sharing))

## O que você pode fazer

- **Guardar e reutilizar prompts:** organize textos por categoria e copie-os para usar nas suas ferramentas favoritas.
- **Organizar arquivos Markdown:** mantenha sua biblioteca de arquivos `.md` acessível para reutilização.
- **Reunir sites e procedimentos:** salve endereços e instruções recorrentes, com vínculos para abrir URLs ou copiar textos.
- **Encontrar conteúdo pela busca global:** localize itens sem navegar manualmente por cada biblioteca.
- **Acessar pelo notch:** abra atalhos e listas rápidas pela borda da tela, com posição e itens configuráveis.
- **Consultar o histórico de cópia:** acesse textos, links e imagens capturados conforme suas preferências.
- **Gerenciar aplicativos:** organize programas e use a integração com WinGet para buscar e instalar pacotes.
- **Personalizar a experiência:** ajuste tema, cor de destaque, fonte e movimento, além do perfil.
- **Preservar seus dados:** use os recursos de backup e restauração para transportar ou recuperar sua organização.

## Por que Ghost?

O Ghost aproxima o conteúdo que você reutiliza das ações que executa no Windows. Um prompt, um link, um procedimento ou um aplicativo: tudo fica em uma central pessoal, com acesso rápido e aparência ajustável.

O pacote portátil inclui o runtime .NET. Extraia a pasta completa e abra `ghost.exe`, sem precisar instalar o runtime separadamente. Os dados do aplicativo ficam localmente na pasta `save`.

## Imagens

<!-- Adicione capturas reais da versão publicada nos caminhos abaixo antes de remover este comentário e ativar as imagens.
![Biblioteca do Ghost com exemplos organizados por categoria](docs/images/ghost-biblioteca.png)
![Busca global do Ghost exibindo resultados](docs/images/ghost-busca.png)
![Notch do Ghost aberto na borda da tela](docs/images/ghost-notch.png)
![Personalização de aparência no Ghost](docs/images/ghost-aparencia.png)
-->

## Baixar e usar

1. Baixe `Ghost-Portable.zip` na [versão mais recente](https://github.com/SEU-USUARIO/ghost/releases/latest).
2. Extraia todo o conteúdo do ZIP para uma pasta.
3. Abra `ghost.exe` dentro da pasta extraída.
4. Mantenha a pasta `support` junto do executável.

Para transportar o aplicativo com seus dados, finalize o Ghost pelas configurações e copie a pasta inteira, incluindo `save`.

Fechar ou minimizar a janela normalmente mantém o Ghost na bandeja do Windows. Use **Finalizar** nas configurações para encerrá-lo.

As funções de instalação pelo WinGet dependem da disponibilidade dessa ferramenta no Windows. Instalações e alterações do sistema exigem ação e confirmação do usuário e podem solicitar permissão de administrador. Fontes opcionais precisam estar instaladas no Windows; o aplicativo usa uma fonte substituta quando necessário.

## Código-fonte

Para estudar ou compilar o projeto, use **Code → Download ZIP** ou clone o repositório. Esse download contém o código; para executar o aplicativo pronto, baixe o pacote portátil em Releases.

O projeto utiliza C#, .NET 10, WPF e SQLite. A versão atual fica em `src/GhostClone1`, cujo nome foi mantido por compatibilidade histórica. Consulte as instruções técnicas de compilação e `THIRD-PARTY-NOTICES.txt` para dependências e avisos de terceiros.

## Feedback

Encontrou um problema ou tem uma sugestão? Abra uma [Issue](https://github.com/SEU-USUARIO/ghost/issues) com a versão usada, os passos para reproduzir e, se possível, uma captura de tela.
