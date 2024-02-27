5 camadas:

dominio/domain -> regra de negócio
dominio contém interfaces (ex: Authentication)

data layer -> implementação dos casos de uso
data layer contém classes que implementam o protocolo (ex: RemoteAuthentication que implementa Authentication)
data layer trata erros da api e trata resposta da api

infra -> onde fica implementações de frameworks externos

presentation -> camada de apresentação de dados

validation -> validações de dados

parei na aula 5


TESTES 
-sut -> system under tests