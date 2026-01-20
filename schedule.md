<!-- Add styles for alternating row colors and borders -->
<style>
    .schedule-table {
        border-collapse: collapse;
        width: 100%;
        text-align: center;
    }
    .schedule-table th, .schedule-table td {
        border: 1px solid #A9A9A9; /* Darker border for all rows and columns */
        padding: 8px;
    }
</style>

<!-- Add a jump-to button to navigate to the current week -->
<p>
    <a href="#week1">Jump to Current Week</a>
</p>

<!-- Week 1 Calendar -->
<table class="table table-bordered schedule-table" id="week1">
  <thead>
    <tr>
      <th class="center schedule-week-num">Week</th>
      <th>Date</th>
      <th>Lecture</th>
      <th>Lab</th>
      <th>Discussion</th>
      <th>Assignment / Exam</th>
    </tr>
  </thead>
  <tbody class="content">
    <tr>
        <td class="schedule-week-num" rowspan=5>Week 1</td> <!-- Week Number -->
        <th>Mon 1/19</th> <!-- Date -->
        <td colspan="4">HOLIDAY</td><!-- Lecture -->
    </tr>
    <tr>
        <th>Tue 1/20</th> <!-- Date -->
        <td colspan="4">NO CLASS</td><!-- Lecture -->
    </tr>
    <tr>
        <th>Wed 1/21</th> <!-- Date -->
        <td>Lec 1. Welcome + Abstraction<br/>
            <a href="https://bcourses.berkeley.edu/courses/1547647/external_tools/90481">(Recording 1)</a><br/>   
            <a href="https://drive.google.com/drive/folders/1ZMfd23KyrJEl9Yw-g_8sXZF7Td4G7_IT">(Slides 1)</a><br/>
            <a href="https://www.gradescope.com/courses/1098053/assignments/6577011">(Lecture Quiz 1)</a>
            </td> <!-- Lecture -->
        <td>No Lab</td><!-- Lab -->
        <td></td> <!-- Discussion -->
        <td></td> <!-- Assignments -->
    </tr>
    <tr>
        <th>Thu 1/22</th> <!-- Date -->
        <td></td><!-- Lecture -->
        <td><a href="/sp26/lab_directory">Lab 1: Welcome to Snap!</a></td> <!-- Lab -->
        <td></td> <!-- Discussion -->
        <td></td> <!-- Assignment / Exam -->
    </tr>
    <tr>
        <th>Fri 1/23</th> <!-- Date -->
        <td>Talk 1: Fun "Ask me anything", abstraction, using python (but NOT making blocks)<br/>
            <a href="https://bcourses.berkeley.edu/courses/1547647/external_tools/90481">(Recording: Talk 1)</a></td> <!-- Lecture -->
        <td></td> <!-- Lab -->
        <td><a href="/sp26/discussion">Disc 1. Welcome to CS10!</a></td> <!-- Discussion -->
        <td></td> <!-- Assignment / Exam -->
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
      <th>Assignment / Exam</th>
    </tr>
  </thead>
  <tbody class="content">
    <tr>
        <td class="schedule-week-num" rowspan=5>Week 2</td> <!-- Week Number -->
        <th>Mon 1/26</th> <!-- Date -->
        <td>Lec 2. Functions<br/>
            <a href="https://bcourses.berkeley.edu/courses/1547647/external_tools/90481">(Recording 2)</a><br/>      
            <a href="https://drive.google.com/drive/folders/1pMyNs4LdwbUrsJmK0m--iMUKwAbXLxmv">(Slides 2)</a><br/>
            <a href="https://www.gradescope.com/courses/1098053/assignments/6577012">(Lecture Quiz 2)</a>
            </td> <!-- Lecture -->
        <td></td><!-- Lab -->
        <td></td> <!-- Discussion -->
        <td></td> <!-- Assignments -->
    </tr>
    <tr>
        <th>Tue 1/27</th> <!-- Date -->
        <td></td><!-- Lecture -->
        <td></td> <!-- Lab -->
        <td></td> <!-- Discussion -->
        <td></td> <!-- Assignment / Exam -->
    </tr>
    <tr>
        <th>Wed 1/28</th> <!-- Date -->
        <td>Lec 3. Abstraction II<br/>
            <a href="https://bcourses.berkeley.edu/courses/1547647/external_tools/90481">(Recording 3)</a><br/>       
            <a href="https://drive.google.com/drive/folders/1RF-WgoEka4wRVxbfZNjLLlKcw7_O7BhN">(Slides 3)</a><br/>
            <a href="https://www.gradescope.com/courses/1098053/assignments/6577022">(Lecture Quiz 3)</a>
            </td> <!-- Lecture -->
        <td></td> <!-- Lab -->
        <td></td> <!-- Discussion -->
        <td></td> <!-- Assignments -->
    </tr>
    <tr>
        <th>Thu 1/29</th> <!-- Date -->
        <td></td><!-- Lecture -->
        <td><a href="/sp26/labs/lab02">Lab 2. Build Your Own Blocks</a></td> <!-- Lab -->
        <td></td> <!-- Discussion -->
        <td></td> <!-- Assignment / Exam -->
    </tr>
    <tr>
        <th>Fri 1/30</th> <!-- Date -->
        <td>Talk 2: Conditionals, Truth Tables, Predicates, Binary/Dec/Hex conversion<br/>
            <a href="https://bcourses.berkeley.edu/courses/1547647/external_tools/90481">(Recording: Talk 2)</a></td> <!-- Lecture -->
        <td><a href="/sp26/labs/lab03">Lab 3. Conditionals, Reporters, & Testing</a></td> <!-- Lab -->
        <td><a href="/sp26/discussion">Disc 2. Number Rep & Control Structures</a></td> <!-- Discussion -->
        <td><a href="/sp26/projects/"><b>Proj 1: Wordle™ Lite Released</b></a></td> <!-- Assignment / Exam -->
    </tr>
  </tbody>
