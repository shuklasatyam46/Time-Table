# Time-Table

<html>
<Head>
</Head>
<body>
    <style>
html {
    height: 100%;
}

body {
    background-image: linear-gradient(rgb(255,255,255), rgb(12, 152, 207));
    text-align: center;
} 
    </style>
    
    <h1 align="center">TIME TABLE</h1>
    <table align="center" border="5px">
        <th>Time</th>
        <th>MONDAY</th>
        <th>Tuesday</th>
        <th>Wednesday</th>
        <th>Thursday</th>
        <th>Friday</th>
        <th>Saturday</th>
        <th>Sunday
        </th>
        <tr><td>8-9</td>
            <td>M2 lec</td>
            <td>Thermo lec</td>
            <td><hr></td>
            <td>MOW</td>
            <td><hr></td>
            <td><hr></td>
            <td><hr></td>
        </tr>
        <tr><td>9-10</td>
        <td><hr></td>
        <td>M2 lec</td>
        <td rowspan="3">Workshop</td>
        <td>M2 lec</td>
        <td>
            <hr>
        </td>
        <td>
            <hr>
        </td>
        <td>
            <hr>
        </td>
        </tr>
        <tr><td>10-11</td>
            <td><hr></td>
            <td><hr></td>
            <td><hr></td>
            <td><hr></td>
            <td><hr></td>
            <td><hr></td>
        </tr>
        <tr><td>11-12</td>
            <td rowspan="2">Bio lab</td>
            <td>ES lec</td>
            <td>ES lec</td>
            <td><hr></td>
            <td><hr></td>
            <td><hr></td>
        </tr>
        <tr><td>12-1</td>
            <td>MOW lec</td>
            <td><hr></td>
            <td>MOW</td>
            <td><hr></td>
            <td><hr></td>
            <td><hr></td>
        </tr>
        <tr><td>1-2</td>
            <td><hr></td>
            <td><hr></td>
            <td><hr></td>
            <td><hr></td>
            <td><hr></td>
            <td><hr></td>
            <td><hr></td>
        </tr>
        <tr><td>2-3</td>
            <td>CP lec</td>
            <td><hr></td>
            <td>CP</td>
            <td>CP</td>
            <td>M2 lec</td>
            <td><hr></td>
            <td><hr></td>
        </tr>
        <tr><td>3-4</td>
            <td>Thermo lec</td>
            <td><hr></td>
            <td>Thermo lec</td>
            <td>Thermo lec</td>
            <td><hr></td>
            <td><hr></td>
            <td><hr></td>
        </tr>
        <tr><td>4-5</td>
            <td><hr></td>
            <td>Workshop lec</td>
            <td><hr></td>
            <td><hr></td>
            <td>ES tut</td>
            <td><hr></td>
            <td><hr></td>
        </tr>
            <tr><td>5-6</td>
                <td><hr></td>
            <td>ES tut</td>
            <td>CP Lab</td>
            <td>MOW</td>
            <td>MOW Tut</td>
            <td><hr></td>
            <td><hr></td>
            </tr>
    </table>
    <button id="change" onclick="changebg()" value="off">change color</button>
    <script >
        function changebg() {
            const btn=document.getElementById("change")
            if (btn.value=="off"){
                document.body.style.backgroundImage = "linear-gradient(rgb(255,32,255), rgb(120, 152, 207))"
                tn.value="on"
            }
            else if (btn.value = "on"){
                document.body.style.backgroundImage = "linear-gradient(rgb(255,255,255), rgb(12, 152, 207))"
                btn.value="off"
            }
        }
    </script>
 </body>  

</html>




