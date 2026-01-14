<head><style>
  body {
    font-family: Arial, sans-serif;
    display: flex;
    justify-content: center;
    align-items: center;
    min-height: 100vh;
    margin: 0;
    background: linear-gradient(degR, #ffffff 0%, #d4edea 100%);
  }
  .button_default{
    padding:10px;
    background-color:white;
    color:black;
  }
  .button_color1{
    padding:10px;
    background-color:rgb(255,0,0);
    color:white;
  }
  .button_color2{
    padding:10px;
    background-color:rgb(0, 136, 255);
    color:white;
  }
  .container1 {
    text-align:left;
    background:rgb(180, 0, 0);
    color:white;
    padding:40px;
    border-radius:20px;
  }
  .container2 {
    text-align:left;
    background:rgb(0, 96, 180);
    color:white;
    padding:40px;
    border-radius:20px;
  }

</head>
<body>
<h1>NoShldJ's scouting site<br>for FIRST Robotics team 3019</h1>
Match #
<input class="fill-out"></input><br>

<p>Select participating teams:<br>
<button class="btn_default" onclick="iroGawari()" value="TEST1">TEST TEAM [1]</button>
<button class="btn_default" onclick="iroGawari()" value="TEST2">TEST TEAM [2]</button><br>
<button class="btn_default" onclick="iroGawari()" value="TEST3">TEST TEAM [3]</button>
<button class="btn_default" onclick="iroGawari()" value="TEST4">TEST TEAM [4]</button><br>
<button class="btn_default" onclick="iroGawari()" value="TEST5">TEST TEAM [5]</button>
<button class="btn_default" onclick="iroGawari()" value="TEST6">TEST TEAM [6]</button><br>
<button class="btn_default" onclick="iroGawari()" value="60">Bionic Bulldogs [60]</button>
<button class="btn_default" onclick="iroGawari()" value="244">RoboDawgs 3D [244]</button><br>
<button class="btn_default" onclick="iroGawari()" value="288">The RoboDawgs [288]</button>
<button class="btn_default" onclick="iroGawari()" value="698">Hamilton Microbots [698]</button><br>
<button class="btn_default" onclick="iroGawari()" value="987">HIGHROLLERS [987]</button>
<button class="btn_default" onclick="iroGawari()" value="991">BroncoBots [991]</button><br>
<button class="btn_default" onclick="iroGawari()" value="996">Mecha Knights [996]</button>
<button class="btn_default" onclick="iroGawari()" value="1165">Team Paradise [1165]</button><br>
<button class="btn_default" onclick="iroGawari()" value="1212">Sentinels [1212]</button>
<button class="btn_default" onclick="iroGawari()" value="1410">The Kraken [1410]</button><br>
<button class="btn_default" onclick="iroGawari()" value="1828">BoxerBots [1828]</button>
<button class="btn_default" onclick="iroGawari()" value="2080">Torbotics [2080]</button><br>
<button class="btn_default" onclick="iroGawari()" value="2122">Team Tators [2122]</button>
<button class="btn_default" onclick="iroGawari()" value="2403">Plasma Robotics [2403]</button><br>
<button class="btn_default" onclick="iroGawari()" value="2478">Westwood Robotics [2478]</button>
<button class="btn_default" onclick="iroGawari()" value="2486">CocoNuts [2486]</button><br>
<button class="btn_default" onclick="iroGawari()" value="2662">RoboKrew [2662]</button>
<button class="btn_default" onclick="iroGawari()" value="2840">PCDS Blue Tide [2840]</button><br>
<button class="btn_default" onclick="iroGawari()" value="3009">High Scalers [3009]</button>
<button class="btn_default" onclick="iroGawari()" value="3019">Firebirds [3019]</button><br>
<button class="btn_default" onclick="iroGawari()" value="3216">MRT [3216]</button>
<button class="btn_default" onclick="iroGawari()" value="3243">Amperes [3243]</button><br>
<button class="btn_default" onclick="iroGawari()" value="3245">Ravens [3245]</button>
<button class="btn_default" onclick="iroGawari()" value="3424">Corax [3424]</button><br>
<button class="btn_default" onclick="iroGawari()" value="3944">All Knights [3944]</button>
<button class="btn_default" onclick="iroGawari()" value="4146">Sabercats [4146]</button><br>
<button class="btn_default" onclick="iroGawari()" value="4731">MONARCH-E [4731]</button>
<button class="btn_default" onclick="iroGawari()" value="4735">DEROF [4735]</button><br>
<button class="btn_default" onclick="iroGawari()" value="5933">JudgeMent Call [5933]</button>
<button class="btn_default" onclick="iroGawari()" value="6352">LAUNCH TEAM [6352]</button><br>
<button class="btn_default" onclick="iroGawari()" value="6922">Apache Genesis [6922]</button>
<button class="btn_default" onclick="iroGawari()" value="7333">Ghost [7333]</button><br>
<button class="btn_default" onclick="iroGawari()" value="7425">Green Valley [7425]</button>
<button class="btn_default" onclick="iroGawari()" value="7426">PAIR OF DICE [7426]</button><br>
<button class="btn_default" onclick="iroGawari()" value="7703">RoboBears [7703]</button>
<button class="btn_default" onclick="iroGawari()" value="7755">Phantom Circuits [7755]</button><br>
<button class="btn_default" onclick="iroGawari()" value="8012">APEX [8012]</button>
<button class="btn_default" onclick="iroGawari()" value="8717">Cyber Vipers [8717]</button><br>
<button class="btn_default" onclick="iroGawari()" value="9059">COLTech [9059]</button>
<button class="btn_default" onclick="iroGawari()" value="9091">A.W.E. [9091]</button><br>
<button class="btn_default" onclick="iroGawari()" value="9501">Sidereal Envoy [9501]</button>
<button class="btn_default" onclick="iroGawari()" value="9534">Wolves (Basic HS) [9534]</button><br>
<button class="btn_default" onclick="iroGawari()" value="9610">Blue Ivy [9610]</button>
<button class="btn_default" onclick="iroGawari()" value="9704">IgKnighted [9704]</button><br>
<button class="btn_default" onclick="iroGawari()" value="9777">Knights of the Lab Table [9777]</button>
<button class="btn_default" onclick="iroGawari()" value="10114">Phantom Talons [10114]</button><br>
<button class="btn_default" onclick="iroGawari()" value="10183">ARC [10183]</button>
<button class="btn_default" onclick="iroGawari()" value="10380">The Dragon Hunters [10380]</button><br>
<button class="btn_default" onclick="iroGawari()" value="10506">Crash Test Dummies []</button>
<button class="btn_default" onclick="iroGawari()" value="10905">Team LOVE [10905]</button><br>
<button class="btn_default" onclick="iroGawari()" value="10933">Tie Dye Samurai [10933]</button>
<button class="btn_default" onclick="iroGawari()" value="10980">The Deadbolts []</button><br>
<button class="btn_default" onclick="iroGawari()" value="10988">Desert Storm []</button>
<button class="btn_default" onclick="iroGawari()" value="11100">Team Epsilon [11100]</button><br>
<button class="btn_default" onclick="iroGawari()" value="11176">RoboRabbits [11176]</button>
<button class="btn_default" onclick="iroGawari()" value="11212">BioHazard [11212]</button><br>
<button class="btn_default" onclick="iroGawari()" value="11479">Formosa Robotics [11479]</button><br></p>



<br>Press the button of the selected action when the team's robot performs that action!
<button onclick="action('hub-shot')">Hub Shot (robot)</button>
<button onclick="action('')">action 2</button>
<button onclick="action('')">action 3</button>
<button onclick="action('')">action 4</button>
</body>
<span hidden>

<button class="btn_default" value=""> []</button>
<button class="btn_default" value=""> []</button><br>

<script>
  var akaIkutsu = 0;
  var awoIkutsu = 0;
  function countMembers(){
    const akai = document.querySelectorAll('.' + button_color1);
    const akai = document.querySelectorAll('.' + button_color2);
    akaIkutsu = akai.length;
    awoIkutsu = awoi.length;
  }
  function iroGawari(){
    countMembers();
    if(class=="button_default"){
      btn.classList.remove(button_default);
      btn.classList.add(button_color1);
  } }
</script>
</span>

<span hidden>
AI's work to copy off of
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>Color-Changing Buttons with Counter</title>
  <style>
    body {
      font-family: Arial, sans-serif;
      display: flex;
      justify-content: center;
      align-items: center;
      min-height: 100vh;
      margin: 0;
      background: linear-gradient(135deg, #667eea 0%, #764ba2 100%);
    }
    .container {
      text-align: center;
      background: white;
      padding: 40px;
      border-radius: 20px;
      box-shadow: 0 10px 30px rgba(0, 0, 0, 0.3);
      max-width: 600px;
    }
    h1 {
      color: #333;
      margin-bottom: 30px;
    }
    .counter-section {
      background: #f8f9fa;
      padding: 20px;
      border-radius: 10px;
      margin-bottom: 30px;
    }
    .counter-section h2 {
      color: #555;
      font-size: 18px;
      margin-bottom: 15px;
    }
    .color-display {
      display: flex;
      flex-direction: column;
      gap: 15px;
    }
    .color-row {
      display: flex;
      align-items: center;
      gap: 10px;
    }
    .color-label {
      font-weight: bold;
      min-width: 60px;
      padding: 8px 15px;
      border-radius: 5px;
      color: white;
    }
    .label-red {
      background-color: #e74c3c;
    }
    .label-blue {
      background-color: #3498db;
    }
    .button-list {
      display: flex;
      flex-wrap: wrap;
      gap: 8px;
      flex: 1;
    }
    .button-indicator {
      background-color: #ecf0f1;
      padding: 5px 12px;
      border-radius: 5px;
      font-size: 14px;
      font-weight: bold;
      color: #555;
    }
    .counter-grid {
      display: grid;
      grid-template-columns: repeat(3, 1fr);
      gap: 10px;
    }
    .color-count {
      padding: 10px;
      border-radius: 8px;
      color: white;
      font-weight: bold;
    }
    .count-red { background-color: #e74c3c; }
    .count-blue { background-color: #3498db; }
    .count-green { background-color: #2ecc71; }
    .button-grid {
      display: grid;
      grid-template-columns: repeat(5, 1fr);
      gap: 15px;
    }
    .btn {
      padding: 15px 20px;
      font-size: 14px;
      font-weight: bold;
      border: none;
      border-radius: 10px;
      cursor: pointer;
      transition: all 0.3s ease;
      color: white;
      background-color: #2ecc71;
    }
    .color1 { background-color: #e74c3c; }
    .color2 { background-color: #3498db; }
    .color-green { background-color: #2ecc71; }
    .btn:hover {
      transform: translateY(-2px);
      box-shadow: 0 5px 15px rgba(0, 0, 0, 0.2);
    }
    .btn:active {
      transform: translateY(0);
    }      
</style></head>
<body>
  <div class="container">
  <h1>Color Cycling Buttons</h1>
  <div class="counter-section">
    <h2>Button Color Status</h2>
      <div class="color-display">
        <div class="color-row">
          <div class="color-label label-red">Red</div>
          <div class="button-list" id="red-buttons"></div>
        </div>
        <div class="color-row">
          <div class="color-label label-blue">Blue</div>
          <div class="button-list" id="blue-buttons"></div>
        </div>
      </div>
    </div>
    <div class="button-grid">
      <button class="btn" onclick="cycleColor(this, 0)">Button 1</button>
      <button class="btn" onclick="cycleColor(this, 1)">Button 2</button>
      <button class="btn" onclick="cycleColor(this, 2)">Button 3</button>
      <button class="btn" onclick="cycleColor(this, 3)">Button 4</button>
      <button class="btn" onclick="cycleColor(this, 4)">Button 5</button>
      <button class="btn" onclick="cycleColor(this, 5)">Button 6</button>
      <button class="btn" onclick="cycleColor(this, 6)">Button 7</button>
      <button class="btn" onclick="cycleColor(this, 7)">Button 8</button>
      <button class="btn" onclick="cycleColor(this, 8)">Button 9</button>
      <button class="btn" onclick="cycleColor(this, 9)">Button 10</button>
      <button class="btn" onclick="cycleColor(this, 10)">Button 11</button>
      <button class="btn" onclick="cycleColor(this, 11)">Button 12</button>
      <button class="btn" onclick="cycleColor(this, 12)">Button 13</button>
      <button class="btn" onclick="cycleColor(this, 13)">Button 14</button>
      <button class="btn" onclick="cycleColor(this, 14)">Button 15</button>
    </div>
  </div>
    <script>
      const colorClasses = ['color1', 'color2'];
      const colorNames = ['red', 'blue'];
      // Track each button's current color index (-1 means default green, 0 = color1, 1 = color2)
      let buttonColorIndexes = [-1, -1, -1, -1, -1, -1, -1, -1, -1, -1, -1, -1, -1, -1, -1];
      // Track counts for each color
      let colorCounts = {
        'color1': 0,
        'color2': 0
      };
      function updateCounterDisplay() {
        const color1Buttons = [];
        const color2Buttons = [];
        // Find which buttons are color1 and which are color2
        buttonColorIndexes.forEach((colorIndex, buttonIndex) => {
          const buttonNumber = buttonIndex + 1;
          if (colorIndex === 0) {
            color1Buttons.push(buttonNumber);
          } else if (colorIndex === 1) {
            color2Buttons.push(buttonNumber);
      }   });
      // Update color1 buttons display (red)
      const redContainer = document.getElementById('red-buttons');
      redContainer.innerHTML = '';
      if (color1Buttons.length === 0) {
        redContainer.innerHTML = '<span style="color: #999;">None</span>';
      } else {
        color1Buttons.forEach(num => {
        const indicator = document.createElement('div');
        indicator.className = 'button-indicator';
        indicator.textContent = `Button ${num}`;
        redContainer.appendChild(indicator);
      }); }
      // Update color2 buttons display (blue)
      const blueContainer = document.getElementById('blue-buttons');
      blueContainer.innerHTML = '';
      if (color2Buttons.length === 0) {
        blueContainer.innerHTML = '<span style="color: #999;">None</span>';
      } else {
        color2Buttons.forEach(num => {
        const indicator = document.createElement('div');
        indicator.className = 'button-indicator';
        indicator.textContent = `Button ${num}`;
        blueContainer.appendChild(indicator);
      });}}
      function cycleColor(btn, buttonIndex) {
        const currentColorIndex = buttonColorIndexes[buttonIndex];
        // Calculate next color index (-1 -> 0 -> 1 -> -1)
        let newColorIndex = currentColorIndex + 1;
        if (newColorIndex > 1) {
          newColorIndex = -1;
            }
            // If not going to default green, check if we need to find an available color
            if (newColorIndex !== -1) {
                let attempts = 0;
                while (newColorIndex !== -1 && attempts < 2) {
                    const nextColor = colorClasses[newColorIndex];
                    // Check if color is at its limit
                    if (colorCounts[nextColor] < 3) {
                        break;
                    }
                    newColorIndex = (newColorIndex + 1) % 2;
                    attempts++;
      }
      // If both colors are at limit, go back to green
      if (newColorIndex !== -1 && colorCounts[colorClasses[newColorIndex]] >= 3) {
        newColorIndex = -1;
      }   }
      // Remove old color class if it exists
      if (currentColorIndex !== -1) {
        const currentColor = colorClasses[currentColorIndex];
        btn.classList.remove(currentColor);
        colorCounts[currentColor]--;
      }
      // Add new color class if not default green
      if (newColorIndex !== -1) {
        const newColor = colorClasses[newColorIndex];
        btn.classList.add(newColor);
        colorCounts[newColor]++;
      }
      // Update button's color index
      buttonColorIndexes[buttonIndex] = newColorIndex;
      // Update the display
      updateCounterDisplay();
    }
    // Initialize the display on page load
    updateCounterDisplay();
  </script>
</span>