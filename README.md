# Boletim

Baseado na aplicação [substack](https://substack.com/) os usuários terão um inbox em que poderam se inscrever em suas categorias de boletins informativos favoritas, que é mantido por criadores de contéudo que atualizam seus inscritos sobre os principais topicos 
que aconteceram durante a semana ou dia, por exemplo, para usuários que gostam de tecnologia, eles podem increver-se em boletins informativos mantido por criadores que falam sobre tecnologia e receber atualizões

Para executar este projeto siga os passos descritos no arquivo [passo-a-passo](passo-a-passo.md)

## Membros da equipe

André Torquato, 501740, Sistemas de Informação

## Papéis ou tipos de usuário da aplicação

- Usuário
- Criador

## Entidades ou tabelas do sistema

- Usuário
- Criador
- Boletim

## Principais funcionalidades da aplicação

- O usuário pode inscrever-se em algum boletim informativo e receber atualizações de criadores
- Um criador pode criar um boletim informativo e enviar atualizações para os usuários

## Tecnologias e frameworks utilizados

**Frontend:**

- VueJS v3.0, Vue-Router e Pinia.
- Axios

**Backend:**

- Strapi


## Operações implementadas para cada entidade da aplicação


| Entidade| Criação | Leitura | Atualização | Remoção |
| --- | --- | --- | --- | --- |
| Usuário |  | x |  |  |
| Criador | X  | X |  X | X |
| Boletim | X |  X  |  |  |

> Lembre-se que é necessário implementar o CRUD de pelo menos duas entidades.

## Rotas da API REST utilizadas

| Método HTTP | URL |
| --- | --- |
| GET | - |
| POST | - |
| PUT | - |
| DELETE | - |
