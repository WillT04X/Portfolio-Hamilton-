<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>Lewis Hamilton</title>

  <!-- Fonts -->
  <link href="https://fonts.googleapis.com/css2?family=Orbitron:wght@700&display=swap" rel="stylesheet">
  <link href="https://fonts.googleapis.com/css2?family=Montserrat:wght@400&display=swap" rel="stylesheet">
  <link rel="stylesheet" href="f1project.css">
</head>
<body>

<header class="header">
  <h1>Lewis Hamilton</h1>
  <div class="nav-toggle" id="navToggle">
    <div></div>
    <div></div>
    <div></div>
  </div>
  <nav class="navigation" id="navMenu">
    <a href="#">Home</a>
    <a href="#">About</a>
    <a href="#">Career</a>
    <a href="#">Teammate</a>
    <a href="#">News</a>
  </nav>
</header>

<div class="main-content">
  <div class="countdown-box">
    <div class="countdown-title">NEXT RACE: <span id="race-name">Loading...</span></div>
    <div class="countdown-timer" id="countdown">
      <div class="time-segment">
        <span class="time-value" id="days">00</span>
        <span class="time-label">Days</span>
      </div>
      <span class="separator">:</span>
      <div class="time-segment">
        <span class="time-value" id="hours">00</span>
        <span class="time-label">Hours</span>
      </div>
      <span class="separator">:</span>
      <div class="time-segment">
        <span class="time-value" id="minutes">00</span>
        <span class="time-label">Minutes</span>
      </div>
      <span class="separator">:</span>
      <div class="time-segment">
        <span class="time-value" id="seconds">00</span>
        <span class="time-label">Seconds</span>
      </div>
    </div>
  </div>

  <div class="card-container">
    <div class="lewis-driver-card">
      <div class="lewis-driver-card-content">
        <h3>🏎️ Lewis Hamilton's 2025</h3>
        <div class="stats">
          <p>Current Position: <span class="highlight">#7</span></p>
          <p>Points: <span class="highlight">53</span></p>
          <p>Race Wins: <span class="highlight">0</span></p>
          <p>Sprint Wins: <span class="highlight">1</span></p>
        </div>
      </div>
    </div>

    <div class="track-driver-card">
      <h3>🏟️ Most Successful Track</h3>
      <img src="silverstone.png" alt="Silverstone Circuit" class="track-image">
      <p>Track: <span class="highlight">Silverstone</span></p>
	  <p>Poles: <span class ="highlight"> 7</span></p>
      <p>Wins: <span class="highlight">8</span></p>
      <p>Podiums: <span class="highlight">11</span></p>
    </div>
  </div>
</div>

<section class="race-calendar">
  <h2>2025 F1 Race Calendar</h2>
  <button class="calendar-toggle" id="toggleCalendar">Show Calendar</button>
