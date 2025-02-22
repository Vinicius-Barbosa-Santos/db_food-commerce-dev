## Deploy JSON Server to Vercel

A template to deploy [JSON Server](https://github.com/typicode/json-server) to [Vercel](https://vercel.com), allow you to run fake REST API online!

Demo from this repository: 

1. https://json-server-in.vercel.app
2. https://json-server-in.vercel.app/api/posts

![Powered by Vercel](https://images.ctfassets.net/e5382hct74si/78Olo8EZRdUlcDUFQvnzG7/fa4cdb6dc04c40fceac194134788a0e2/1618983297-powered-by-vercel.svg)

### How to use

1. Click "**Use this template**" or clone this repository.
2. Update or use the default [`db.json`](./db.json) in the repository.
3. Sign Up or login into [Vercel](https://vercel.com).
4. From the Vercel dashboard, click "**+ New Project**" then "**Import**" your repository.
5. In the "**Configure Project**" screen, leave everything default and click "**Deploy**".
6. Wait until deployment is done, and your own JSON server is ready to serve!

## Default `db.json`

```json
{
  "burgers": [
    {
      "id": 1,
      "snack": "burger",
      "name": "Mega",
      "description": "O artesanal tamanho família recheado com três carnes suculentas, queijo e bacon.",
      "price": 25.5,
      "image": "https://i.imgur.com/upjIUnG.jpg"
    },
    {
      "id": 2,
      "snack": "burger",
      "name": "Extra Bacon",
      "description": "Criado para os amantes de bacon, possui em todas as suas camadas bacon bem assado e ainda queijo e carne.",
      "price": 23.5,
      "image": "https://i.imgur.com/B4J04AJ.jpg"
    },
    {
      "id": 3,
      "snack": "burger",
      "name": "Tradicional",
      "description": "O simples também é delicioso, principalmente se envolver nossa carne artesanal e queijo.",
      "price": 12,
      "image": "https://i.imgur.com/Jz506jB.jpg"
    },
    {
      "id": 4,
      "snack": "burger",
      "name": "Big Carne",
      "description": "Uma carne artesanal de primeira qualidade com 4cm de altura e uma salada completa com alface, cebola, tomate e outros.",
      "price": 18.0,
      "image": "https://i.imgur.com/bF8EdBb.jpg"
    },
    {
      "id": 5,
      "snack": "burger",
      "name": "Carne dupla",
      "description": "Já pensou em comer aquele sanduíche com carne dupla e saborosa, recheada com queijo, molho e salada? Então você pensou exatamente nesse hambúrguer.",
      "price": 20,
      "image": "https://i.imgur.com/fdEY2kY.jpg"
    }
  ],

  "pizzas": [
    {
      "id": 1,
      "snack": "pizza",
      "name": "Calabresa",
      "description": "Pizza recheada com calabresa, cebola, mussarela, orégano e azeitona, tendo uma borda recheada com catupiry.",
      "price": 25,
      "image": "https://i.imgur.com/5rjJGkV.jpg"
    },
    {
      "id": 2,
      "snack": "pizza",
      "name": "Portuguesa",
      "description": "Pizza recheada com presunto, mussarela, ovo, cebola, azeitona, orégano, tomate e molho de tomate, tendo uma borda recheada com catupiry.",
      "price": 28.5,
      "image": "https://i.imgur.com/WCoyGoI.png"
    },
    {
      "id": 3,
      "snack": "pizza",
      "name": "Frango com Catupiry",
      "description": "Pizza recheada com frango, catupiry e brócolis, tendo uma borda recheada com catupiry.",
      "price": 24,
      "image": "https://i.imgur.com/BuXrO8d.jpg"
    },
    {
      "id": 4,
      "snack": "pizza",
      "name": "Napolitana",
      "description": "Pizza recheada com queijo, mussarela, tomate e couve, tendo uma borda recheada com catupiry.",
      "price": 30,
      "image": "https://i.imgur.com/u3DfvCE.jpg"
    },
    {
      "id": 5,
      "snack": "pizza",
      "name": "Mussarela",
      "description": "Pizza recheada com mussarela, tendo uma borda recheada com catupiry. ",
      "price": 20.5,
      "image": "https://i.imgur.com/kPNXpa0.jpg"
    },
    {
      "id": 6,
      "snack": "pizza",
      "name": "Marguerita",
      "description": "Pizza recheada com calabresa, mussarela, cebola, azeitona e orégano, tendo uma borda recheada com catupiry.",
      "price": 25.5,
      "image": "https://i.imgur.com/AsEfsZN.jpg"
    },
    {
      "id": 7,
      "snack": "pizza",
      "name": "Brigadeiro com Morango",
      "description": "Pizza doce recheada com brigadeiro e morango.",
      "price": 35.0,
      "image": "https://i.imgur.com/43yC2Ap.jpg"
    },
    {
      "id": 8,
      "snack": "pizza",
      "name": "Banana",
      "description": "Pizza doce recheada com banana e leite condensado.",
      "price": 33.5,
      "image": "https://i.imgur.com/Pcrgg1P.jpg"
    },
    {
      "id": 9,
      "snack": "pizza",
      "name": "Chocolate",
      "description": "Pizza doce recheada com chocolate e bolinhas de chocolate.",
      "price": 30,
      "image": "https://i.imgur.com/RahAKkH.jpg"
    }
  ],

  "drinks": [
    {
      "id": 1,
      "snack": "drink",
      "name": "Coca-Cola 2L",
      "description": "A tradicional Coca-Cola que a família brasileira adora.",
      "price": 12,
      "image": "https://i.imgur.com/Lg3aKhf.jpg"
    },
    {
      "id": 2,
      "snack": "drink",
      "name": "Guaraná Antarctica",
      "description": "O irresistível e saboroso Guaraná Antarctica em sua versão de latinha.",
      "price": 6.5,
      "image": "https://i.imgur.com/hOBrOIm.jpg"
    },
    {
      "id": 3,
      "snack": "drink",
      "name": "Suco de Abacaxi",
      "description": "Suco natural de abacaxi com leves incrementos de algumas hortaliças para fortificar sua saúde.",
      "price": 8,
      "image": "https://i.imgur.com/VV9qTMh.jpg"
    },
    {
      "id": 4,
      "snack": "drink",
      "name": "Suco de Laranja",
      "description": "Suco natural de laranja para você que é amante dessa fruta.",
      "price": 8,
      "image": "https://i.imgur.com/2Lf2gHy.jpg"
    }
  ],

  "ice-creams": [
    {
      "id": 1,
      "snack": "ice-cream",
      "name": "Casquinha",
      "description": "A casquinha crocante e saborosa que nossos clientes amam.",
      "price": 4.5,
      "image": "https://i.imgur.com/YGmeoCm.jpg"
    },
    {
      "id": 2,
      "snack": "ice-cream",
      "name": "Chocolate com granulado",
      "description": "Sorvete de chocolate com granulados em chocolate para você se deliciar.",
      "price": 6,
      "image": "https://i.imgur.com/osAHOLe.jpg"
    },
    {
      "id": 3,
      "snack": "ice-cream",
      "name": "Flocos",
      "description": "O tradicional flocos vem com cobertura em chocolate para adocicar seu dia.",
      "price": 7,
      "image": "https://i.imgur.com/qgnFLiy.jpg"
    },
    {
      "id": 4,
      "snack": "ice-cream",
      "name": "Creme",
      "description": "O simples sorvete de creme com um gosto irresistível.",
      "price": 6.5,
      "image": "https://i.imgur.com/dFLysrT.jpg"
    },
    {
      "id": 5,
      "snack": "ice-cream",
      "name": "Morango",
      "description": "O clássico sorvete de morango que deixe tudo mais leve.",
      "price": 10,
      "image": "https://i.imgur.com/0TWnEI7.jpg"
    }
  ]
}

```

## Enable write operations

By default, only GET operation is allowed, thanks to the contribution by [@VicAv99](https://www.github.com/VicAv99) at [#6](https://github.com/kitloong/json-server-vercel/issues/6), we can now enable write operations as well.

You can find the example code in [`api/server.js`](./api/server.js).

## Reference

1. https://github.com/typicode/json-server
2. https://vercel.com
3. https://shadowsmith.com/how-to-deploy-an-express-api-to-vercel
