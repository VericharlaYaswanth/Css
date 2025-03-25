/* General Styles */
body {
  margin: 0;
  font-family: Arial, sans-serif;
}
.loading-screen {
  display: flex;
  flex-direction: column;
  justify-content: center;
  align-items: center;
  height: 100vh;
  background-color: #f0f0f0;
}
.logo {
  width: 150px;
  margin-bottom: 20px;
}
.loading-bar-container {
  width: 200px;
  height: 10px;
  background-color: #ddd;
  border-radius: 5px;
  overflow: hidden;
}
.loading-bar {
  width: 50%;
  height: 100%;
  background-color: #007bff;
  animation: loading 2s infinite;
}
@keyframes loading {
  0% { width: 0; }
  50% { width: 100%; }
  100% { width: 0; }
}
.login-container {
  display: flex;
  flex-direction: column;
  align-items: center;
  justify-content: center;
  height: 100vh;
  background-color: #f0f0f0;
}
.title {
  font-size: 2rem;
  margin-bottom: 10px;
}
.subtitle {
  font-size: 1.2rem;
  margin-bottom: 20px;
}
.input-box {
  width: 300px;
  padding: 10px;
  margin-bottom: 10px;
  border: 1px solid #ccc;
  border-radius: 5px;
}
.login-btn {
  width: 320px;
  padding: 10px;
  background-color: #007bff;
  color: white;
  border: none;
  border-radius: 5px;
  cursor: pointer;
}
.forgot-password {
  margin-top: 10px;
  color: #007bff;
  cursor: pointer;
}
.home-container {
  display: flex;
  flex-direction: column;
  min-height: 100vh;
}
.navbar {
  display: flex;
  justify-content: space-between;
  align-items: center;
  padding: 10px 20px;
  background-color: #007bff;
  color: white;
}
.nav-left {
  display: flex;
  align-items: center;
}
.menu-btn {
  background: none;
  border: none;
  color: white;
  font-size: 1.5rem;
  cursor: pointer;
}
.menu-dropdown {
  position: absolute;
  top: 50px;
  left: 20px;
  background-color: white;
  border: 1px solid #ccc;
  border-radius: 5px;
  padding: 10px;
  display: flex;
  flex-direction: column;
}
.menu-dropdown button {
  background: none;
  border: none;
  padding: 5px 10px;
  cursor: pointer;
}
.nav-logo {
  width: 100px;
  margin-left: 20px;
}
.nav-right {
  display: flex;
  align-items: center;
}
.user-info {
  margin-right: 20px;
}
.nav-btn {
  background: none;
  border: none;
  color: white;
  margin-right: 20px;
  cursor: pointer;
}
.cart-btn {
  background: none;
  border: none;
  color: white;
  font-size: 1.5rem;
  cursor: pointer;
}
/* Cart Styles */
.cart-container {
  position: fixed;
  top: 70px;
  right: 20px;
  width: 400px;
  max-height: 80vh;
  overflow-y: auto;
  background-color: white;
  border: 1px solid #ccc;
  border-radius: 10px;
  padding: 20px;
  z-index: 1000;
  box-shadow: 0 4px 8px rgba(0, 0, 0, 0.1);
}
.cart-items {
  display: flex;
  flex-direction: column;
  gap: 15px;
}
.cart-item {
  display: flex;
  justify-content: space-between;
  align-items: center;
  padding: 10px;
  border: 1px solid #eee;
  border-radius: 5px;
}
.cart-item-details {
  flex: 1;
}
.cart-item-details h3 {
  margin: 0 0 5px 0;
}
.cart-item-details p {
  margin: 5px 0;
}
.remove-btn {
  background-color: #ff4545;
  color: white;
  border: none;
  border-radius: 5px;
  padding: 5px 10px;
  cursor: pointer;
}
.cart-total {
  margin-top: 20px;
  padding-top: 10px;
  border-top: 1px solid #ccc;
  display: flex;
  flex-direction: column;
  align-items: flex-end;
}
.checkout-btn {
  background-color: #007bff;
  color: white;
  border: none;
  border-radius: 5px;
  padding: 10px 20px;
  margin-top: 10px;
  cursor: pointer;
}
.close-cart-btn {
  background-color: #eee;
  border: none;
  border-radius: 5px;
  padding: 5px 10px;
  margin-top: 15px;
  cursor: pointer;
  width: 100%;
}
.slideshow-container {
  position: relative;
  width: 100%;
  height: 400px;
  overflow: hidden;
}
.slideshow-img {
  width: 100%;
  height: 100%;
  object-fit: cover;
}
.welcome-text {
  position: absolute;
  top: 50%;
  left: 50%;
  transform: translate(-50%, -50%);
  color: white;
  font-size: 3rem;
  text-shadow: 2px 2px 4px rgba(0, 0, 0, 0.5);
}
.services-section {
  padding: 20px;
  text-align: center;
}
.service-grid {
  display: grid;
  grid-template-columns: repeat(3, 1fr);
  gap: 20px;
  margin-top: 20px;
}
.service-card {
  background: none;
  border: 1px solid #ccc;
  border-radius: 10px;
  padding: 20px;
  cursor: pointer;
  transition: transform 0.2s;
}
.service-card:hover {
  transform: scale(1.05);
}
.service-img {
  width: 100%;
  height: 150px;
  object-fit: cover;
  border-radius: 10px;
}
.service-name {
  margin-top: 10px;
  font-size: 1.2rem;
}
.clients-section {
  padding: 20px;
  text-align: center;
  background-color: #f0f0f0;
}
.wedding-options {
  padding: 20px;
  text-align: center;
}
.wedding-grid {
  display: grid;
  grid-template-columns: repeat(2, 1fr);
  gap: 20px;
  margin-top: 20px;
}
.wedding-option-card {
  background: none;
  border: 1px solid #ccc;
  border-radius: 10px;
  padding: 20px;
  cursor: pointer;
  transition: transform 0.2s;
}
.wedding-option-card:hover {
  transform: scale(1.05);
}
.wedding-option-img {
  width: 100%;
  height: 150px;
  object-fit: cover;
  border-radius: 10px;
}
.wedding-option-name {
  margin-top: 10px;
  font-size: 1.2rem;
}
.wedding-management-options {
  padding: 20px;
  text-align: center;
}
.management-grid {
  display: grid;
  grid-template-columns: repeat(2, 1fr);
  gap: 20px;
  margin-top: 20px;
}
.management-option {
  background: none;
  border: 1px solid #ccc;
  border-radius: 10px;
  padding: 20px;
  cursor: pointer;
  transition: transform 0.2s;
}
.management-option:hover {
  transform: scale(1.05);
}
.decoration-options {
  padding: 20px;
  text-align: center;
}
.decoration-grid {
  display: grid;
  grid-template-columns: repeat(4, 1fr);
  gap: 20px;
  margin-top: 20px;
}
.decoration-card {
  background: none;
  border: 1px solid #ccc;
  border-radius: 10px;
  padding: 20px;
  cursor: pointer;
  transition: transform 0.2s;
}
.decoration-card:hover {
  transform: scale(1.05);
}
.decoration-img {
  width: 100%;
  height: 150px;
  object-fit: cover;
  border-radius: 10px;
}
.decoration-name {
  margin-top: 10px;
  font-size: 1.2rem;
}
.decoration-price {
  margin-top: 5px;
  font-size: 1rem;
  color: #007bff;
}
/* Seating Capacity Section */
.seating-capacity-section {
  padding: 20px;
  text-align: center;
  margin-top: 20px;
  background-color: #f9f9f9;
  border-radius: 10px;
  max-width: 600px;
  margin-left: auto;
  margin-right: auto;
}
.seating-input {
  width: 200px;
  padding: 10px;
  margin: 20px 0;
  border: 1px solid #ccc;
  border-radius: 5px;
  font-size: 1rem;
  text-align: center;
}
.price-breakdown {
  margin: 15px 0;
  font-size: 1rem;
  text-align: left;
  padding: 10px;
  background-color: #f0f0f0;
  border-radius: 5px;
  display: inline-block;
}
.add-to-cart-btn {
  background-color: #007bff;
  color: white;
  border: none;
  border-radius: 5px;
  padding: 10px 20px;
  font-size: 1rem;
  cursor: pointer;
  margin-top: 15px;
  transition: background-color 0.2s;
}

