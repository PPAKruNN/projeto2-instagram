# projeto2-instagram
Instagram UI clone, project figma made by Driven bootcamp.


## Extras:
- [ ] REFAZER STORIES, ficaram ruins.
- [ ] Colocar Box-Shadow no stories-box.



## ✅ Requisitos
- Layout
    - [ ]  Aplicar layout para *desktop*, seguindo layout fornecido no Figma;
    - [ ]  Aplicar layout para *mobile*, seguindo layout fornecido no Figma;
    - [ ]  O layout sem *sidebar* deve ser ativado quando a largura da tela for menor que 935px;
    - [ ]  O layout para *mobil*e deve ser ativado quando a largura da tela for menor que 614px;
    - [ ]  Não é obrigatório que a *sidebar* fique fixa conforme o usuário desce na página como ocorre no Instagram (mas é um bônus).
- Ícones
    - [ ]  Utilize os ícones da biblioteca [Ionicons](https://ionicons.com/);
    
    💡A seção **Dicas** contém um tutorial para utilizar a biblioteca.
    
- Stories
    - [ ]  Deve haver, no modo *desktop*, uma setinha no canto direito dos *stories* (conforme mostrado no layout do Figma).
    - [ ]  A setinha não precisa funcionar ao clicar (só será possível quando vermos JavaScript).

## ✅ Bônus (opcional)
    - Stories
        - [ ]  Na caixa dos *stories*, deve haver itens o suficiente para ultrapassar a largura, mas os itens a mais não devem ser exibidos, conforme *layout*.
        - [ ]  Não pode haver um *scroll* horizontal visível.

    - Informações de curtidas nos post
        - [ ]  Desenvolver para *desktop e mobile*, seguindo layout bônus fornecido no Figma;
        
    - Vídeo
        - [ ]  Pelo menos um dos posts deve ser um vídeo;
        - [ ]  Não é necessário ter o botão de play;
        - [ ]  O vídeo deve ser inserido tanto no formato .mp4 e .ogg, para que funcione em qualquer navegador;
        - [ ]  O vídeo deve ser iniciado automaticamente;
        - (Para não incomodar o usuário, os navegadores (nem todos) não permitem que um vídeo toque automaticamente a não ser que o som esteja desativado.     
        Então, se colocou o atributo para iniciar o vídeo automaticamente e não funcionou, desative o som dele.)

    - Sidebar fixa
        - Se você acessar a página do Instagram do seu computador e descer na página, perceberá que a barra lateral continua visível, fixa na página;
        - A ideia deste bônus é implementar este comportamento, fazendo que, ao descer na página, a coluna permaneça no mesmo lugar sempre.
        
    - Comentários
        - Pelos propósitos do projeto, não adicionamos os comentários das postagens no *layout* do Figma. Estes são os requisitos deste bônus:
            - [ ]  Ter comentários nas postagens, com botão de *like* no canto direito em cada comentário;
            - [ ]  Uma caixa para digitar o comentário, utilizando a tag `input`;
            - [ ]  Um botão ao lado desta caixa para **Publicar**, com cor `#B2DFFC` inicialmente e, ao passar o mouse, fique com a cor `#0095F6` com uma transição que dura `300ms`. Procure pela propriedade *transition* para fazer isso