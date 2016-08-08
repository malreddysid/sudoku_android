## Sudoku Solver - Android App

This repo contains an android implementation of the sudoku solver in [sudoku_DL](https://github.com/malreddysid/sudoku_DL).

## How to Setup
* Download the repo.
* Run the `push.sh` file in `proto_files/` to move the model and network files into the mobile.
* Install the app using Android Studio or using the apk found at `app/build/outputs/apk/app-debug.apk`.

## Screenshots

<!---
![1](/static/1.png "1") ![2](/static/2.png "2") ![3](/static/3.png "3")
-->

<br>
<center><div class="imgcap">
<div style="display:inline-block;">
    <img src="/static/1.png" width="150">
</div>
<div style="display:inline-block; margin-left: 20px;">
    <img src="/static/2.png" width="150">
</div>
<div style="display:inline-block; margin-left: 20px;">
    <img src="/static/3.png" width="150">
</div>
</div></center>
<br>

## Implementation

You can read more about the implementation in my blog [here](https://malreddysid.github.io/android/2016/08/02/sudoku-solver-android.html).

## TODO

* Improve the puzzle solving algorithm.
* Imporve the look of the app - Overlay the solution on top of the puzzle similar to Google Word Lens.
* Improve the grid extraction algorithm.