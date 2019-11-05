# Instalar-Software
Script para instalacao de software

# Como importar um modulo de Powershell?  <br>
Dentro do Powershell, utilize os comandos: <br>
Set-ExecutionPolicy Bypass -force # Atribui a permissao <br>
$modulo = "caminhoModulo\nomeModulo.psm1" # Define o caminho do modulo <br>
Unblock-File -Path $modulo # Desbloqueia o arquivo <br>
Import-Module $modulo -Force # Carrega o modulo <br>
