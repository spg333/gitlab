# gitlab
Q1: Is the keyword "fixes" the only way to auto-close an issue from a PR 
(pull request). Is there other keywords that can accomplish the same thing?
No, the keyword "fixes" is not the only way. There are more kewords to do same thing as the keyword "fixes" which is the list below.
close
closes
closed
fix
fixes
fixed
resolve
resolves
resolved

Q2: Do you have to create a new PR EVERYTIME you want to close an issue,
or is it possible to close multiple issues within a single PR? If so, 
how? Yes, we can use the keword and issue number mutiple times.

Q3: Provide an example of using map that is different from the one I have done.
Your example must use map both as a named function declaration and with an
anonymous function. 

Within comments, explain exactly what map is doing. Finally, why is the
"transformation function" we discussed in class sometimes referred to 
as a callback function. 

<!DOCTYPE html>
<html >
<head>
    
</head>
<body>
<!-- <script src = "script.js"></script> -->

<body>

<script>
var numbers = [1, 2, 3];
var array1 = numbers.map(myfunction) //map is looping through the elements in numbers array and 
excute my function for every elemet

function myfunction(num) {
  return num + 10;
}

var array2 = numbers.map(function (num){return num + 10;}) // doing same thing as earlier but it makes the code simpler

document.write(array1)
document.write(array2)

</script>

</body>
</html>
