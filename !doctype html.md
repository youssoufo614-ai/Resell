<!doctype html>  
  
<html lang="fr">  
<head>  
  <meta charset="utf-8" />  
  <meta name="viewport" content="width=device-width,initial-scale=1" />  
  <title>Resell — Plateforme de revente moderne</title>  
  <style>  
    /* Resell - Styles modernes et responsive */  
    * {  
      margin: 0;  
      padding: 0;  
      box-sizing: border-box;  
    }  
  
```  
body {  
  font-family: -apple-system, BlinkMacSystemFont, 'Segoe UI', Roboto, Oxygen, Ubuntu, Cantarell, sans-serif;  
  background: #fff;  
  color: #1a1a1a;  
  line-height: 1.6;  
}  
  
/* Header */  
.header {  
  background: #fff;  
  border-bottom: 1px solid #e5e5e5;  
  position: sticky;  
  top: 0;  
  z-index: 100;  
  box-shadow: 0 1px 3px rgba(0,0,0,0.05);  
}  
  
.header-content {  
  max-width: 1200px;  
  margin: 0 auto;  
  padding: 1rem 1.5rem;  
  display: flex;  
  align-items: center;  
  justify-content: space-between;  
  gap: 2rem;  
}  
  
.logo-section {  
  display: flex;  
  align-items: center;  
  gap: 1rem;  
}  
  
.logo {  
  width: 48px;  
  height: 48px;  
  background: #1a1a1a;  
  border-radius: 12px;  
  display: flex;  
  align-items: center;  
  justify-content: center;  
  flex-shrink: 0;  
}  
  
.logo svg {  
  width: 28px;  
  height: 28px;  
}  
  
.brand-info h1 {  
  font-size: 1.5rem;  
  font-weight: 700;  
  color: #1a1a1a;  
  margin-bottom: 0.125rem;  
}  
  
.brand-info p {  
  font-size: 0.875rem;  
  color: #666;  
}  
  
.header-actions {  
  display: flex;  
  gap: 0.75rem;  
}  
  
/* Buttons */  
.btn {  
  padding: 0.625rem 1.25rem;  
  border: none;  
  border-radius: 8px;  
  font-size: 0.9375rem;  
  font-weight: 600;  
  cursor: pointer;  
  transition: all 0.2s ease;  
  display: inline-flex;  
  align-items: center;  
  justify-content: center;  
  gap: 0.5rem;  
  white-space: nowrap;  
}  
  
.btn-secondary {  
  background: #fff;  
  color: #1a1a1a;  
  border: 1px solid #e5e5e5;  
}  
  
.btn-secondary:hover {  
  background: #f5f5f5;  
  border-color: #d5d5d5;  
}  
  
.btn-primary {  
  background: #1a1a1a;  
  color: #fff;  
}  
  
.btn-primary:hover {  
  background: #333;  
  transform: translateY(-1px);  
  box-shadow: 0 4px 8px rgba(0,0,0,0.15);  
}  
  
.btn:active {  
  transform: translateY(0);  
}  
  
/* Container */  
.container {  
  max-width: 1200px;  
  margin: 0 auto;  
  padding: 3rem 1.5rem;  
  min-height: calc(100vh - 200px);  
}  
  
/* Empty State */  
.empty-state {  
  text-align: center;  
  padding: 4rem 2rem;  
}  
  
.empty-icon {  
  width: 120px;  
  height: 120px;  
  margin: 0 auto 2rem;  
  background: #f5f5f5;  
  border-radius: 50%;  
  display: flex;  
  align-items: center;  
  justify-content: center;  
}  
  
.empty-icon svg {  
  width: 60px;  
  height: 60px;  
  color: #999;  
  stroke: #999;  
}  
  
.empty-state h2 {  
  font-size: 1.75rem;  
  margin-bottom: 1rem;  
  color: #1a1a1a;  
  font-weight: 700;  
}  
  
.empty-state p {  
  font-size: 1.125rem;  
  color: #666;  
  margin-bottom: 2rem;  
  max-width: 500px;  
  margin-left: auto;  
  margin-right: auto;  
}  
  
/* Products Grid */  
.products-grid {  
  display: grid;  
  grid-template-columns: repeat(auto-fill, minmax(280px, 1fr));  
  gap: 1.5rem;  
  margin-top: 2rem;  
}  
  
.products-grid.hidden {  
  display: none;  
}  
  
.product-card {  
  background: #fff;  
  border: 1px solid #e5e5e5;  
  border-radius: 12px;  
  overflow: hidden;  
  transition: all 0.2s ease;  
  cursor: pointer;  
}  
  
.product-card:hover {  
  box-shadow: 0 8px 16px rgba(0,0,0,0.1);  
  transform: translateY(-4px);  
  border-color: #d5d5d5;  
}  
  
.product-image {  
  width: 100%;  
  height: 220px;  
  background: #f5f5f5;  
  display: flex;  
  align-items: center;  
  justify-content: center;  
  color: #999;  
  font-size: 0.875rem;  
  overflow: hidden;  
  position: relative;  
}  
  
.product-image img {  
  width: 100%;  
  height: 100%;  
  object-fit: cover;  
}  
  
.product-info {  
  padding: 1.25rem;  
}  
  
.product-info h3 {  
  font-size: 1.125rem;  
  margin-bottom: 0.5rem;  
  color: #1a1a1a;  
  font-weight: 600;  
}  
  
.product-info p {  
  font-size: 0.9375rem;  
  color: #666;  
  margin-bottom: 0.75rem;  
  line-height: 1.5;  
}  
  
.product-price {  
  font-size: 1.25rem;  
  font-weight: 700;  
  color: #1a1a1a;  
  margin-bottom: 1rem;  
}  
  
.product-badge {  
  display: inline-block;  
  padding: 0.25rem 0.75rem;  
  background: #f0f0f0;  
  border-radius: 6px;  
  font-size: 0.75rem;  
  font-weight: 600;  
  color: #666;  
  margin-bottom: 0.75rem;  
  text-transform: uppercase;  
}  
  
/* Modal */  
.modal {  
  position: fixed;  
  inset: 0;  
  background: rgba(0,0,0,0.5);  
  display: flex;  
  align-items: center;  
  justify-content: center;  
  z-index: 1000;  
  padding: 1rem;  
  animation: fadeIn 0.2s ease;  
}  
  
.modal.hidden {  
  display: none;  
}  
  
@keyframes fadeIn {  
  from { opacity: 0; }  
  to { opacity: 1; }  
}  
  
.modal-content {  
  background: #fff;  
  border-radius: 16px;  
  max-width: 600px;  
  width: 100%;  
  max-height: 90vh;  
  overflow-y: auto;  
  position: relative;  
  animation: slideUp 0.3s ease;  
}  
  
@keyframes slideUp {  
  from {  
    opacity: 0;  
    transform: translateY(20px);  
  }  
  to {  
    opacity: 1;  
    transform: translateY(0);  
  }  
}  
  
.modal-header {  
  padding: 1.5rem;  
  border-bottom: 1px solid #e5e5e5;  
  display: flex;  
  justify-content: space-between;  
  align-items: center;  
  position: sticky;  
  top: 0;  
  background: #fff;  
  z-index: 10;  
}  
  
.modal-header h2 {  
  font-size: 1.5rem;  
  font-weight: 700;  
  color: #1a1a1a;  
}  
  
.close-btn {  
  width: 32px;  
  height: 32px;  
  border: none;  
  background: #f5f5f5;  
  border-radius: 8px;  
  cursor: pointer;  
  font-size: 1.25rem;  
  display: flex;  
  align-items: center;  
  justify-content: center;  
  color: #666;  
  transition: all 0.2s ease;  
}  
  
.close-btn:hover {  
  background: #e5e5e5;  
  color: #1a1a1a;  
}  
  
.modal-body {  
  padding: 1.5rem;  
}  
  
.product-limit {  
  text-align: center;  
  color: #666;  
  font-size: 0.875rem;  
  margin-bottom: 1.5rem;  
  padding: 0.75rem;  
  background: #f5f5f5;  
  border-radius: 8px;  
}  
  
/* Form */  
.form-group {  
  margin-bottom: 1.5rem;  
}  
  
.form-group label {  
  display: block;  
  font-weight: 600;  
  margin-bottom: 0.5rem;  
  color: #1a1a1a;  
  font-size: 0.9375rem;  
}  
  
.form-group input,  
.form-group textarea,  
.form-select {  
  width: 100%;  
  padding: 0.75rem;  
  border: 1px solid #e5e5e5;  
  border-radius: 8px;  
  font-size: 1rem;  
  font-family: inherit;  
  transition: all 0.2s ease;  
}  
  
.form-group input:focus,  
.form-group textarea:focus,  
.form-select:focus {  
  outline: none;  
  border-color: #1a1a1a;  
  box-shadow: 0 0 0 3px rgba(26,26,26,0.1);  
}  
  
.form-group textarea {  
  min-height: 120px;  
  resize: vertical;  
}  
  
.form-group input::placeholder,  
.form-group textarea::placeholder {  
  color: #999;  
}  
  
.upload-btn {  
  width: 100%;  
  padding: 1rem;  
  border: 2px dashed #e5e5e5;  
  border-radius: 8px;  
  background: #fafafa;  
  cursor: pointer;  
  display: flex;  
  align-items: center;  
  justify-content: center;  
  gap: 0.5rem;  
  color: #666;  
  font-weight: 600;  
  transition: all 0.2s ease;  
}  
  
.upload-btn:hover {  
  border-color: #1a1a1a;  
  background: #f5f5f5;  
  color: #1a1a1a;  
}  
  
.image-preview {  
  margin-top: 1rem;  
  border-radius: 8px;  
  overflow: hidden;  
  border: 1px solid #e5e5e5;  
}  
  
.image-preview img {  
  width: 100%;  
  height: auto;  
  display: block;  
}  
  
.image-preview.hidden {  
  display: none;  
}  
  
.modal-footer {  
  padding: 1.5rem;  
  border-top: 1px solid #e5e5e5;  
  display: flex;  
  gap: 1rem;  
  position: sticky;  
  bottom: 0;  
  background: #fff;  
}  
  
.modal-footer .btn {  
  flex: 1;  
  padding: 0.875rem;  
}  
  
/* Product Detail Styles */  
.detail-image {  
  width: 100%;  
  height: 300px;  
  background: #f5f5f5;  
  border-radius: 8px;  
  margin-bottom: 1.5rem;  
  display: flex;  
  align-items: center;  
  justify-content: center;  
  overflow: hidden;  
}  
  
.detail-image img {  
  width: 100%;  
  height: 100%;  
  object-fit: cover;  
}  
  
.detail-section {  
  margin-bottom: 1.5rem;  
}  
  
.detail-section h3 {  
  font-size: 1.125rem;  
  font-weight: 600;  
  margin-bottom: 0.5rem;  
  color: #1a1a1a;  
}  
  
.detail-section p {  
  color: #666;  
  line-height: 1.6;  
}  
  
.detail-price {  
  font-size: 1.75rem;  
  font-weight: 700;  
  color: #1a1a1a;  
  margin: 1rem 0;  
}  
  
.detail-info-grid {  
  display: grid;  
  grid-template-columns: repeat(2, 1fr);  
  gap: 1rem;  
  margin-top: 1rem;  
}  
  
.detail-info-item {  
  padding: 0.75rem;  
  background: #f5f5f5;  
  border-radius: 8px;  
}  
  
.detail-info-item strong {  
  display: block;  
  font-size: 0.8125rem;  
  color: #666;  
  margin-bottom: 0.25rem;  
  text-transform: uppercase;  
  font-weight: 600;  
}  
  
.detail-info-item span {  
  font-size: 1rem;  
  color: #1a1a1a;  
}  
  
/* Footer */  
.site-footer {  
  background: #f5f5f5;  
  padding: 2rem 1.5rem;  
  text-align: center;  
  border-top: 1px solid #e5e5e5;  
  margin-top: 4rem;  
}  
  
.site-footer p {  
  color: #666;  
  font-size: 0.875rem;  
}  
  
/* Animations */  
@keyframes slideIn {  
  from {  
    transform: translateX(400px);  
    opacity: 0;  
  }  
  to {  
    transform: translateX(0);  
    opacity: 1;  
  }  
}  
  
@keyframes slideOut {  
  from {  
    transform: translateX(0);  
    opacity: 1;  
  }  
  to {  
    transform: translateX(400px);  
    opacity: 0;  
  }  
}  
  
/* Responsive */  
@media (max-width: 768px) {  
  .header-content {  
    flex-direction: column;  
    gap: 1rem;  
    padding: 1rem;  
  }  
  
  .brand-info p {  
    display: none;  
  }  
  
  .header-actions {  
    width: 100%;  
  }  
  
  .header-actions .btn {  
    flex: 1;  
  }  
  
  .container {  
    padding: 2rem 1rem;  
  }  
  
  .products-grid {  
    grid-template-columns: repeat(auto-fill, minmax(240px, 1fr));  
    gap: 1rem;  
  }  
  
  .modal-content {  
    margin: 0;  
    border-radius: 16px 16px 0 0;  
    max-height: 95vh;  
  }  
  
  .empty-state {  
    padding: 2rem 1rem;  
  }  
  
  .empty-state h2 {  
    font-size: 1.5rem;  
  }  
  
  .empty-state p {  
    font-size: 1rem;  
  }  
  
  .empty-icon {  
    width: 100px;  
    height: 100px;  
  }  
  
  .empty-icon svg {  
    width: 50px;  
    height: 50px;  
  }  
  
  .detail-info-grid {  
    grid-template-columns: 1fr;  
  }  
}  
  
@media (max-width: 480px) {  
  .btn {  
    padding: 0.5rem 1rem;  
    font-size: 0.875rem;  
  }  
  
  .logo {  
    width: 40px;  
    height: 40px;  
  }  
  
  .logo svg {  
    width: 24px;  
    height: 24px;  
  }  
  
  .brand-info h1 {  
    font-size: 1.25rem;  
  }  
  
  .modal-header h2 {  
    font-size: 1.25rem;  
  }  
  
  .products-grid {  
    grid-template-columns: 1fr;  
  }  
}  
  
/* Utility Classes */  
.hidden {  
  display: none !important;  
}  
```  
  
  </style>  
