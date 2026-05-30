# guia-como-ser-um-monge-do-java
Guias e fluxogramas para ir do básico ao especialista em Java
- Acesse as pastas para encontrar guias de estudo e fluxogramas com mapas mentais para a linguagem Java.
- Abaixo temos apenas um roadmap da linguagem como um todo.
- O conteudo estará em português, espanhol e inglês (Devido a necessidade de projetos estudo java nesses idiomas).

# Roadmap de Aprendizado Java

Este roadmap cobre desde os fundamentos da linguagem até tópicos de nível especialista, incluindo a JVM e ecossistema.

## 🟢 Nível Básico (Iniciante)

### 1. Introdução ao Java
- História e características
- JDK, JRE, JVM
- Instalação e configuração do ambiente
- Primeiro programa: Hello World

### 2. Sintaxe básica
- Estrutura de um arquivo `.java`
- Comentários (single line, multi line, javadoc)
- Palavras reservadas
- Convenções de nomenclatura

### 3. Tipos de dados primitivos
- `byte`, `short`, `int`, `long`
- `float`, `double`
- `char`, `boolean`
- Literais e conversões (casting implícito e explícito)

### 4. Variáveis e operadores
- Declaração e inicialização
- Operadores aritméticos, relacionais, lógicos
- Operadores de atribuição, incremento/decremento
- Operador ternário

### 5. Controle de fluxo
- `if`, `else if`, `else`
- `switch` (tradicional e com expressões)
- `for` (clássico e enhanced for)
- `while`, `do-while`
- `break`, `continue`, `return`

### 6. Arrays
- Declaração, criação e inicialização
- Acesso e modificação de elementos
- Arrays multidimensionais
- Atributo `length`

### 7. Strings
- Classe `String` (imutabilidade)
- Métodos principais (`length`, `charAt`, `substring`, `indexOf`, etc.)
- Concatenação e `StringBuilder` / `StringBuffer`
- Comparação (`equals`, `equalsIgnoreCase`, `compareTo`)

### 8. Escopo e tempo de vida de variáveis
- Variáveis locais, de instância e estáticas
- Shadowing

---

## 🟡 Nível Intermediário

### 9. Orientação a objetos (fundamentos)
- Classes e objetos
- Atributos e métodos
- Construtores (sobrecarga, encadeamento com `this()`)
- Modificadores de acesso (`private`, `default`, `protected`, `public`)

### 10. Encapsulamento
- Getters e setters
- JavaBeans

### 11. Herança
- `extends`
- Construtor e `super()`
- Sobrescrita de métodos (`@Override`)
- Classes e métodos `final`

### 12. Polimorfismo
- Referência de superclasse para subclasse
- Ligação dinâmica
- `instanceof`

### 13. Classes e membros estáticos
- `static` (atributos, métodos, blocos)
- Métodos de fábrica

### 14. Pacotes (packages)
- Declaração `package`
- Importação (`import`)
- Classpath básico

### 15. Tratamento de exceções
- `try`, `catch`, `finally`
- `throw`, `throws`
- Exceções checked vs unchecked
- Hierarquia: `Throwable`, `Exception`, `RuntimeException`, `Error`
- `try-with-resources` (Java 7+)

### 16. Enumerações (enums)
- Declaração básica
- Campos, construtores e métodos em enums

### 17. Collections Framework (parte 1)
- `List` (`ArrayList`, `LinkedList`)
- `Set` (`HashSet`, `TreeSet`, `LinkedHashSet`)
- `Queue` (`PriorityQueue`, `ArrayDeque`)
- Iteração: `for-each`, `Iterator`, `ListIterator`

### 18. Genéricos (básico)
- Classes e métodos genéricos
- Type safety
- Wildcards (`?`, `? extends T`, `? super T`)

### 19. Classes internas (nested classes)
- Member inner classes
- Local classes
- Anonymous classes

### 20. Expressões lambda (Java 8+)
- Sintaxe `(param) -> expressão`
- Interfaces funcionais (`@FunctionalInterface`)
- `java.util.function` (`Predicate`, `Consumer`, `Supplier`, `Function`)

### 21. Stream API (básico)
- Criação de streams
- Operações intermediárias (`filter`, `map`, `sorted`, `distinct`)
- Operações terminais (`collect`, `forEach`, `reduce`, `count`)

### 22. Datas e horas (java.time - Java 8+)
- `LocalDate`, `LocalTime`, `LocalDateTime`
- `ZonedDateTime`, `OffsetDateTime`
- `Period`, `Duration`
- Formatação (`DateTimeFormatter`)

### 23. Input/Output básico
- `File`, `Path`, `Paths`, `Files` (NIO.2)
- Leitura e escrita com `BufferedReader`, `BufferedWriter`
- Scanner

### 24. Concorrência básica
- `Thread` e `Runnable`
- `synchronized`
- `volatile`
- `Thread.sleep`, `join`

---

## 🔴 Nível Avançado

### 25. Collections Framework (profundo)
- `Map` (`HashMap`, `TreeMap`, `LinkedHashMap`, `ConcurrentHashMap`)
- Algoritmos de ordenação e busca (`Collections`, `Arrays`)
- Comparators (`Comparable` vs `Comparator`)
- Implementações thread-safe

### 26. Genéricos avançados
- Type erasure
- Bridge methods
- Recursive type bounds
- Wildcard capture

### 27. Anotações (annotations)
- Anotações padrão (`@Override`, `@Deprecated`, `@SuppressWarnings`)
- Criação de anotações customizadas
- Retentions (`SOURCE`, `CLASS`, `RUNTIME`)
- Processamento de anotações em tempo de execução (Reflection)

