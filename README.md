# Terminallang

**Terminallang** é uma ferramenta simples e eficaz para o aprendizado de idiomas usando a linha de comando. Com esse script, você pode registrar, organizar e revisar frases em diferentes idiomas, ajudando a melhorar seu vocabulário e fluência.

Este projeto é ideal para quem quer aprender idiomas de maneira prática e direta, utilizando um terminal para manter suas anotações e revisões organizadas.

## Funcionalidades

- **Adicionar frases**: Adicione frases em qualquer idioma, com a pronúncia e tradução opcional.
- **Revisar frases**: Exiba as frases salvas com paginação, permitindo uma revisão eficiente.
- **Pesquisar frases**: Encontre rapidamente frases por palavras-chave.
- **Personalizar o limite de frases por página**: Defina o número de frases exibidas por página ao revisar ou buscar frases.
- **Limpar o terminal**: Limpe o terminal para uma navegação mais organizada.

## Como Usar

### 1. Menu de Opções
   Após iniciar o script, você verá um menu com as seguintes opções:

   - `1) ✏️ Adicionar frases`
   - `2) 📖 Ver todas as frases`
   - `3) 🔍 Pesquisar frases`
   - `4) ⚙️ Alterar limite de frases por página`
   - `5) 🧹 Limpar terminal`
   - `6) ❌ Sair`

   Use os números para escolher a opção desejada.

### 2. Adicionar Frases
Para adicionar frases em inglês, basta digitar a frase, incluir a pronúncia entre parênteses e a tradução entre colchetes. Exemplo:

```
I am learning English. (ai ãm lêrning inglix) [Eu estou aprendendo inglês.]
```

O script irá verificar se a frase já foi adicionada anteriormente, evitando duplicatas.

### 3. Ver Todas as Frases
Você pode visualizar todas as frases salvas com paginação, facilitando a navegação.

### 4. Pesquisar Frases
Digite um termo de busca para localizar frases que contenham esse termo.

### 5. Alterar Limite de Frases por Página
Você pode alterar o número de frases exibidas por página, facilitando a navegação, especialmente se você tiver muitas frases salvas.

### 6. Limpar o Terminal
Use esta opção para limpar o terminal, mantendo o ambiente de trabalho limpo e organizado.


## Requisitos

- **Linux, macOS ou Windows** com suporte a Bash.
- **Bash** (O script utiliza comandos padrão do Bash como `grep`, `sed`, e `mkdir`).
- **Editor de texto** (opcional, para editar o arquivo de anotações).

## Como Rodar o Script

1. **Clone o repositório**:
   ```bash
   git clone https://github.com/Gazaxian/terminallang.git
   ```

2. **Dê permissão de execução ao script**:
   ```bash
   chmod +x terminallang.sh
   ```

3. **Execute o script**:
   ```bash
   ./terminallang.sh
   ```

## Personalizações

- O arquivo onde as frases são armazenadas está configurado para ser salvo em `~/anotacoes.txt`. Caso deseje alterar, edite a variável `ARQUIVO` no início do script.
- O número de frases por página pode ser ajustado a qualquer momento através da opção "Alterar limite de frases por página" no menu principal.

## Licença

Este projeto está licenciado sob a **MIT License** - veja o arquivo [LICENSE](LICENSE) para mais detalhes.
