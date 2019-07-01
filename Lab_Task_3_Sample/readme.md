<!DOCTYPE html>
<html>
<head>
	<title>HTML Assignment</title>
</head>
<body>
	<h1> CSE482L: Internet and Web Technology Summer'19</h1>
	<div>
		<p>To introduce a student with the modern web development techniques in order to develop state-of-the-art web applications and that can be scalable with ease. The course provides a comprehensive overview of both front-end and back-end technologies like HTML5, CSS3, JavaScript, PHP and MYSQL. Upon completing the course, a learner will have a concise understanding of server- side and client-side programming knowledge.</p>
	</div>
	<div>
		<table border="1x">
			<thead>
				<tr>
					<th>Language</th>
					<th>Logo</th>
					<th>more information here</th>
				</tr>
			</thead>
			<tbody>
				<tr>
					<td>HTML</td>
					<td><img src="html.png"></td>
					<td><a href="https://en.wikipedia.org/wiki/HTML">Click Here</a></td>
				</tr>
				<tr>
					<td>CSS</td>
					<td><img src="css.png"></td>
					<td><a href="https://en.wikipedia.org/wiki/Cascading_Style_Sheets">Click Here</a></td>
				</tr>		
			</tbody>
		</table>
	</div>
	<br/>
	<form action="submit.html">	
    	<div>
      		<label for="name">Name:</label>
      		<input type="text" name="name" id="name" placeholder="Your Name" required />
      		<label for="nsu-id">NSU ID:</label>
      		<input type="text" name="nsu-id" id="nsu-id" placeholder="Your ID" required />
    	</div>
    	<br/>
    	<div>
        	<label for="radio-choice-1">Male</label>
        	<input type="radio" name="radio-choice" id="radio-choice-1" value="choice-1" />
       		<label for="radio-choice-2">Female</label>
       		<input type="radio" name="radio-choice" id="radio-choice-2" value="choice-2" />
       		<label for="radio-choice-3">Other</label>
        	<input type="radio" name="radio-choice" id="radio-choice-3" value="choice-3" />
     	</div>
     	<br/>
     	<div>
      		<label for="email">Email:</label>
      		<input type="email" name="email" id="email" required placeholder="your email">
    	</div>
    	<br/>
    	<div>
	      <label for="select-choice">Date:</label>
	      <select name="select-choice" id="select-choice">
	        <option value="0" selected disabled>Month</option>
	        <option value="may">May</option>
	        <option value="june">Jun</option>
	        <option value="july">Jul</option>
	        <option value="august">Aug</option>
	      </select>
	      <select name="date" id="day">
	        <option value="0" selected disabled>Day</option>
	        <option value="1">1</option>
	        <option value="2">2</option>
	        <option value="3">3</option>
	        <option value="4">4</option>
	        <option value="5">5</option>
	        <option value="6">6</option>
	        <option value="7">7</option>
	        <option value="8">8</option>
	        <option value="9">9</option>
	        <option value="10">10</option>
	        <option value="11">11</option>
	        <option value="12">12</option>
	        <option value="13">13</option>
	        <option value="14">14</option>
	        <option value="15">15</option>
	        <option value="16">16</option>
	        <option value="17">17</option>
	        <option value="18">18</option>
	        <option value="19">19</option>
	        <option value="20">20</option>
	        <option value="21">21</option>
	        <option value="22">22</option>
	        <option value="23">23</option>
	        <option value="24">24</option>
	        <option value="25">25</option>
	        <option value="26">26</option>
	        <option value="27">27</option>
	        <option value="28">28</option>
	        <option value="29">29</option>
	        <option value="30">30</option>
	        <option value="31">31</option>
	      </select>
	      <select name="year" id="year">
	        <option value="0" selected disabled>Year</option>
	        <option value="2019">2019</option>
	      </select>
    </div>
    <br/>
    <div>
      <label for="checkbox" >I agree that the full assignment is completed by myself</label>
      <input type="checkbox" name="checkbox" id="checkbox" required>
    </div>
    <br/>
    <div>
      <input type="submit" value="Submit" / action="https://github.com/NeloyNSU/CSE482_Summer-19_Section7?">
    </div>
	</form>

</body>
</html>
