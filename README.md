# Automação básica de compra em ecommerce do ramo gráfico utilizando Python com Selenium.

Compra básica, de um produto que possui apenas um arquivo de envio e selecionando boleto como forma de pagamento. Ao finalizar o pedido, na tela de sucesso, o mesmo é cancelado.

Realizada validação do surgimento do elemento na página, por meio de um While com a função que encontra uma lista de elementos no site, então na condição é necessário utilizar o find_elements e na ação que vai realizar no elemento, utilizar o find_element.
time.sleep() utilizado para aguardar carregamento da página.

Para executar o esse script é necessário realizar cadastro no site, e substituir "Seu Usuário" e "Sua senha" nos comandos que selecionam os elementos name de login e senha.

Script foi desenvolvido no Jupyter Notebook e utilizado o Chrome para execução. Necessário download do webdriver chrome e adiciona-lo na raiz do anaconda.
