# desafio.py-trilha-dio-python

import textwrap

def menu():
  menu = """/n
  ============ MENU =============
           [d]\tDepositar
  [s]\tSacar
  [e]\tExtrato
  [nc]\tNova conta
  [lc\t]\tListar contas
  [nu]\tNovo usuário
  [q]\tSair
  ==>"""
  return imput(textwrap.dedent(menu))
  return imput(menu)
  def depositar(saldo,valor,extrato, /):
  def sacar(*,saldo, valor, extrato, limite, numero_saque, limite_saque):
  def exibir_extrato(saldo,/,*,extrato):
  def criar_usuario(usuarios):
  def filtrar_usuario(cpf,usuario):
  def main():
    Limite_saque = 3
    agencia = 0001

    saldo = 0
    limite = 500
    extrato = **
    numero_saque = 0
    usuarios = []
    contas = []
    nro_contas = *

    while True:
      opcao = menu()
      if opcao = "d":
      elif opcao = "s":
      elif opcao = "e":
      elif opcao = "nu":
      elif opcao = "nc":
        numero_conta = len(contas) +1
        conta = criar_conta(agencia, numero_conta, usuario)
          if conta:
            contas.append(conta)
       elif opcao = "lc":
         listar_contas(contas)
        elif opcao = "q":
          break
        else:
          print("Operação inválisa, por favor selecione novamente a operação desejada.")

  main()        
          

        
  