<div class ="calendar-wrapper">
  <table class="calendar-table" id="calendarTable">
    <thead>
      <tr>
        <th>Round</th>
        <th>Date</th>
        <th>Grand Prix</th>
        <th>Location</th>
        <th>Winner</th>
      </tr>
    </thead>
    <tbody>
  <tr class="mclaren"><!-- race 1 -->
    <td>1</td><td>March 16</td><td>Australia</td><td>Melbourne</td><td>Lando Norris</td> 
  </tr>
  <tr class="ferrari sprint"><!-- sprint -->
    <td>Sprint 1</td>
    <td>March 22</td>
    <td>China <span class="sprint-label">🏁 Sprint</span></td>
    <td>China</td>
    <td>Lewis Hamilton</td>
  </tr>
  <tr class="mclaren"><!-- race 2 -->
    <td>2</td><td>March 23</td><td>China</td><td>Shanghai</td><td>Oscar Piastri</td>
  </tr>
  <tr class="redbull"><!-- race 3 -->
    <td>3</td><td>April 6</td><td>Japan</td><td>Suzuka</td><td>Max Verstappen</td>
  </tr>
  <tr class="mclaren"><!-- race 4 -->
    <td>4</td><td>April 13</td><td>Bahrain</td><td>Sakhir</td><td>Oscar Piastri</td>
  </tr>
  <tr class="mclaren"><!-- race 5 -->
    <td>5</td><td>April 20</td><td>Saudi Arabia</td><td>Jeddah</td><td>Oscar Piastri</td>
  </tr>
  <tr class="mclaren sprint"><!-- sprint -->
    <td>Sprint 2</td>
    <td>May 3</td>
    <td>Miami <span class="sprint-label">🏁 Sprint</span></td>
    <td>Miami</td>
    <td>Lando Norris</td>
  </tr>
  <tr class="mclaren"><!-- race 6 -->
    <td>6</td><td>May 4</td><td>United States of America</td><td>Miami</td><td>Oscar Piastri</td>
  </tr>
  <tr class ="redbull"><!-- race 7 -->
    <td>7</td><td>May 18</td><td>Italy</td><td>Imola</td><td>Max Verstappen</td>
  </tr>
  <tr><!-- race 8 -->
    <td>8</td><td>May 25</td><td>Monaco</td><td>Monaco</td><td>TBD</td>
  </tr>
  <tr><!-- race 9 -->
    <td>9</td><td>June 1</td><td>Spain</td><td>Barcelona</td><td>TBD</td>
  </tr>
  <tr><!-- race 10 -->
    <td>10</td><td>June 15</td><td>Canada</td><td>Montréal</td><td>TBD</td>
  </tr>
  <tr><!-- race 11 -->
    <td>11</td><td>June 29</td><td>Austria</td><td>Spielberg</td><td>TBD</td>
  </tr>
  <tr><!-- race 12 -->
    <td>12</td><td>July 6</td><td>Great Britain</td><td>Silverstone</td><td>TBD</td>
  </tr>
  <tr class ="sprint">
	<td>Sprint 3</td>
	<td>July 26</td>
	<td>Belgium<span class="sprint-label">🏁 Sprint</span></td>
	<td>Belgium</td>
	<td> TBD</td>
	</tr>
  <tr><!-- race 13 -->
    <td>13</td><td>July 27</td><td>Belgium</td><td>Spa-Francorchamps</td><td>TBD</td>
  </tr>
  <tr><!-- race 14 -->
    <td>14</td><td>August 3</td><td>Hungary</td><td>Budapest</td><td>TBD</td>
  </tr>
  <tr><!-- race 15 -->
    <td>15</td><td>August 31</td><td>Netherlands</td><td>Zandvoort</td><td>TBD</td>
  </tr>
  <tr><!-- race 16 -->
    <td>16</td><td>September 7</td><td>Italy</td><td>Monza</td><td>TBD</td>
  </tr>
  <tr><!-- race 17 -->
    <td>17</td><td>September 21</td><td>Azerbaijan</td><td>Baku</td><td>TBD</td>
  </tr>
  <tr><!-- race 18 -->
    <td>18</td><td>October 5</td><td>Singapore</td><td>Marina Bay</td><td>TBD</td>
  </tr>
  <tr class ="sprint">
	<td>Sprint 4</td>
	<td>October 18</td>
	<td>Austin<span class ="sprint-label">🏁 Sprint</span></td>
	<td>Austin</td>
	<td>TBD</td>
	</tr>
  <tr><!-- race 19 -->
    <td>19</td><td>October 19</td><td>United States</td><td>Austin</td><td>TBD</td>
  </tr>
  <tr><!-- race 20 -->
    <td>20</td><td>October 26</td><td>Mexico</td><td>Mexico City</td><td>TBD</td>
  </tr>
  <tr class ="sprint">
	<td>Sprint 5</td>
	<td>November 8</td>
	<td>São Paulo<span class ="sprint-label">🏁 Sprint</span></td>
	<td>São Paulo</td>
	<td>TBD</td>
	</tr>
  <tr><!-- race 21 -->
    <td>21</td><td>November 9</td><td>Brazil</td><td>São Paulo</td><td>TBD</td>
  </tr>
  <tr><!-- race 22 -->
    <td>22</td><td>November 22</td><td>Las Vegas</td><td>Las Vegas</td><td>TBD</td>
  </tr>
  <tr class ="sprint">
	<td>Sprint 6</td>
	<td>November 28</td>
	<td>Lusail<span class = "sprint-label">🏁 Sprint</span></td>
	<td>Lusail</td>
	<td>TBD</td>
	</tr>
  <tr><!-- race 23 -->
    <td>23</td><td>November 29</td><td>Qatar</td><td>Lusail</td><td>TBD</td>
  </tr>
  <tr><!-- race 24 -->
    <td>24</td><td>December 6</td><td>Abu Dhabi</td><td>Yas Island</td><td>TBD</td>
  </tr>
