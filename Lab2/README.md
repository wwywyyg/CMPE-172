# Screen shot & Discussion 

## spring_MVC_SC
This is the screen shot of Spring_MVC demo 
![Spring_MVC_SC](https://github.com/wwywyyg/CMPE-172/blob/main/Lab2/Images/Spring_MVC_SC.png)

## Spring Lombok Function Screen Shot and Discussion 

# 1.ValAndVarUserDemo & Discussion 
The ValAndVarUserDemo_SC is the screenshot of the ValAndVarUserDemo function output.
![ValAndVarUserDemo_SC](https://github.com/wwywyyg/CMPE-172/blob/main/Lab2/Images/ValAndVarUserDemo_SC.png)

```
a)This demo is testing the "val" and "var" features.

b)"val" is to for statement local variable, also the variable will  claim the variable to   final variable if use "val",
  "var" is almost the same with "val" the different is "var" not claim variable to final.
  from the code we can see that the initial value of "money" is 53, but it's use var statement , after reassignment, the value is 80.
  The output is show that the value is 80.
```

# 2.FieldLevelGetterSetterDemo & Discussion 
The FieldLevelGetterSetterDem_SC is the screenshot of the FieldLevelGetterSetterDem function output.
![FieldLevelGetterSetterDem](https://github.com/wwywyyg/CMPE-172/blob/main/Lab2/Images/FieldLevelGetterSetterDemo_SC.png)

```
a)This demo is testing the @getter and @setter annotations.

b)From the output, the methods shows the get and set fo the username, also the get of the user age. 
  From source code , we can see that there are @Getter and @ Setter above userName, @Getter above userAge.
```


# 3.GetterSetterUserDemo & Discussion 
The GetterSetterUserDemo_SC is the screenshot of the GetterSetterUserDemo function output.
![GetterSetterUserDemo_SC](https://github.com/wwywyyg/CMPE-172/blob/main/Lab2/Images/GetterSetterUserDemo_SC.png)

```
a)This demo is for the getter and setter annotation methods.

b)From the source code, we can see that the @Getter and @Setter are above the GetterSetterUserDemo Class,
  it's generate setter and getter for userID,userName and userAge. 
  we can check that from the output. each variable has getter and setter, the setter parameter of userID and UserAge are int,
  for userName is string. 
```

# 4.ConstructorUserDemo & Discussion
The ConstructorUserDemo_SC is the screenshot of the ConstructorUserDemo function output.
![ConstructorUserDemo](https://github.com/wwywyyg/CMPE-172/blob/main/Lab2/Images/ConstructorUserDemo_SC.png)

```
a)This demo is for testing Constructor annotation

b)from source code we can see there are @NoArgsconstructor and @AllArgsconstructor,NoArgsconstructor is generate a constructor with no parameter.
  AllArgsconstructor is generates a constructor with 1 parameter for each field in your class.

```

# 5.DataUserDemo & Discussion
The DataUserDemo_SC is the screenshot of the DataUserDemo function output.

```
a)This demo is test @data annotation. 

b)Use @data is means you have add @Getter/@Setter , @ToString, @EqualsAndHashCode and @RequiredArgsConstructor annotations in the same time.
  From the output, we can see the setter and getter of each filed in the class.

```

# 6.NonNullUserDemo & Discussion
The NonNullUserDemo_SC is the screenshot of the NonNullUserDemo function output.
![NonNullUserDemo](https://github.com/wwywyyg/CMPE-172/blob/main/Lab2/Images/NonNullUserDemo_SC.png)

```
a)This demo is test the @NoNull annotation.

b)NoNull is judge the object is null or not null, if it's null, it will throw NullPointerException.
  In source code , there is @NoNull before string userName, and the output is throw the  NullPointerException,  means  the userName is Null.
```