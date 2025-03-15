# Script de Anotações de Frases em Inglês Ilimitadas

Este script permite salvar frases em inglês, com a pronúncia e tradução, de forma ilimitada. O objetivo é ajudar no estudo de inglês ao permitir a fácil organização de frases com suas respectivas traduções e pronúncias. Além disso, ele também permite a pesquisa por palavras-chave dentro das frases salvas.

## Funcionalidade:
- Salve frases de inglês de forma ilimitada.
- Cada frase pode ter sua pronúncia e tradução associadas.
- Pesquise por palavras-chave nas frases salvas.
- Exibe as frases com cores para facilitar a leitura:
  - **Frase em inglês**: Cor branca.
  - **Pronúncia**: Cor azul.
  - **Tradução**: Cor verde.

## Como usar:
1. Salve o script em um arquivo `.sh` e torne-o executável.
2. Execute o script e escolha entre adicionar uma nova frase ou pesquisar por palavras-chave.
3. Ao adicionar uma frase, você será solicitado a inserir a frase em inglês, a pronúncia e a tradução.
4. Ao pesquisar, insira uma palavra-chave para procurar nas frases salvas. O script mostrará todas as frases que contêm a palavra pesquisada, com a pronúncia e a tradução.

### Exemplo de Execução:

```bash
$ ./anotacoes_inglês_ilimitado.sh

O script fornecerá opções como:

Adicionar nova frase.
Pesquisar por palavra-chave.
Exemplo de saída:
Quando você adicionar uma nova frase, o script solicitará:

Frase em inglês.
Pronúncia da frase.
Tradução da frase.
Quando você pesquisar uma palavra-chave, o script exibirá as frases que contêm a palavra pesquisada, assim:

vbnet
Copiar
Editar
Frase: "I am learning English." 
Pronúncia: "Ai ãm lérning Inglish."
Tradução: "Eu estou aprendendo inglês."
Dependências:
grep
sed
awk
Certifique-se de que essas ferramentas estão instaladas no seu sistema para que o script funcione corretamente.
