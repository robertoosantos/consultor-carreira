# consultor-carreira
Agente de inteligência artificial como consultor de carreira desenvolvido no curso de IA Generativa na Era da Transformação Digital no MIT

## Como Utilizar?

### Via chat

Acesse: [https://robertos.app.n8n.cloud/webhook/096601ba-fce4-4951-b7d0-0c41a1a9ef9d/chat](https://robertos.app.n8n.cloud/webhook/096601ba-fce4-4951-b7d0-0c41a1a9ef9d/chat)

### Via workflow n8n

#### Requisitos
1. Possuir uma conta na plataforma [n8n](https://n8n.io/)
2. Possuir uma conta na plataforma [DeepSeek](https://platform.deepseek.com/)
3. Possuir uma conta no serviço de banco de dados NoSQL [MongoDB](https://www.mongodb.com/)

#### Etapas
1. Crie um novo _workflow_ no n8n
2. Neste repositório, acesse o arquivo [agente-n8n-consultor-carreira.json](agente-n8n-consultor-carreira.json)
3. Copie (CTRL+C) seu conteúdo
4. Cole (CTRL+V) o conteúdo no _workflow_ criado na etapa anterior
5. Note que os elementos do DeepSeek e MongoDB estão sinalizados em vermelho.
6. Clique duas vezes no componente do DeepSeek e siga esse [passo-a-passo](https://docs.n8n.io/integrations/builtin/credentials/deepseek/?utm_source=n8n_app&utm_medium=credential_settings&utm_campaign=create_new_credentials_modal) para criar uma nova conexão (_create new credential_)
7. Utilize essa conexão nos demais componentes do DeepSeek
8. Clique duas vezes no componente do MongoDB e siga esse [passo-a-passo](https://docs.n8n.io/integrations/builtin/credentials/mongodb/?utm_source=n8n_app&utm_medium=credential_settings&utm_campaign=create_new_credentials_modal) para criar uma nova conexão (_create new credential_)
9. Na barra superior do _workflow_ ative-o clicando no botão próximo ao texto _Inactive_
10. Clique duas vezes no componente com o nome: **Interface de Usuário**
11. Copie o _Chat URL_
12. Cole num navegador e comece a interagir com o agente de IA
