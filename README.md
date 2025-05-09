# dio_ecommerce_cloud
Laboratório para implantação de uma aplicação no Azure, utilizando o Azure SQL Server e o armazenamento de Blobs do Azure.

Foi realizado o desenvolvimento de uma aplicação na linguagem Python, utilizando o framework Streamlit, gerando facilmente um formulário para envio de dados.

Os dados são enviados por este formulário com destino a um servidor SQL Server no Azure. Os registros são inseridos em uma tabela chamada produtos, utilizando a biblioteca pymssql para conexão com  Azure SQL Server.

Através do framework Streamlit é realizado upload de imagens que são armazenadas no Blob da Azure, a biblioteca python Azure Storage Blob é utlizada como cliente para se conectar ao serviço de armazenamento do Azure.

Formulário gerado pelo stremlit:

![Captura de tela 2025-05-09 184754](https://github.com/user-attachments/assets/4e703903-71a3-4c27-ac4c-41505ce541ef)


