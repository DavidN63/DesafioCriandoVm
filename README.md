# DesafioCriandoVm

# 💻 Desafio: Criação de Máquina Virtual no Azure

Este repositório contém a documentação do desafio prático proposto no bootcamp **GFT Start #7 .NET** da DIO, com o objetivo de aplicar conhecimentos sobre **Computação em Nuvem** utilizando o **Microsoft Azure**.

---

## 📘 Resumo

O desafio consistiu na criação e configuração de uma **máquina virtual (VM)** no ambiente da Azure, aplicando conceitos de infraestrutura como serviço (**IaaS**), segurança, escalabilidade e gerenciabilidade. Ao final, a VM foi acessada com sucesso via SSH ou RDP, comprovando seu funcionamento.


## ⚙️ Passo a Passo da Criação da VM

1. **Login no Azure Portal**  
   
2. **Criação do Grupo de Recursos**  
   - Nome: `rg-desafio-cloud`
   - Região: `Brazil South`

3. **Criação da Máquina Virtual**  
   - Nome da VM: `vm-desafio-gft`
   - Opções de disponibilidade: Zona de disponibilidade
   - Tipo de segurança: Computadores virtuais de inicialização confiavel
   - Sistema operacional: `Ubuntu 24.04 LTS - x64 Gen2
   - Arquitetura de VM: x64
   - Tamanho: `Standard_B1s`
   - Autenticação: SSH
   - Nome do Par de chaves: david01
   - Abertura de porta: 22

4. **Configuração de Rede**
   - IP público gerado automaticamente
   - Grupo de segurança de rede: básico

5. **Acesso à VM**
   
6. **Validação**
   - Teste de conectividade e verificação do sistema operacional em execução.

---