</tbody>

  </table>
</div>
</section>

<script>
document.addEventListener("DOMContentLoaded", function() {
  // Toggle navigation menu on mobile
  const navToggle = document.getElementById('navToggle');
  const navMenu = document.getElementById('navMenu');
  
  if (navToggle) {
    navToggle.addEventListener('click', function() {
      navMenu.classList.toggle('active');
    });
  }

  // Calendar toggle functionality
  const toggleCalendarBtn = document.getElementById('toggleCalendar');
  const calendarTable = document.getElementById('calendarTable');
  
  toggleCalendarBtn.addEventListener('click', function() {
    if (calendarTable.style.display === 'none' || calendarTable.style.display === '') {
      calendarTable.style.display = 'table';
      toggleCalendarBtn.textContent = 'Hide Calendar';
    } else {
      calendarTable.style.display = 'none';
      toggleCalendarBtn.textContent = 'Show Calendar';
    }
  });

  const raceSchedule = [
    { date: new Date("March 16, 2025 04:00:00"), name: "Australian Grand Prix" },
	{ date: new Date("March 22, 2025 03:00:00"), name: "🏁 Chinese Sprint 🏁" },
    { date: new Date("March 23, 2025 07:00:00"), name: "Chinese Grand Prix" },
    { date: new Date("April 6, 2025 06:00:00"), name: "Japanese Grand Prix" },
    { date: new Date("April 13, 2025 16:00:00"), name: "Bahrain Grand Prix" },
    { date: new Date("April 20, 2025 18:00:00"), name: "Saudi Arabian Grand Prix" },
	{ date: new Date("May 4, 2025 17:00:00"), name: "🏁 Miami Sprint 🏁" },
    { date: new Date("May 4, 2025 21:00:00"), name: "Miami Grand Prix" },
    { date: new Date("May 18, 2025 14:00:00"), name: "Italian Grand Prix" },
    { date: new Date("May 25, 2025 14:00:00"), name: "Monaco Grand Prix" },
    { date: new Date("June 1, 2025 14:00:00"), name: "Spanish Grand Prix" },
    { date: new Date("June 15, 2025 19:00:00"), name: "Canadian Grand Prix" },
    { date: new Date("June 29, 2025 14:00:00"), name: "Austrian Grand Prix" },
    { date: new Date("July 6, 2025 15:00:00"), name: "British Grand Prix" },
	{ date: new Date("July 26, 2025 11:00:00"), name: "🏁 Belgium Sprint 🏁" },
    { date: new Date("July 27, 2025 14:00:00"), name: "Belgian Grand Prix" },
    { date: new Date("August 3, 2025 14:00:00"), name: "Hungarian Grand Prix" },
    { date: new Date("August 31, 2025 14:00:00"), name: "Dutch Grand Prix" },
    { date: new Date("September 7, 2025 14:00:00"), name: "Italian Grand Prix" },
    { date: new Date("September 21, 2025 12:00:00"), name: "Azerbaijan Grand Prix" },
    { date: new Date("October 5, 2025 13:00:00"), name: "Singapore Grand Prix" },
	{ date: new Date("October 18, 2025 18:00:00"), name: "🏁 US Sprint 🏁" },
    { date: new Date("October 19, 2025 20:00:00"), name: "United States Grand Prix" },
    { date: new Date("October 26, 2025 20:00:00"), name: "Mexican Grand Prix" },
	{ date: new Date("November 8, 2025 14:00:00"), name: "🏁 Brazil Sprint 🏁" },
    { date: new Date("November 9, 2025 17:00:00"), name: "Brazilian Grand Prix" },
	{ date: new Date("November 23, 2025 04:00:00"), name: "Las Vegas Grand Prix" },
	{ date: new Date("November 29, 2025 14:00:00"), name: "🏁 Qatar Sprint 🏁" },
	{ date: new Date("November 30, 2025 16:00:00"), name: "Qatar Grand Prix" },
    { date: new Date("November 7, 2025 13:00:00"), name: "Abu Dhabi Grand Prix" },
  ];
  
  let raceIndex = 0;
  const countdownDisplay = document.querySelector("#countdown");
  const raceNameElement = document.getElementById("race-name");

  function updateCountdown() {
    const now = new Date();
    
    // Find the next upcoming race
    for(let i = 0; i < raceSchedule.length; i++) {
      if(raceSchedule[i].date > now) {
        raceIndex = i;
        break;
      }
    }
    
    const raceDate = raceSchedule[raceIndex].date;
    const raceName = raceSchedule[raceIndex].name;
    const timeDiff = raceDate - now;

    // Update race name
    raceNameElement.textContent = raceName;

    // Update countdown timer
    if (timeDiff > 0) {
      const days = Math.floor(timeDiff / (1000 * 60 * 60 * 24));
      const hours = Math.floor((timeDiff % (1000 * 60 * 60 * 24)) / (1000 * 60 * 60));
      const minutes = Math.floor((timeDiff % (1000 * 60 * 60)) / (1000 * 60));
      const seconds = Math.floor((timeDiff % (1000 * 60)) / 1000);
      
      document.getElementById("days").textContent = days.toString().padStart(2, '0');
      document.getElementById("hours").textContent = hours.toString().padStart(2, '0');
      document.getElementById("minutes").textContent = minutes.toString().padStart(2, '0');
      document.getElementById("seconds").textContent = seconds.toString().padStart(2, '0');
    }
  }

  updateCountdown();
  setInterval(updateCountdown, 1000);
});
</script>

