<!DOCTYPE html>
<html>
<head>
<style> 
div {
  width: 40px;
  height: 40px;
  background-color: white;
  position: relative;
  animation-name: example;
  animation-duration: 2s;
}

@keyframes example {
  0%   {background-color:purple; left:0px; top:0px;}
  25%  {background-color:white; left:200px; top:0px;}
  50%  {background-color:purple; left:200px; top:200px;}
  75%  {background-color:white; left:0px; top:200px;}
  100% {background-color:purple; left:0px; top:0px;}
}
</style>
</head>
<body>


<div></div>

</body>
</html>