</table>

<br/>
<!-- Week 3 Calendar -->
<table class="table table-bordered schedule-table" id="week3">
  <thead>
    <tr>
        <th class="center schedule-week-num">Week</th>
        <th>Date</th>
        <th>Lecture</th>
        <th>Lab</th>
        <th>Discussion</th>
        <th>Assignment / Exam</th>
    </tr>
  </thead>
  <tbody class="content">
    <tr>
        <td class="schedule-week-num" rowspan=5>Week 3</td> <!-- Week Number -->
        <th>Mon 2/02</th> <!-- Date -->
        <td>Lec 4. Iteration NEW<br/>
            <a href="https://bcourses.berkeley.edu/courses/1547647/external_tools/90481">(Recording 4)</a><br/>       
            <a href="https://drive.google.com/drive/folders/1RF-WgoEka4wRVxbfZNjLLlKcw7_O7BhN">(Slides 4)</a><br/>
            <a href="https://www.gradescope.com/courses/1098053/assignments/6577022">(Lecture Quiz 4)</a>
            </td> <!-- Lecture -->
        <td></td> <!-- Lab -->
        <td></td> <!-- Discussion -->
        <td></td> <!-- Assignment / Exam -->
    </tr>
    <tr>
        <th>Tue 2/03</th> <!-- Date -->
        <td></td><!-- Lecture -->
        <td></td> <!-- Lab -->
        <td></td> <!-- Discussion -->
        <td></td> <!-- Assignment / Exam -->
    </tr>
    <tr>
        <th>Wed 2/04</th> <!-- Date -->
        <td>Lec 5. Variables, Lists, Scope, HOFs<br/>
            <a href="https://bcourses.berkeley.edu/courses/1547647/external_tools/90481">(Recording 5)</a><br/>      
            <a href="https://drive.google.com/drive/folders/1X88498eFRUfx33I3f2fkE7uh5yh1rHfq">(Slides 5)</a><br/>
            <a href="https://www.gradescope.com/courses/1098053/assignments/6577029">(Lecture Quiz 5)</a></td> <!-- Lecture -->
        <td></td> <!-- Lab -->
        <td></td> <!-- Discussion -->
        <td></td> <!-- Assignments -->
    </tr>
    <tr>
        <th>Thu 2/05</th> <!-- Date -->
        <td></td><!-- Lecture -->
        <td><a href="/sp26/labs/lab04">Lab 4. Iteration NEW</a></td> <!-- Lab -->
        <td></td> <!-- Discussion -->
        <td></td> <!-- Assignment / Exam -->
    </tr>
    <tr>
        <th>Fri 2/06</th> <!-- Date -->
        <td>Talk 3: HOFs<br/>
            <a href="https://bcourses.berkeley.edu/courses/1547647/external_tools/90481">(Recording: Talk 3)</a></td> <!-- Lecture -->
        <td><a href="/sp26/labs/lab05">Lab 5. Lists & HOFs</a></td> <!-- Lab -->
        <td><a href="/sp26/discussion">Disc 3. Domain/Range, Scoping, Iteration, Lists</a></td> <!-- Discussion -->
        <td><a href="/sp26/projects/"><b>Proj 1 DUE</b></a></td> <!-- Assignment / Exam -->
    </tr>
  </tbody>
</table>

