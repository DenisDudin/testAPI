testAPI

POST https://blog.kata.academy/api/users

Registration:

{
"user": {
"username": "denisdudin",
"email": "iversuss@yandex.ru",
"token": "eyJhbGciOiJIUzI1NiIsInR5cCI6IkpXVCJ9.eyJpZCI6IjY0NGI4ZGJhNjBjNjc1MWIwMGI3NmQ0YyIsInVzZXJuYW1lIjoiZGVuaXNkdWRpbiIsImV4cCI6MTY4Nzg1NzA4MiwiaWF0IjoxNjgyNjczMDgyfQ.np9Mli4dY4SVwVdaGEkfEfO2LmL1DaVCsYM5Z5KzsJA"
}
}

POST https://blog.kata.academy/api/users/login

Authentication:

{
"user": {
"username": "denisdudin",
"email": "iversuss@yandex.ru",
"token": "eyJhbGciOiJIUzI1NiIsInR5cCI6IkpXVCJ9.eyJpZCI6IjY0NGI4ZGJhNjBjNjc1MWIwMGI3NmQ0YyIsInVzZXJuYW1lIjoiZGVuaXNkdWRpbiIsImV4cCI6MTY4Nzg1NzIyNiwiaWF0IjoxNjgyNjczMjI2fQ.cnsdsJtM-Qc_RNaTfIU_WkaQX9yQzC9WV0AcM-wVVDk"
}
}

POST https://blog.kata.academy/api/profiles/denisdudin

Get User:

{
"profile": {
"username": "denisdudin",
"image": "https://static.productionready.io/images/smiley-cyrus.jpg",
"following": false
}
}