</body>
</html>/* Base layout and typography for the page */
body {
  background-color: #f4f4f4; /* Light gray background */
  font-family: 'Montserrat', sans-serif; /* Use Montserrat font */
  color: #333; /* Dark gray text color */
  line-height: 1.6; /* Line height for readability */
  margin: 0; /* Remove default margin */
  overflow-x: hidden; /* Prevent horizontal scrolling */
  padding: 0; /* Remove default padding */
}

/* Adjusting padding to prevent overlap with fixed header */
.main-content {
  padding-top: 250px; 
}

/* Header styling */
.header {
  position: fixed; /* Fix header at the top of the page */
  top: 0; 
  width: 100%; /* Full width */
  background-color: #f9221c; /* Red background color */
  display: flex; /* Use flexbox for layout */
  flex-direction: column;
  align-items: center; /* Center content horizontally */
  padding: 15px; 
  z-index: 1000; /* Ensure it stays above other elements */
  box-shadow: 0 4px 8px rgba(0, 0, 0, 0.7); /* Subtle shadow */
  border: solid white 5px; /* White border */
  box-sizing: border-box; /* Include border in width/height calculations */
}

/* Header text: Lewis Hamilton's name with animated gradient */
.header h1 {
  font-size: calc(4vw + 20px); /* Responsive font size */
  font-family: 'Orbitron', sans-serif; /* Futuristic font */
  font-weight: bold;
  text-transform: uppercase;
  letter-spacing: 2px;
  background: linear-gradient(90deg, black, white, black); /* Shimmering metallic gradient */
  background-size: 200%; /* Make background larger for animation */
  color: transparent;
  -webkit-background-clip: text; /* Clip the gradient to text */
  background-clip: text; 
  animation: lewisFade 4s infinite linear; /* Infinite animation for shimmering effect */
  text-shadow: 1px 1px 2px rgba(0, 0, 0, 0.8); /* Subtle text shadow */
  margin: 0; /* Remove default margin */
}