<br/>
<!-- Week 4 Calendar -->
<table class="table table-bordered schedule-table" id="week4">
  <thead>
    <tr>
      <th class="center schedule-week-num">Week</th>
      <th>Date</th>
      <th>Lecture</th>
      <th>Lab</th>
      <th>Discussion</th>
      <th>Assignment / Exam</th>
    </tr>
  </thead>
  <tbody class="content">
    <tr>
      <td class="schedule-week-num" rowspan="5">Week 4</td>
      <th>Mon 2/09</th>
      <td>Lec 6. Algorithms<br/>
          <a href="https://bcourses.berkeley.edu/courses/1547647/external_tools/90481">(Recording 6)</a><br/>
          <a href="https://drive.google.com/drive/folders/1MaDZp9WNo0GXgw5uo4_J9eyCBJN3B2MO">(Slides 6)</a><br/>
          <a href="https://www.gradescope.com/courses/1098053/assignments/6577004">(Lecture Quiz 6)</a>
      </td>
      <td></td>
      <td></td>
      <td><a href="/sp26/projects/"><b>Proj 2 Released</b></a></td>
    </tr>
    <tr>
      <th>Tue 2/10</th>
      <td></td>
      <td></td>
      <td></td>
      <td></td>
    </tr>
    <tr>
      <th>Wed 2/11</th>
      <td>Lec 7. Algorithmic Complexity<br/>
          <a href="https://bcourses.berkeley.edu/courses/1547647/external_tools/90481">(Recording 7)</a><br/>
          <a href="https://drive.google.com/drive/folders/196es2A1TR6iijUgHt10i0ocd43R2mpb-">(Slides 7)</a><br/>
          <a href="https://www.gradescope.com/courses/1098053/assignments/6577027">(Lecture Quiz 7)</a>
      </td>
      <td></td>
      <td></td>
      <td></td>
    </tr>
    <tr>
      <th>Thu 2/12</th>
      <td></td>
      <td><a href="/sp26/labs/lab06">Lab 6. Algorithms</a></td>
      <td></td>
      <td></td>
    </tr>
    <tr>
      <th>Fri 2/13</th>
      <td>Talk 4: Quest 1 Preview<br/>
          <a href="https://bcourses.berkeley.edu/courses/1547647/external_tools/90481">(Recording: Talk 4)</a>
      </td>
      <td><a href="/sp26/labs/lab07">Lab 7. Algorithmic Complexity</a></td>
      <td><a href="/sp26/discussion">Disc 4. HOFs + Algorithmic Complexity</a></td>
      <td><b>QUEST 1</b></td>
    </tr>
  </tbody>
</table>

<br/>
<!-- Week 5 Calendar -->
<table class="table table-bordered schedule-table" id="week5">
  <thead>
    <tr>
      <th class="center schedule-week-num">Week</th>
      <th>Date</th>
      <th>Lecture</th>
      <th>Lab</th>
      <th>Discussion</th>
      <th>Assignment / Exam</th>
    </tr>
  </thead>
  <tbody class="content">
    <tr>
      <td class="schedule-week-num" rowspan=5>Week 5</td>
      <th>Mon 2/16</th>
      <td colspan="4">HOLIDAY</td>
    </tr>
    <tr>
      <th>Tue 2/17</th>
      <td></td>
      <td></td>
      <td></td>
      <td></td>
    </tr>
    <tr>
      <th>Wed 2/18</th>
      <td>Lec 8. Recursion I (Functional)<br/>
          <a href="https://bcourses.berkeley.edu/courses/1547647/external_tools/90481">(Recording 8)</a><br/>
          <a href="https://drive.google.com/drive/folders/197HzbXqlMuS8XyTilFZuNkjYIH8dpTUi?usp=sharing">(Slides 8)</a><br/>
          <a href="https://www.gradescope.com/courses/1098053/assignments/6577006">(Lecture Quiz 8)</a>
      </td>
      <td></td>
      <td></td>
      <td><b>QUEST 1</b></td>
    </tr>
    <tr>
      <th>Thu 2/19</th>
      <td></td>
      <td><a href="/sp26/labs/lab08">Lab 8. Boards</a></td>
      <td></td>
      <td></td>
    </tr>
    <tr>
      <th>Fri 2/20</th>
      <td>Talk 5: Quest 1 Review<br/>
            <a href="https://bcourses.berkeley.edu/courses/1547647/external_tools/90481">(Recording: Talk 5)</a></td> <!-- Lecture -->  
      <td></td>
      <td><a href="/sp26/discussion">Disc 5. Nested Lists + Recursion</a></td>
      <td><b>QUEST 2</b></td>
    </tr>
  </tbody>
</table>

<br/>
<!-- Week 6 Calendar -->
<table class="table table-bordered schedule-table" id="week6">
  <thead>
    <tr>
      <th class="center schedule-week-num">Week</th>
      <th>Date</th>
      <th>Lecture</th>
      <th>Lab</th>
      <th>Discussion</th>
      <th>Assignment / Exam</th>
    </tr>
  </thead>
  <tbody class="content">
    <tr>
      <td class="schedule-week-num" rowspan=5>Week 6</td>
      <th>Mon 2/23</th>
      <td>Lec 9. Recursion II (Fractals)<br/>
          <a href="https://bcourses.berkeley.edu/courses/1547647/external_tools/90481">(Recording 9)</a><br/>
          <a href="https://drive.google.com/drive/folders/1bR5cxJinuZZhVz4hKphD-HMS2nYD4d6Q?usp=sharing">(Slides 9)</a><br/>
          <a href="https://www.gradescope.com/courses/1098053/assignments/6577030">(Lecture Quiz 9)</a>
      </td>
      <td></td>
      <td></td>
      <td></td>
    </tr>
    <tr>
      <th>Tue 2/24</th>
      <td></td>
      <td></td>
      <td></td>
      <td></td>
    </tr>
    <tr>
      <th>Wed 2/25</th>
      <td>Lec 10. Recursion III (Count Change)<br/>
          <a href="https://bcourses.berkeley.edu/courses/1547647/external_tools/90481">(Recording 10)</a><br/>
          <a href="https://drive.google.com/drive/folders/1IqNGB45VcUVvBJNT60BRbuuIeTvARtR6?usp=sharing">(Slides 10)</a><br/>
          <a href="https://www.gradescope.com/courses/1098053/assignments/6577025">(Lecture Quiz 10)</a>
      </td>
      <td></td>
      <td></td>
      <td></td>
    </tr>
    <tr>
      <th>Thu 2/26</th>
      <td></td>
      <td><a href="/sp26/labs/lab09">Lab 9. Trees & Fractals</a></td>
      <td></td>
      <td></td>
    </tr>
    <tr>
      <th>Fri 2/27</th>
      <td>Talk 6: Quest 2 Review<br/>
            <a href="https://bcourses.berkeley.edu/courses/1547647/external_tools/90481">(Recording: Talk 6)</a></td> <!-- Lecture -->    
      <td><a href="/sp26/labs/lab10">Lab 10. Recursive Reporters</a></td>
      <td><a href="/sp26/discussion">Disc 6. Recursion II</a></td>
      <td><a href="/sp26/projects/"><b>Proj 2 Due</b></a><br/><b>QUEST 2</b><br/><b>QUEST 3</b></td>
    </tr>
  </tbody>
