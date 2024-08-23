// App.jsx
import React from 'react';
import './HomePage.css';
import Header from './components/Header';
import Hero from './components/Hero';
import About from './components/About';
import Teams from './components/Teams';
import Events from './components/Events';
import Footer from './components/Footer';
import Contact from './components/Contact';



function App() {
  return (
    
    <div className="App">
       <Header />
      <Hero />
      <About />
      <Teams />
      <Events />
      <Contact />
      <Footer />
    </div>
  );
}

export default App;