/* Animation for shimmering gradient text */
@keyframes lewisFade {
  0% { background-position: -200%; }
  100% { background-position: 200%; }
}

/* Navigation container for menu links */
.navigation {
  display: flex;
  align-items: center;
  justify-content: center; /* Center navigation items */
  gap: 15px; /* Space between navigation items */
  margin-top: 10px;
}

/* Navigation links styling */
.navigation a {
  color: white; /* White text color */
  text-align: center;
  padding: 10px 10px;
  text-decoration: none; /* Remove underline */
  font-size: 18px;
  transition: background-color 0.3s, color 0.3s; /* Smooth hover transition */
}

/* Navigation hover effects */
.navigation a:hover {
  background-color: black; /* Dark background on hover */
  color: white; /* White text on hover */
}

/* Hamburger menu for mobile */
.nav-toggle {
  display: none; /* Hide by default */
  flex-direction: column;
  cursor: pointer;
}

/* Hamburger icon lines styling */
.nav-toggle div {
  width: 25px;
  height: 3px;
  background-color: white; /* White color for the lines */
  margin: 3px 0; /* Space between lines */
}

/* Responsive mobile navigation */
@media (max-width: 700px) {
  .navigation {
    display: none; /* Hide navigation links */
    flex-direction: column; /* Stack links vertically */
    position: absolute;
    top: 100%;
    right: 0;
    background-color: #f9221c; /* Red background */
    width: 100%;
  }

  .navigation a {
    padding: 15px;
    border-top: 1px solid white; /* Border between links */
  }

  .nav-toggle {
    display: flex; /* Show hamburger menu */
  }

  .navigation.active {
    display: flex; /* Show the navigation menu when active */
  }

  .main-content {
    padding-top: 220px; /* Adjust for mobile view */
  }
}

/* Countdown timer box container */
.countdown-box {
  background-color: black; /* Black background */
  color: white; /* White text */
  text-align: center;
  padding: 30px 20px; /* Increased padding for better spacing */
  max-width: 1200px; /* Set max width */
  width: 100%;
  border-style: solid;
  border-color: grey;
  border-width: 5px 0; /* Border on top and bottom */
  box-shadow: 0px 4px 10px rgba(0, 0, 0, 0.5); /* Subtle shadow */
  margin: 0 auto; /* Center the box */
  box-sizing: border-box; /* Include padding/border in width/height */
}

/* Countdown box heading styling */
.countdown-box h2 {
  font-size: clamp(1.5rem, 5vw, 3rem); /* Responsive font size */
  font-weight: bold;
  text-transform: uppercase;
  margin-bottom: 10px;
  white-space: nowrap; /* Prevent text from wrapping */
}

/* "Next Race Loading" text styling */
.countdown-title {
  font-family: 'Orbitron', sans-serif;
  font-size: 1.8rem; /* Increased font size */
  margin-bottom: 20px;
  color: white;
  text-shadow: 2px 2px 4px rgba(0, 0, 0, 0.5); /* Subtle shadow */
}

/* Countdown timer styling: flex layout with red background */
.countdown-timer {
  display: flex;
  justify-content: center;
  align-items: center;
  gap: 20px; /* Space between segments */
  font-family: 'Orbitron', sans-serif;
  flex-wrap: wrap;
  padding: 15px;
  background-color: rgba(249, 34, 28, 0.2); /* Light red background */
  border-radius: 10px; /* Rounded corners */
  max-width: 800px;
  margin: 0 auto; /* Center the container */
}

/* Individual countdown segments */
.time-segment {
  display: flex;
  flex-direction: column; /* Stack the numbers and labels */
  align-items: center;
  min-width: 80px; /* Minimum width for each segment */
}

/* Countdown numerical value styling */
.time-value {
  font-size: calc(min(12vw, 70px)); /* Responsive font size */
  font-weight: bold;
  margin-bottom: 5px;
  color: #f9221c; /* Red color for numbers */
  text-shadow: 0 0 10px rgba(249, 34, 28, 0.5); /* Glowing text effect */
}

