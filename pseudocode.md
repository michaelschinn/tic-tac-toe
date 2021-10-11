

# Game



## View
## Model
```
const boardState = 0,1,2;
const winConditionsArray =
[
    [[0,0],[1,0],[2,0]],
    [[0,1],[1,1],[2,1]],
    [[0,2],[1,2],[2,2]],
    [[0,0],[0,1],[0,2]],
    [[1,0],[1,1],[1,2]],
    [[2,0],[2,1],[2,2]],
    [[0,0],[1,1],[2,2]],
    [[2,0],[1,1],[0,2]]
];
```

## Controller
```
function setBoardState(boardState){
    switch(boardState){
        case 0:
            model.init
            view.build('initial')
            break;
        case 1:
            view.build('inPlay')
            break;
        case 2:
            

    }
}
```