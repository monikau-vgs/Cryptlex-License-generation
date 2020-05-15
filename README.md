# nodejs-license-generator
An example Node.js app which handles license generation and renewal

1.npm install
2.npm start
3.Goto Postman ->set url=localhost:3002/license
                 method=post,
                 set authentication bearer token which is created using cryptlex.
                    process for creating token:-Cryptlex docs->api->personal access token->generate token successfully.

                request body:{
                    {
                        "email":"ukirdemonika19@gmail.com",
                        "first_name":"Monika",
                        "last_name":"Ukirde", 
                        "order_id":"01"
                    }

                    response:=Generate license key.(got the license key)
                

