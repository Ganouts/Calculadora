print("Olá,Bem vindo à calculadora")

while true do 

	print("Insira o primeiro valor")
  valor1 = io.read()

  while type(tonumber(valor1)) ~= "number" do
    if valor1 == "sair" then
      return 
    elseif valor1 == "Sair" then
      return 
    elseif valor1 == "exit" then
      return 
    elseif valor1 == "Exit" then
      return 
    else
      print("Insira um número")
      valor1 = io.read()
    end
  end

  print("Insira um sinal de calculo(+,-,*,/)")

  fim = 0
  sinal = io.read()

  while fim == 0 do
    if sinal == "+" then
      sinal = sinal
      fim = 1
    elseif sinal == "-" then
      sinal = sinal
      fim = 1
    elseif sinal == "/" then
      sinal = sinal
      fim = 1
    elseif sinal == "*" then
      sinal = sinal
      fim = 1
    else print("Insira um sinal")
      sinal = io.read()
    end
  end

  print("Insira o segundo valor")
  valor2 = string.lower(io.read())

  while type(tonumber(valor2)) ~= "number" do
    if valor2 == "sair" or valor2 == "exit" or valor2 == "saída" then
      return
    else
      print("Insira um número")
      valor2 = string.lower(io.read())
    end
  end

  total = "Erro na operação"
--Base do script,é onde acontece as verificações do sinais dados e os calculos.
  if sinal == "+" then
    total = valor1 + valor2
    elseif sinal == "-" then
      total = valor1 - valor2
    elseif sinal == "/" then
      total = valor1 / valor2
    elseif sinal == "*" then
      total = valor1 * valor2
    else print(total)
    end
--Confere se recebeu um valor divido por 0.
  if tostring(total) == "-1.#IND" then
    total = "Valor indefinido"
  elseif tostring(total) == "-nan" then
    total = "Valor indefinido"
  elseif tostring(total) == "inf" then
    total = "Valor indefinido"
  end

  print("Valor: " .. total)
  print('Digite "sair" para fechar ou digite "novamente" para calcular:')
  final = string.lower(io.read())

  while true do
  if final == "sair" then
    return
  elseif final == "novamente" then
    break
  else print('Digite "sair" para fechar ou digite "novamente" para calcular:')
    final = string.lower(io.read())
   end
  end
end
