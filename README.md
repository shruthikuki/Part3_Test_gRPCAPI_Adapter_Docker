# Part3_Test_gRPCAPI_Adapter

The docker compose bundle runs two containers: 
grpc container which runs the Test Grpc server and responsible for sharing the main.proto file using volumes and the other adapter container which adapter server on tomcat.

We make use of WinForms-based HTTP Client “I’m Only Resting” as the means of a test script to access the Test gRPC API via the JSON Adapter API
