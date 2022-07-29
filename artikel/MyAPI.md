# API POINTS #
## BIODATA ##
*Menampilkan data semua pengguna*
```
GET: /biodata

response:

[
  {
    "id"       : "",
    "avatar"   : "",
    "nama"     : "",
    "des"      : "",
    "about"     : "",
  },
  
]
```
*Menampilkan data dengan id tertentu*
```
GET: /biodata/[id]

response :

{
    "id"       : "",
    "avatar"   : "",
    "nama"     : "",
    "des"      : "",
    "about"     : "",
}
```
*Menambahkan data pengguna*
```
POST: /biodata

data:
{
    "id"       : "",
    "avatar"   : "",
    "nama"     : "",
    "des"      : "",
    "about"     : "",
}
response:

true    // if success
false   // if failure
```
*Edit data pengguna*
```
PUT: /biodata

data:
{
    "id"       : "",
    "avatar"   : "",
    "nama"     : "",
    "des"      : "",
    "about"     : "",
}
  
response:
true    // if success
false   // if failure
```
*Menghapus data anggota*
```
DELETE: /biodata

response:
true    // if success
false   // if failure
```
## ARTICLE ##
*Menampilkan data semua article*
```
GET: /article

response:
[
  {
     "id"           : "",
     "title"        : "",
     "author"       : "",
     "markdown"     : "",
     "content"      : "",
     "thumbnail"    : "",
  }
]
```
*Menampilkan data article dengan id tertentu*
```
GET: /article/[id]

response:
{
     "id"           : "",
     "title"        : "",
     "author"       : "",
     "markdown"     : "",
     "content"      : "",
     "thumbnail"    : "",
}
```
*Menambahkan article*
```
POST: /article

data:
{
     "id"           : "",
     "title"        : "",
     "author"       : "",
     "markdown"     : "",
     "content"      : "",
     "thumbnail"    : "",
}
response :
true    // if success
false   // if failure
```
*Memperbarui article*
```
PUT: /article

data:
{
     "id"           : "",
     "title"        : "",
     "author"       : "",
     "markdown"     : "",
     "content"      : "",
     "thumbnail"    : "",
}

response:
true    // if success
false   // if failure
```
*Menghapus article*
```
DELETE: /article/[id]

response:
true    // if success
false   //if failure
```
