# **UFO Core Knowledge (Version 1.1)**

**Purpose:** Concise description of core UFO elements for GPT retrieval and reasoning in ontology-informed analysis and modelling.

## **Conventions**

* Terms are listed in alphabetical order.  
* Each entry has one canonical term.  
* Definitions are short and operational.    
* Moment is a dependent endurant.  
* Plan Description is treated as a subtype of Normative Description.

## **Concepts**

### **Category**

**Definition:** A Category is a rigid non-sortal universal that captures essential properties shared by instances of different identity-supplying types, without supplying an identity criterion of its own.

| Property | Value |
| :---- | :---- |
| **Type** | Universal |
| **Subtype** | Non-sortal, rigid |
| **Key Distinction** | Unlike a Kind, a Category does not provide identity conditions. |
| **Parent** | Universal |
| **Contrasts With** | Kind |
| **Examples** | Physical Object |

### **Constituent**

**Definition:** A Constituent is something that forms part of a Situation.

| Property | Value |
| :---- | :---- |
| **Type** | Situation-related notion |
| **Subtype** | Constitutive part |
| **Key Distinction** | A Constituent is not a basic ontological category like Endurant or Perdurant, but a role something plays within a Situation. |
| **Parent** | Situation-related notion |
| **Contrasts With** | Situation, Situation Type |
| **Examples** | Greta in the jar-opening case, The medicine jar, Greta's finger strength, A plan for opening the jar |

### **Endurant**

**Definition:** An Endurant is an individual that is wholly present whenever it exists.

| Property | Value |
| :---- | :---- |
| **Type** | Individual |
| **Subtype** | Wholly present entity |
| **Key Distinction** | Unlike a Perdurant, an Endurant does not unfold through temporal parts in the same way as an event or process. |
| **Parent** | Individual |
| **Contrasts With** | Perdurant |
| **Examples** | A person, A hospital, A medicine jar |

### **Individual**

**Definition:** An Individual is a particular entity that exists as a single instance and can instantiate Universals.

| Property | Value |
| :---- | :---- |
| **Type** | Most general ontological category |
| **Subtype** | Particular |
| **Key Distinction** | An Individual is particular, whereas a Universal is general. |
| **Parent** | None |
| **Contrasts With** | Universal |
| **Examples** | Greta, This specific jar, This treatment event |

### **Intrinsic Moment**

**Definition:** An Intrinsic Moment is a dependent entity that inheres in a single bearer and cannot exist independently of that bearer.

| Property | Value |
| :---- | :---- |
| **Type** | Moment |
| **Subtype** | Dependent on a single bearer (Mode, Quality) |
| **Key Distinction** | Intrinsic Moments depend on one bearer, whereas Relators connect multiple bearers. |
| **Parent** | Moment |
| **Contrasts With** | Relator |
| **Examples** | A person's pain, Greta's finger strength, The colour of the jar |

### **Kind**

**Definition:** A Kind is a rigid sortal universal that provides an identity principle for its instances.

| Property | Value |
| :---- | :---- |
| **Type** | Universal |
| **Subtype** | Sortal, rigid |
| **Key Distinction** | A Kind tells us what an entity fundamentally is and supplies identity criteria. |
| **Parent** | Universal |
| **Contrasts With** | Category, Subkind, Role, Phase |
| **Examples** | Person, Organisation, Jar |

### **Mode**

**Definition:** A Mode is an Intrinsic Moment that is not naturally represented in a value space in the way Qualities are.

| Property | Value |
| :---- | :---- |
| **Type** | Intrinsic Moment |
| **Subtype** | Non-qualitative dependent entity |
| **Key Distinction** | A Quality is typically measurable in a quality space, whereas a Mode is usually not. |
| **Parent** | Intrinsic Moment |
| **Contrasts With** | Quality |
| **Examples** | Greta's finger strength, A person's belief, A system's fragility |

### **Moment**

**Definition:** A Moment is a dependent entity that cannot exist on its own but must inhere in or depend on other entities.

| Property | Value |
| :---- | :---- |
| **Type** | Dependent Endurant |
| **Subtype** | Existentially dependent entity (Intrinsic Moment, Relator) |
| **Key Distinction** | Moments are contrasted with Substantials, which can exist independently. |
| **Parent** | Endurant |
| **Contrasts With** | Substantial, Perdurant |
| **Examples** | A colour, A capacity, A marriage, A legal obligation |

### **Normative Description**

**Definition:** A Normative Description is a description that defines norms, rules, permissions, obligations, prohibitions, or other normative structures recognized in a social context.

| Property | Value |
| :---- | :---- |
| **Type** | Social Object |
| **Subtype** | Description with normative force |
| **Key Distinction** | It does not merely describe reality, but specifies how agents ought, may, or must act, or how institutional reality is structured. |
| **Parent** | Social Object |
| **Contrasts With** | Proposition, Plan Description |
| **Examples** | A law, A policy, A contract, A regulation |

### **Perdurant**

