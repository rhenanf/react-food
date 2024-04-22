<h1>Food Order App</h1>

<p>This project is a simple food order app built with React for the frontend and Express.js for the backend, developed as part of <a href="https://www.udemy.com/course/react-the-complete-guide-incl-redux/">Maximilian Schwarzmüller's React course</a> on Udemy. It allows users to browse a menu, add items to their cart, and submit their orders. The backend saves order data as a JSON file in a <code>data</code> folder.</p>

<h2>Features</h2>
<ul>
    <li>Browse a menu of food items.</li>
    <li>Add items to the cart.</li>
    <li>Submit orders.</li>
    <li>Backend saves orders as JSON file.</li>
</ul>

<h2>Installation</h2>
<ol>
    <li>Clone the repository:</li>
</ol>

<pre><code>git clone https://github.com/rhenanf/react-food.git</code></pre>

<ol start="2">
    <li>Install dependencies for both the frontend and backend:</li>
</ol>

<pre><code>cd react-food
npm install
cd backend
npm install
</code></pre>

  <ol start="3">
      <li>Run the backend server:</li>
  </ol>

  <pre><code>npm start</code></pre>

  <ol start="4">
      <li>Run the frontend development server:</li>
  </ol>

  <pre><code>cd ..
npm run dev
</code></pre>

<p>Visit <a href="http://localhost:5173">http://localhost:5173</a> in your browser to view the app.</p>

<h2>Usage</h2>
<ol>
    <li>Browse the menu on the homepage.</li>
    <li>Click on items to add them to your cart.</li>
    <li>Review your cart, adjust quantities if needed, and enter your details.</li>
    <li>Click "Submit Order" to submit your order.</li>
    <li>Your order will be saved and can be viewed in the JSON file.</li>
</ol>

<h2>Folder Structure</h2>
<ul>
    <li><code>backend</code>: Contains the Express.js backend code.
        <ul>
            <li><code>data</code>: Stores JSON files for orders.</li>
        </ul>
    </li>
    <li><code>src</code>: Contains the React frontend code.</li>
</ul>
