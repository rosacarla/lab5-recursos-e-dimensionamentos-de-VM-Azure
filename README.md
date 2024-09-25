# ☁️ CONSTRUINDO ARQUITETURAS NO AZURE  
 
<p align="center">
  <img src="https://i.postimg.cc/Gmxtwttm/azure-fundamentals.png" width="256">
</p>

---  
## ⏯️ INTRODUÇÃO  

<p align='justify'>Neste laboratório do bootcamp <i>Azure Essencials</i>, foram abordadas questões referentes a regiões de disponibilidade e criação de grupo de recursos no portal <a href='https://portal.azure.com/'><i>Microsoft Azure</i></a>. Através do projeto, foram exploradas as regiões no Globo da Microsoft e simuladas algumas configurações para criação de grupo de recursos. </p>     

<p align="center">
  <img src='https://github.com/rosacarla/lab4-construindo-arquiteturas-no-Azure/blob/main/images/regiao-grupo-de-recursos.png' width=880> 
</p>

--- 
## 🗒️RESUMO DOS TÓPICOS:  

<p align='justify'>- Inicialmente, explorou-se o globo com as regiões de disponibilidade do Azure. Por exemplo, no Brasil existem 2 regiões: <i>Brazil South</i> em SP (reservada para todos os consumidores e parceiros) e <i>Brazil Southeast</i> no RJ (reservada para consumdores brasileiros, que requerem cenário baseado em <i>disaster recovery</i>). </p>     

<p align="center">
  <img src='https://github.com/rosacarla/lab4-construindo-arquiteturas-no-Azure/blob/main/images/regiao-detalhes.png' width=880> 
</p>

<p align='justify'>- Quanto à <i>Data Residency</i>, a região <i>Brazil South</i> repllica os dados automaticamente para os US e a região <i>Brazil Southeast</i> replica os dados para dentro do território nacional.</p>    

<p align="center">
  <img src='https://github.com/rosacarla/lab4-construindo-arquiteturas-no-Azure/blob/main/images/regiao-satelites.png' width=880>  
</p>

<p align='justify'>- Na visualização do globo, é demonstrado o cabeamento que conecta as regiões, satélites, e ainda é possível fazer um tour virtual por um datacenter da Microsoft.</p>    

<p align="center">
  <img src='https://github.com/rosacarla/lab4-construindo-arquiteturas-no-Azure/blob/main/images/globo-microsot-azure.gif' width=880> 
</p>

<p align='justify'>- Para criar um grupo de recursos, é preciso selecionar alguma região que está disponível. Atribuir uma tag para cada grupo de recursos para facilitar a leitura da fatura.</p>    

<p align="center">
  <img src='https://github.com/rosacarla/lab4-construindo-arquiteturas-no-Azure/blob/main/images/regiao-grupo-rec-criado.png' width=880>  
</p>  

<p align='justify'>- Na área IAM (Controle de acesso) pode-se dar permissionamento para alguém ou remover. Cada usuário receberá permissão para trabalhar com o grupo de recursos do projeto em que estiver envolvido. O permissionamento é responsabilidade do cliente, sendo recomendável que se conceda o menos permissionamento possível para cada pessoa, para evitar ações indevidas. </p>     

<p align="center">
  <img src='https://github.com/rosacarla/lab4-construindo-arquiteturas-no-Azure/blob/main/images/regiao-acesso-recursos.png'> 
</p>

<p align='justify'>- Há diversas funcionalidades, como: visualizador de recursos para mostrar uma árvore com ícones de todos os recursos que já foram criados; parte de Eventos são visualizadas as automatizações; gerenciamentos de custos, dentre outras.</p>    

<p align="center">
  <img src='https://github.com/rosacarla/lab4-construindo-arquiteturas-no-Azure/blob/main/images/regiao-visualiza-recursos.png'> 
</p>

<p align='justify'>- É permitido colocar itens de outros locais no grupo de recursos. Por exemplo, uma rede virtual criada na região <i>Brazil South</i> pode ser incluída no grupo de recursos da região <i>East US 2</i>. </p>    

<p align="center">
 <img src='https://github.com/rosacarla/lab4-construindo-arquiteturas-no-Azure/blob/main/images/regiao-incluir-recurso.png' width=880>  
</p>

---  
## ✍️ AUTORA    

Carla Edila Silveira  
Contato: rosa.carla@pucpr.edu.br  

---  

## ©️ LICENÇA

[MIT](https://choosealicense.com/licenses/mit/)  

---  

## 🔗 LINKS ÚTEIS  

- [Rede global do Azure](https://azure.microsoft.com/pt-br/explore/global-infrastructure/global-network/?msockid=0918e6742c7f677b085cf2a02d0666cb)
- [Controlar e organizar os recursos do Azure com o <i>Azure Resource Manager</i>](https://learn.microsoft.com/pt-br/training/modules/control-and-organize-with-azure-resource-manager/?WT.mc_id=azureportalcard_Service_ResourceGrps_-inproduct-azureportal)
- [O que é o <i>Azure Resource Manager</i>?](https://learn.microsoft.com/pt-br/azure/azure-resource-manager/management/overview?WT.mc_id=APC-Resourcegroups)
- [Documentação do <i>Azure Resource Manager</i>](https://learn.microsoft.com/pt-br/azure/azure-resource-manager/?WT.mc_id=APC-Resourcegroups)

---  
