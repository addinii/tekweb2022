API POINTS
Adapun api point yang saya bangun untuk portfolio saya di artikel

Artikel
Menampilkan seluruh Artikel
GET: /Artikel

response:
[
{
"id": "",
"avatar": "",
"nama": "",
"des": "",
"about": ""
}
{
...
}
]
Menampilkan Artikel berdasarkan id
GET: /Artikel/[id]

response:
{
"id": "",
"avatar": "",
"nama": "",
"des": "",
"about": ""
}
Menambahkan Artikel
POST: /Artikel

data:
{
"id": "",
"avatar": "",
"nama": "",
"des": "",
"about": ""
}

response:
true //if true
false //if false
Mengubah Artikel
PUT: /Artikel

data:
{
"id": "",
"avatar": "",
"nama": "",
"des": "",
"about": ""
}

response:
true //if true
false //if false
Menghapus Artikel
DELETE: /Artikel

response:
true //if true
false //if false
