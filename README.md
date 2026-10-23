# exercicio2
Exercicio

# 🛡️ Desafio DIO - Estudo de Ransomware e Keylogger em Ambiente Controlado

## 📋 Sobre o Projeto

Este projeto foi desenvolvido com o objetivo de compreender o funcionamento de dois dos tipos de malware mais conhecidos no cenário de cibersegurança:

- Ransomware
- Keylogger

O estudo foi realizado em ambiente controlado e com finalidade exclusivamente educacional, visando entender os riscos associados a essas ameaças e as principais estratégias de prevenção e defesa.

---

# 🎯 Objetivos

- Entender o funcionamento de um ransomware.
- Compreender como um keylogger coleta informações.
- Identificar indicadores de comprometimento.
- Estudar mecanismos de defesa contra malware.
- Documentar o processo de aprendizado.
- Utilizar o GitHub como portfólio técnico.

---

# 🦠 O que é um Ransomware?

Ransomware é um tipo de software malicioso que impede o acesso aos dados da vítima até que seja realizado o pagamento de um resgate.

Seu funcionamento geralmente envolve:

1. Infecção inicial.
2. Execução do malware.
3. Criptografia dos arquivos.
4. Exibição da mensagem de resgate.
5. Exigência de pagamento.

## Fluxo Simplificado

```text
Infecção
    ↓
Execução
    ↓
Criptografia
    ↓
Arquivos inacessíveis
    ↓
Pedido de resgate
```

---

# 📁 Simulação de Ransomware

Nesta atividade foi realizada uma simulação conceitual do comportamento de um ransomware utilizando arquivos de teste.

## Estrutura Utilizada

```text
projeto/
│
├── arquivos_teste/
│   ├── documento.txt
│   └── imagem.jpg
│
└── README.md
```

### Objetivo

Demonstrar como arquivos podem ser afetados por processos de criptografia e a importância de possuir backups atualizados.

---

# ⌨️ O que é um Keylogger?

Keylogger é um tipo de malware projetado para registrar teclas digitadas por um usuário.

As informações capturadas podem incluir:

- Usuários
- Senhas
- Dados bancários
- Informações pessoais

## Fluxo Simplificado

```text
Digitação do usuário
        ↓
Captura das teclas
        ↓
Armazenamento dos dados
        ↓
Possível vazamento de informações
```

---

# 🔍 Simulação de Keylogger

O estudo envolveu a análise conceitual de uma aplicação que registra entradas de teclado em ambiente controlado.

### Informações analisadas

- Eventos de teclado
- Armazenamento local
- Riscos para credenciais
- Métodos de detecção

---

# 🚨 Impactos de um Ransomware

Um ransomware pode causar:

- Perda temporária de acesso aos arquivos;
- Interrupção das operações de uma empresa;
- Prejuízos financeiros;
- Vazamento de informações;
- Danos à reputação.

---

# 🚨 Impactos de um Keylogger

Um keylogger pode resultar em:

- Roubo de credenciais;
- Acesso indevido a contas;
- Fraudes financeiras;
- Vazamento de dados pessoais;
- Comprometimento de sistemas corporativos.

---

# 🔐 Medidas de Prevenção

## Backup

Manter cópias de segurança atualizadas.

Exemplo:

```text
Regra 3-2-1

3 cópias dos dados
2 mídias diferentes
1 cópia fora do ambiente principal
```

---

## Antivírus

Benefícios:

- Identificação de ameaças conhecidas;
- Bloqueio de arquivos maliciosos;
- Monitoramento em tempo real.

---

## Firewall

Funções:

- Controle de conexões;
- Bloqueio de tráfego suspeito;
- Redução da superfície de ataque.

---

## Atualizações

Manter:

- Sistema operacional atualizado;
- Navegadores atualizados;
- Aplicações atualizadas.

---

## Conscientização dos Usuários

Boas práticas:

✅ Não abrir anexos suspeitos

✅ Não clicar em links desconhecidos

✅ Utilizar senhas fortes

✅ Utilizar autenticação multifator

✅ Reportar comportamentos suspeitos

---

## Sandboxing

A sandbox permite executar aplicações em ambientes isolados para análise segura.

Benefícios:

- Redução de riscos;
- Identificação de comportamentos maliciosos;
- Testes controlados.

---

# 🔎 Indicadores de Comprometimento (IoCs)

## Possíveis sinais de ransomware

- Arquivos inacessíveis;
- Extensões desconhecidas;
- Lentidão repentina;
- Mensagens de resgate.

---

## Possíveis sinais de keylogger

- Processos desconhecidos;
- Consumo anormal de recursos;
- Tráfego de rede suspeito;
- Alertas do antivírus.

---

# 📚 Aprendizados Obtidos

Durante o desenvolvimento deste projeto foi possível compreender:

- Como o ransomware afeta a disponibilidade dos dados;
- Como keyloggers representam riscos para credenciais;
- A importância de backups;
- A relevância do monitoramento contínuo;
- O papel da conscientização dos usuários na segurança da informação.

---

# ✅ Conclusão

Este projeto proporcionou um entendimento prático sobre duas das ameaças mais relevantes da atualidade: ransomware e keylogger.

Mesmo em ambiente controlado, foi possível observar como essas ameaças exploram falhas técnicas e humanas para comprometer sistemas e informações.

A principal lição obtida é que a prevenção continua sendo a estratégia mais eficiente, combinando tecnologia, processos e treinamento dos usuários.

---

# 👨‍💻 Autor

**Carlos Vinicius Ribeiro**

Projeto desenvolvido para a formação de Cibersegurança da DIO.
