# Microservices

### Are Microservices an option for M&T?

---

## Two worlds out there

- Gurus |
- Party poopers |

---

## Know your buzzword
### Guru: Martin Fowler

- [A definition (2014)](https://martinfowler.com/articles/microservices.html)
- [A guide](https://martinfowler.com/microservices/)
- [A talk](https://www.youtube.com/watch?v=wgdBVIX9ifA)
- Some noise
  - [Bounded Contexts (DDD)](https://martinfowler.com/bliki/BoundedContext.html)
  - [Blue-Green Deployments](https://martinfowler.com/bliki/BlueGreenDeployment.html)
  - [Phoneix Servers](https://martinfowler.com/bliki/PhoenixServer.html)
  - Etc

---

## Know your buzzword
### Guru: Martin Fowler

- Componentization via Services
- Organized around Business Capabilities
- Products not Projects
- Smart endpoints and dumb pipes
- Decentralized Governance
- Decentralized Data Management
- Infrastructure Automation
- Design for failure
- Evolutionary Design

---

## Know your buzzword
### The Book

![Building Microservices](https://martinfowler.com/articles/microservices/images/sam-book.jpg)

---

## Underlying Concerns

- Are Microservices just SOA? |
- How big is a microservice? |

---

## MicroServices vs SOA

- SOA, different definitions for different people. For some of them, this means ESB. But ESB are not compatible with third Microservices common caracteristic.
- MicroServices ⊂ SOA. Microservices architecture is a subset of SOA.

---

## Advantages

* Different technologies per components
* Component internal evolution minimise impacts compared to a functionnality or module evolution within a Monolith
* Different Microservices deployed on different machines compared to a Monolith cluster.
  * If Microservice A is more loaded than B, A can be scaled horizontally but not B

---

## Advantages

* Feature teams organization (Catalog, order management, ...) compared to teams organized by technologies (DBA, .Net Devs, ...)
* No unique database mess which leads to hard model refactoring, deadlocks between different functionalities.
* Platform / Technologies best suited for a specific Microservice

---

### Monolith vs MicroService

| _Monolith_   |     _Microservice_      |
|----------|:-------------:|
| Simplicity |  Partial deployment |
| Consistence |    Avaibility   |
| Inter-module refactoring | Preserve modularity |
|  | Platform / Technology best suited |

---

## Prerequisites
* Rapid provisioning (rapid environment set-up)
* Basic monitoring
* Rapid applications deployment
* Devops culture

---

## Party Poopers

[Microservices architecture: What the gurus say about it](https://herbertograca.com/2017/01/26/microservices-architecture/)
> Most of the projects don’t need a Microservices Architecture, what they need is a good architecture

---

## Party Poopers

[The Death of Microservice Madness in 2018](http://www.dwmkerr.com/the-death-of-microservice-madness-in-2018/)
> Netflix are great at devops. Netfix do microservices. Therefore: If I do microservices, I am great at devops.

---

## Party Poopers

- Increased complexity for developers |
- Increased complexity for operators |
- Increased complexity for devops |
- It requires serious expertise |
- Real world systems often have poorly defined boundaries |

---

## Party Poopers

- The complexities of state are often ignored |
- The complexitities of communication are often ignored |
- Versioning can be hard |
- Distributed Transactions |
- Microservices can be monoliths in disguise |

---

## Party Poopers

[Questions](http://www.dwmkerr.com/content/images/2018/01/questions.png)
![Questions](http://www.dwmkerr.com/content/images/2018/01/questions.png)

---

## Some Balance

[Microservice Envy (2015)](https://www.thoughtworks.com/radar/techniques/microservice-envy)
> Some teams are rushing in to adopting microservices without understanding the changes to development, test, and operations. Our general advice remains simple. Avoid microservice envy and start with one or two services before rushing headlong into developing more, to allow your teams time to adjust and understand the right level of granularity.

---

## Some Balance

[Martin Fowler - Monolith First](https://martinfowler.com/bliki/MonolithFirst.html)
![Monolith First](https://martinfowler.com/bliki/images/microservice-verdict/path.png)

---

## Some Balance

[About When Not to Do Microservices](http://blog.christianposta.com/microservices/when-not-to-do-microservices/)
- If you’re the Pioneers, stick with monoliths |
- If you’re the Settlers, you may need microservices |
- If your’e the Town Planners, you may need microservices |

---

## Some Balance

[How to decompose a monolith](https://herbertograca.com/2017/01/26/microservices-architecture/#how-to-decompose-a-monolith)

---

### Questions?

---

### M&T: share your goals!!

---

### Thanks!
