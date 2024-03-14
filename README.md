# Repositório dos Exercícios de Python da Squad Mae C. Jemison do Bootcamp Back-end Python e Django

## SQUAD MAE C. JEMISON - Desafio Rick e Morty

Este repositório contém os exercícios de Python da Squad Mae C. Jemison, parte do Bootcamp Back-end Python e Django.

```
projeto/
│
├── app/
│   ├── config/
│   │   └── config.py
│   ├── controller/
│   │   └── controllers.py
|   |── doc/
│   │   └── Explicacao_desafio.pdf
|   └── static/
│   |   ├── style.css
│   |   └── images
|   |        └── rick_and_morty_background.jpg
|   └──── templates/
|   |       ├── episodes.html
|   |       ├── episode.html
|   |       ├── locations.html
|   │       └── location.html
|   └── app.py
├── README.md
└── requirements.txt
```

### _Membros da Squad:_

- Ana Paula Martins Braga | [apmbraga](https://github.com/apmbraga)
- Angela Filomena | [anbaptista](https://github.com/anbaptista/)
- Daniele Ferreira Galvão | [DanieleFG](https://github.com/DanieleFG)
- Indhira Viana Freire | [Indhira Viana](https://github.com/Indy-electro)
- Manuele Maurício Lamenha | [Manu](https://github.com/Manu3052)
- Millena Figueredo | [MildePaula](https://github.com/MildePaula)
- Quesia De Araújo Santos | [quesia-araujo](https://github.com/quesia-araujo)
- Siomara Mota | [siomara777](https://github.com/siomara777)
- Tamar Bender | [tamarbender](https://github.com/tamarbender)
- Yohanna Oliveira Cavalcanti | [8b1tz](https://github.com/8b1tz)

### _Resolução dos Desafios:_

A resolução dos desafios foi realizada através de comunicação no Discord, reuniões no Google Meet e divisão de tarefas entre os membros da squad.

- **21/02:** Primeira reunião para resolução de exercícios, definição de horários e divisão de tarefas.
- **Até a data de entrega:** Comunicação contínua no Discord, troca de informações, esclarecimento de dúvidas e colaboração mútua.

Valorizamos o trabalho em equipe e a criação de um ambiente cooperativo para garantir um aprendizado eficaz e uma experiência gratificante para todas as participantes.

### _Como excutar:_

### Clonar o repositório

Clone o repositório utilizando o seguinte comando:

```
git clone https://github.com/8b1tz/desafio_rick_and_morty
```

### Crie um ambiente virtual

```
python -m venv .venv
```

### Ative o ambiente virtual

```
.venv\Scripts\activate
```

### Instale as dependências dentro do requirements.txt

```
pip install -r requirements.txt
```

### Entre no diretório correto :D

```
cd app
```

### Rode o Flask :D

```
flask --app app run
```


### Telas:

#### /home
<img src="https://github.com/8b1tz/desafio_rick_and_morty/assets/53948477/fb3706a9-4967-43d0-9c77-990549a34b6e" width="500">

- A tela /home representa a página inicial do aplicativo, onde os usuários são recebidos ao acessar a plataforma. Esta tela pode incluir informações sobre o universo de Rick and Morty, destaques de episódios ou uma visão geral das últimas aventuras.

#### /episodes 
<img src="https://github.com/8b1tz/desafio_rick_and_morty/assets/53948477/0eacd94e-9d07-42b5-a831-fbb9ff431a56" width="500">

- A tela /episodes exibe uma lista de episódios disponíveis da série Rick and Morty. Os usuários podem explorar e descobrir novos episódios nesta página. Dependendo da implementação, pode haver opções de filtro ou ordenação para ajudar os usuários a encontrar os episódios desejados.

#### /episode/{id} 
<img src="https://github.com/8b1tz/desafio_rick_and_morty/assets/53948477/138fe046-b2a0-405e-9190-bef4033e8896" width="500">

- A tela /episode/{id} exibe informações detalhadas sobre um episódio específico da série Rick and Morty, identificado pelo seu ID. Os usuários podem encontrar detalhes como título do episódio, sinopse, data de lançamento, entre outros.

#### /profiles
<img src="https://github.com/8b1tz/desafio_rick_and_morty/assets/53948477/659a89b7-1462-446f-b6db-df270269101e" width="500">

- A tela /profiles exibe uma lista de perfis de personagens da série Rick and Morty. Os usuários podem explorar e descobrir informações sobre diferentes personagens nesta página.

#### /profile/{id}
<img src="https://github.com/8b1tz/desafio_rick_and_morty/assets/53948477/aa4b0fa1-a333-4aa7-9b4a-a0aeebda0224" width="500">

- A tela /profile/{id} exibe informações detalhadas sobre um personagem específico da série Rick and Morty, identificado pelo seu ID. Os usuários podem encontrar detalhes como nome, status, espécie, entre outros.

#### /locations
<img src="https://github.com/8b1tz/desafio_rick_and_morty/assets/53948477/78712e0d-2468-48a1-bace-56843ebef6c2" width="500">

- A tela /locations exibe uma lista de locais da série Rick and Morty. Os usuários podem explorar e descobrir informações sobre diferentes locais nesta página.

#### /location/{îd}
<img src="https://github.com/8b1tz/desafio_rick_and_morty/assets/53948477/0bb098ab-3993-487c-9808-9d6d86671ca3" width="500">

- A tela /location/{id} exibe informações detalhadas sobre um local específico da série Rick and Morty, identificado pelo seu ID. Os usuários podem encontrar detalhes como nome, tipo, dimensão, entre outros.


