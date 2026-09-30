Arquitetura da solução : veja a figura "arquitetura.png"
Tecnologia escolhida: JWT
como executar os serviços: suba config-server, eureka-server e gateway. Suba depois auth-service e em seguida os outros serviços. Utilize os endpoints.
como realizar autenticação: utilizar o endpoint "auth-service/usuarios/login", fornecendo email e senha.
endpoints públicos: "/auth-service/usuarios/login", "/auth-service/usuarios"
endpoints protegidos: "/clientes-service/clientes", "/produtos-service/produtos", "/produtos-service/produtos/{id}",
"/vendas-service/vendas" (get ou post)