</table>

<br/>
<!-- Week 7 Calendar -->
<table class="table table-bordered schedule-table" id="week7">
  <thead>
    <tr>
      <th class="center schedule-week-num">Week</th>
      <th>Date</th>
      <th>Lecture</th>
      <th>Lab</th>
      <th>Discussion</th>
      <th>Assignment / Exam</th>
    </tr>
  </thead>
  <tbody class="content">
    <tr>
      <td class="schedule-week-num" rowspan=5>Week 7</td>
      <th>Mon 3/02</th>
      <td>Lec 11. Testing + 2048<br/>
          <a href="https://bcourses.berkeley.edu/courses/1547647/external_tools/90481">(Recording 11)</a><br/>
          <a href="https://drive.google.com/drive/folders/1vDV-fA55SkL7dJHZdKUZfdKXdGQAwQQN?usp=sharing">(Slides 11)</a><br/>
          <a href="https://www.gradescope.com/courses/1098053/assignments/6577034">(Lecture Quiz 11)</a>
      </td>
      <td></td>
      <td></td>
      <td><a href="/sp26/projects/"><b>Proj 3 Released</b></a></td>
    </tr>
    <tr>
      <th>Tue 3/03</th>
      <td></td>
      <td></td>
      <td></td>
      <td></td>
    </tr>
    <tr>
      <th>Wed 3/04</th>
      <td>Lec 12. Higher-Order Functions<br/>
          <a href="https://bcourses.berkeley.edu/courses/1547647/external_tools/90481">(Recording 12)</a><br/>
          <a href="https://drive.google.com/drive/folders/12thQx9MxMPzJdXqeCPusd1blSmgJBoMb?usp=sharing">(Slides 12)</a><br/>
          <a href="https://www.gradescope.com/courses/1098053/assignments/6577037">(Lecture Quiz 12)</a>
      </td>
      <td></td>
      <td></td>
      <td></td>
    </tr>
    <tr>
      <th>Thu 3/05</th>
      <td></td>
      <td><a href="/sp26/labs/lab11">Lab 11. Testing + 2048</a></td>
      <td></td>
      <td></td>
    </tr>
    <tr>
      <th>Fri 3/06</th>
      <td>Talk 7: Recursion<br/>
          <a href="https://bcourses.berkeley.edu/courses/1547647/external_tools/90481">(Recording: Talk 7)</a>
      </td>
      <td><a href="/sp26/labs/lab12">Lab 12. Functions as Data, HOFs</a></td>
      <td><a href="/sp26/discussion">Disc 7. HOFs, Lambdas, Debugging</a></td>
      <td><b>QUEST 3</b></td>
    </tr>
  </tbody>
</table>

<br/>
<!-- Week 8 Calendar -->
<table class="table table-bordered schedule-table" id="week8">
  <thead>
    <tr>
      <th class="center schedule-week-num">Week</th>
      <th>Date</th>
      <th>Lecture</th>
      <th>Lab</th>
      <th>Discussion</th>
      <th>Assignment / Exam</th>
    </tr>
  </thead>
  <tbody class="content">
    <tr>
      <td class="schedule-week-num" rowspan=5>Week 8</td>
      <th>Mon 3/09</th>
      <td>Lec 13. Guest Lecture: Saving the World with Computing<br/>
          <a href="https://bcourses.berkeley.edu/courses/1547647/external_tools/90481">(Recording 13)</a><br/>
          <a href="https://drive.google.com/drive/folders/1qeqivahR8DMR9xzT9hc_UfwOqO6bu4ax?usp=sharing">(Slides 13)</a><br/>
          <a href="https://www.gradescope.com/courses/1098053/assignments/6577044">(Lecture Quiz 13)</a>
      </td>
      <td></td>
      <td></td>
      <td><a href="/sp26/projects/"><b>Proj 4 Released</b></a></td>
    </tr>
    <tr>
      <th>Tue 3/10</th>
      <td></td>
      <td></td>
      <td></td>
      <td></td>
    </tr>
    <tr>
      <th>Wed 3/11</th>
      <td>Lec 14. Computing in Education<br/>
          <a href="https://bcourses.berkeley.edu/courses/1547647/external_tools/90481">(Recording 14)</a><br/>
          <a href="https://drive.google.com/drive/folders/1uviKMrpsrj1_skyztQx-aqgAbwj0QLcN?usp=sharing">(Slides 14)</a><br/>
          <a href="https://www.gradescope.com/courses/1098053/assignments/6577028">(Lecture Quiz 14)</a>
      </td>
      <td></td>
      <td></td>
      <td></td>
    </tr>
    <tr>
      <th>Thu 3/12</th>
      <td></td>
      <td>Midterm Practice</td>
      <td></td>
      <td></td>
    </tr>
    <tr>
      <th>Fri 3/13</th>
      <td>Talk 8: Midterm 1 Preview<br/>
          <a href="https://bcourses.berkeley.edu/courses/1547647/external_tools/90481">(Recording: Talk 8)</a></td>
      <td>Midterm Practice</td>
      <td><a href="/sp26/discussion">Disc 8. Midterm Preview</a></td>
      <td><b>MIDTERM 1</b></td>
    </tr>
  </tbody>
