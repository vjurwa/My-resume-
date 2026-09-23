<!DOCTYPE html>
<html>
  <head>
    <title>Calendar</title>
    <link rel="stylesheet" href="styles.css" />
  </head>
      <body class="page">
      <table class="l" cellspacing="15px">
  <tr>
    <td class="c" colspan="7"><h1 align="center"><div class="calendar-title">calendar</div>
</h1></td>
  </tr>
  <tr class="h">
    <td>Mon</td>
    <td>Tue</td>
    <td>Wed</td>
    <td>Thu</td>
    <td>Fri</td>
    <td>Sat</td>
    <td>Sun</td>
  </tr>
  <tr class="r">
    <td>1</td>
    <td>2</td>
    <td>3</td>
    <td>4</td>
    <td>5</td>
    <td>6</td>
    <td>7</td>
  </tr>
    <tr class="r1">
    <td>8</td>
    <td>9</td>
    <td>10</td>
    <td>11</td>
   <td>12</td>
    <td>13</td>
    <td>14</td>
  </tr>
  <tr class="r2">
    <td>15</td>
    <td>16</td>
    <td>17</td>
    <td>18</td>
    <td>19</td>
    <td>20</td>
    <td>21</td>
  </tr>
  <tr class="r3">
    <td>22</td>
    <td>23</td>
    <td>24</td>
    <td>25</td>
    <td>26</td>
    <td>27</td>
    <td>28</td>
  </tr>
    <tr>
    <td>29</td>
    <td>30</td>
    <td>31</td>
  </tr>
  </table>
  </body>
</html>
background: white;
  border: 2px solid black;
  border-radius: 8px;
  box-shadow: 0px 0px 8px gray;
  width: 70px;
  height: 25px;
  text-align: center;
}
.l{border:2px solid black;font-style:italic;
font-weight:bold;border-radius:15px;text-align:center;}
.h:hover td{background-color:red;width:3px;}
.c:hover{background-color:red;font-weight:bold;}
.r:hover td{background-color:green; align: center;}
.r1:hover td{background-color:green;}
.r2:hover td{background-color:green;}
.r3:hover td{background-color:green;}
.page{background-color:yellow;}
.calendar-title{
  font-size: 45px;
  font-weight: bold;
  text-align: center;
  animation: slide 3s infinite alternate;
  background: white;
  border: 3px solid black;
  border-radius: 15px;
  padding: 10px;
}

@keyframes slide{
  0%{ transform: translateX(-10px); color: black; }
  100%{ transform: translateX(10px); color: green; }
}


