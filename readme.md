Trabalho realizado Gabriel Hideki Hiroi, Guilherme Machado

Classes:

FintechApp: String
ContaBancaria: String
TransacaoBancaria: String
Cliente: Pessoa
ClienteEmpresarial: Pessoa


ContaBancaria:

numeroConta: número da conta bancária
nomeTitular: nome completo do titular da conta
identificacaoPessoal: número de identificação pessoal do titular da conta
saldo: saldo atual da conta bancária do titular

TransacaoBancaria:

valor: valor da transação bancaria
data: data da transação bancaria
tipo: tipo de transação bancaria (depósito, saque ou transferência)
contaOrigem: conta bancária de origem da transação
contaDestino: conta bancária de destino da transação

Cliente:

nomeCompleto: nome completo do cliente
identificacaoPessoal: número de identificação pessoal do cliente (CPF ou RG)
email: endereço de email do cliente
telefone: número de telefone do cliente
endereco: endereço do cliente

ClienteEmpresarial:

nomeEmpresa: nome da empresa do cliente empresarial
cnpj: número de registro da empresa (CNPJ)
endereco: endereço da empresa
email: endereço de email do cliente empresarial
telefone: número de telefone do cliente empresarial


FintechApp:

abrirContaBancaria(cliente): abre uma nova conta bancária para um cliente
verificarSaldo(contaBancaria): retorna o saldo atual de uma conta bancária
depositar(contaBancaria, valor): adiciona um valor ao saldo de uma conta bancária
sacar(contaBancaria, valor): retira um valor do saldo de uma conta bancária
transferir(contaOrigem, contaDestino, valor): transfere um valor de uma conta bancária para outra
gerarQRCode(contaDestino, valor): gera um QR Code para uma transferência bancária
ContaBancaria:

atualizarSaldo(valor): atualiza o saldo da conta bancária após uma transação
TransacaoBancaria:

registrarTransacao(): registra as informações de uma transação bancária
Cliente:

Lista de dados: ArrayList<dados>

fornecerDadosPessoais(): coleta as informações pessoais do cliente
ClienteEmpresarial:

fornecerDadosEmpresariais(): coleta as informações da empresa do cliente empresarial
Relacionamentos:
