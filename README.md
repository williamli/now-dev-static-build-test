# Directory Listing Bug with static-build on `now dev`

1. When deployed code with `now` (https://now-dev-static-build-test-qhdcewbvk.now.sh) the directory listing 
shows a movie.json and a movie.html file. Both are accessible directly using their URL.

2. When `now dev` is run, only a `package.json` is shown in directory listing but **inaccessible** (http://localhost:3000/package.json).

3. It is still possible to navigate to movie.html and movie.json directly using links like http://localhost:3000/movie.html.
