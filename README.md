<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title> Puzzle Assignment</title>
  <style>
    body {
      font-family: Calibri;
      margin: 0;
      padding: 0;
      box-sizing: border-box;
    }
    .grid-container {
      display: grid;
      grid-template-rows: auto;
      grid-gap: 20px;
      padding: 0px;
    }
    .section {
      border: 1px solid #ccc;
      padding: 20px;
      max-width: 55%
    }
    .flex-container {
      display: flex;
      justify-content: space-between;
      align-items: center;
    }
    .puzzle {
      display: flex;
      flex-wrap: wrap;
      list-style: none;
      padding: 100;
      margin: 0;
    }
    .puzzle-item {
      width: calc(25% - 4px);
      margin: 2px;
    }
    .faulty-piece {
      display: none; 
    }
    img {
      max-width: 100%;
      height: auto;
    }
  </style>
</head>
<body>
  <div class="grid-container">
    <div class="section">
      <h2>Name: Demyd Venhlovskyi</h2>
      <h2>Puzzle: Snowmen</h2>
    </div>
    <div class="section">
      <h2> Puzzle Pieced Together</h2>
      <div class="flex-container">
        <ul class="puzzle">
          <li class="puzzle-item"><img src="puzzle-image/puzzle2_K.jpg" alt="Piece K"></li>
	  <li class="puzzle-item"><img src="puzzle-image/puzzle2_M.jpg" alt="Piece M"></li>
	  <li class="puzzle-item"><img src="puzzle-image/puzzle2_E.jpg" alt="Piece E"></li>
	  <li class="puzzle-item"><img src="puzzle-image/puzzle2_G.jpg" alt="Piece G"></li>          
	  <li class="puzzle-item"><img src="puzzle-image/puzzle2_A.jpg" alt="Piece A"></li>
	  <li class="puzzle-item"><img src="puzzle-image/puzzle2_D.jpg" alt="Piece D"></li>
	  <li class="puzzle-item"><img src="puzzle-image/puzzle2_L.jpg" alt="Piece L"></li>
	  <li class="puzzle-item"><img src="puzzle-image/puzzle2_B.jpg" alt="Piece B"></li>
	  <li class="puzzle-item"><img src="puzzle-image/puzzle2_F.jpg" alt="Piece F"></li>
	  <li class="puzzle-item"><img src="puzzle-image/puzzle2_J.jpg" alt="Piece J"></li>
	  <li class="puzzle-item"><img src="puzzle-image/puzzle2_H.jpg" alt="Piece H"></li>
	  <li class="puzzle-item"><img src="puzzle-image/puzzle2_I.jpg" alt="Piece I"></li>
    	  <li class="puzzle-item faulty-piece"><img src="puzzle-image/puzzle2_C.jpg" alt="Faulty Piece C"></li>
        </ul>
      </div>
    </div>
    <div class="section">
      <h2>Assignment Date: 12/6/2023 </h2>
    </div>
  </div>
</body>
</html>