</head>  
<body>  
  <header class="header">  
    <div class="header-content">  
      <div class="logo-section">  
        <div class="logo">  
          <svg viewBox="0 0 24 24" fill="none" xmlns="http://www.w3.org/2000/svg">  
            <path d="M3 9L12 2L21 9V20C21 20.5304 20.7893 21.0391 20.4142 21.4142C20.0391 21.7893 19.5304 22 19 22H5C4.46957 22 3.96086 21.7893 3.58579 21.4142C3.21071 21.0391 3 20.5304 3 20V9Z" stroke="white" stroke-width="2" stroke-linecap="round" stroke-linejoin="round"/>  
          </svg>  
        </div>  
        <div class="brand-info">  
          <h1>Resell</h1>  
          <p>Plateforme de revente moderne</p>  
        </div>  
      </div>  
      <div class="header-actions">  
        <button class="btn btn-secondary" id="addProductBtn">  
          <svg width="20" height="20" viewBox="0 0 24 24" fill="none" xmlns="http://www.w3.org/2000/svg">  
            <path d="M12 5V19M5 12H19" stroke="currentColor" stroke-width="2" stroke-linecap="round" stroke-linejoin="round"/>  
          </svg>  
          Ajouter  
        </button>  
        <button class="btn btn-primary" id="subscribeBtn">  
          <svg width="20" height="20" viewBox="0 0 24 24" fill="none" xmlns="http://www.w3.org/2000/svg">  
            <path d="M12 2L15.09 8.26L22 9.27L17 14.14L18.18 21.02L12 17.77L5.82 21.02L7 14.14L2 9.27L8.91 8.26L12 2Z" stroke="currentColor" stroke-width="2" stroke-linecap="round" stroke-linejoin="round"/>  
          </svg>  
          S'abonner  
        </button>  
      </div>  
    </div>  
  </header>  
  
  <main class="container">  
    <!-- Empty State -->  
    <div id="emptyState" class="empty-state">  
      <div class="empty-icon">  
        <svg viewBox="0 0 24 24" fill="none" xmlns="http://www.w3.org/2000/svg">  
          <path d="M21 16V8C20.9996 7.64927 20.9071 7.30481 20.7315 7.00116C20.556 6.69751 20.3037 6.44536 20 6.27L13 2.27C12.696 2.09446 12.3511 2.00205 12 2.00205C11.6489 2.00205 11.304 2.09446 11 2.27L4 6.27C3.69626 6.44536 3.44398 6.69751 3.26846 7.00116C3.09294 7.30481 3.00036 7.64927 3 8V16C3.00036 16.3507 3.09294 16.6952 3.26846 16.9988C3.44398 17.3025 3.69626 17.5546 4 17.73L11 21.73C11.304 21.9055 11.6489 21.9979 12 21.9979C12.3511 21.9979 12.696 21.9055 13 21.73L20 17.73C20.3037 17.5546 20.556 17.3025 20.7315 16.9988C20.9071 16.6952 20.9996 16.3507 21 16Z" stroke="currentColor" stroke-width="2" stroke-linecap="round" stroke-linejoin="round"/>  
        </svg>  
      </div>  
      <h2>Aucun produit pour le moment</h2>  
      <p>Commencez à vendre en ajoutant votre premier produit. C'est rapide et facile !</p>  
      <button class="btn btn-primary" id="addFirstProductBtn">Ajouter votre premier produit</button>  
    </div>  
  
```  
<!-- Products Grid -->  
<div id="productsGrid" class="products-grid hidden"></div>  
```  
  
  </main>  
  
  <!-- Add Product Modal -->  
  
  <div id="addProductModal" class="modal hidden">  
    <div class="modal-content">  
      <div class="modal-header">  
        <h2>Ajouter un nouveau produit</h2>  
        <button class="close-btn" id="closeModalBtn">✕</button>  
      </div>  
      <div class="modal-body">  
        <div class="product-limit">Remplissez les détails pour publier votre produit. (<span id="productCount">0</span>/5 produits utilisés)</div>  
  
```  
    <form id="productForm">  
      <div class="form-group">  
        <label>Nom du produit *</label>  
        <input type="text" id="productName" placeholder="ex: iPhone 13 Pro" required>  
      </div>  
  
      <div class="form-group">  
        <label>Description *</label>  
        <textarea id="productDesc" placeholder="Décrivez votre produit..." required></textarea>  
      </div>  
  
      <div class="form-group">  
        <label>Prix (XAF) *</label>  
        <input type="number" id="productPrice" placeholder="ex: 250000" required>  
      </div>  
  
      <div class="form-group">  
        <label>Numéro de téléphone *</label>  
        <input type="tel" id="productPhone" placeholder="+225 07 00 00 00 00" required>  
      </div>  
  
      <div class="form-group">  
        <label>Ville *</label>  
        <input type="text" id="productCity" placeholder="ex: Abidjan" required>  
      </div>  
  
      <div class="form-group">  
        <label>Catégorie *</label>  
        <select id="productCategory" class="form-select" required>  
          <option value="electronics">Électronique</option>  
          <option value="fashion">Mode</option>  
          <option value="home">Maison</option>  
        </select>  
      </div>  
  
      <div class="form-group">  
        <label>Image du produit *</label>  
        <input type="file" id="productImage" accept="image/*" style="display:none">  
        <button type="button" class="upload-btn" id="uploadBtn">  
          <svg width="20" height="20" viewBox="0 0 24 24" fill="none" xmlns="http://www.w3.org/2000/svg">  
            <path d="M21 15V19C21 19.5304 20.7893 20.0391 20.4142 20.4142C20.0391 20.7893 19.5304 21 19 21H5C4.46957 21 3.96086 20.7893 3.58579 20.4142C3.21071 20.0391 3 19.5304 3 19V15M17 8L12 3M12 3L7 8M12 3V15" stroke="currentColor" stroke-width="2" stroke-linecap="round" stroke-linejoin="round"/>  
          </svg>  
          <span id="uploadText">Télécharger une image</span>  
        </button>  
        <div id="imagePreview" class="image-preview hidden"></div>  
      </div>  
    </form>  
  </div>  
  <div class="modal-footer">  
    <button class="btn btn-secondary" id="cancelBtn">Annuler</button>  
    <button class="btn btn-primary" id="submitProductBtn">Ajouter le produit</button>  
  </div>  
</div>  
```  
  
  </div>  
  
  <!-- Product Detail Modal -->  
  
  <div id="productDetailModal" class="modal hidden">  
    <div class="modal-content">  
      <div class="modal-header">  
        <h2 id="detailTitle">Détails du produit</h2>  
        <button class="close-btn" id="closeDetailBtn">✕</button>  
      </div>  
      <div class="modal-body" id="detailBody">  
      </div>  
      <div class="modal-footer">  
        <button class="btn btn-secondary" id="closeDetailFooterBtn">Fermer</button>  
        <button class="btn btn-primary" id="contactSellerBtn">Contacter le vendeur</button>  
      </div>  
    </div>  
  </div>  
  
  <footer class="site-footer">  
    <p>© 2024 Resell — Plateforme de revente moderne</p>  
  </footer>  
  
  <script>  
    // Resell - Application JavaScript  
    let products = [];  
    let selectedImage = null;  
  
    // DOM Elements  
    const addProductBtn = document.getElementById('addProductBtn');  
    const addFirstProductBtn = document.getElementById('addFirstProductBtn');  
    const subscribeBtn = document.getElementById('subscribeBtn');  
    const addProductModal = document.getElementById('addProductModal');  
    const productDetailModal = document.getElementById('productDetailModal');  
    const closeModalBtn = document.getElementById('closeModalBtn');  
    const closeDetailBtn = document.getElementById('closeDetailBtn');  
    const closeDetailFooterBtn = document.getElementById('closeDetailFooterBtn');  
    const cancelBtn = document.getElementById('cancelBtn');  
    const submitProductBtn = document.getElementById('submitProductBtn');  
    const contactSellerBtn = document.getElementById('contactSellerBtn');  
    const emptyState = document.getElementById('emptyState');  
    const productsGrid = document.getElementById('productsGrid');  
    const productForm = document.getElementById('productForm');  
    const uploadBtn = document.getElementById('uploadBtn');  
    const productImage = document.getElementById('productImage');  
    const imagePreview = document.getElementById('imagePreview');  
    const uploadText = document.getElementById('uploadText');  
    const productCount = document.getElementById('productCount');  
  
    // Utility Functions  
    function formatPrice(value) {  
      return new Intl.NumberFormat('fr-FR').format(value);  
    }  
  
    function getCategoryLabel(category) {  
      const labels = {  
        electronics: 'Électronique',  
        fashion: 'Mode',  
        home: 'Maison'  
      };  
      return labels[category] || category;  
    }  
  
    function generateId() {  
      return 'prod_' + Date.now() + '_' + Math.random().toString(36).substr(2, 9);  
    }  
  
    // Modal Functions  
    function openAddProductModal() {  
      if (products.length >= 5) {  
        alert('Limite atteinte ! Vous avez déjà ajouté 5 produits. Abonnez-vous pour en ajouter plus.');  
        return;  
      }  
      addProductModal.classList.remove('hidden');  
      document.body.style.overflow = 'hidden';  
    }  
  
    function closeAddProductModal() {  
      addProductModal.classList.add('hidden');  
      document.body.style.overflow = 'auto';  
      resetForm();  
    }  
  
    function openProductDetailModal(product) {  
      const detailBody = document.getElementById('detailBody');  
        
      detailBody.innerHTML = `  
        <div class="detail-image">  
          ${product.image ? `<img src="${product.image}" alt="${product.name}">` : '📦 Image produit'}  
        </div>  
          
        <div class="detail-section">  
          <div class="product-badge">${getCategoryLabel(product.category)}</div>  
          <h3>${product.name}</h3>  
          <div class="detail-price">${formatPrice(product.price)} XAF</div>  
        </div>  
  
        <div class="detail-section">  
          <h3>Description</h3>  
          <p>${product.description}</p>  
        </div>  
  
        <div class="detail-section">  
          <h3>Informations du vendeur</h3>  
          <div class="detail-info-grid">  
            <div class="detail-info-item">  
              <strong>Téléphone</strong>  
              <span>${product.phone}</span>  
            </div>  
            <div class="detail-info-item">  
              <strong>Ville</strong>  
              <span>${product.city}</span>  
            </div>  
          </div>  
        </div>  
      `;  
  
      contactSellerBtn.dataset.phone = product.phone;  
      contactSellerBtn.dataset.productName = product.name;  
        
      productDetailModal.classList.remove('hidden');  
      document.body.style.overflow = 'hidden';  
    }  
  
    function closeProductDetailModal() {  
      productDetailModal.classList.add('hidden');  
      document.body.style.overflow = 'auto';  
    }  
  
    function resetForm() {  
      productForm.reset();  
      selectedImage = null;  
      imagePreview.classList.add('hidden');  
      imagePreview.innerHTML = '';  
      uploadText.textContent = 'Télécharger une image';  
    }  
  
    // Image Upload  
    uploadBtn.addEventListener('click', () => {  
      productImage.click();  
    });  
  
    productImage.addEventListener('change', (e) => {  
      const file = e.target.files[0];  
      if (file) {  
        if (file.size > 5 *  