.add-to-cart-btn:hover {
  background-color: #0056b3;
}

/* Event Details Form Styles */
.event-details-section {
  padding: 20px;
  text-align: center;
  margin-top: 20px;
  background-color: #f9f9f9;
  border-radius: 10px;
  max-width: 600px;
  margin-left: auto;
  margin-right: auto;
  margin-bottom: 40px;
}

.event-details-form {
  display: flex;
  flex-direction: column;
  gap: 15px;
  margin-top: 20px;
}

.form-group {
  display: flex;
  flex-direction: column;
  align-items: flex-start;
  text-align: left;
}

.form-group label {
  font-weight: bold;
  margin-bottom: 5px;
}

.event-input {
  width: 100%;
  padding: 10px;
  border: 1px solid #ccc;
  border-radius: 5px;
  font-size: 1rem;
}

.time-group {
  width: 100%;
}

.time-inputs {
  display: flex;
  gap: 10px;
  width: 100%;
}

.time-input {
  flex: 3;
  padding: 10px;
  border: 1px solid #ccc;
  border-radius: 5px;
  font-size: 1rem;
}

.ampm-select {
  flex: 1;
  padding: 10px;
  border: 1px solid #ccc;
  border-radius: 5px;
  font-size: 1rem;
}

.event-summary {
  margin-top: 20px;
  padding: 15px;
  background-color: #f0f0f0;
  border-radius: 10px;
  text-align: left;
}

