
## 中文说明｜Normative Scope

**WorldSeed 并不是一个学习理论、智能理论或认知解释体系。**  
它不解释学习如何发生、表示如何形成、泛化为何存在。

WorldSeed 专注于一个**严格狭窄的语义切面**：  
当学习结果被**主张、比较或解释**时，必须满足的前提条件。

具体而言，WorldSeed 要求任何此类主张都必须建立在**显式声明的世界**之上，包括但不限于：

- 世界身份（world identity）  
- 可执行动作（admissible actions）  
- 观察者及感知边界（observers & sensing boundaries）  
- 数值语义（numerical semantics）  
- 不可逆降解（irreversible degradation）

WorldSeed **不评判经验性能或实用效果**。  
其裁决只关乎**语义上的可比较性**，  
而非系统在工程上是否“有效”。

就此而言，WorldSeed 与学习机制是**正交的**；  
它是一种关于**学习结论的语义合同**，  
而不是对模型、数据集或基准的使用指南或设计规范。

---

### 📎 Normative Scope & Positioning (WorldSeed)

**WorldSeed is not a theory of learning, intelligence, or cognition.**  
It does not explain how learning happens, how representations form, or why models generalize.

WorldSeed operates on a strictly narrower semantic slice:  
it specifies the conditions under which learning outcomes may be meaningfully **claimed**, **compared**, or **interpreted**.

Concretely, WorldSeed requires that any such claim be grounded in an **explicitly declared world**, including:

- world identity  
- admissible actions  
- observers and sensing boundaries  
- numerical semantics  
- irreversible degradation

WorldSeed does **not** judge empirical performance or practical utility.  
Its verdicts concern **semantic comparability only**, not whether a system “works” in practice.

In this sense, WorldSeed is **orthogonal to learning mechanisms**.  
It functions as a **semantic contract on learning claims**,  
not as a prescription for models, datasets, or benchmarks.

---
### Semantic Scope

WorldSeed 提供的是一个前置的语义一致性层，
适用于那些基于观测过程、学习表示，
或跨系统 / 实验比较而产生的结论主张。

它不改变既有形式体系的内部数学结构，
也不规定模型、方法或算法的选择。<br>

WorldSeed 约束的是：
这些形式体系所产生的结果，
在何种条件下可以被有意义地解释为
关于同一个世界的陈述。

这类结论形式包括但不限于：
学习系统、统计推断、仿真研究以及经验评估流程。

---

WorldSeed provides a pre-model semantic consistency layer
for claims derived from observational processes, learned representations,
or comparative evaluation across systems or experiments.

It does not alter the internal mathematics of existing formalisms,
nor does it prescribe models, methods, or algorithms.
Instead, it constrains the conditions under which results produced by such formalisms
may be meaningfully interpreted as statements about the same world.

This includes, but is not limited to,
learning-based systems, statistical inference,
simulation-based studies, and empirical evaluation pipelines.

---

## 🔗 链接与引用 (Links & References)
WorldSeed 项目包含以下核心组件：

- **主仓库 (Core):** [worldseed](https://github.com/uulong950/worldseed)
- **规范标准 (Spec):** [worldseed-spec](https://github.com/uulong950/worldseed-spec)
- **检查工具 (Lint):** [worldseed-lint](https://github.com/uulong950/worldseed-lint)

📄 **相关论文/记录:** [Zenodo Record](https://zenodo.org/records/18083337)

### 📚 引用格式 (Citation)

如果您在研究或项目中使用了 WorldSeed，请引用以下 BibTeX：


@misc{worldseed_2025,
  title  = {WorldSeed: Axiomatic Specification and Infrastructure for Physically Learnable Worlds}, 
  author = {Zhang, Xiaolong},
  year   = {2025},
  month  = {12},
  day    = {29},
  url    = {[https://zenodo.org/records/18083337](https://zenodo.org/records/18083337)},
  doi    = {10.5281/zenodo.18083337},
  note   = {Zenodo Record 18083337}
}

### 📘 Further Reading

For concrete examples of how WorldSeed affects the interpretation
and comparability of learning results, see:

- Blog-01: When the World Becomes a First-Class Object
  (blogs/blog01.md)

These posts are illustrative, not normative.
The specification and lint rules remain the sole authority.

