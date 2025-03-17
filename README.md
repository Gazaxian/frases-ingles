# Diário de Inglês - Anotações Ilimitadas

Este script em **Bash** foi desenvolvido para ajudar no estudo de inglês, permitindo salvar frases, suas pronúncias e traduções, fazer buscas e navegar por essas anotações de forma simples e prática. O script também oferece funcionalidades como alterar o limite de frases exibidas por página e limpar o terminal.

## Funcionalidades

- **Adicionar frases**: Salve frases em inglês com suas respectivas pronúncias e traduções.
- **Ver todas as frases**: Visualize as frases salvas com paginação para navegação fácil.
- **Pesquisar frases**: Realize buscas por palavras-chave nas frases salvas.
- **Alterar limite de frases por página**: Modifique o número de frases que são exibidas por página.
- **Limpar o terminal**: Limpe o terminal para manter o ambiente organizado.

## Como Usar

### 1. Adicionar Frases
Para adicionar frases em inglês, basta digitar a frase, incluir a pronúncia entre parênteses e a tradução entre colchetes. Exemplo:

```
I am learning English. (ai ãm lêrning inglix) [Eu estou aprendendo inglês.]
```

O script irá verificar se a frase já foi adicionada anteriormente, evitando duplicatas.

### 2. Ver Todas as Frases
Você pode visualizar todas as frases salvas com paginação, facilitando a navegação.

### 3. Pesquisar Frases
Digite um termo de busca para localizar frases que contenham esse termo.

### 4. Alterar Limite de Frases por Página
Você pode alterar o número de frases exibidas por página, facilitando a navegação, especialmente se você tiver muitas frases salvas.

### 5. Limpar o Terminal
Use esta opção para limpar o terminal, mantendo o ambiente de trabalho limpo e organizado.

## Requisitos

- Sistema operacional com suporte ao Bash (Linux, macOS, etc.).
- O script utiliza comandos padrão do Bash como `grep`, `sed`, e `mkdir`.

## Como Rodar o Script

1. **Clone o repositório**:
   ```bash
   git clone https://github.com/Gazaxian/frases-ingles.git
   ```

2. **Dê permissão de execução ao script**:
   ```bash
   chmod +x diario-de-ingles.sh
   ```

3. **Execute o script**:
   ```bash
   ./diario-de-ingles.sh
   ```

## Personalizações

- O arquivo onde as frases são armazenadas está configurado para ser salvo em `~/Documentos/Ingles/anotacoes.txt`. Caso deseje alterar, edite a variável `ARQUIVO` no início do script.
- O número de frases por página pode ser ajustado a qualquer momento através da opção "Alterar limite de frases por página" no menu principal.

## Licença

Este projeto está licenciado sob a **MIT License** - veja o arquivo [LICENSE](LICENSE) para mais detalhes.