</table>

<br/>
<!-- Week 9 Calendar -->
<table class="table table-bordered schedule-table" id="week9">
  <thead>
    <tr>
      <th class="center schedule-week-num">Week</th>
      <th>Date</th>
      <th>Lecture</th>
      <th>Lab</th>
      <th>Discussion</th>
      <th>Assignment / Exam</th>
    </tr>
  </thead>
  <tbody class="content">
    <tr>
      <td class="schedule-week-num" rowspan=5>Week 9</td>
      <th>Mon 3/16</th>
      <td>Lec 15. Programming Paradigms<br/>
          <a href="https://bcourses.berkeley.edu/courses/1547647/external_tools/90481">(Recording 15)</a><br/>
          <a href="https://drive.google.com/drive/folders/1Aazmz_UAl1aomvsqUFlXdcGC6eKGy2BH?usp=drive_link">(Slides 15)</a><br/>
          <a href="https://www.gradescope.com/courses/1098053/assignments/6577060">(Lecture Quiz 15)</a>
      </td>
      <td></td>
      <td></td>
      <td></td>
    </tr>
    <tr>
      <th>Tue 3/17</th>
      <td></td>
      <td></td>
      <td></td>
      <td></td>
    </tr>
    <tr>
      <th>Wed 3/18</th>
      <td>Lec 16. OOP in Snap!<br/>
          <a href="https://bcourses.berkeley.edu/courses/1547647/external_tools/90481">(Recording 16)</a><br/>
          <a href="https://drive.google.com/drive/folders/1xpzxhmuzQ5NIYwlHOOuw_jCgF4qFgLxA?usp=sharing">(Slides 16)</a><br/>
          <a href="">(Lecture Quiz 16)</a>
      </td>
      <td></td>
      <td></td>
      <td><a href="/sp26/projects/"><b>Proj 3 Due</b></a></td> <!-- Assignment / Exam -->  
    </tr>
    <tr>
      <th>Thu 3/19</th>
      <td></td>
      <td>Project 4 // Work Session</td>
      <td></td>
      <td><b>MIDTERM 1</b></td>
    </tr>
    <tr>
      <th>Fri 3/20</th>
      <td>Talk 9: Midterm 1 Review<br/>
          <a href="https://bcourses.berkeley.edu/courses/1547647/external_tools/90481">(Recording: Talk 9)</a></td>
      <td><a href="/sp26/labs/lab13">Lab 13. OOP in Snap!</a></td>
      <td><a href="/sp26/discussion">Disc 9. OOP</a></td>
      <td><b>MIDTERM 2</b></td>
    </tr>
  </tbody>
</table>

<br/>
<!-- Week 10 Calendar -->
<table class="table table-bordered schedule-table" id="week10">
  <thead>
    <tr>
      <th class="center schedule-week-num">Week</th>
      <th>Date</th>
      <th>Lecture</th>
      <th>Lab</th>
      <th>Discussion</th>
      <th>Assignment / Exam</th>
    </tr>
  </thead>
  <tbody class="content">
    <tr>
      <td class="schedule-week-num" rowspan=5>Week 10</td>
      <th>Mon 3/23</th>
      <td colspan="4">HOLIDAY</td>
    </tr>
    <tr>
      <th>Tue 3/24</th>
      <td colspan="4">HOLIDAY</td>
    </tr>
    <tr>
      <th>Wed 3/25</th>
      <td colspan="4">HOLIDAY</td>
    </tr>
    <tr>
      <th>Thu 3/26</th>
      <td colspan="4">HOLIDAY</td>
    </tr>
    <tr>
      <th>Fri 3/27</th>
      <td colspan="4">HOLIDAY</td>
    </tr>
  </tbody>
</table>

