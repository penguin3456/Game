// Define game states and variables
let player = {
    health: 100,
    energy: 100,
    morale: 100,
    inventory: {
        food: 0,
        water: 0,
        wood: 0
    }
};

// Function to start the game
function startGame() {
    console.log("You wake up in a forest after a plane crash. You must survive and find a way to safety.");
    explore();
}

// Function for exploring different areas
function explore() {
    let choice = prompt("You are in the forest. What do you want to do?\n1. Gather resources\n2. Move to another area\n3. Rest and regain energy");

    switch (choice) {
        case "1":
            gatherResources();
            break;
        case "2":
            moveToAnotherArea();
            break;
        case "3":
            rest();
            break;
        default:
            console.log("Invalid choice.");
            explore();
            break;
    }
}

// Function to gather resources
function gatherResources() {
    let randomEvent = Math.random();
    if (randomEvent < 0.3) {
        console.log("You found some berries and collected wood.");
        player.inventory.food += 1;
        player.inventory.wood += 1;
    } else if (randomEvent < 0.6) {
        console.log("You found a stream and collected water.");
        player.inventory.water += 1;
    } else {
        console.log("You searched but found nothing.");
    }

    explore();
}

// Function to move to another area
function moveToAnotherArea() {
    console.log("You move to another area.");
    // Implement different area logic
    explore();
}

// Function to rest and regain energy
function rest() {
    console.log("You rest and regain some energy.");
    player.energy += 20;
    // Implement random events during rest
    explore();
}

// Start the game
startGame();
