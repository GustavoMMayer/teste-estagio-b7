# Teste para vaga de Estagiário Dev Web

O objetivo deste teste é entender o candidato, sua experiência e sua capacidade de resolução de problemas com dúvidas e detalhes que serão exigidos no dia-a-dia como Estagiário em Desenvolvimento Web.
O teste é baseado em questionamentos e problemas a serem resolvidos.

### Como será feito o teste?
O teste é dividido em 2 etapas:
- Questões teóricas.
- Projeto prático, quer seja correção de bug ou criação do mesmo.

O candidato precisa criar um repositório próprio com a seguinte estrutura:
- No README serão respondidas as questões teóricas (pergunta e resposta), de forma organizada e explicada.
- No próprio repositório estará o projeto prático, corrigido e/ou criado.

Após a finalização, o candidato deve enviar um e-mail para suporte@b7web.com.br com o link do repositório original (este) bem como o link do repositório pessoal com a resolução.

## Questões Teóricas

1. Qual a função do "head" no HTML?
    Carregar as informações preliminares da pagina, caracteres, tamhanho da viewport, CSS, titulo ...

2. Quando uma página é criada, ela automaticamente se adapta a todos os tipos de tela? Por que?
    Depende, se a pagina tiver sido criada com os conceios de responsividade, sim, ela se adapta. Ao adaptar a pagina com responsividade, são reposicionados os elementos de forma que fiquem confortaveis em determinados tamanhos de tela. Estas 'adaptações' devem ser previstas para os mais variados tamanhos de tela.

3. O código HTML e CSS é renderizado no servidor e repassado para o navegador em forma de imagem?
    Não, o codigos HTML e CSS, são reenderizados pelo navegador, ocorrendo totalmente no lado cliente.

4. Qual a função das tags H (h1, h2, h3, etc) no HTML?
    São tags de titulos. Servem para dar destaque aos titulos, possuem formatação prévia e valor semantico, o maior destaque é a h1 e vai diminundo.

5. O que é SEO e como funciona?
    São tecnicas utilizadas para otimizar a visibilidade do site perante aos mecanismos de busca, como google, yahoo. Geralmente os sites tem um ranking, que quanto melhor a posição, mai visibilidade tem o site. Para melhorar a posição do ranking, podem ser utlizadas palavaras chave na arquitetura do site, dispositivos de segurança...


6. O uso de media query é obrigatório em todas as páginas?
    Não, mas é recomendado na maioria dos casos.


7. Qual a diferença entre CSS Inline e CSS em um arquivo?
    No CSS inline, as configurações de estilização são inseridas dentro da tag HTML, enquanto no CSS em arquivo temos a separação dos arquivos de HTML e CSS, sendo feito a estilização com base no nome da tag, classe ou Id.

8. Como criar animações no CSS? Dê um exemplo.
    As animações mais comuns são o transition, que define um efeito de transição quando ocorre mudanças de um elemento da pagina e hover que faz o efeito pré definido quando passa o mouse sobre o elemento configurado
    .container{
        background-color:#055
        transition: all easy 0.2;
    }
    .container:hover{
        babackground-color:#0bb;
    }
    Nesta animação os elementos da classe container terão uma animação de troca de cor de fundo quando o mouse for posicionado sobre o elemento.


9. Qual a diferença entre class e ID no CSS?
    ID pode ser utilizada em apenas um elemento do HTML, no CSS é referenciado como # antes do nome enquanto a class pode ser atribuida a varios elementos que compartilham a mesma estilização, referenciado com "." antes do nome.

10. Quais os diferentes tipos de seletores CSS?
    Existem varias possibilidades de seletores, os mais utilizados são:
    ID, seleciona o elemento unico do HTML, indicado por # antes do nome;
    class, pode selecionar varios elementos do HTML, indicado por '.' antes do nome;
    tipo, seleciona todos os item de determinado tipo, ex, h1, p, a ...;
    



## Projeto prático

O candidato deve criar a página da imagem a seguir:
![Layout](https://i.ibb.co/Bydq2FZ/screencapture-spotify-br-2022-05-10-15-13-17.png)

Algumas observações importantes:
- Fazer a página responsiva não é obrigatório, mas a apresentação dos elementos deve ser o mais próximo possível da imagem.
- Todas as imagens necessárias estão neste repositório, na pasta "assets".
- Efeitos de hover não são obrigatórios, mas são um plus.

O candidato deve estar atento para obedecer principalmente as cores corretas e tamanhos aproximados.
