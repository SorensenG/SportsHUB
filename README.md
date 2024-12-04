# SportHub 🏀⚽🎾

**SportHub** é um sistema para gerenciamento de reservas de quadras esportivas. Ele permite que os usuários aluguem quadras, cancelem reservas e consultem a agenda de reservas de forma simples e eficiente.

---

## 🎯 **Objetivo do Projeto**
Proporcionar uma solução prática para o gerenciamento de quadras esportivas, permitindo que os usuários realizem reservas e acompanhem a disponibilidade de horários de forma fácil e intuitiva.

---

## 🚀 **Funcionalidades**
- **Alugar Quadra:** Permite o registro de uma nova reserva fornecendo RA, data e horário.
- **Cancelar Reserva:** Opção para cancelar reservas existentes informando o RA.
- **Consultar Agenda:** Exibe todas as reservas registradas.

---

## 📋 **Requisitos**
### **Requisitos Funcionais**
- Cadastro de reservas.
- Exclusão e atualização de reservas existentes.
- Consulta da agenda de reservas.

### **Requisitos Não Funcionais**
- Uso de estruturas de repetição e funções.
- Implementação de ponteiros e alocação dinâmica de memória.
- Modularização com recursividade.
- Persistência de dados em arquivos no disco.

---

## 🛠️ **Tecnologias Utilizadas**
- **Linguagem:** C
- **Recursos Adotados:** Arquivos para persistência de dados, alocação dinâmica de memória, modularização e recursividade.

---

## 📐 **Arquitetura do Sistema**
O sistema é modular, com cada funcionalidade representada por uma função específica:
1. **alugarQuadra:** Registra uma nova reserva no arquivo `agenda.txt`.
2. **alterarAgenda:** Cancela uma reserva existente, atualizando o arquivo.
3. **consultarAgenda:** Lê o arquivo e exibe todas as reservas registradas.

### 🔗 **Fluxo de Dados**
1. O usuário insere RA, data e horário na função **alugarQuadra**.
2. As informações são gravadas no arquivo `agenda.txt`.
3. A função **alterarAgenda** permite cancelamento de reservas existentes.
4. A função **consultarAgenda** exibe todas as reservas armazenadas.

---

## 🖥️ **Decisões de Design**
- **Alocação Dinâmica:** Gerencia eficientemente a memória para lidar com diferentes quantidades de reservas.
- **Persistência de Dados:** Armazena reservas em um arquivo texto (`agenda.txt`) para fácil acesso e manutenção.

---

## 📬 **Contato**
Para dúvidas ou sugestões, entre em contato:
- **Gabriel Sorensen**: [g.soren.sen2004@gmail.com](mailto:g.soren.sen2004@gmail.com)
