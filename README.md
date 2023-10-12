
# 2. Programming with OOPs

> * `POP` => Procedure Oriented Programming : C , Pascal , FORTRAN 
> * `OOP` => Object Oriented Programming : C++,Dart,Java,C#,Python,etc

<br/><br/>

### - What is Object Oriented Programming ?

> * OOP is Concept by which code becomes well structured, well Organized, well Secured and increases it's reusability.
> * It is a concept where every procedure must be done through object.
> * All the logical part of code will be done by object.
<br/><br/>
### - Principles of OOP :

> * 4 Principles OOP :
>
>   * 1. Encapsulation
>   * 2. Inheritence
>   * 3. Polymorphism
>   * 4. Data Abstraction

<br/><br/>
  #### 1. Encapsulation (to wrap/combine) :    
  > * Encapsulation means wrapping code as much as you can in a class.
  > * every logic must be written in class.
  > * It helps in hiding the implementation details and provides data protection.

  > * `Setter` 
  > * `Getter`
  > * `Constructor`
  > * `Destructor`

<br/><br/>
   #### 2. Inheritance (to share) :
  > * To Share Data class to another class.<br>
  > * data can be shared or accessed through multiple class
  > * Types :<br>
  > * `Single` 
  > * `Multilevel`
  > * `Hierarchichal`
  > * `Multiple`
  > * `Hybrid` 

<br/><br/>
 #### 3. Polymorphism (to behave in multiple way) :
  > * methods can be duplicated with different singatures.
  > * 2 types :<br>
  > * `Compile Time : `<br>
  > * Method Overloading
  > * Operator Overloading 
  > * `Run Time`<br>
  > * Method Overriding(over writting)
  > * Virtual Function   

<br/><br/>
 #### 4. Data Abstraction (to secure) :
  > * decides where data will be accessed.
  > * manage which data can be accessed through object. 
  > * `Access Modifiers : `<br>
  > * public
  > * private
  > * protected 
  > * `Abstract class`<br>
  > * pure virtual function

<br/><br/>
<p><img src = "https://github.com/SJaynesh/CPP-Languge-Ch-02/assets/115562979/009e97fc-1ee6-439e-b524-2d15c0253f22.png" width=60% height=50%></p>

https://github.com/SJaynesh/CPP-Languge-Ch-02/assets/115562979/62b1204a-2cb5-4d72-88d5-1b70ce6103b8

<br/><br/>
#### Two components of OOP :
 > `Class` <br/>
 > `Object` <br/>

<br/><br/>
### Class & Object :

  #### class : 
  > * One type of blueprint structure + UDF
  > * `Collection of Data Members(Attributes) and Data Member Functions(Methods).` 
<br><br>
> * Data Members == Variable == Attributes
> * Member Function == UDF == Methodes
<br/>
 #### object : 
  > * `Instance(variable) of class.`
  > * reference of class.
  > * to access the attributes or methods of class we must create object of class.
<br/><br/>
<p><img src = "https://github.com/SJaynesh/CPP-Languge-Ch-02/assets/115562979/c8e53e10-b9e5-4d54-947f-dfd09f975f42.png" width=40% height=30%></p>
<p><img src = "https://github.com/SJaynesh/CPP-Languge-Ch-02/assets/115562979/53ecf52f-2846-417d-be7d-ee544d6e2df3.png" width=40% height=30%></p>
<p><img src = "https://github.com/SJaynesh/CPP-Languge-Ch-02/assets/115562979/0b170d96-98cd-4c75-b10b-fcf5e32fafda.png" width=60% height=50%></p>

https://github.com/SJaynesh/CPP-Languge-Ch-02/assets/115562979/8cd02d9c-bc67-4177-95f6-a3ebf182743f


<br/><br/>
### Access Modifiers (public & private) :
  #### `private   (default)` :
  > * limited to class.
#### `public` :
  > *  can be accessed everywhere throgh object.
#### `protected` :
  > * can be accessed in derived class.
<br/><br/>

https://github.com/SJaynesh/CPP-Languge-Ch-02/assets/115562979/2476d498-66cd-41d1-a0ea-03e1c2c829d1

<br/>
<pre>
    Syntax:
				
				class ClassName {
					//access modifiers
					//attributes
					//methods
				};
				
				int main() {				
					ClassName objName;
					
					var = objName.attribute;
					objName.method();				
				}
  </pre>




