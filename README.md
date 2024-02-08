# ACBrLibGTINPython
Exemplo de uso da ACBrLibGTIN com Python
O programa em Pythom está no arquivo ACBrGTIN.py

#ACBrGTIN.INI
Neste arquivo são definidas algumas configurações para o funcionamento correto da consulta.
Todos os path estão definidos para que este teste esteja na pasta "C:\ACBrLibGTINPython", caso utilize um caminho diferente lembre-se de alterar no INI
Verifique e configure a seção [DFe] de acordo com o certificado digital que você vai utilizar. A configuração do arquivo é para um A1 que está instalado na máquina em que o exemplo foi desenvolvido, portanto não vai funcionar na sua máquina até que você configure corretamente com o seu certificado.
A documentação completa do arquivo INI pode ser encontrada em https://acbr.sourceforge.io/ACBrLib/ACBrLibGTIN.html

#ACBrGTIN64.dll
A DLL não é disponibilizada com este exemplo. Foi utilizada a versão Windows, Single Thread e 64 Bits.
Você encontra a DLL para baixar em https://www.projetoacbr.com.br/forum/files/
Existe a Versão DEMO e a versão PRO. Considere se tornar assinante PRO > https://www.projetoacbr.com.br/pro

# Dependencias
Os arquivos descritos abaixo devem ser mantidos junto ao exemplo e sua eventual aplicação que usar esse recurso.
Tem como dependencias DLLs da OpenSSL e da LibXml2 - as disponibilizadas nesse repositório são de 64 bits.
Também usa arquivos de Schemas disponibilizados nesse repositório.
O arquivo ACBrGTINServicos.ini é usado para mapear os endereços utilizados no acesso.
