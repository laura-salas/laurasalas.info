# UI Study - Midterm

## Intro

#### Autres types d'interfaces

* Interface humain-objet
* Interface humain-produit

#### Definition: what is a Human-Machine-interface?

In industrial settings, HMIs can be used to:

- Visually display data
- Track production time, trends, and tags
- Oversee KPIs
- Monitor machine inputs and outputs
- And more

#### Common uses of HMIs

HMIs communicate with **Programmable Logic Controllers (PLCs)** and **input/output sensors** to get and display information for users to view. 

**HMI screens can be used for a single function, like monitoring and tracking**, or for performing more sophisticated operations, like switching machines off or increasing production speed, depending on how they are implemented.

-----

#### La question centrale:

Supposons que: 

* l’utilisateur sait ce qu’il veut faire 
* l’objet en est capable

### Est-ce que l’interface permet à l’utilisateur de faire ce qu’il veut?

plus précisement:

### Dans quelle mesure l'interface permet-t- elle à l'utilisateur de faire ce qu'il veut?

----

#### Definition: Usability 

The **degree** to which a product can be **used** by specific users, to accomplish precise goals with effectiveness, effiency *and* satisfaction.

* **Effectiveness:** the product allows the user to reach the end goal that was expected.
* **Efficiency**: the user reaches the end result with as little effort or little time as possible.
* **Satisfaction**: comfort from the user/positive (subjective) feedback about the experience.

#### **The importance of usability**

* The product sells better 

  * The iPhone vs. IBM Simon

* Unusable websites are often abandoned

  * Source of frustration and often source of failure

* Badly used objects can be dangerous 

  

  <img src="image-20220224051154160.png">

#### The responsibility of making something usable

...goes to the designer



#### Mental and physical capabilities of a human user 



- l<img src="image-20220224051224616.png" style="float: right;" height="150em;">a perception (visuelle, tactile, auditive)
- la mémoire
- l’interprétation des informations cognitifs
- Prise des décisions
- la motricité, i.e., d’interagir physiquement avec les machines

(all but the last one )



##### Examples of theoretical models that simplify and formalize the process of conception that takes into account these cognitive and motor processes (from above)



<img src="image-20220224051410797.png">



-----

#### Getting to know the user 

* les objectifs
* les connaissances
* la terminologie
* la façon de travailler
* les éventuelles limitations de perception

##### How do we find this out?

* **Reflection**: think about how hanita would use this UI
* **Observation**: observe hanita using her apps
* **Surveys**: ask hanita why she do this 
* **Usage scenarios:** imagine hypothetical hanita with hypothetical UI

----

### Development and usability

 Analysing to better...

* Understand human performance<img src="image-20220224051457621.png" style="float: right;" width="300px;">
* Getting to know the user

###### However, creating a good UI from the first go is highly <u>unlikely</u>

### ...Enter: iterative development 

Design -> Prototype -> Evaluation

#### Why is it so hard to conceive good UIs?

* You're not the user and can't put yourself in their shoes as a programmer 
* The user is **always** right: recurrent problems are blamed on the system
* ...But the user *isn't* always right: users aren't always designers. They don't always know what's best for them.

---

----

## Performance humaine 

### Perception, mémoire, motricité

##### MOST problems with interfaces are due to the designer not recognizing the <u>limitations and tendency to be wrong</u> of humans

##### <span style=" background: transparent; background-image: linear-gradient(
    to right,
    rgba(255, 225, 0, 0.1),
    rgba(255, 225, 0, 0.7) 4%,
    rgba(255, 225, 0, 0.3)
  );padding: 0.2em 0.4em;border-radius: 0.8em 0.3em;">→ Mistake because of the **DESIGN**, **<u>NOT</u>** human error</span>



### The myth of human error 

Most humans are imperfect & inprevisible 

* Bad memory
* We don't see things that are right there
* We're really confused
* We tire ourselves and become annoying 

### What's actually to blame

