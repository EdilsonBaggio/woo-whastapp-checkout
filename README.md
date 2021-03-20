
<h3>Envie dados da compra para o vendedor pelo whatsapp.</h3>
<p>Vá até p painel do wordpress e instale o plugin Checkout Field Editor for WooCommerce depois clique em woocommerce, crie os campos no CHECKOUT FORM, adicione os seguintes campos</p>
<strong>Important para o funcionamento, crie os seguintes campos</strong>
<br/>
<p>
* Nome<br/>
* Sobrenome<br/>
* Pais <br/>
* Endereço <br/>
* Bairro <br/>
* Complemento <br/>
* Numero <br/>
* Cidade <br/>
* Estado <br/>
* Cep <br/>
* Telefone <br/>
* E-mail <br/>
* Forma de Pagamento, nesse voce vai incluir um dropdown - dinheiro, débito, crédito etc. Vai do que for melhor pra você.<br/>
* Observações
</p><br/>
<p>Abaixo um exemplo das informaçoes do produto e dados do cliênte enviadas pelo whatsapp. 
<br/>Entre na pasta do plugin woocommerce e faça um backup do arquivo order-details.php e troque ele por este que está no repositório.</p>
<br/>
<img src="images/exemplo.jpg" width="491"/>
<h2>No wp-config adicione um define com o numero da loja ex: define('WHATSAPP','5511900000000');<h2/>
