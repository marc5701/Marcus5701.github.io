<html>
 <script type="text/javascript">
 antal = parseInt(prompt("Indtast antal varer"))
 stykpris = parseInt(prompt("stykpris"))
 total = antal * stykpris

if(total >= 1000){ alert("Du har fået rabat")
 rabat = total * 0.75}

else if(antal >= 25){ alert("Du har fået rabat")
 rabat = total * 0.75}

else if(antal >= 8){ alert("Du har fået rabat")
 rabat = total * 0.40}

else if(antal >= 3){ alert("Du har fået rabat")
 rabat = total * 0.15}

else{rabat = 0}
total = total - rabat
alert("Du skal betale "+total+" kr")



 </script>
</html>
