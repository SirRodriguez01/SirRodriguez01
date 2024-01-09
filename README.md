obstacle = [Cactus2, Cactus1];

distance_of_obstacle = 2;


function onGreenPlayButtonClicked() {

    Hatch.setBackgroundSound('tetris theme');


    function forever() {

        dinoMoveForward();

    };

    forever();

}


Hatch.onKeyDown(function(event) {

    if (event.code === 'Space') {

        Player.jump();

        Hatch.playSound('Jump sound');

    }

});