* **Functionality** problem : what are the functions of the object? are they doing what i want them to do?
* **Visibility**: what's the current mode? control sequence: what control sequence must I do to obtain what I want?
*  <span style=" background: transparent; background-image: linear-gradient(
      to right,
      rgba(255, 225, 0, 0.1),
      rgba(255, 225, 0, 0.7) 4%,
      rgba(255, 225, 0, 0.3)
    );padding: 0.2em 0.4em;border-radius: 0.8em 0.3em; padding-left: 0.1em;">**<u>Feedback</u>**: how do I know if my operations went well? (!!!!)</span>
  * How do i know my button clicked properly??

### Goals of UX (User eXperience)/Usability

<img src="image-20220224051535725.png">



### ✨✨✨✨✨✨✨✨✨✨✨✨✨✨✨✨✨✨✨✨✨✨✨✨✨

### <img src="image-20220224042747232.png" style="float:left;" width="200px">  

### **EE<u>SUS</u>M** -> **E**fficacity, **E**fficiency, **S**ecurity, **U**sability, **S**implicity of Learning, **M**emorability 



EEEEE *sus* MMMMMMMMM

### ✨✨✨✨✨✨✨✨✨✨✨✨✨✨✨✨✨✨✨✨✨✨✨✨

#### <span style=" background: transparent; background-image: linear-gradient(to right,
    rgba(255, 225, 0, 0.1),
    rgba(255, 225, 0, 0.7) 4%,
    rgba(255, 225, 0, 0.3)
  );padding: 0.2em 0.4em;border-radius: 0.8em 0.3em; padding-left: 0.1em;">Definition: Usability</span>
The **degree** to which a product can be **used** by specific users, to accomplish precise goals with effectiveness, effiency *and* satisfaction.

* **Effectiveness:** the product allows the user to reach the end goal that was expected.
* **Efficiency**: the user reaches the end result with as little effort or little time as possible.
* **Satisfaction**: comfort from the user/positive (subjective) feedback about the experience.

* **Simplicity of learning**: the ease at which the users get used to and use the surface 
* **Visibility**: the ease to <u>**see** and **understand** the state</u> of the system 
* **Errors**:  measure of the quantitity of these, as well as their impact
* <span style="color: gray;">**Memorability** : the capacity to remember how to use the interface</span>

#### Where do designers go wrong? 

* They fail to understand the **range/variety** of **uses** and their **limitations**
* They don't foresee the different **contexts** for use 
* They **don't provide enough detailed instructions** of how to use it 
* They **don't communicate what was done, or don't provide any feedback** at all (lack of feedback)

####  Why is design so hard?

##### Tasks are complex and hard to define 

* the machine doesn't understand the goal of the user
* <span style=" background: transparent; background-image: linear-gradient(to right,
      rgba(255, 225, 0, 0.1),
      rgba(255, 225, 0, 0.7) 4%,
      rgba(255, 225, 0, 0.3)
    );padding: 0.2em 0.4em;border-radius: 0.8em 0.3em; padding-left: 0.1em;">how to distribute the tasks/responsibilities between the machine and the user? (!!!)</span>

##### Tasks are complex and unpredictable 

* **Users are often indecisive** 
* They use things in unpredictable ways 

##### Tasks are getting more and more complex 

* The **amount** of things to control is increasing constantly(!)
* **Feedback** is more complex, **less natural/intuitive** 
* **Errors ** are more serious/have more ramifications 

##### The pressure of the market 

* Adding functionalities isn't expensive (lies but ok)

* Adding controls/feedback is tho

* Design time is expeez

* Some consumers prefer a cost/visual design(?)

  

#### Definition: Performance & Human cognition 

The set of mental and physical capacities linked to cognitive processes 

**an actual example: ** At which speed can we press a button? 

**<u>not</u> an example:** how long can we survive at -24 C? (unrelated to us being mentally capable or not.)

#### Definition: Cognition 

The set of **mental processes** that contribute to the **functionning of knowledge**

* Acquiring knowledge
* Using knowledge 

##### Different types of knowledge:

* Know-how (procedure)
* Technical knowledge (the facts)
* Languages
* etc.



















---



## Principes de design

### Facilité d’apprendre, visibilité, erreurs, efficience



---

----

## 

## Techniques de design
### Analyse de tâches, prototypage, tests utilisateur



---

----

## 

## Évaluation
### Conception de tests, statistiques



---

----

## 

## Réalité virtuelle
### Interaction personne-robot