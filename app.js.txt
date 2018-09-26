var express = require('express');
var app = express();

app.get("/", function(req,res){
  res.send("<h1>Welcome to our first app</h1>")
});

app.listen(process.env.PORT||3500, function () {
    console.log("server is listening on port 3000");
});