<br/>
<!-- Week 11 Calendar -->
<table class="table table-bordered schedule-table" id="week11">
  <thead>
    <tr>
      <th class="center schedule-week-num">Week</th>
      <th>Date</th>
      <th>Lecture</th>
      <th>Lab</th>
      <th>Discussion</th>
      <th>Assignment / Exam</th>
    </tr>
  </thead>
  <tbody class="content">
    <tr>
      <td class="schedule-week-num" rowspan=5>Week 11</td>
      <th>Mon 3/30</th>
      <td>Lec 17. Python I - Intro<br/>
          <a href="https://bcourses.berkeley.edu/courses/1547647/external_tools/90481">(Recording 17)</a><br/>
          <a href="https://drive.google.com/drive/u/0/folders/1-Odp1zmmdr5ImbHw6k2LqtE6rOFO3fWm">(Slides 17)</a><br/>
          <a href="https://www.gradescope.com/courses/1098053/assignments/6577083">(Lecture Quiz 17)</a>
      </td>
      <td></td>
      <td></td>
      <td></td>
    </tr>
    <tr>
      <th>Tue 3/31</th>
      <td></td>
      <td></td>
      <td></td>
      <td></td>
    </tr>
    <tr>
      <th>Wed 4/01</th>
      <td>Lec 18. Python II - Data Types & Structures<br/>
          <a href="https://bcourses.berkeley.edu/courses/1547647/external_tools/90481">(Recording 18)</a><br/>
          <a href="https://drive.google.com/drive/u/0/folders/1cymjfiH3Ldrn99hCC74Wj7ctxF9TPXz5">(Slides 18)</a><br/>
          <a href="https://www.gradescope.com/courses/1098053/assignments/6577048">(Lecture Quiz 18)</a></td>
      <td></td>
      <td></td>
      <td><a href="/sp26/projects/"><b>Proj 4 Due</b></a><br/><a href="/sp26/projects/"><b>Final Projects Released</b></a></td>
    </tr>
    <tr>
      <th>Thu 4/02</th>
      <td></td>
      <td><a href="/sp26/labs/lab14">Lab 14. Welcome to Python</a></td>
      <td><a href="/sp26/projects/">Proj 4 Presentations</a></td>
      <td><a href="/sp26/projects/">Proj 4 Presentations</a></td>
    </tr>
    <tr>
      <th>Fri 4/03</th>
      <td>Talk 10: Midterm 2 review<br/>
          <a href="https://bcourses.berkeley.edu/courses/1547647/external_tools/90481">(Recording: Talk 10)</a></td>
      <td><a href="/sp26/labs/lab15">Lab 15. Data Structures in Python</a></td>
      <td></td>
      <td><b>MIDTERM 3</b></td>
    </tr>
  </tbody>
</table>

<br/>
<!-- Week 12 Calendar -->
<table class="table table-bordered schedule-table" id="week12">
  <thead>
    <tr>
      <th class="center schedule-week-num">Week</th>
      <th>Date</th>
      <th>Lecture</th>
      <th>Lab</th>
      <th>Discussion</th>
      <th>Assignment / Exam</th>
    </tr>
  </thead>
  <tbody class="content">
    <tr>
      <td class="schedule-week-num" rowspan=6>Week 12</td>
      <th>Mon 4/06</th>
      <td>Lec 19. Concurrency<br/>
          <a href="https://bcourses.berkeley.edu/courses/1547647/external_tools/90481">(Recording 19)</a><br/>
          <a href="https://drive.google.com/drive/folders/1yXM2gsE4jsCO1_5J4tSBMViX6IbvhD_D?usp=drive_link">(Slides 19)</a><br/>
          <a href="https://www.gradescope.com/courses/1098053/assignments/7143927">(Lecture Quiz 19)</a>
      </td>
      <td></td>
      <td></td>
      <td><a href="/sp26/projects/">Final Project Proposal Meetings</a></td>
    </tr>
    <tr>
      <th>Tue 4/07</th>
      <td></td>
      <td></td>
      <td></td>
      <td><a href="/sp26/projects/">Final Project Proposal Meetings</a></td>
    </tr>
    <tr>
      <th>Wed 4/08</th>
      <td>Lec 20. Gen AI<br/>
          <a href="https://bcourses.berkeley.edu/courses/1547647/external_tools/90481">(Recording 20)</a><br/>
          <a href="https://drive.google.com/drive/folders/1l1pNdsfMMWigJ4xB3s6_HwLn8mnsLjRU?usp=drive_link">(Slides 20)</a><br/>
          <a href="https://www.gradescope.com/courses/1098053/assignments/6577047">(Lecture Quiz 20)</a>
      </td>
      <td></td>
      <td></td>
      <td><a href="/sp26/projects/">Final Project Proposal Meetings</a></td>
    </tr>
    <tr>
      <th>Thu 4/09</th>
      <td></td>
      <td><a href="/sp26/labs/lab16">Lab 16. Concurrency</a></td>
      <td></td>
      <td><a href="/sp26/projects/">Final Project Proposals Due</a><br/><a href="/sp26/projects/">Proj 4 Comments Due</a><br/><a href="/sp26/projects/">Proj 4 Makeup Presentations Due</a></td>
    </tr>
    <tr>
      <th>Fri 4/10</th>
      <td>Talk 11: Python live coding<br/>
          <a href="https://bcourses.berkeley.edu/courses/1547647/external_tools/90481">(Recording: Talk 11)</a>
      </td>
      <td>CU + Post Term Practice</td>
      <td><a href="/sp26/discussion">Disc 12: Data Structures in Python</a></td>
      <td><a href="/sp26/projects/">Final Project Proposal Meetings</a></td>
    </tr>
    <tr>
      <th>Sat 4/11</th>
      <td></td>
      <td></td>
      <td></td>
      <td><b>MIDTERM 3</b></td>
    </tr>
  </tbody>
