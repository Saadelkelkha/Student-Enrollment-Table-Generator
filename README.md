# Student-Enrollment-Table-Generator
This HTML program constructs a table to display student distribution among classes in the "Developpement" and "Gestion" branches. It effectively communicates the number of students in each class using HTML and CSS for a visually appealing and informative presentation.
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Document</title>
    <style>
        table , tr,td{
            border: 1px solid black;
            text-decoration-color: aliceblue;
            align-content: center;  
        }
    </style>
</head>
<body>
    <table width="760" align="center">
        <tr>
            <td colspan="3" align="center"><b>Repartition des stagiaires par classe</b></td>
        </tr>
        <tr>
            <td align="center"><b>Branch</b></td>
            <td align="center"><b>Classe</b></td>
            <td align="center"><b>Nombre d'eleves</b></td>
        </tr>
        <tr>
            <td align="center" rowspan="3">Developpement</td>
            <td align="center">TDI1</td>
            <td align="center">32</td>
        </tr>
        <tr>
            <td align="center">TDI2</td>
            <td align="center">16</td>
        </tr>
        <tr>
            <td align="center">TDI3</td>
            <td align="center">14</td>
        </tr>
        <tr>
            <td align="center" rowspan="3">Gestion</td>
            <td align="center">GE1</td>
            <td align="center">36</td>
        </tr>
        <tr>
            <td align="center">GE2</td>
            <td align="center">20</td>
        </tr>
        <tr>
            <td align="center">GE3</td>
            <td align="center">18</td>
        </tr>
    </table>
</body>
</html>
