# table_html
Creating table using html and css style
<!DOCTYPE html>
<html lang="en">
  <head>
    <title>Food Preferences Survey Form</title>
    <meta charset="UTF-8" />
    <meta name="viewport" content="width=device-width" />
    <title>Food Preference Survey Form</title>
    <style>
    body{
        font-family:sans-serif;
    }
    th, td{
        padding:10px;
    }
    label{
        margin-right:20px;
    }
    button{
        margin:2px;
    }
    </style>
  </head>
  <body>
  <h1>Food Preferences - Survey Form<h1>
  <h5>Please fill out and submit the survey form at the earliest</h5>
  <hr />
  <form action="" method="post">
  <table>
   <tr>
     <td>1. Name</td>
     <td><input type="text" name="user"/></td>
   </tr>
   <tr>
    <td>2. Age</td>
    <td><input type="number" name="age" min="13" max="100"/><td>
   </tr>
   <tr>
    <td>3. Where do you eat most often?</td>
    <td>
    <input type="radio" id="home" name="location" value="home">
    <label for="home">at home</label>
    <input type="radio" id="work_or_school" name="location" value="work_or_school">
    <label for="work_or_school">at work /school</label>
    <input type="radio" id="restaurant" name="location" value="restaurant">
    <label for="restaurant">at a restaurant</label>
    </td>
   </tr>
   <tr>
    <td colspan="2">4. Specify, how often?</td>
   </tr>
   <tr>
    <td colspan="2">
      <table style="font-size: 0.7em; border: 1px solid">
        <thead>
         <th> </th>
         <th>everyday</th>
         <th>a few times a week</th>
         <th>once a week</th>
         <th>several times a month</th>
         <th>once a month</th>
         <th>less often than once a month</th>
        </thead>
   <tbody>
    <tr>
      <td>You prepare your own meals</td>
      <td style="text-align:center"><input type="radio" name="you prepare" value="every day"/></td>
      <td style="text-align:center"><input type="radio" name="you prepare" value="a few times a week"/></td>
      <td style="text-align:center"><input type="radio" name="you prepare" value="once a week"/></td>
      <td style="text-align:center"><input type="radio" name="you prepare" value="several times a month"/></td>
      <td style="text-align:center"><input type="radio" name="you prepare" value="once a month"/></td>
      <td style="text-align:center"><input type="radio" name="you prepare" value="less often than once a month"/></td>
    </tr>
    <tr>
      <td>You eat out</td>
      <td style="text-align:center"><input type="radio" name="you_eat_out" value="every day"/></td>
      <td style="text-align:center"><input type="radio" name="you_eat_out" value="a few times a week"/></td>
      <td style="text-align:center"><input type="radio" name="you_eat_out" value="once a week"/></td>
      <td style="text-align:center"><input type="radio" name="you_eat_out" value="several times a month"/></td>
      <td style="text-align:center"><input type="radio" name="you_eat_out" value="once a month"/></td>
      <td style="text-align:center"><input type="radio" name="you_eat_out" value="less often than once a month"/></td>
    </tr>
    <tr>
      <td>You order food for home</td>
      <td style="text-align:center"><input type="radio" name="you_order_food" value="every day"/></td>
      <td style="text-align:center"><input type="radio" name="you_order_food" value="a few times a week"/></td>
      <td style="text-align:center"><input type="radio" name="you_order_food" value="once a week"/></td>
      <td style="text-align:center"><input type="radio" name="you_order_food" value="several times a month"/></td>
      <td style="text-align:center"><input type="radio" name="you_order_food" value="once a month"/></td>
      <td style="text-align:center"><input type="radio" name="you_order_food" value="less often than once a month"/></td>
    </tr>
   </tbody>
   </table>
   </td>
   </tr>
   <tr><td colspan="2">5. The most common places you visit are restaurants serving food of origin:</td></tr>
   <tr>
       <td colspan="2">
         <table>
             <tr>
               <td><input type="checkbox" id="polish" name="food origin preference" value="polish"/>
               <label for="polish">Polish<label>
               </td>
               <td><input type="checkbox" id="indian" name="food origin preference" value="polish"/>
               <label for="indian">Indian<label>
               </td>
             </tr>
             <tr>
               <td><input type="checkbox" id="italian" name="food origin preference" value="polish"/>
               <label for="italian">Italian<label>
               </td>
               <td><input type="checkbox" id="spanish" name="food origin preference" value="polish"/>
               <label for="indian">Spanish<label>
               </td>
             </tr>
             <tr>
               <td><input type="checkbox" id="asian" name="food origin preference" value="polish"/>
               <label for="asian">Asian<label>
               </td>
               <td><input type="checkbox" id="chinese" name="food origin preference" value="polish"/>
               <label for="chinese">Chinese<label>
               </td>
             </tr>
             <tr>
               <td><input type="checkbox" id="american" name="food origin preference" value="polish"/>
               <label for="american">American<label>
               </td>
               <td><input type="checkbox" id="other" name="food origin preference" value="polish"/>
               <label for="other">Other<label>
               </td>
             </tr>
         </table>
       </td>
   </tr>
    <tr>
     <td>6. Given an option would you go vegan?</td>
     <td>
     <input type="radio" name="vegan" id="sure" value="sure"/><label for="sure">Sure</label>
     <input type="radio" name="vegan" id="no" value="no"/><label for="no">No</label>
     </td>
    </tr>
    <tr>
    <td><button>Submit</button><button type="reset">Reset</button></td>
    </tr>
  </table>
  </form>
  </body>
</html>
![Table_page-0001](https://github.com/baroque111/table_html/assets/43350344/f3ecb4d3-e44b-4508-adde-0ceac1094b93)
