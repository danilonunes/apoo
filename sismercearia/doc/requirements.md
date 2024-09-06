# Casos de Uso

## UC01: Realizar Venda

### Ator(es):
* Cliente
* Operadora de pagamentos
### Interessado(s) e interesse(s):
### Pré-condições:
### Pós-condições:
### Questões em aberto:
### Fluxo Principal:

1. O cliente escolhe os produtos e leva ao caixa.

2. [IN] O funcionário registra os itens.

3. [OUT] O sistema exibe o valor total da compra.

4. [IN] O funcionário finaliza a venda.

5. [OUT] O sistema informa as formas de pagamento.

6. [IN] O cliente escolhe a forma e realiza o pagamento.
6.1. Pagamento com dinheiro.  
6.2. Pagamento com cartão de débito.  
6.3. Pagamento com cartão de crédito.  
6.4. Pagamento com Pix.  
6.5. Pagamento com vale refeição.  

7. [OUT] O funcionário confirma o pagamento e entrega o comprovante ao cliente.

### Variantes

**6.1 Pagamento com dinheiro**  
6.1.1. O cliente entrega as notas.   
6.1.2. O funcionário registra o valor recebido.  
6.1.3. O sistema informa o troco.  
6.1.4. O funcionário entrega o troco ao cliente (se houver troco).  

**6.2. Pagamento com cartão de débito**  
6.2.1. O cliente usa o cartão na interface de identificação.  
6.2.2. O sistema envia os dados do cartão para a operadora de cartões.  
6.2.3. A operadora envia o número de autorização.  

**6.3. Pagamento com cartão de crédito**  
6.3.1. O cliente usa o cartão na interface de identificação.
6.3.2. O sistema informa as opções de parcelamento.  
6.3.3. O cliente escolhe o parcelamento.  
6.3.4. O sistema envia os dados do cartão e parcelamento para a operadora de cartões.  
6.3.5 A operadora envia o número de autorização.  

**6.4. Pagamento com Pix**  
6.4.1. O sistema solicita uma chave para pagamento a operadora de *pagamentos*.  
6.4.2. O sistema exibe a chave para pagamento.   
6.4.3. O cliente realiza o pagamento.  
6.4.4. O operadora envia o número de autirização.  
6.4.5. O sistema registra o pagamento.  

**6.5. Pagamento com vale refeição**  
6.5.1. O cliente usa o cartão na interface de identificação.  
6.5.2. O sistema envia os dados do cartão para a operadora de cartões.  
6.5.3. A operadora envia o número de autorização. 

### Exceções