</table>

<br/>
<!-- Week 13 Calendar -->
<table class="table table-bordered schedule-table" id="week13">
  <thead>
    <tr>
      <th class="center schedule-week-num">Week</th>
      <th>Date</th>
      <th>Lecture</th>
      <th>Lab</th>
      <th>Discussion</th>
      <th>Assignment / Exam</th>
    </tr>
  </thead>
  <tbody class="content">
    <tr>
      <td class="schedule-week-num" rowspan=6>Week 13</td>
      <th>Mon 4/13</th>
      <td>Lec 21. Guest Lecture: Human-computer interaction (HCI)<br/>
          <a href="https://bcourses.berkeley.edu/courses/1547647/external_tools/90481">(Recording 21)</a><br/>
          <a href="https://drive.google.com/drive/folders/1_aS9Z63gj2rkRhYr38xoAcAuyjqehK5X?usp=drive_link">(Slides 21)</a><br/>
          <a href="https://www.gradescope.com/courses/1098053/assignments/6577081">(Lecture Quiz 21)</a>
      </td>
      <td></td>
      <td></td>
      <td></td>
    </tr>
    <tr>
      <th>Tue 4/14</th>
      <td></td>
      <td></td>
      <td></td>
      <td></td>
    </tr>
    <tr>
      <th>Wed 4/15</th>
      <td>Lec 22. Ethics in AI<br/>
          <a href="https://bcourses.berkeley.edu/courses/1547647/external_tools/90481">(Recording 22)</a><br/>
          <a href="https://drive.google.com/drive/folders/1CVZJWEKwJDovWhi8xvyWyUnPFL1jx9jg?usp=drive_link">(Slides 22)</a><br/>
          <a href="https://www.gradescope.com/courses/1098053/assignments/6577077">(Lecture Quiz 22)</a>
      </td>
      <td></td>
      <td></td>
      <td></td>
    </tr>
    <tr>
      <th>Thu 4/16</th>
      <td></td>
      <td><a href="/sp26/labs/lab17">Lab 17. Text Processing in Python</a></td>
      <td></td>
      <td></td>
    </tr>
    <tr>
      <th>Fri 4/17</th>
      <td>Talk 12: POSTTERM 1 PREVIEW<br/>
          <a href="https://bcourses.berkeley.edu/courses/1547647/external_tools/90481">(Recording: Talk 12)</a>
      </td>
      <td><a href="/sp26/labs/lab18">Lab 18. FUN Data Science</a></td>
      <td><a href="/sp26/discussion">Disc 13: Concurrency + Postterm Practice</a></td>
      <td><b>POSTTERM 1</b></td>
    </tr>
  </tbody>
</table>

<br/>
<!-- Week 14 Calendar -->
<table class="table table-bordered schedule-table" id="week14">
  <thead>
    <tr>
      <th class="center schedule-week-num">Week</th>
      <th>Date</th>
      <th>Lecture</th>
      <th>Lab</th>
      <th>Discussion</th>
      <th>Assignment / Exam</th>
    </tr>
  </thead>
  <tbody class="content">
    <tr>
      <td class="schedule-week-num" rowspan=6>Week 14</td>
      <th>Mon 4/20</th>
      <td>Lec 23. Python III - Game Theory<br/>
          <a href="https://bcourses.berkeley.edu/courses/1547647/external_tools/90481">(Recording 23)</a><br/>
          <a href="https://drive.google.com/drive/folders/17GcLVgPDtacDOrcVoCca9DkWHxYhP6Jr?usp=drive_link">(Slides 23)</a><br/>
          <a href="https://www.gradescope.com/courses/1098053/assignments/6577076">(Lecture Quiz 23)</a>
      </td>
      <td></td>
      <td></td>
      <td></td>
    </tr>
    <tr>
      <th>Tue 4/21</th>
      <td></td>
      <td></td>
      <td></td>
      <td></td>
    </tr>
    <tr>
      <th>Wed 4/22</th>
      <td>Lec 24. Python IV – OOP<br/>
          <a href="https://bcourses.berkeley.edu/courses/1547647/external_tools/90481">(Recording 24)</a><br/>
          <a href="https://drive.google.com/drive/folders/1CVZJWEKwJDovWhi8xvyWyUnPFL1jx9jg?usp=drive_link">(Slides 24)</a><br/>
          <a href="https://www.gradescope.com/courses/1098053/assignments/6577077">(Lecture Quiz 24)</a>
      </td>
      <td></td>
      <td></td>
      <td></td>
    </tr>
    <tr>
      <th>Thu 4/23</th>
      <td></td>
      <td>Catchup</td>
      <td></td>
      <td><b>POSTTERM 1</b></td>
    </tr>
    <tr>
      <th>Fri 4/24</th>
      <td>Talk 13: POSTTERM 1 REVIEW<br/>
          <a href="https://bcourses.berkeley.edu/courses/1547647/external_tools/90481">(Recording: Talk 13)</a>
      </td>
      <td></td>
      <td><a href="/sp26/discussion">Disc 14. Postterm Practice</a></td>
      <td><b>POSTTERM 2</b></td>
    </tr>
  </tbody>
