Setelah menjalankan server dengan npm run start, lakukan command berikut pada terminal/CMD/Gitbash :

curl -X GET http://localhost:5000/hello/dicoding?lang=id
// output: {"message":"Hai, dicoding"}
curl -X GET http://localhost:5000/hello/dicoding
// output: {"message":"Hello, dicoding"}