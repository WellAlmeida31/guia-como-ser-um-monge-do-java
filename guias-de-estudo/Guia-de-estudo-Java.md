# Guia de Estudos Java - Roadmap Completo com Livros e Cursos

Este documento organiza as melhores referências (cursos, livros e artigos) para cada etapa do aprendizado da linguagem Java, desde o pensamento computacional até o nível especialista.

---

## 🧠 Fundamentos Essenciais (Para qualquer nível)

### Pensamento Computacional
- **O que focar**: Lógica, abstração, decomposição de problemas, reconhecimento de padrões.
- **Curso recomendado**:
    - [Computação: Fundamentos e Pensamento Computacional - Alura](https://cursos.alura.com.br/course/computacao-fundamentos-computacao-pensamento-computacional)

> 💡 **Dica**: Este é o ponto de partida ideal para iniciantes absolutos, antes mesmo de escrever a primeira linha de código.

---

## 🟢 Nível Básico e Intermediário

### Cursos abrangentes (do zero ao mercado)

| Recurso | Foco principal | Link |
| :--- | :--- | :--- |
| **Java do zero ao profissional** (Udemy) | Fundamentos completos, programação orientada a objetos, JDBC | [Acessar curso](https://www.udemy.com/course/fundamentos-de-programacao-com-java/learn/lecture/26919700) |
| **Java COMPLETO - Nélio Alves** (Udemy) | OO, UML, JDBC, JavaFX, Spring Boot, JPA/Hibernate, MySQL, MongoDB | [Acessar curso](https://www.udemy.com/course/java-curso-completo/learn/lecture/53745893) |
| **Praticando Java - Alura** | Tópicos básicos do dia a dia (muitos esquecem o básico) | [Guia de aprendizado](https://cursos.alura.com.br/app/learning-guide/alura/praticando-java) |
| **Java Programming MOOC** (Universidade de Helsinque) | Estruturas de listas e mapas (Parte I - a partir do capítulo 3, Parte II - a partir do capítulo 8) | [MOOC Java](https://java-programming.mooc.fi/) |

### Livros fundamentais

| Livro | Autor | Por que ler |
| :--- | :--- | :--- |
| **Java Efetivo (3ª edição)** | Joshua Bloch | As melhores práticas para a plataforma Java. Essencial para escrever código limpo, eficiente e profissional. |
| **Use a Cabeça! Java** | Kathy Sierra & Bert Bates | Abordagem visual e divertida, excelente para iniciantes que querem fixar os fundamentos de OO e sintaxe. |

### Artigos sobre estruturas de dados internas

| Tópico | Link |
| :--- | :--- |
| Diferença entre ArrayList e LinkedList, funcionamento interno da LinkedList | [Medium - Guia completo de LinkedList](https://medium.com/@YodgorbekKomilo/a-comprehensive-guide-to-linkedlist-in-java-a64a4584a3dd) |
| O que acontece por trás da interface LinkedList | [DevMedia - LinkedList por trás da interface](https://www.devmedia.com.br/linkedlists-o-que-acontece-por-tras-da-interface/24613) |

> 💡 **Dica extra**: Após estes artigos, estude também o código-fonte interno de `HashMap` (como funciona o hashing, colisões e redimensionamento) e `ArrayList` (mecanismo de crescimento dinâmico).

---

## 🔴 Nível Avançado

### Cursos recomendados

| Curso | Plataforma | Tópicos |
| :--- | :--- | :--- |
| **Java Advanced** (Nelio Alves) | Udemy | Lambdas, Streams, generics avançados, programação funcional |
| **Concorrência e Performance** (Alura) | Alura | Threads, `java.util.concurrent`, tuning |
| **Spring Framework (vários cursos)** | Alura, Udemy, DevDojo | APIs REST, JPA, segurança, testes |

### Livros avançados

| Livro | Autor | Foco |
| :--- | :--- | :--- |
| **The Well-Grounded Java Developer (2ª ed)** | Benjamin J. Evans et al. | JVM, bytecode, módulos, performance, containers |
| **Modern Java in Action** | Raoul-Gabriel Urma | Lambdas, streams, programação funcional e reativa com Java 8/9/10 |

### Artigos e referências complementares

- **Funcionamento interno da `ConcurrentHashMap`** – vale a pena buscar artigos no Medium/Baeldung sobre segment locking e adaptações para Java 8+.
- **Documentação oficial do `java.util.stream`** – explore pacotes, interfaces e classes concretas para entender o design da API.

---

## ⚫ Nível Especialista

### Cursos especialistas

| Recurso | Autor/Plataforma | Diferencial |
| :--- | :--- | :--- |
| **Java Specialists Superpack 2025** | Heinz Kabutz | Concorrência avançada (Virtual Threads), bytecode, agents, performance, GC tuning. Inclui certificações. |
| **Java Memory Management** | Pluralsight | Entenda heap, stack, garbage collectors (G1, ZGC, Shenandoah) na prática |

### Livros para especialistas

| Livro | Autor | Profundidade |
| :--- | :--- | :--- |
| **Java Concurrency in Practice** | Brian Goetz | A bíblia da concorrência: segurança de threads, locks, `java.util.concurrent`, análise de riscos |
| **The Java Virtual Machine Specification** | Tim Lindholm et al. | A especificação oficial da JVM. Leitura densa, mas indispensável para quem quer dominar bytecode e classloading. |

### Recursos complementares extras

- **Bytecode e manipulação**:
    - Site: [ASM Bytecode Framework](https://asm.ow2.io/)
    - Livro: *Java Bytecode Engineering* (S. P. A. et al., mais antigo, mas útil para fundamentos)
- **Padrões de projeto**:
    - Livro: *Padrões de Projeto* (Erich Gamma et al.) – o clássico "Gang of Four", aplicado a Java.
- **Desempenho e tuning**:
    - Livro: *Java Performance (2ª ed)* – Scott Oaks (O'Reilly)

---

## 📌 Resumo por nível de conhecimento

| Nível | Principais recursos |
| :--- | :--- |
| **Pensamento Computacional** | Curso Alura (link acima) |
| **Básico ao Intermediário** | MOOC, Nelio Alves (Udemy), *Java Efetivo*, *Use a Cabeça! Java*, artigos sobre `ArrayList` vs `LinkedList` |
| **Avançado** | *The Well-Grounded Java Developer*, *Modern Java in Action*, cursos de Spring, artigos de `ConcurrentHashMap` e Stream API |
| **Especialista** | *Java Concurrency in Practice*, *JVM Specification*, curso *Java Specialists*, *Java Performance* (Scott Oaks) |

---

## ✅ Checklist de habilidades práticas

- [ ] Pensamento computacional e lógica de programação
- [ ] Sintaxe básica, tipos, operadores, controle de fluxo
- [ ] Arrays, Strings, uso correto de `StringBuilder`
- [ ] POO: classes, herança, polimorfismo, encapsulamento
- [ ] Tratamento de exceções (checked/unchecked)
- [ ] Collections Framework: `List`, `Set`, `Map`, `Queue`
- [ ] Generics e wildcards
- [ ] Lambdas e Stream API
- [ ] `java.time` (datas modernas)
- [ ] Concorrência: `Thread`, `ExecutorService`, `CompletableFuture`
- [ ] JDBC e acesso a banco de dados
- [ ] Servlet/JSP ou diretamente Spring Boot
- [ ] Testes unitários (JUnit, Mockito)
- [ ] Build tools (Maven ou Gradle)
- [ ] Controle de versão com Git
- [ ] Conhecimento profundo da JVM (GC, bytecode, classloading)
- [ ] Otimização de performance e profiling

---

## 🌐 Referências úteis (sempre atualizadas)

- [Documentação oficial da Oracle](https://docs.oracle.com/en/java/)
- [Baeldung](https://www.baeldung.com/) – tutoriais práticos para todos os níveis
- [Java Code Geeks](https://www.javacodegeeks.com/)
- [InfoQ – Java](https://www.infoq.com/java/)
- [Stack Overflow – Java](https://stackoverflow.com/questions/tagged/java)

---

## 🧩 Como usar este guia

1. **Comece pelo Pensamento Computacional** se você é muito iniciante.
2. **Escolha um dos cursos abrangentes** (Nelio Alves ou MOOC) para a base sólida.
3. **Pratique diariamente** com pequenos projetos.
4. **Avance para os livros** *Java Efetivo* e *The Well-Grounded Java Developer*.
5. **Aprofunde em tópicos específicos** (concorrência, performance, bytecode) conforme sua necessidade profissional.

> ⚠️ **Não tente consumir tudo de uma vez.** A maestria em Java leva anos. Foque em um nível por vez e pratique intensamente.