/* Time label (hours, minutes, seconds) styling */
.time-label {
  font-size: 1rem;
  text-transform: uppercase;
  letter-spacing: 1px;
}

/* Separator between time values */
.separator {
  font-size: 42px; /* Larger separator */
  font-weight: bold;
  color: #f9221c; /* Red color for separators */
}

/* Container for driver card and track card, flex layout for responsive design */
.card-container {
  display: flex;
  justify-content: center;
  align-items: stretch;
  flex-wrap: wrap;
  gap: 20px;
  max-width: 1200px;
  margin: 50px auto;
  padding: 20px;
}

.lewis-driver-card {
  position: relative;
  background: black; /* Solid black background */
  color: white;
  width: calc(50% - 20px);
  min-width: 250px;
  padding: 20px;
  border-radius: 15px;
  border: 5px solid #f9221c;
  box-shadow: 0 8px 20px rgba(0, 0, 0, 0.8);
  overflow: hidden;
  text-align: left;
  flex: 1;
}

/* Transparent Lewis Hamilton PNG layered over black background */
.lewis-driver-card::after {
  content: '';
  position: absolute;
  top: 0;
  left: 0;
  height: 100%;
  width: 100%;
  background: url('lewishamilton.png') center/contain no-repeat;
  opacity: 1;
  z-index: 0; /* Behind text but above background */
}

/* Gradient overlay, still visible */
.lewis-driver-card::before {
  content: '';
  position: absolute;
  top: 0;
  left: 0;
  height: 100%;
  width: 100%;
  background: linear-gradient(
    135deg,
    rgba(249, 34, 28, 0.7),
    rgba(217, 0, 0, 0.7),
    rgba(255, 204, 0, 0.7)
  );
  opacity: 0.6;
  z-index: 0; /* Still behind text */
}

/* Content stays on top */
.lewis-driver-card-content {
  position: relative;
  z-index: 1;
  display: flex;
  justify-content: center;
  flex-direction: column;
  align-items: center;
  text-align: center;
  padding: 20px;
  width: 100%;
  height: 100%;
  box-sizing: border-box;
}


/* Title inside driver card */
.lewis-driver-card h3 {
  font-size: 2rem;
  margin-bottom: 20px;
  text-transform: uppercase;
  text-shadow: 2px 2px 5px black; /* Black shadow for visibility */
}

/* Stats inside the driver card, stacked vertically */
.lewis-driver-card .stats {
  display: flex;
  flex-direction: column;
  gap: 15px;
  font-size: 1.3rem;
  text-shadow: 1px 1px 3px rgba(0, 0, 0, 0.9); /* Darker text shadow */
  width: 100%;
  max-width: 350px;
}

/* Highlighted stats (bold) */
.highlight {
  font-weight: bold;
  color: #ffffff;
  font-size: 1.5rem;
  text-shadow: 1px 1px 2px black;
}


/* Track card container for Lewis Hamilton's best track */
.track-driver-card {
  background: black;
  color: white;
  width: calc(50% - 20px);
  min-width: 250px;
  padding: 20px;
  border-radius: 15px;
  border: 5px solid #f9221c;
  box-shadow: 0 8px 20px rgba(0,0,0,0.8);
  text-align: center;
  flex: 1;
  display: flex;
  flex-direction: column;
  justify-content: center;
  align-items: center;
}

/* Track card title styling */
.track-driver-card h3 {
  font-size: 1.8rem;
  margin-bottom: 15px;
  text-transform: uppercase;
  text-shadow: 2px 2px 5px black;
}

/* Track image responsive styling */
.track-image {
  width: 100%;
  max-width: 250px; /* Control image size */
  height: auto;
  border-radius: 10px;
  margin: 20px 0;
}

/* Responsive layout for smaller screens */
@media (max-width: 900px) {
  .lewis-driver-card,
  .track-driver-card {
    width: 100%; /* Full width for cards on small screens */
    flex: none;
  }

  .lewis-driver-card {
    min-height: 350px;
  }
}

