# 2. Programming with OOPs

> * `POP` => Procedure Oriented Programming : C
> * `OOP` => Object Oriented Programming : C++,Dart,Java,C#,Python,etc

### - What is Object Oriented Programming ?

> OOP is Concept by which code becomes well structured, well Organized, well Secured and increases it's reusability.
> It is a concept where every procedure must be done through object.
> All the logical part of code will be done by object.

### - Principles of OOP :

> * 4 Principles OOP :
>
>   * 1. Encapsulation
>   * 2. Inheritence
>   * 3. Polymorphism
>   * 4. Data Abstraction


  #### 1. Encapsulation (to wrap/combine) :    
  > * Encapsulation means wrapping code as much as you can in a class.
  > * every logic must be written in class.
  > * It helps in hiding the implementation details and provides data protection.

  > * `Setter` 
  > * `Getter`
  > * `Constructor`
  > * `Destructor`


   #### 2. Inheritance (to share) :
  > * To Share Data class to another class.<br>
  > * data can be shared or accessed through multiple class
  > * Types :<br>
  > * `Single` 
  > * `Multilevel`
  > * `Hierarchichal`
  > * `Multiple`
  > * `Hybrid` 


 #### 3. Polymorphism (to behave in multiple way) :
  > * methods can be duplicated with different singatures.
  > * 2 types :<br>
  > * `Compile Time : `<br>
  > * Method Overloading
  > * Operator Overloading 
  > * `Run Time`<br>
  > * Method Overriding(over writting)
  > * Virtual Function   


 #### 4. Data Abstraction (to secure) :
  > * decides where data will be accessed.
  > * `Access Modifiers : `<br>
  > * public
  > * private
  > * protected 
  > * `Abstract class`<br>
  > * pure virtual function 


### Class & Object :

  #### class : 
  > * One type of blueprint structure + UDF
  > * `Collection of Data Members(Attributes) and Data Member Functions(Methods).` 
<br><br>
> * Data Members == Variable == Attributes
> * Member Function == UDF == Methodes

 #### object : 
  > * `Instance(variable) of class.`
  > * reference of class.
  > * to access the attributes or methods of class we must create object of class.

<p><img src = "https://github.com/SJaynesh/CPP-Languge-Ch-02/assets/115562979/c8e53e10-b9e5-4d54-947f-dfd09f975f42.png" width=40% height=30%></p>
<p><img src = "https://github.com/SJaynesh/CPP-Languge-Ch-02/assets/115562979/53ecf52f-2846-417d-be7d-ee544d6e2df3.png" width=40% height=30%></p>


### Access Modifiers (public & private) :
> *  `private `

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




