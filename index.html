<html>
<script>
  var pos = 0;
const pacArray = [
  ['./pacman1.png', './pacman2.png'],
  ['./pacman3.png', './pacman4.png'],
];
let direction = 0;
const pacMen = []; // This array holds all the pacmen

// This function returns an object with random values
function setToRandom(scale) {
  return {
    x: Math.random() * scale,
    y: Math.random() * scale,
  };
}

// Factory to make a PacMan at a random position with random velocity
function makePac() {
  // returns an object with random values scaled {x: 33, y: 21}
  let velocity = setToRandom(10); // {x:?, y:?}
  let position = setToRandom(200);

  // Add image to div id = game
  let game = document.getElementById('game');
  let newimg = document.createElement('img');
  newimg.style.position = 'absolute';
  newimg.src = './pacman1.png';
  newimg.width = 100;

  // Set position here
  newimg.style.left = position.x + 'px';
  newimg.style.top = position.y + 'px';

  // Add new child image to game
  game.appendChild(newimg);

  // Return details in an object
  return {
    position,
    velocity,
    newimg,
  };
}

function update() {
  // Loop over pacmen array and move each one and move image in DOM
  pacMen.forEach((item) => {
    checkCollisions(item);
    item.position.x += item.velocity.x;
    item.position.y += item.velocity.y;

    // Check if PacMan hits the edge of the screen and change position to stay within the frame of the web page
    if (item.position.x + item.newimg.width > window.innerWidth || item.position.x < 0) {
      item.velocity.x = -item.velocity.x;
    }
    if (item.position.y + item.newimg.width > window.innerHeight || item.position.y < 0) {
      item.velocity.y = -item.velocity.y;
    }

    item.newimg.style.left = item.position.x + 'px';
    item.newimg.style.top = item.position.y + 'px';
  });
  setTimeout(update, 20);
}

function checkCollisions(item) {
  // TODO: detect collision with all walls and make PacMan bounce
}

function makeOne() {
  pacMen.push(makePac()); // Add a new PacMan
}

// Event listener for "Add PacMan" button
document.getElementById('add').addEventListener('click', makeOne);

// Event listener for "Start Game" button
document.getElementById('start').addEventListener('click', function () {
  update();
});

</script>

<body>
    <div id='game'>
        <button onclick='makeOne()' width='200' height='30'>Add PacMan</button>
        <button onclick='update()' width='200' height='30'>Start Game</button>

    </div>
</body>

</html>