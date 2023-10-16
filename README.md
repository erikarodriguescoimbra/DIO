# DIO
ProjetoETL 📈



[<img src="https://media.licdn.com/dms/image/C4D12AQEAbubuyDdt4A/article-cover_image-shrink_600_2000/0/1594949995585?e=2147483647&v=beta&t=C3wqaJJ-KB-BdYeRoSVW-WwSEjefcS7fP2GdAnINv7A" width="100">](URL_DO_SEU_NOTEBOOK_NO_COLAB)

Contexto: Você é um cientista de dados no Santander e recebeu a tarefa de envolver seus clientes de maneira mais personalizada. Seu objetivo é usar o poder da IA Generativa para criar mensagens de marketing personalizadas que serão entregues a cada cliente.
Começando a ETL:
Fiz uma tabela CSV com esses dados: 
UserID
5166
5167
5168
Me foi dado o endpoint GET:
- [https://sdw-2023-prd.up.railway.app/users/{id}](https://sdw-2023-prd.up.railway.app/users/{id})

    
(API da Santander Dev Week 2023) para obter os dados de cada cliente. O professor sugeriu que poderíamos fazer os cadastros dos clientes que usaríamos fiz 3. 
Foi feito o cadastro e visualizado os clientes,usei a API do ChatGPT (OpenAI) para gerar uma mensagem de marketing personalizada para cada cliente. Executei duas mensagens, a última queria que fosse algo divertido.
     A mensagem para cada cliente ficou pronta, você vai enviar essas informações de volta para a API, atualizando a lista de "news" de cada usuário usando o endpoint PUT 
[https://sdw-2023-prd.up.railway.app/users/{id}](https://sdw-2023-prd.up.railway.app/users/{id}).

📊
- [(https://sdw-2023-prd.up.railway.app/users/5166}](https://sdw-2023-prd.up.railway.app/users/5166})
- [(https://sdw-2023-prd.up.railway.app/users/5167)](https://sdw-2023-prd.up.railway.app/users/5167)
- [(https://sdw-2023-prd.up.railway.app/users/5168)](https://sdw-2023-prd.up.railway.app/users/5168)