**Definition:** A Perdurant is an individual that unfolds in time and has temporal parts.

| Property | Value |
| :---- | :---- |
| **Type** | Individual |
| **Subtype** | Temporally extended entity |
| **Key Distinction** | Unlike an Endurant, a Perdurant is not wholly present at each moment of its existence. |
| **Parent** | Individual |
| **Contrasts With** | Endurant, Moment |
| **Examples** | A surgery, A meeting, A care process, A movement |

### **Phase**

**Definition:** A Phase is an anti-rigid sortal universal that classifies entities based on intrinsic but contingent conditions.

| Property | Value |
| :---- | :---- |
| **Type** | Universal |
| **Subtype** | Sortal, anti-rigid |
| **Key Distinction** | An entity can enter or leave a Phase while remaining the same individual. A Phase differs from a Role, which depends on relational context. |
| **Parent** | Universal |
| **Contrasts With** | Role, PhaseMixin |
| **Examples** | Child, Adult, Broken Device |

### **PhaseMixin**

**Definition:** A PhaseMixin is an anti-rigid non-sortal universal whose instances may belong to different identity-supplying types, but which is still based on intrinsic contingent conditions rather than relational ones.

| Property | Value |
| :---- | :---- |
| **Type** | Universal |
| **Subtype** | Non-sortal, anti-rigid |
| **Key Distinction** | Like a Phase, it is based on contingent intrinsic conditions; unlike a Phase, it does not assume one common identity principle for all instances. |
| **Parent** | Universal |
| **Contrasts With** | Phase, RoleMixin |
| **Examples** | Temporarily Disabled Entity |

### **Plan Description**

**Definition:** A Plan Description is a description of an intended course of action, typically specifying how an agent may act in order to achieve some goal.

| Property | Value |
| :---- | :---- |
| **Type** | Normative Description |
| **Subtype** | Action-oriented description |
| **Key Distinction** | A Plan Description is action-oriented, whereas a Proposition describes a situation that may be satisfied or not satisfied. |
| **Parent** | Normative Description |
| **Contrasts With** | Proposition |
| **Examples** | A treatment plan, A procedure for opening a sealed container, A workflow specification |

### **Proposition**

**Definition:** A Proposition is an abstract content that specifies a possible or desirable situation and can be satisfied or not satisfied by reality.

| Property | Value |
| :---- | :---- |
| **Type** | Abstract Object |
| **Subtype** | Intentional content |
| **Key Distinction** | A Proposition is not itself a concrete Situation; it is what a belief, desire, or goal is about. |
| **Parent** | Abstract Object |
| **Contrasts With** | Situation, Situation Type, Plan Description, Normative Description |
| **Examples** | The medicine jar is open, The patient has access to medication |

### **Quality**

**Definition:** A Quality is an Intrinsic Moment that can be located in a quality space and is typically measurable or characterizable by values.

| Property | Value |
| :---- | :---- |
| **Type** | Intrinsic Moment |
| **Subtype** | Value-space dependent entity |
| **Key Distinction** | Unlike a Mode, a Quality is typically associated with dimensions such as colour, weight, temperature, or height. |
| **Parent** | Intrinsic Moment |
| **Contrasts With** | Mode |
| **Examples** | The jar's weight, Greta's height, The lid's tightness |

### **Relator**

**Definition:** A Relator is a dependent entity that mediates a relation between two or more bearers.

| Property | Value |
| :---- | :---- |
| **Type** | Moment |
| **Subtype** | Relationally dependent entity |
| **Key Distinction** | A Relator depends on multiple entities and grounds a material relation among them, whereas an Intrinsic Moment depends on only one bearer. |
| **Parent** | Moment |
| **Contrasts With** | Intrinsic Moment |
| **Examples** | A marriage, An employment relation, A treatment agreement |

### **Role**

**Definition:** A Role is an anti-rigid sortal universal that an entity instantiates only in a relational context.

| Property | Value |
| :---- | :---- |
| **Type** | Universal |
| **Subtype** | Sortal, anti-rigid |
| **Key Distinction** | A Role depends on external relations, whereas a Phase depends on intrinsic contingent conditions. |
| **Parent** | Universal |
| **Contrasts With** | Phase, RoleMixin |
| **Examples** | Student, Patient, Customer, Supplier |

### **RoleMixin**

**Definition:** A RoleMixin is an anti-rigid non-sortal universal that depends on relational context and can be instantiated by entities with different identity principles.

| Property | Value |
| :---- | :---- |
| **Type** | Universal |
| **Subtype** | Non-sortal, anti-rigid |
| **Key Distinction** | It is the non-sortal counterpart of a Role. |
| **Parent** | Universal |
| **Contrasts With** | Role, PhaseMixin |
| **Examples** | Customer-like Party, Insured Party |

### **Scene**

**Definition:** A Scene is a temporally extended whole composed of temporally related Situations.

