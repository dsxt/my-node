let http = require('http');
let server = http.createServer(function(request,response){
    console.log('有人访问了');
    response.write('来了来了');
    response.end();
})
server.listen(8088);