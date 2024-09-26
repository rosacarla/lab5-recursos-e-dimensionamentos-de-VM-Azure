☁️ CONGIGURANDO RECURSOS E DIMENSIONAMENTOS DE MÁQUINAS VIRTUAIS NO AZURE  
 
<p align="center">
  <img src="https://i.postimg.cc/Gmxtwttm/azure-fundamentals.png" width="256">
</p>

---  
## ⏯️ INTRODUÇÃO  

<p align='justify'>Neste laboratório do bootcamp <i>Azure Essencials</i>, foram abordadas questões referentes a formas de configuração de recursos e dimensionamentos de máquinas virtuais no portal <a href='https://portal.azure.com/'><i>Microsoft Azure</i></a>. Através do projeto,foram explorados os conceitos sobre redes virtuais, balanceamento de carga. </p>     

<p align="center">
  <img src='https://github.com/rosacarla/lab5-recursos-e-dimensionamentos-de-VM-Azure/blob/main/images/criar-vm-serieF.png' width=880> 
</p>

--- 
## 🗒️RESUMO DOS TÓPICOS:  

<p align='justify'>- Ao criar uma máquina virutal no Azure, serão incluidas automaticamente algumas configurações pré-definidas, como indica o aviso sobre a série F em destaque na imagem acima. Ao selecionar a região, recomenda-se escolher regiões com custo menor, como <i>(US) East US 2</i>. A escolha da Zona de Disponibilidade tem como consequência a escolha de um datacenter específico. </p>     

<p align="center">
  <img src='https://github.com/rosacarla/lab5-recursos-e-dimensionamentos-de-VM-Azure/blob/main/images/vm-coniguracoes-adicionais.png' width=880> 
</p>

<p align='justify'>- É importante saber configurar o conjunto de dimensionamento de máquinas virtuais, com quantas máquinas vai começar, em quantas se farão alterações, o que vai mudar nelas e até quanto alguma vai crescer.</p>    

<p align="center">
  <img src='https://github.com/rosacarla/lab5-recursos-e-dimensionamentos-de-VM-Azure/blob/main/images/deimensionar-nro-vm.png' width=880>  
</p>

<p align='justify'>- Na visualização do globo, é demonstrado o cabeamento que conecta as regiões, satélites, e ainda é possível fazer um tour virtual por um datacenter da Microsoft.</p>    

<p align="center">
  <img src= '  ' width=880> 
</p>

<p align='justify'>- Para criar um grupo de recursos, é preciso selecionar alguma região que está disponível. Atribuir uma tag para cada grupo de recursos para facilitar a leitura da fatura.</p>    

<p align="center">
  <img src='  ' width=880>  
</p>  

<p align='justify'>- Na área IAM (Controle de acesso) pode-se dar permissionamento para alguém ou remover. Cada usuário receberá permissão para trabalhar com o grupo de recursos do projeto em que estiver envolvido. O permissionamento é responsabilidade do cliente, sendo recomendável que se conceda o menos permissionamento possível para cada pessoa, para evitar ações indevidas. </p>     

<p align="center">
  <img src=' '> 
</p>

<p align='justify'>- Há diversas funcionalidades, como: visualizador de recursos para mostrar uma árvore com ícones de todos os recursos que já foram criados; parte de Eventos são visualizadas as automatizações; gerenciamentos de custos, dentre outras.</p>    

<p align="center">
  <img src='  '> 
</p>

<p align='justify'>- É permitido colocar itens de outros locais no grupo de recursos. Por exemplo, uma rede virtual criada na região <i>Brazil South</i> pode ser incluída no grupo de recursos da região <i>East US 2</i>. </p>    

<p align="center">
 <img src= ' width=880>  
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

- [Máquinas Virtuais do Azure](https://azure.microsoft.com/pt-br/products/virtual-machines)
- [Área de Trabalho Virtual do Azure](https://azure.microsoft.com/pt-br/products/virtual-desktop)
- [Tutorial: criar um aplicativo de funções que se conecta aos serviços do Azure usando identidades em vez de segredos](https://learn.microsoft.com/pt-br/azure/azure-functions/functions-identity-based-connections-tutorial)

---