### 28. Reflection API
- Obter `Class` (`.class`, `getClass()`, `Class.forName()`)
- Inspecionar e invocar métodos
- Acessar/alterar campos privados
- Limitações e problemas de performance

### 29. Stream API avançada
- Streams paralelos (`parallelStream`)
- Coletores customizados (`Collector`)
- `flatMap`, `groupingBy`, `partitioningBy`
- Performance e pitfalls

### 30. Concorrência avançada (java.util.concurrent)
- `ExecutorService`, `ThreadPoolExecutor`
- `Callable`, `Future`, `CompletableFuture`
- `Lock`, `ReentrantLock`, `Condition`
- `Semaphore`, `CountDownLatch`, `CyclicBarrier`
- `BlockingQueue`, `ConcurrentHashMap`
- `Atomic` classes (`AtomicInteger`, `LongAdder`)
- `ForkJoinPool`

### 31. Padrões de projeto (design patterns) em Java
- Criacionais: Singleton, Factory, Builder, Prototype
- Estruturais: Adapter, Decorator, Proxy, Composite
- Comportamentais: Strategy, Observer, Command, Template Method

### 32. Módulos (Java Platform Module System - Java 9+)
- `module-info.java`
- Requisitos (`requires`, `requires transitive`)
- Exportação (`exports`, `exports ... to`)
- Serviços (`provides`, `uses`)

### 33. JVM internals (para especialista)
- Classloading (bootstrap, extension, application)
- Garbage Collection (G1, ZGC, Shenandoah, Serial, Parallel)
- Heap, stack, metaspace, código nativo
- Just-In-Time (JIT) compilation (C1, C2)
- Escape analysis, lock coarsening, inlining

### 34. Performance e tuning
- Ferramentas: JConsole, VisualVM, Mission Control, Async Profiler
- Análise de heap dump
- GC tuning flags
- Benchmarking com JMH

### 35. Programação funcional em Java
- Currying, partial application
- Monads (Optional, Stream)
- Pattern matching (previsto em versões futuras)
- Imutabilidade profunda

### 36. Serialização
- `Serializable` e `serialVersionUID`
- `transient`, `writeObject`, `readObject`
- Externalizable
- Cuidados de segurança

### 37. Networking
- `Socket`, `ServerSocket`
- `DatagramSocket` (UDP)
- `URL`, `HttpURLConnection`
- HttpClient (Java 11+)

### 38. Internacionalização (i18n)
- `Locale`, `ResourceBundle`
- Formatação de números, moedas, datas

---

## ⚫ Nível Especialista

### 39. Bytecode e manipulação de código
- Estrutura do arquivo `.class`
- Instruções da JVM (iconst, invokevirtual, etc.)
- Bibliotecas: ASM, Byte Buddy, Javassist

### 40. Agentes Java (Instrumentation)
- `java.lang.instrument`
- Carregamento dinâmico de agentes
- Transformação de bytecode em tempo de execução

### 41. Classloaders customizados
- Hierarquia e delegação
- Hot swapping
- Isolamento de classes

### 42. Concorrência sem bloqueios (lock-free)
- Algoritmos baseados em CAS
- Implementação de estruturas lock-free

### 43. Código nativo (JNI/JNA)
- Java Native Interface
- Chamada de bibliotecas C/C++

### 44. Segurança avançada
- Security Manager e Policy
- Criptografia (JCA/JCE): `MessageDigest`, `Cipher`, `KeyStore`
- Assinatura digital, certificados
- Classloaders seguros

### 45. Compilação antecipada (AOT) e GraalVM
- Native image
- Truffle framework

### 46. Construção de frameworks
- Injeção de dependência manual
- Processamento de anotações em tempo de compilação (APT)
- Proxies dinâmicos (`java.lang.reflect.Proxy`)

### 47. Internalização da memória
- `sun.misc.Unsafe` (limitações e perigos)
- `VarHandle` (Java 9+)
- Memory segments (Foreign Memory Access API)

### 48. Reactive programming
- Project Reactor (`Mono`, `Flux`)
- Compatibilidade com `Flow` (Java 9+)
- Backpressure

### 49. Testes avançados
- Mocks (Mockito, EasyMock)
- Testes de concorrência
- Testes de performance com JMH
- Mutation testing (PIT)

### 50. Troubleshooting e profiling em produção
- Análise de thread dumps
- Heap dumps e MAT
- Flight Recorder events
- Byteman para injeção de falhas

---

## 📚 Sugestão de ordem de estudos com projetos práticos

| Nível | Projeto sugerido |
|-------|------------------|
| Básico | Calculadora, jogo da velha no terminal |
| Intermediário | Sistema de biblioteca (CRUD com arquivos), app de tarefas com collections |
| Avançado | Servidor HTTP simples, framework de injeção de dependência |
| Especialista | Profiler customizado, framework de persistência ou agente Java para monitoramento |

---

## 🧰 Ferramentas recomendadas por nível

- **Básico:** IntelliJ IDEA (Community), Eclipse, VS Code + extensões Java
- **Intermediário:** Maven/Gradle, JUnit, Git
- **Avançado:** JMH, JProfiler/YourKit, VisualVM, Postman (para APIs)
- **Especialista:** ASM/ByteBuddy, JMH, GraalVM, Arthas, Byteman

---

## 📖 Referências úteis

- [Documentação oficial da Oracle](https://docs.oracle.com/en/java/)
- Effective Java (Joshua Bloch)
- Java Concurrency in Practice (Brian Goetz)
- The Java Virtual Machine Specification
- Baeldung, Java Code Geeks, InfoQ
