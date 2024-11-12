# Relatório Final

Nome: Manuella Filipe Peres
RA: 22.224.029-3

# Introdução

Este relatório apresenta o desenvolvimento e os resultados do projeto realizado para a disciplina CCP4670. O projeto consiste na criação de um aplicativo em React Native, abordando o tema de um software de músicas, onde o usuário poderá acessar suas músicas e playlists preferidas. O aplicativo visa permitir ao usuário se registrar, logar, criar uma nova playlist, acessar uma playlist já existente, adicionar novas músicas à playlist escolhida, removê-las, assim como acessar a aba de recomendações, onde ele poderá escutar a música (por meio do redirecionamento no YouTube) e adicioná-la na playlist de seu gosto, o público alvo são todos os amantes da música, que desejam conhecer novas músicas e ter suas playlists particulares para escutá-las no momento que quiserem.

# Motivação

A escolha por desenvolver um aplicativo sobre um software de músicas surgiu a partir da ideia de eu ser uma grande amante de música, o que me inspirou a criar esse aplicativo para que eu possa salvar todas minhas músicas preferidas em playlists personalizadas para mim, além de acessar recomendações que eu posso escutar e ver se gosto, assim, adicionando-as nas minhas playlists.
Música sempre foi algo que me deixou menos ansiosa, portanto, um aplicativo de música é algo que me deixaria mais calma por ter minhas músicas preferidas ao meu lado em todos os momentos, desestressando e além disso, tendo uma sensação de particularidade para minhas playlists.

# Objetivo

O objetivo principal deste projeto é desenvolver um aplicativo mobile funcional em React Native que possui a opção de se registrar ou logar em um aplicativo de músicas, quando logado, o usuário vai para a aba de playlists, onde serão listadas todas as playlists salvas na memória da conta do usuário, ele pode escolher uma playlist específica e nela, adicionar, remover ou escutar a música por meio do redirecionamento no YouTube, além disso, o usuário pode remover uma playlist caso deseje. Na aba "recomendações", podemos ver algumas músicas pré-selecionadas que o usuário pode escutar clicando no link que irá levá-lo para seu respectivo redirecionamento no YouTube, assim, caso ele goste pode escolher uma playlist que mais se adeque à música e adicioná-la rapidamente à playlist escolhida.

Além disso, o projeto busca:
Implementar funcionalidades como [cadastro, login, adição de música, remoção de música e playlist, redirecionamento para o YouTube, adição de imagens na capa da música de acordo com seu índice, e vibração ao clicar em botões, além disso, utilizamos o AsyncStorage para salvar as informações em uma espécie de banco de dados]. Todas essas funcionalidades visam a melhor experiência ao usuário, visando um design interessante e fácil de utilizar.

# Funcionalidades

O aplicativo desenvolvido conta com as seguintes funcionalidades:

[Cadastro e Login]: [Permite que o usuário se registre ou faça login no aplicativo para acessar suas playlists e recomendações personalizadas.]
[Adicionar e Remover Músicas]: [O usuário pode adicionar músicas às playlists ou removê-las conforme desejar, mantendo a biblioteca organizada.]
[Redirecionamento para o YouTube]: [Ao selecionar uma música, o usuário é redirecionado para o YouTube para ouvi-la diretamente na plataforma.]
[Gerenciamento de Playlists]: [O usuário pode criar novas playlists, adicionar músicas a playlists existentes, ou remover playlists e músicas quando desejar.]
[Recomendações de Músicas]: [Exibe uma lista de músicas pré-selecionadas que o usuário pode ouvir no YouTube e adicionar às suas playlists favoritas.]
[Imagens na capa das músicas]: [Pega o índice da música e adiciona uma foto ao lado dela com o número respectivo da música.]
[Vibração em Botões]: [Ao clicar nos botões do aplicativo, o celular vibra, melhorando a experiência de interação.]
[Armazenamento com AsyncStorage]: [As informações de playlists e músicas são salvas no AsyncStorage, funcionando como um banco de dados.]

# Conclusão

A partir do desenvolvimento deste projeto, foi possível atingir meu principal objetivo que é entender mais sobre React.Js e desenvolvimento de aplicativos, além de aprender com as funcionalidades implementadas pude melhorar minha lógica de programação. Os principais desafios foram implementar a lógica de redirecionamento pro youtube pois demorei para ter uma solução para o problema, posteriormente implementando o nome da música no link de pesquisa do YouTube e assim, deu tudo certo no final.
Um dos melhores aprendizados foi como aprimorar meus conhecimentos em JavaScript com React.js, além do desenvolvimento de aplicativos, conhecimento essencial para o mercado de trabalho atualmente, onde o mundo dos aplicativos está cada vez mais crescendo.
Algumas melhorias que poderiam ser implementadas seriam o estudo da implementação de músicas no AsyncStorage em vez do redirecionamento, fazendo o usuário acessar a música diretamente do aplicativo.
Essas ideias com certeza serão implementadas no futuro visando o desenvolvimento do meu conhecimento de React.JS para que eu aprimore cada vez mais minhas habilidades.
Gostaria de agradeçer aos professores Isaac Jesus e Luciano Rossi pela oportunidade de aprender uma linguagem tão moderna e atual no mercado, me permitindo aprimorar minhas soft e hard skills com o projeto.

# Imagens do projeto

Tela de carregamento

![image](https://github.com/user-attachments/assets/7c8fa7c0-8d88-4a1a-83ce-6145609ace10)

Registrar

![image](https://github.com/user-attachments/assets/8fc67d32-b2ac-4ec9-9198-1d1d66fa06ac)

Login

![image](https://github.com/user-attachments/assets/0c949e4f-7bf5-49ba-be6a-42e12330856b)

Tela de playlists com todas salvas no AsyncStorage


![image](https://github.com/user-attachments/assets/870fb7fa-87b4-4b1d-acd9-67b7e5d464fa)



Excluindo uma das playlists

![image](https://github.com/user-attachments/assets/565d5e5a-d3b2-4275-9fec-3806e9c8a939)


Tela de criar playlist

![image](https://github.com/user-attachments/assets/761ef1a2-5584-4c0c-82c8-8ce6022ae94d)

Adicionando nova playlist

![image](https://github.com/user-attachments/assets/af9b59d7-2e07-4148-b3b7-b943095026b9)

Clicando na playlist especifica

![image](https://github.com/user-attachments/assets/a7fa46da-fb58-4ce0-9bbf-4787072d66bd)

Clicando no redirecionamento pro youtube

![image](https://github.com/user-attachments/assets/701889f4-3593-4e44-a009-7a63b51019a6)

Adicionando nova musica

![image](https://github.com/user-attachments/assets/7327a7f8-4fae-49ce-b589-bc5ef982d697)

Após adicioná-la

![image](https://github.com/user-attachments/assets/69451ccb-5ca1-4148-add9-098927e8bd15)

Retirando a música

![image](https://github.com/user-attachments/assets/c7128b7b-8c61-4410-a7af-2d4c57fe0882)


Tela de recomendações

![image](https://github.com/user-attachments/assets/b93dd479-44d2-4622-ab8c-8f03b22f9311)


Selecionando uma playlist

![image](https://github.com/user-attachments/assets/a0920dfb-3c6c-4bb7-8163-02b287e9c03a)


Após adicioná-la

![image](https://github.com/user-attachments/assets/28426458-8861-44c7-ab5f-7c96ea6e17d9)
