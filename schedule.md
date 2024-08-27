<!-- Add styles for alternating row colors and borders -->
<style>
    .schedule-table {
        border-collapse: collapse;
        width: 100%;
        text-align: center;
    }
    .schedule-table th, .schedule-table td {
        border: 2px solid #A9A9A9; /* Darker border for all rows and columns */
        padding: 8px;
    }
    .schedule-table tbody tr:nth-child(even) {
        background-color: #f2f2f2; /* Gray background for even rows */
    }
    .schedule-table tbody tr:nth-child(odd) {
        background-color: #ffffff; /* White background for odd rows */
    }
    .schedule-week-num {
        background-color: #ddd; /* Background color for week number column */
        font-weight: bold;
    }
</style>

<!-- Add a jump-to button to navigate to the current week -->
<p>
    <a href="#week2">Jump to Current Week</a>
</p>

<!-- Week 1 Calendar -->
<table class="table table-bordered schedule-table" id="week1" bordercolor="##000000" text-align="center">
  <thead>
    <tr>
      <th class="center schedule-week-num">Week</th>
      <th>Date</th>
      <th>Lecture</th>
      <th>Lab</th>
      <th>Discussion</th>
      <th>Assignment</th>
    </tr>
  </thead>
  <tbody class="content" bordercolor="##000000" text-align: center;>
    <tr>
        <td rowspan=5>Week 1</td> <!-- Week Number -->
        <!-- WEEK ONE------------------------------------------------------------ -->
        <th>Mon 8/26</th> <!-- Date -->
        <td></td><!-- Lecture -->
        <td></td> <!-- Lab -->
        <td></td> <!-- Discussion -->
        <td></td> <!-- Assignment -->
    </tr>
    <tr>
        <th>Tue 8/27</th> <!-- Date -->
        <td>Lec 1. Logistics + Abstraction<br/>
        <a href="https://youtu.be/mQvFn-nuJ_4?si=Cek4gEYiQuZU9znV">(Recording 1)</a><br/>
        <a href="https://drive.google.com/file/d/1yqYDxVGeiSQZ-6qlgcgM9OWBbaAaIb11/view?usp=drive_link">(Slides 1)</a><br/>
        <a href="https://www.gradescope.com/courses/831412/assignments/4825047">(Lecture Quiz 1)</a>
        </td><!-- Lecture -->
        <td></td> <!-- Lab -->
        <td></td> <!-- Discussion -->
        <td><a href="https://forms.gle/yzbXZa6y8No9jS9t9">Presemester Survey Released</a><br/> <b>Due (08/30)</b></td> <!-- Assignment -->
    </tr>
    <tr>
        <th>Wed 8/28</th> <!-- Date -->
        <td>Lec 2. Functions + Conditional Logic<br/>
        <a href="">(Recording 2)</a><br/>      
        <a href="">(Slides 2)</a><br/>
        <a href="">(Lecture Quiz 2)</a>
        </td> <!-- Lecture -->
        <td><a href="https://docs.google.com/document/d/1A-e8t_ow2SamdUqJC9tfT11-ZaCn351NW3CpD-KvxN8/edit?usp=sharing">Lab 1. Welcome to Snap!</a></td> <!-- Lab -->
        <td></td> <!-- Discussion -->
        <td></td> <!-- Assignments -->
    </tr>
    <tr>
        <th>Thu 8/29</th> <!-- Date -->
        <td></td><!-- Lecture -->
        <td></td> <!-- Lab -->
        <td rowspan="5"><a href="">Disc 1. Boolean Operators and Truth Tables </a></td> <!-- Discussion -->
        <td></td> <!-- Assignment -->
    </tr>
    <tr>
        <th>Fri 8/30</th> <!-- Date -->
        <td></td><!-- Lecture -->
        <td></td> <!-- Lab -->
        <td></td> <!-- Discussion -->
        <td></td> <!-- Assignment -->
    </tr>
  </tbody>
</table>

<br/>

<!-- Week 2 Calendar -->
<table class="table table-bordered schedule-table" id="week2">
  <thead>
    <tr>
        <th class="center schedule-week-num">Week</th>
        <th>Date</th>
        <th>Lecture</th>
        <th>Lab</th>
        <th>Discussion</th>
        <th>Assignment</th>
    </tr>
  </thead>
  <tbody class="content">
    <tr>
        <td rowspan=5>Week 2</td> <!-- Week Number -->
        <!-- WEEK TWO------------------------------------------------------------ -->
        <th>Mon 9/2</th> <!-- Date -->
        <td colspan="4">NO CLASS (Holiday)</td><!-- Lecture -->
    </tr>
    <tr>
        <th>Tue 9/3</th> <!-- Date -->
        <td></td><!-- Lecture -->
        <td></td> <!-- Lab -->
        <td rowspan="5"><a href="">Disc 1. Welcome to Snap!</a></td> <!-- Discussion -->
        <td><a href="">Proj 1: Worldle Released</a><br/><b>Due (9/10)</b></td> <!-- Assignment -->
    </tr>
    <tr>
        <th>Wed 9/4 </th> <!-- Date -->
        <td>Lec 3. Numbers + Abstraction<br/>
        <a href="">(Recording 3)</a><br/>      
        <a href="">(Slides 3)</a><br/>
        <a href="">(Lecture Quiz 3)</a>
        </td> <!-- Lecture -->
        <td><a href="">Lab 2. Build Your Own Blocks</a></td> <!-- Lab -->
        <td></td> <!-- Discussion -->
        <td></td> <!-- Assignments -->
    </tr>
    <tr>
        <th>Thu 9/5</th> <!-- Date -->
        <td></td><!-- Lecture -->
        <td></td> <!-- Lab -->
        <td></td> <!-- Discussion -->
        <td></td> <!-- Assignment -->
    </tr>
    <tr>
        <th>Fri 9/6</th> <!-- Date -->
        <td></td><!-- Lecture -->
        <td></td> <!-- Lab -->
        <td></td> <!-- Discussion -->
        <td></td> <!-- Assignment -->
    </tr>
  </tbody>
</table>
