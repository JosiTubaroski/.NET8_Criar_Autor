
<div> 
<p><a href="https://github.com/JosiTubaroski/WEB-API-com-.NET-8-e-SQL-Server">Home</a></p>
</div> 

<img src="https://github.com/JosiTubaroski/Controllers_Services/blob/main/img/01_Fx_Controller_Interface_Service_2.jpg"/>

# End-Point: Criar Autor

1. Criar a pasta 'Dto', dentro a 'Dto' a pasta 'Autor' e dentro da pasta 'Autor' criar a Classe 'AutorCriacaoDto.cs'

2. Na classe incluir as propriedades Nome e Sobrenome que serão preenchidos

<img src="https://github.com/JosiTubaroski/.NET8_Criar_Autor/blob/main/img/01_Classe_Criar_AutorDto.png"/>  

3. Criar o método 'CriarAutor' dentro da classe de Interface 'IAutorInterface.cs'

<img src="https://github.com/JosiTubaroski/.NET8_Criar_Autor/blob/main/img/02_Criar_Autor_Interface.png"/> 

4. Após a inclusão do método na 'IAutorInterface.cs', ir na AutorService e selecionar 'CTRL'  '.'  e selecionar a opção 'Implementar Interface'.
   
<img src="https://github.com/JosiTubaroski/.NET8_Criar_Autor/blob/main/img/03_AutorService_CriarAutor.png"/>

5. Criar o método [HttpPost("CriarAutor")] na AutorControler

<img src="https://github.com/JosiTubaroski/.NET8_Criar_Autor/blob/main/img/04_CriarAutor_AutorContoler.png"/>

6. Selecionar F5, e testar o EndPoint POST /api/Autor/CriarAutor

<img src="https://github.com/JosiTubaroski/.NET8_Criar_Autor/blob/main/img/05_Post_CriarAutor_1.png"/>

<img src="https://github.com/JosiTubaroski/.NET8_Criar_Autor/blob/main/img/06_Post_Request.png"/>

<img src="https://github.com/JosiTubaroski/.NET8_Criar_Autor/blob/main/img/07_Response.png"/>
