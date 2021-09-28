# Pair Programming Team

1. Teddy Omondi

2. Felix  obiero



# Table of Content

This week topics

1. [Float](#float)
2. [Flex](#flex)
3. [table](#table)

<a name="float"></a>
## 1. Float

Lorem Ipsum is simply dummy text of the printing and typesetting industry. Lorem Ipsum has been the industry's standard dummy text ever since the 1500s, when an unknown printer took a galley of type and scrambled it to make a type specimen book. It has survived not only five centuries, but also the leap into electronic typesetting, remaining essentially unchanged. It was popularised in the 1960s with the release of Letraset sheets containing Lorem Ipsum passages, and more recently with desktop publishing

Lorem Ipsum is simply dummy text of the printing and typesetting industry. Lorem Ipsum has been the industry's standard dummy text ever since the 1500s, when an unknown printer took a galley of type and scrambled it to make a type specimen book. It has survived not only five centuries, but also the leap into electronic typesetting, remaining essentially unchanged. It was popularised in the 1960s with the release of Letraset sheets containing Lorem Ipsum passages, and more recently with desktop publishing

<a name="flex"></a>
## 2. Flex Property


The Flexible Box Module, usually referred to as flexbox, was designed as a one-dimensional layout model, and as a method that could offer space distribution between items in an interface and powerful alignment capabilities.
1. The FlexBox Axis
    When working with flexbox you need to think in terms of two axes — the main axis and the cross axis. The main axis is defined by the flex-direction property, and the cross axis runs perpendicular to it. Everything we do with flexbox refers back to these axes, so it is worth understanding how they work from the outset.

<h3>The row main axis</h3>
<br>
<img src="https://developer.mozilla.org/en-US/docs/Web/CSS/CSS_Flexible_Box_Layout/Basic_Concepts_of_Flexbox/basics1.png">

<h3>The column main axis</h3>
<br>
<img src="https://developer.mozilla.org/en-US/docs/Web/CSS/CSS_Flexible_Box_Layout/Basic_Concepts_of_Flexbox/basics2.png">

<br>
<p>An Example of a simple flexbox implementation is: </p>
<br>

```css
main {
  display: flex;
  flex-direction: column;
  
}
```



<a name="table"></a>
## 3. table

The table HTML element represents tabular data — that is, information presented in a two-dimensional table comprised of rows and columns of cells containing data.

<p>The code below shows implementation of simple table in html</p>
<br>

```html
<table>
   <tr>    
     <th>Team</th>
     <th>Points</th>
   </tr>
   <tr>
    <td>M Blue</td>
    <td>52</td>
   </tr>
   <tr>
    <td>Tots</td>
    <td>50</td>
   </tr>
   <tr>
    <td>Poolers</td>
    <td>48</td>
   </tr>
   <tr>
    <td>Shooters</td>
    <td>47</td>
   </tr>
  </table> 
  ```

  Now lets add some styling to the table 

  ```css 
table,td,th{
  padding: 5px;
  border: 2px solid black;
  border-collapse: collapse;
}
table{
  width: 400px;
}
th{
  background-color: blue;
  color: white;
}
```

### Our final results will be :

<table style="width: 400px; border: 2px solid black; padding: 5px;">

   <tr>    
     <th style="background-color: blue; ">Team</th>
     <th style="background-color: blue; ">Points</th>
   </tr>
   <tr>
    <td>M Blue</td>
    <td>52</td>
   </tr>
   <tr>
    <td>Tots</td>
    <td>50</td>
   </tr>
   <tr>
    <td>Poolers</td>
    <td>48</td>
   </tr>
   <tr>
    <td>Shooters</td>
    <td>47</td>
   </tr>
  </table> 

