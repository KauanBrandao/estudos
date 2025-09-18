# Introdução a Testes Unitários

**Testes unitários** são um tipo de teste de software focado em verificar pequenas partes do código de forma isolada, geralmente funções ou métodos individuais.  
O objetivo é garantir que cada “unidade” do sistema funcione corretamente, independentemente das demais.  

## Benefícios dos Testes Unitários
- Detectar erros cedo no desenvolvimento.  
- Facilitar a manutenção e evolução do código.  
- Dar mais confiança em refatorações, já que asseguram que o comportamento esperado não foi quebrado.  

Na prática, os testes unitários são automatizados e escritos pelo próprio desenvolvedor, usando frameworks como **JUnit** (Java), **pytest** (Python) ou **Jest** (JavaScript).

---

## Testes em Java

### JUnit e Mockito (Dentro do Spring Starter Test)
- **JUnit**: Framework de testes unitários que fornece um ambiente de execução e diversas ferramentas para criação e execução de testes em Java.  
- **Mockito**: Biblioteca que facilita a criação de *mocks* e a simulação de comportamentos de dependências dentro dos testes.

- **Spring Starter Test**: Por padrão, essa biblioteca ja vem instalada nas dependências do Spring contendo o JUnit, Mockito e entre outros, ou seja, a Spring Starter Teste é um tipo de pack que já vem com essas outras bibliotecas instaladas.

---

## O que são Mocks?

**Mocks** são objetos "falsos" usados em testes de software para **simular o comportamento de dependências reais** (como banco de dados, APIs externas, serviços ou classes complexas).  

Eles são úteis em testes unitários porque:
- Permitem isolar a unidade de código que você está testando.  
- Evitam depender de recursos externos (como um banco real ou rede).  
- Ajudam a controlar cenários específicos (ex: simular erro de conexão, retorno de dados diferentes, etc.).  

👉 Em outras palavras, em vez de chamar a dependência real, você cria um *mock* que retorna respostas controladas.
