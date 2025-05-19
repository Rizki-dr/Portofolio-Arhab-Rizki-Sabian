body {
  font-family: Arial, sans-serif;
  margin: 0;
  padding: 0;
  background-color: #f4f4f4;
  color: #333;
  transition: background-color 0.3s, color 0.3s;
}

.dark-mode {
  background-color: #1e1e1e;
  color: #f4f4f4;
}

header {
  padding: 2rem;
  text-align: center;
  background-color: #007acc;
  color: white;
}

header .toggle-container {
  position: absolute;
  top: 1rem;
  right: 1rem;
}

section {
  padding: 2rem;
}

h2 {
  border-bottom: 2px solid #007acc;
  padding-bottom: 0.5rem;
}

ul {
  list-style-type: square;
  margin-left: 1.5rem;
}

.experience-item {
  margin-bottom: 1.5rem;
}

footer {
  text-align: center;
  padding: 1rem;
  background-color: #333;
  color: white;
}

.switch {
  position: relative;
  display: inline-block;
  width: 40px;
  height: 20px;
}

.switch input {
  opacity: 0;
  width: 0;
  height: 0;
}

.slider {
  position: absolute;
  cursor: pointer;
  top: 0;
  left: 0;
  right: 0;
  bottom: 0;
  background-color: #ccc;
  transition: 0.4s;
  border-radius: 20px;
}

.slider:before {
  position: absolute;
  content: "";
  height: 14px;
  width: 14px;
  left: 3px;
  bottom: 3px;
  background-color: white;
  transition: 0.4s;
  border-radius: 50%;
}

input:checked + .slider {
  background-color: #007acc;
}

input:checked + .slider:before {
  transform: translateX(20px);
}

a {
  color: #007acc;
  text-decoration: none;
}

a:hover {
  text-decoration: underline;
}
