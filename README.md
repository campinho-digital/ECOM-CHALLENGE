#### Em uma cidade vibrante chamada Innoville, onde a inovação era a linguagem principal e a busca por tecnologia de ponta impulsionava os corações e mentes dos habitantes. Nesse cenário empolgante, nasceu a TechTreasures, uma empresa fundada por visionários apaixonados pela fusão de tecnologia e estilo de vida. A TechTreasures tinha uma missão clara: tornar as últimas inovações tecnológicas acessíveis a todos, transformando o cotidiano das pessoas com produtos que uniam funcionalidade, design e experiência excepcional.

<img width="663" alt="Captura de Tela 2023-10-13 às 19 00 26" src="https://github.com/campinho-digital/ECOM-CHALLENGE/assets/108235987/24ed1d68-0106-4980-8851-a7b316f3a6b0">


 #### A história começou quando os fundadores, Alice e David, perceberam a lacuna no mercado local. Apesar do desejo por dispositivos e gadgets inovadores, muitos habitantes de Innoville não tinham acesso fácil a esses tesouros tecnológicos. Determinados a mudar isso, Alice e David decidiram criar a TechTreasures, uma loja online que traria o futuro diretamente para a porta das casas.




#### Para esse desafio você dará forma a TechTreasures, inicialmente desenvolvemos as páginas iniciais desse ECommerce para termos um MVP para apresentar a Alice e David. O desafio conta com dois sistemas, um no qual você terá que criar uma interface para os usuários e outro na qual a interface será destinada a Alice e David para que eles coloquem novos produtos para os clientes. 

#### O time de Design da TechTreasures deixou disponivel o layout para a criação do MVC 

<img width="457" alt="Captura de Tela 2023-10-13 às 19 09 17" src="https://github.com/campinho-digital/ECOM-CHALLENGE/assets/108235987/d2a081b0-ebee-4f0b-b374-43b69f33ac20">

<img width="419" alt="Captura de Tela 2023-10-13 às 19 02 05" src="https://github.com/campinho-digital/ECOM-CHALLENGE/assets/108235987/57d397dd-7b3a-4609-9d3f-6b2eea596d0d">

<img width="422" alt="Captura de Tela 2023-10-13 às 19 03 29" src="https://github.com/campinho-digital/ECOM-CHALLENGE/assets/108235987/c6836f41-62df-4d53-a1b7-c01fad1e50d3">

<img width="530" alt="Captura de Tela 2023-10-13 às 19 15 00" src="https://github.com/campinho-digital/ECOM-CHALLENGE/assets/108235987/19653ea7-34c3-4abd-a16e-475d799e6f30">


#### Você terá que desenvolver:
- Uma página de login e uma de registro
- Uma página que liste os produtos para que os clientes possam acessar
- Uma página de detalhe de cada produto
- Uma página de Adm que seja possível adicionar novos produtos a loja
  
#### Será um diferencial:
- Implementar o carrinho para que o cliente possa adicionar produtos que ele dejesa


#### Categorias:
O time de negócio definiu as seguintes categorias, ou seja os produtos adicionados precisam fazer parte de uma delas:
- Casa Inteligente
- Eletrônico
- Esportes
- Gadgets de Viagem
- Saúde e Bem-Estar
- Tecnologia para o Trabalho Remoto
- Áudio e entretenimeto

#### A API da TechTreasures ja foi desenvolvida e conta com a seguinte documentação: 



Para criar um novo usuario: 
`api/auth/local/register`

~~~JSON
{
  "username": "campinho",
  "email": "campinho@mail.com",
  "password": "campinho1234"
}

~~~


Para garantir troca segura de informações entre partes em um formato que pode ser verificado e confiável o registro gerará um token JWT :
- JWT (JSON Web Token) é um padrão aberto (RFC 7519) que define uma maneira compacta e autocontida de representar informações entre duas partes de uma forma que pode ser verificada e validada.

####  Atenção: para acessar os demais endpoints como o `/products` será preciso sempre estar autenticado.


### Para acessar os produtos
`api/products`

~~~JSON
{
  "username": "campinho",
  "email": "campinho@mail.com",
  "password": "campinho1234"
}

~~~

- O JWT deverá ser passado no Header (Cabeçalho): Contém informações sobre como o JWT é codificado, como o tipo de token e o algoritmo de assinatura usado:
<img width="1014" alt="Captura de Tela 2023-10-13 às 18 56 00" src="https://github.com/campinho-digital/ECOM-CHALLENGE/assets/108235987/f9374bf8-fcda-4c49-97a9-d46ed7d7c846">









