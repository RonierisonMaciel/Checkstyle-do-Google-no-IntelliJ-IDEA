# Configurar o Checkstyle do Google no IntelliJ IDEA

Siga os passos abaixo para configurar o Checkstyle do Google no IntelliJ IDEA:

## 1. Instalar o plugin Checkstyle-IDEA

1. Abra o IntelliJ IDEA.
2. Clique em `File` (Arquivo) > `Settings` (Configurações) ou use o atalho `Ctrl+Alt+S`.
3. Selecione `Plugins` no painel à esquerda.
4. Clique na aba `Marketplace` e pesquise por "Checkstyle".
5. Encontre o plugin "Checkstyle-IDEA" e clique em `Install` (Instalar).
6. Após a instalação, clique em `Restart IDE` (Reiniciar IDE) para aplicar as mudanças.

## 2. Configurar o Checkstyle do Google

1. Vá em `File` (Arquivo) > `Settings` (Configurações) novamente ou use o atalho `Ctrl+Alt+S`.
2. Selecione `Tools` (Ferramentas) no painel à esquerda e clique em `Checkstyle`.
3. Clique no botão `+` para adicionar uma nova configuração.
4. Escolha um nome para a configuração (por exemplo, "Google Checkstyle") e selecione "Use a local Checkstyle file" (Usar um arquivo de Checkstyle local).
5. Baixe o arquivo de configuração do Checkstyle do Google [aqui](https://raw.githubusercontent.com/checkstyle/checkstyle/master/src/main/resources/google_checks.xml).
6. Clique no botão `...` ao lado do campo "File" (Arquivo) e navegue até o local onde você salvou o arquivo google_checks.xml baixado no passo 2.5.
7. Clique em `Next` (Avançar) e, em seguida, `Finish` (Concluir).
8. Certifique-se de que a caixa de seleção "Activate Checkstyle for this project" (Ativar Checkstyle para este projeto) esteja marcada e selecione a configuração que você acabou de criar no menu suspenso.
9. Clique em `Apply` (Aplicar) e, em seguida, `OK`.

## 3. Utilizar o Checkstyle do Google

1. No painel à direita, clique na aba "Checkstyle".
2. Selecione os arquivos ou diretórios que você deseja verificar, clique com o botão direito do mouse e escolha `Check Current File` (Verificar Arquivo Atual) ou `Check All Files` (Verificar Todos os Arquivos).
3. O IntelliJ mostrará os problemas encontrados e suas respectivas localizações. Você pode corrigir os problemas manualmente ou usar a funcionalidade "Quick Fix" (Correção Rápida) para corrigir automaticamente alguns deles.

Agora você configurou e ativou o Checkstyle do Google no IntelliJ IDEA. Quando trabalhar em projetos, o Checkstyle ajudará a garantir que o seu código siga as diretrizes de
