<h1>Soal No.1 : Profile Skiljek</h1>

```js
{
"_id": "ObjectId('ABC')",
"full_name": "Nurul Trisna Aulya",
"email": "aulyaatn@gmail.com",
"phone_number": 0889********
}
```

<h1>Soal No.2 : Profile Skilshop</h1>
<h2>Relasi One-to-Many</h2>

```js
{
    "_id": "ObjectId('CBA')",
    "full_name": "Nurul Trisna Aulya",
    "phone_mumber": 0889********
    "address": [
        "ObjectId('OLE')",
        "ObjectId('WDM')",
    ]
}
```

<h1>Soal No.3</h1>
<h2>Relasi One-to-One</h2>

```js
{
    "_id": "ObjectId('ABA')",
    "product_name": "Shirt",
    "brand_name": "SkilShirt",
    "variant": [{
        "_id": "ObjectId('BAB')",
        "variant_name_1": "Shirt Blousse",
        "color": "White",
        "quantity": 14,
        "price": "Rp 120.000",
    },{
         "_id": "ObjectId('CAC')",
        "variant_name_2": "Shirt Navy Piece",
        "color": "Navy",
        "quantity": 20,
        "price": "Rp 150.000",
    }]
}
```

<h1>Soal No.4</h1>
<h2>Relasi One-to-Many</h2>

```js
[
    {
    "_id": "ObjectId('SKV')",
    "cinema_name": "Fantasy Jam",
    "film": [
        "ObjectId('Harry Potter and the Goblet of Fire')",
        "ObjectId('Harry Potter and the Cursed Child')"
    ],
    "location": "Tangerang"
    },
    {
    "_id": "ObjectId('VKS')",
    "cinema_name": "Horror Time 10",
    "film": [
        "ObjectId('The Conjuring')",
        "ObjectId('The Shining')"
    ],
     "location": "Bandung"
    }
]
```