.event-summary h3 {
  margin-top: 0;
  color: #007bff;
}

.event-summary p {
  margin: 5px 0;
}

.footer {
  padding: 20px;
  text-align: center;
  background-color: #007bff;
  color: white;
  margin-top: auto;
}

/* New Styles for Photographer and Priest Features */

/* Photographer Section Styles */
.photographer-section {
  padding: 20px;
  text-align: center;
  margin-top: 20px;
  background-color: #f9f9f9;
  border-radius: 10px;
  max-width: 600px;
  margin-left: auto;
  margin-right: auto;
}

.photographer-grid {
  display: grid;
  grid-template-columns: repeat(3, 1fr);
  gap: 15px;
  margin-top: 15px;
}

.photographer-card {
  background: none;
  border: 1px solid #ccc;
  border-radius: 10px;
  padding: 15px;
  cursor: pointer;
  transition: all 0.2s;
}

.photographer-card:hover {
  transform: scale(1.03);
}

.photographer-card.selected {
  border: 2px solid #007bff;
  background-color: #f0f8ff;
}

.photographer-img {
  width: 100%;
  height: 100px;
  object-fit: cover;
  border-radius: 5px;
}

.photographer-name {
  margin: 10px 0 5px 0;
  font-size: 1rem;
}

.photographer-price {
  margin: 0;
  font-size: 0.9rem;
  color: #007bff;
  font-weight: bold;
}

/* Priest Section Styles */
.priest-section {
  padding: 20px;
  text-align: center;
  margin-top: 20px;
  background-color: #f9f9f9;
  border-radius: 10px;
  max-width: 600px;
  margin-left: auto;
  margin-right: auto;
}

.priest-options {
  display: flex;
  justify-content: center;
  gap: 15px;
  margin-top: 15px;
}

.priest-option {
  padding: 10px 15px;
  border: 1px solid #ccc;
  border-radius: 5px;
  background-color: white;
  cursor: pointer;
  transition: all 0.2s;
}

.priest-option:hover {
  background-color: #f0f0f0;
}

.priest-option.selected {
  border: 2px solid #007bff;
  background-color: #f0f8ff;
}

/* Additional Options Container */
.additional-options-section {
  padding: 20px;
  text-align: center;
}

/* Price Summary Styles */
.price-summary {
  margin-top: 20px;
  padding: 15px;
  background-color: #f0f0f0;
  border-radius: 10px;
  text-align: left;
  max-width: 600px;
  margin-left: auto;
  margin-right: auto;
}

.price-summary h3 {
  margin-top: 0;
  color: #007bff;
}

.price-summary p {
  margin: 5px 0;
}

/* Fully Managed Options Styles */
.fully-managed-options {
  padding: 20px;
  text-align: center;
  margin-top: 20px;
  background-color: #f9f9f9;
  border-radius: 10px;
  max-width: 600px;
  margin-left: auto;
  margin-right: auto;
}

/* Media Queries */
@media (max-width: 768px) {
  .service-grid {
    grid-template-columns: repeat(2, 1fr);
  }
  
  .decoration-grid {
    grid-template-columns: repeat(2, 1fr);
  }
  
  .photographer-grid {
    grid-template-columns: repeat(2, 1fr);
  }
  
  .cart-container {
    width: 90%;
    right: 5%;
  }
  
  .event-details-section {
    width: 90%;
  }
}

@media (max-width: 480px) {
  .service-grid {
    grid-template-columns: 1fr;
  }
  
  .wedding-grid {
    grid-template-columns: 1fr;
  }
  
  .management-grid {
    grid-template-columns: 1fr;
  }
  
  .decoration-grid {
    grid-template-columns: 1fr;
  }

  .photographer-grid {
    grid-template-columns: 1fr;
  }

  .time-inputs {
    flex-direction: column;
  }

  .priest-options {
    flex-direction: column;
    align-items: center;
  }
}
