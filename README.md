# Instalar-Software
Script para instalacao de software

Como importar um modulo de Powershell? 
Dentro do Powershell, utilize os comandos: 
Set-ExecutionPolicy Bypass -force # Atribui a permissao
$modulo = "caminhoModulo\nomeModulo.psm1" # Define o caminho do modulo
Unblock-File -Path $modulo # Desbloqueia o arquivo
Import-Module $modulo -Force # Carrega o modulo
