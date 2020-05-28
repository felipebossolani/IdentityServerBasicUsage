# Projeto IdentityServer - Uso Básico

Projeto contém o necessário para subir uma aplicação MVC utilizando um servidor de SSO em IdentityServer. 
Projeto feito para estudos. **Não utiliza-lo em ambientes produtivos!!**

# Utilização do Repositório

Baixe o repo através do git clone:
```
git clone https://github.com/felipebossolani/IdentityServerBasicUsage.git
```
E depois os seguintes comandos:
```
cd IdentityServerBasicUsage
start IdentityServerBasicUsage.sln
```

Com o Visual Studio aberto apenas de um run que os dois projetos irão ser executados. 
Caso não utilize o Visual Studio então você precisará de duas linhas de comando. 
Na primeira:
```
cd acme.sso
dotnet run
```
Na segunda:
```
cd acme.mvc
dotnet run
```

O SSO está na porta 5001 e o MVC na porta 5003. 
Você precisa criar um SSL local para os testes:
```
dotnet dev-certs https --trust
```
[Referência](https://www.hanselman.com/blog/DevelopingLocallyWithASPNETCoreUnderHTTPSSSLAndSelfSignedCerts.aspx)