/* Mobile styling adjustments */
@media (max-width: 768px) {
  .countdown-timer {
    gap: 10px;
  }

  .time-value {
    font-size: calc(min(10vw, 60px)); /* Adjust font size on mobile */
  }

  .separator {
    font-size: 32px; /* Smaller separators */
  }

  .time-segment {
    min-width: 60px; /* Smaller min width for segments */
  }

  .countdown-title {
    font-size: 1.5rem; /* Adjust title size */
  }
}

/* Very small screen styling */
@media (max-width: 500px) {
  .main-content {
    padding-top: 240px;
  }

  .time-segment {
    min-width: 50px;
  }

  .separator {
    font-size: 24px;
  }

  .time-value {
    font-size: calc(min(8vw, 40px));
  }

  .time-label {
    font-size: 0.8rem; /* Smaller time labels */
  }

  .countdown-timer {
    padding: 10px; /* Reduced padding */
  }
}

/* Race calendar container styling */
.race-calendar {
  max-width: 1000px;
  margin: 50px auto;
  padding: 20px;
  background-color: #fff;
  border: 5px solid #f9221c;
  border-radius: 15px;
  box-shadow: 0 8px 20px rgba(0,0,0,0.5);
  text-align: center;
}

/* Calendar heading styling */
.race-calendar h2 {
  font-family: 'Orbitron', sans-serif;
  color: #f9221c;
  font-size: 2rem;
  margin-bottom: 20px;
}

/* Calendar table hidden by default */
.calendar-table {
  width: 100%;
  border-collapse: collapse;
  font-size: 1rem;
  display: none;
  table-layout: fixed; /* evenly distributed columns */
}

.calendar-table th,
.calendar-table td {
  border: 1px solid #ccc;
  padding: 12px;
  text-align: center;
  white-space: normal;      /* allow text wrap */
  word-wrap: break-word;    /* break long words */
}

/* Header for calendar table */
.calendar-table th {
  background-color: #f9221c;
  color: white;
  text-transform: uppercase;
}

/* Alternate row coloring */
.calendar-table tr:nth-child(even) {
  background-color: #f9f9f9;
}

/* Calendar toggle button styling */
.calendar-toggle {
  display: inline-block;
  background-color: #f9221c;
  color: white;
  font-family: 'Orbitron', sans-serif;
  font-size: 1.2rem;
  padding: 12px 24px;
  border: none;
  border-radius: 8px;
  cursor: pointer;
  margin-bottom: 20px;
  transition: all 0.3s ease;
  box-shadow: 0 4px 8px rgba(0,0,0,0.3);
}

.calendar-toggle:hover {
  background-color: #d31a14;
  transform: translateY(-2px);
  box-shadow: 0 6px 12px rgba(0,0,0,0.4);
}

.calendar-toggle:active {
  transform: translateY(1px);
  box-shadow: 0 2px 4px rgba(0,0,0,0.3);
}

.calendar-wrapper {
  overflow-x: auto;
  -webkit-overflow-scrolling: touch;
  max-width: 100%;
}

/* Responsive tweaks for smaller screens */
@media (max-width: 480px) {
  .calendar-table {
    font-size: 0.75rem;
  }
  .calendar-table th,
  .calendar-table td {
    padding: 6px 8px;
  }
}

/* McLaren - orange text for the winner column */
tr.mclaren td:last-child {
  color: #ff8700; /* Bright McLaren orange */
  font-weight: bold;
  text-shadow: 1px 1px 2px #000;
  font-family: 'Orbitron', sans-serif;
  text-transform: uppercase;
}

/* Ferrari - red text for the winner column */
tr.ferrari td:last-child {
  color: #dc0000; /* Ferrari red */
  font-weight: bold;
  text-shadow: 1px 1px 2px #000;
  font-family: 'Orbitron', sans-serif;
  text-transform: uppercase;
}

/* Red Bull - deep blue text for the winner column */
tr.redbull td:last-child {
  color: #1e41ff; /* Red Bull blue */
  font-weight: bold;
  text-shadow: 1px 1px 2px #000;
  font-family: 'Orbitron', sans-serif;
  text-transform: uppercase;
}


/* Optional: distinguish sprints visually */
tr.sprint {
  font-weight: bold;
}





