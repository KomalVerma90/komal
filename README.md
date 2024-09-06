// import { useState } from 'react';
// import { hello_backend } from 'declarations/hello_backend';

// function App() {
//   const [greeting, setGreeting] = useState('');

//   function handleSubmit(event) {
//     event.preventDefault();
//     const name = event.target.elements.name.value;
//     hello_backend.greet(name).then((greeting) => {
//       setGreeting(greeting);
//     });
//     return false;
//   }

//   return (
//     <main>
//       <img src="/logo2.svg" alt="DFINITY logo" />
//       <br />
//       <br />
//       <form action="#" onSubmit={handleSubmit}>
//         <label htmlFor="name">Enter your name: &nbsp;</label>
//         <input id="name" alt="Name" type="text" />
//         <button type="submit">Click Me!</button>
//       </form>
//       <section id="greeting">{greeting}</section>
//     </main>
//   );
// }

// export default App;

// src/LandingPage.js
import React from 'react';
// import './LandingPage.css'; // Import a CSS file for styling

const LandingPage = () => {
  return (
    <div className="landing-page">
      <header className="header">
        <h1>Welcome to Our Landing Page</h1>
        <p>Your one-stop solution for amazing services</p>
        <button className="cta-button">Get Started</button>
      </header>
      <section className="features">
        <div className="feature">
          <h2>Feature 1</h2>
          <p>Description of feature 1.</p>
        </div>
        <div className="feature">
          <h2>Feature 2</h2>
          <p>Description of feature 2.</p>
        </div>
        <div className="feature">
          <h2>Feature 3</h2>
          <p>Description of feature 3.</p>
        </div>
      </section>
      <footer className="footer">
        <p>&copy; 2024 Your Company</p>
      </footer>
    </div>
  );
};

export default LandingPage;
