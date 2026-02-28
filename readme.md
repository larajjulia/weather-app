CONHECIMENTOS ADQUIRIDOS


> * { }, trata-se do seletor universal que aplica estilo à todos os elementos da página simultâneamente. 


> A combinação width: 100% e height: 100dvh para o body é essencial porque a largura do pai (html), por padrão, já ocupa 100% da tela, porém a altura não é previamente definida, então é preciso especificar o dynamic viewport height (dvh), que é a medida que não depende do pai e é melhor que o vh, porque corrige alguns problemas com a apresentação dos sites no celular (onde, à medida que você desce a tela, a barra de navegação tende a sumir e somente o vh pode dar problema).

> A combinação dos comandos:
    background-size: cover;
    background-position: center;
    background-repeat: no-repeat;
> faz com que a imagem (caso seja muito grande) ocupe toda a tela com apenas um pedaço, fique descentralizada ou se repita (caso seja muito pequena para o elemento que é o html, isto é, a página como um todo).

body::before
> é uma forma de adicionar algo visual sem "sujar" o HTML com elementos não semânticos. E, como o nome diz, adiciona efeitos antes do próximo conteúdo (enquanto o ::after adicionaria depois, por exemplo).