| Property | Value |
| :---- | :---- |
| **Type** | Temporally Extended Whole |
| **Subtype** | Whole composed of temporally related situations |
| **Key Distinction** | A Situation is a particular configuration treated as a whole; a Scene unifies multiple such configurations into a larger whole across time. |
| **Parent** | Temporally Extended Whole |
| **Contrasts With** | Situation, Situation Type |
| **Examples** | A medical consultation scene, A patient discharge scene, A jar-opening attempt from start to finish |

### **Situation**

**Definition:** A Situation is a concrete complex of entities, properties, and relations that obtains in reality and can be grasped as a whole.

| Property | Value |
| :---- | :---- |
| **Type** | Individual |
| **Subtype** | Concrete complex |
| **Key Distinction** | A Situation is concrete and particular, whereas a Situation Type is general and a Proposition is abstract. |
| **Parent** | Individual |
| **Contrasts With** | Situation Type, Proposition, Scene |
| **Examples** | Greta holding a closed jar while lacking the strength to open it |

### **Situation Type**

**Definition:** A Situation Type is a universal whose instances are Situations sharing a certain structure.

| Property | Value |
| :---- | :---- |
| **Type** | Universal |
| **Subtype** | Universal over situations |
| **Key Distinction** | A Situation Type is general, whereas a Situation is particular. |
| **Parent** | Universal |
| **Contrasts With** | Situation, Proposition |
| **Examples** | Person unable to open container, Patient undergoing examination |

### **Subkind**

**Definition:** A Subkind is a rigid specialization of a Kind that inherits the identity principle of that Kind.

| Property | Value |
| :---- | :---- |
| **Type** | Universal |
| **Subtype** | Sortal, rigid |
| **Key Distinction** | A Subkind refines a Kind without introducing a new identity criterion. |
| **Parent** | Kind |
| **Contrasts With** | Kind, Role, Phase |
| **Examples** | Woman as a subkind of Person, Hospital as a subkind of Organisation |

### **Substantial**

**Definition:** A Substantial is an existentially independent Endurant, that is, an entity that can exist in its own right rather than depending on another bearer.

| Property | Value |
| :---- | :---- |
| **Type** | Endurant |
| **Subtype** | Existentially independent endurant |
| **Key Distinction** | A Substantial contrasts with a Moment, which depends on something else in order to exist. |
| **Parent** | Endurant |
| **Contrasts With** | Moment |
| **Examples** | A person, An organisation, A jar |

### **Universal**

**Definition:** A Universal is a general type that can be instantiated by multiple Individuals.

| Property | Value |
| :---- | :---- |
| **Type** | General ontological category |
| **Subtype** | Repeatable type |
| **Key Distinction** | A Universal is repeatable across many instances, whereas an Individual is a particular instance. |
| **Parent** | None |
| **Contrasts With** | Individual |
| **Examples** | Person, Patient, Situation Type, Quality Type |

## **Relation Triples**

| Subject | Predicate | Object |
| :---- | :---- | :---- |
| Category | is\_a | Universal |
| Constituent | part\_of | Situation |
| Endurant | is\_a | Individual |
| Intrinsic Moment | is\_a | Moment |
| Kind | is\_a | Universal |
| Mode | is\_a | Intrinsic Moment |
| Moment | is\_a | Endurant |
| Normative Description | is\_a | Social Object |
| Perdurant | is\_a | Individual |
| Phase | is\_a | Universal |
| PhaseMixin | is\_a | Universal |
| Plan Description | is\_a | Normative Description |
| Proposition | is\_a | Abstract Object |
| Quality | is\_a | Intrinsic Moment |
| Relator | is\_a | Moment |
| Role | is\_a | Universal |
| RoleMixin | is\_a | Universal |
| Scene | composed\_of | Situation |
| Situation | is\_a | Individual |
| Situation | has\_part | Constituent |
| Situation Type | is\_a | Universal |
| Situation | instantiates | Situation Type |
| Situation | may\_satisfy | Proposition |
| Subkind | is\_a | Universal |
| Subkind | specializes | Kind |
| Substantial | is\_a | Endurant |
| Universal | contrasts\_with | Individual |
| Individual | instantiates | Universal |
| Intrinsic Moment | contrasts\_with | Relator |
| Quality | contrasts\_with | Mode |
| Role | contrasts\_with | Phase |
| RoleMixin | contrasts\_with | PhaseMixin |
| Moment | contrasts\_with | Substantial |
| Endurant | contrasts\_with | Perdurant |

## **Usage Notes**

* Prefer canonical terms exactly as listed.  
* Distinguish carefully between Individual and Universal.  
* Distinguish carefully between Endurant and Perdurant.  
* Distinguish carefully between Substantial and Moment.  
* Distinguish carefully between Intrinsic Moment and Relator.  
* Distinguish carefully between Mode and Quality.  
* Distinguish carefully between Role and Phase.  
* Distinguish carefully between Situation, Situation Type, and Proposition.  
* Use Scene for a temporally extended whole composed of situations.  
* Use Plan Description when the emphasis is on intended action.
