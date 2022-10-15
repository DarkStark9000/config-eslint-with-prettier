<html>
  <h1>Config files for future reuse and avoiding conflict</h1>
  
  <p><h3>What does this repo contain ? </h3>
  <h4>This repo has eslint and prettier files json config files to be used in projects made with Create-React-App.
  The Eslint config uses the base Airbnb style and then has some custom rules modifications.</h4></p>
  
  <p><h3>How to use these files ?</h3>
  <h4>
    Step 1: Create a React project folder using npx create-react-app or building it from scratch.
    <br></br> 
    Step 2: Copy the files <code>.eslintrc</code>, <code>.prettierrc</code> &
    <code>.gitignore</code> to your project root.
    <br></br>
    Step 3: Run the following commands one after the other:<br></br>
    <pre>npm i -D eslint prettier eslint-plugin-prettier eslint-config-prettier eslint-plugin-node eslint-config-node</pre>
    <pre>npx install-peerdeps --dev eslint-config-airbnb</pre>
  </h4></p>

  <p><h3>Are there any conflict ?</h3>
  <h4>
    The <code>.eslintrc</code> and <code>.prettierrc</code> files have been configured and tested to write React code using jsx syntax. There is reported no conflict.
  </h4></p>

  <p><h3>Are there any dependencies that need to be satisfied ?</h3>
  <h4>The <code>.eslintrc</code> have been configured so that it can be used with any verison of React.
  </h4></p>
</html>
