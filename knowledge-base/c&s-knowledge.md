# **C&S Concept Knowledge**

## **Concepts**

### **Barrier**

**Definition:** A Barrier is a constituent in a Challenging Situation that plays a hindering role with respect to the Goal of the Agent’s Intention.

| Property            | Value                                                                                                          |
| :------------------ | :------------------------------------------------------------------------------------------------------------- |
| **Type**            | Universal                                                                                                      |
| **Subtype**         | RoleMixin                                                                                                      |
| **Key Distinction** | A Barrier is not a free-standing problem label, but a role played by a constituent in a Challenging Situation. |
| **Parent**          | Constituent                                                                                                    |
| **Contrasts With**  | Challenge, Challenging Situation, Challenge Mechanism Description                                              |
| **Examples**        | Greta’s low finger strength, The high tightness of the jar lid                                                 |

---

### **Challenge**

**Definition:** A Challenge is a Relator that depends on a Practical Situation and on an Intention inhering in the Agent in that situation.

| Property            | Value                                                                                                                             |
| :------------------ | :-------------------------------------------------------------------------------------------------------------------------------- |
| **Type**            | Moment                                                                                                                            |
| **Subtype**         | Relator                                                                                                                           |
| **Key Distinction** | A Challenge grounds the relation in which a Practical Situation hinders or threatens the achievement of the Goal of an Intention. |
| **Parent**          | Relator                                                                                                                           |
| **Contrasts With**  | Barrier, Challenging Situation, Solution                                                                                          |
| **Examples**        | Greta’s difficulty in opening the medicine jar                                                                                    |

---

### **Challenging Situation**

**Definition:** A Challenging Situation is a Practical Situation that participates in a Challenge Relator.

| Property            | Value                                                                                                                            |
| :------------------ | :------------------------------------------------------------------------------------------------------------------------------- |
| **Type**            | Individual                                                                                                                       |
| **Subtype**         | Situation                                                                                                                        |
| **Key Distinction** | A Challenging Situation is a Practical Situation considered under the aspect that it hinders or threatens the Agent’s Intention. |
| **Parent**          | Practical Situation                                                                                                              |
| **Contrasts With**  | Practical Situation, Challenge                                                                                                   |
| **Examples**        | Greta’s jar-opening situation in which her low finger strength and the tight lid hinder her goal                                 |

---

### **Practical Situation**

**Definition:** A Practical Situation is a Situation that involves an Agent, an Intention inhering in that Agent, and a Plan Description that guides a course of action for achieving the Goal of that Intention.

| Property            | Value                                                                                                                             |
| :------------------ | :-------------------------------------------------------------------------------------------------------------------------------- |
| **Type**            | Individual                                                                                                                        |
| **Subtype**         | Situation                                                                                                                         |
| **Key Distinction** | A Practical Situation is action-oriented: it involves an Agent directed toward a Goal and acting according to a Plan Description. |
| **Parent**          | Situation                                                                                                                         |
| **Contrasts With**  | Situation, Challenging Situation                                                                                                  |
| **Examples**        | Greta’s situation of trying to open the medicine jar by gripping and unscrewing the lid                                           |

---

### **Solution Action**

**Definition:** A Solution Action is the concrete process that implements a Solution.

| Property            | Value                                                                                                                                                                |
| :------------------ | :------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| **Type**            | Individual                                                                                                                                                           |
| **Subtype**         | Event                                                                                                                                                                |
| **Key Distinction** | A Solution Action is the actual process or activity through which a Solution is carried out, whereas a Solution Description specifies or guides what should be done. |
| **Parent**          | Event                                                                                                                                                                |
| **Contrasts With**  | Solution Description, Plan Description                                                                                                                               |
| **Examples**        | Greta’s actual finger-training activity, Greta’s actual use of a jar opener, The actual transfer of medicine to an easier-to-open container                          |

---

### **Solution Description**

**Definition:** A Solution Description is an action-guiding description that specifies how a Solution is intended to transform a Challenging Situation into one in which the Agent’s Goal is easier to achieve.

| Property            | Value                                                                                                                                                                                                                                                  |
| :------------------ | :----------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| **Type**            | Social Object                                                                                                                                                                                                                                          |
| **Subtype**         | Plan Description                                                                                                                                                                                                                                       |
| **Key Distinction** | A Solution Description specifies how a Solution should be carried out; it is not the concrete process that implements the Solution.                                                                                                                    |
| **Parent**          | Normative Description                                                                                                                                                                                                                                  |
| **Contrasts With**  | Solution Action, Challenge Mechanism Description                                                                                                                                                                                                       |
| **Examples**        | A description specifying that Greta should strengthen her fingers before opening the jar, A description specifying that Greta should use a jar opener, A description specifying that the medicine should be transferred to an easier-to-open container |

## **Relation Triples**

| Subject               | Predicate       | Object                        |
| :-------------------- | :-------------- | :---------------------------- |
| Barrier               | is_a            | RoleMixin                     |
| Barrier               | role_played_by  | Constituent                   |
| Barrier               | part_of         | Challenging Situation         |
| Challenge             | is_a            | Relator                       |
| Challenge             | depends_on      | Practical Situation           |
| Challenge             | depends_on      | Intention                     |
| Challenge             | grounds         | hinders_or_threatens relation |
| Challenging Situation | is_a            | Practical Situation           |
| Challenging Situation | participates_in | Challenge                     |
| Practical Situation   | is_a            | Situation                     |
| Practical Situation   | has_constituent | Agent                         |
| Practical Situation   | has_constituent | Intention                     |
| Practical Situation   | has_constituent | Plan Description              |
| Solution Action       | is_a            | Event                         |
| Solution Action       | implements      | Solution                      |
| Solution Description  | is_a            | Plan Description              |
| Solution Description  | specifies       | Solution Action               |
| Solution Description  | transforms      | Challenging Situation         |

## **Usage Notes**

* Distinguish carefully between Challenge and Barrier.
* Use Challenge for the Relator that grounds the hindering relation.
* Use Barrier for a constituent that plays a hindering role in a Challenging Situation.
* Use Challenging Situation only for a Practical Situation that participates in a Challenge.
* Use Solution Description for the action-guiding specification of a Solution.
* Use Solution Action for the concrete process through which the Solution is implemented.