</table>

<br/>
<!-- Week 15 Calendar -->
<table class="table table-bordered schedule-table" id="week15">
  <thead>
    <tr>
      <th class="center schedule-week-num">Week</th>
      <th>Date</th>
      <th>Lecture</th>
      <th>Lab</th>
      <th>Discussion</th>
      <th>Assignment / Exam</th>
    </tr>
  </thead>
  <tbody class="content">
    <tr>
      <td class="schedule-week-num" rowspan=5>Week 15</td>
      <th>Mon 4/27</th>
      <td>Lec 25. Alumni Panel<br/>
          <a href="https://bcourses.berkeley.edu/courses/1547647/external_tools/90481">(Recording 25)</a><br/>
          <a href="https://docs.google.com/presentation/d/1VhCulWZmBBCiIbiqgzCpSNoG03UkNfsFR-2paSl6T7Q/edit?usp=sharing">(Slides 25)</a><br/>
          <a href="https://www.gradescope.com/courses/1098053/assignments/6577058">(Lecture Quiz 25)</a>
      </td>
      <td></td>
      <td></td>
      <td></td>
    </tr>
    <tr>
      <th>Tue 4/28</th>
      <td></td>
      <td></td>
      <td></td>
      <td></td>
    </tr>
    <tr>
      <th>Wed 4/29</th>
      <td>Lec 26. Conclusion and Farewell<br/><br/>
          <a href="https://bcourses.berkeley.edu/courses/1547647/external_tools/90481">(Recording 26)</a><br/>
          <a href="https://drive.google.com/drive/folders/1wGA9aByrWClTdocxSn0B4aiceK54cPtU?usp=drive_link">(Slides 26)</a><br/>
          <a href="https://www.gradescope.com/courses/1098053/assignments/6577082">(Lecture Quiz 26)</a>
      </td>
      <td></td>
      <td></td>
      <td></td>
    </tr>
    <tr>
      <th>Thu 4/30</th>
      <td></td>
      <td>Project Work Session</td>
      <td></td>
      <td></td>
    </tr>
    <tr>
      <th>Fri 5/01</th>
      <td>Talk 14: POSTTERM 2 REVIEW<br/>
          <a href="https://bcourses.berkeley.edu/courses/1547647/external_tools/90481">(Recording: Talk 14)</a></td>
      <td>Practice Postterm</td>
      <td><a href="/sp26/discussion">Disc 15: Review</a></td>
      <td><b>POSTTERM 2</b><br/><b>POSTTERM 3</b></td>
    </tr>
  </tbody>
</table>

<br/>

<!-- RRR Week Calendar -->
<table class="table table-bordered schedule-table" id="rrrweek">
  <thead>
    <tr>
      <th class="center schedule-week-num">Week</th>
      <th>Date</th>
      <th>Lecture</th>
      <th>Lab</th>
      <th>Discussion</th>
      <th>Assignment / Exam</th>
    </tr>
  </thead>
  <tbody class="content">
    <tr>
      <td class="schedule-week-num" rowspan=5>RRR Week</td>
      <th>Mon 5/04</th>
      <td></td>
      <td></td>
      <td></td>
      <td></td>
    </tr>
    <tr>
      <th>Tue 5/05</th>
      <td></td>
      <td></td>
      <td></td>
      <td></td>
    </tr>
    <tr>
      <th>Wed 5/06</th>
      <td></td>
      <td></td>
      <td></td>
      <td></td>
    </tr>
    <tr>
      <th>Thu 5/07</th>
      <td></td>
      <td></td>
      <td></td>
      <td><a href="/sp26/projects/">Final Project Due</a></td>
    </tr>
    <tr>
      <th>Fri 5/08</th>
      <td></td>
      <td></td>
      <td></td>
      <td><b>POSTTERM 3</b></td>
    </tr>
  </tbody>
</table>

<br/>
<!-- Finals Week Calendar -->
<table class="table table-bordered schedule-table" id="finalsweek">
  <thead>
    <tr>
      <th class="center schedule-week-num">Week</th>
      <th>Date</th>
      <th>Lecture</th>
      <th>Lab</th>
      <th>Discussion</th>
      <th>Assignment / Exam</th>
    </tr>
  </thead>
  <tbody class="content">
    <tr>
      <td class="schedule-week-num" rowspan=5>Finals Week</td>
      <th>Mon 5/11</th>
      <td></td>
      <td></td>
      <td></td>
      <td></td>
    </tr>
    <tr>
      <th>Tue 5/12</th>
      <td></td>
      <td></td>
      <td></td>
      <td></td>
    </tr>
    <tr>
      <th>Wed 5/13</th>
      <td></td>
      <td></td>
      <td></td>
      <td></td>
    </tr>
    <tr>
      <th>Thu 5/14</th>
      <td></td>
      <td></td>
      <td></td>
      <td></td>
    </tr>
    <tr>
      <th>Fri 5/15</th>
      <td></td>
      <td></td>
      <td></td>
      <td></td>
