# ChallengeDecodificador-ONE-T7
"Praticando lógica de programação: challenge Decodificador de Texto"

## Descrição
![Badge em Desenvolvimento](http://img.shields.io/static/v1?label=STATUS&message=EM%20DESENVOLVIMENTO&color=GREEN&style=for-the-badge)

Este projeto é uma aplicação web simples que permite criptografar e descriptografar textos utilizando substituições específicas para cada vogal. Desenvolvido como parte do programa Oracle ONE, o projeto tem como objetivo aplicar conceitos de manipulação de strings e interface de usuário.

## Funcionalidades

- **Criptografar texto**: Substitui as vogais no texto de entrada por códigos específicos.
- **Descriptografar texto**: Reverte a criptografia, restaurando o texto original.
- **Copiar texto**: Permite copiar o texto criptografado/descriptografado para a área de transferência.
> :construction: Projeto em construção :construction:
- **Responsividade**: A interface é ajustável para diferentes tamanhos de tela, garantindo boa usabilidade em dispositivos móveis e desktop.
- **Rodapé**: Inclui informações do desenvolvedor e links para redes sociais.

### As "chaves" de criptografia que utilizaremos são:
- A letra "e" é convertida para "enter".
- A letra "i" é convertida para "imes".
- A letra "a" é convertida para "ai".
- A letra "o" é convertida para "ober".
- A letra "u" é convertida para "ufat".

### Requisitos:
- Deve funcionar apenas com letras minúsculas
- Não devem ser utilizados letras com acentos nem caracteres especiais
- Deve ser possível converter uma palavra para a versão criptografada e também retornar uma palavra criptografada para a versão original.
  
## Como Usar
1. **Digite o texto**: Insira o texto no campo de entrada.
2. **Criptografar ou Descriptografar**: Clique no botão correspondente para criptografar ou descriptografar o texto.
3. **Copiar**: Utilize o botão "Copiar" para copiar o resultado para a área de transferência.

## Tecnologias Utilizadas
- **HTML5**: Estrutura da aplicação.
- **CSS3**: Estilização da interface.
- **JavaScript**: Manipulação do DOM e lógica de criptografia/descriptografia.

## Estrutura de Arquivos
```plaintext
/
|-- index.html         # Estrutura principal da página
|-- style.css          # Estilos e layout da página
|-- script.js          # Funções de criptografia e interações do usuário
|-- img/               # Imagens usadas na aplicação
|   |-- logoAlura.png  # Logo da Alura
|   |-- linkedin.svg   # Ícone do LinkedIn
|   |-- discord.svg    # Ícone do Discord
|   |-- github.svg     # Ícone do GitHub
|-- README.md          # Este arquivo
```
##
