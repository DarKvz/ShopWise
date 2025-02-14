# 🚀 Welcome to ShopWise - Software Testing!

Welcome to the **ShopWise** repository, an amazing project developed to enhance the online shopping experience! 🛍️ Here, you'll find all the documentation and test cases that ensure the system works efficiently and securely.

---

## 🤔 What is ShopWise?

**ShopWise** is a platform designed to make online shopping easier, offering features such as:
- **Secure Login and Registration** 🔐
- **Smart Search and Filters** 🔎
- **Shopping Cart and Favorites** ❤️
- **Product Interaction via Camera** 📸

Our goal is to ensure that each functionality is tested and validated to provide the best user experience!

---

## ✅ What are we testing?

### 🔐 **Authentication and Registration**
- [Login Screen](ShopWise%20Tela%20de%20login.docx)
- [Sign-Up Screen](ShopWise%20-%20Tela%20de%20Inscrever-se.docx)
- [Password Recovery](ShopWise%20Esqueceu%20sua%20senha.docx)

### 🛍️ **Navigation and User Experience**
- [Initial Screen](ShopWise%20TelaInicial.docx)
- [Home Page](ShopWise%20-%20Home%20Page.docx)
- [Product Screen](ShopWise%20-%20Tela%20de%20produto.docx)
- [Favorites Screen](ShopWise%20-%20Favorito.docx)
- [Camera Usage for Sales](ShopWise%20-%20Camera.docx)

---

## 🔎 How do we test?

We use **BDD (Behavior-Driven Development)** with test scenarios written in **Gherkin**, along with **Functional Test Cases** to ensure everything works as expected.

### 📌 Example Test - Login

```gherkin
Feature: Login Screen

  Scenario: User successfully logs in
    Given the user is on the login screen
    When they enter their correct credentials
    And click the "Login" button
    Then the system should redirect them to the home page 🎉
```

### 📌 Example Test Case - Product Screen

| ID      | Description                             | Steps | Expected Outcome |
|---------|----------------------------------------|--------|------------------|
| CT_001  | Access the Product Screen             | 1. Click on the selected product<br>2. View product options<br>3. Add to cart | Product selected and added to the cart 🛒 |

---

## 🚀 How to Test?

1. Clone the repository:
   ```bash
   git clone https://github.com/your-username/shopwise-software-testing.git
   ```
2. Browse the `.docx` files to understand the test scenarios.
3. Execute the test cases and watch the magic happen! ✨

---

## 📜 License

This project was developed for academic purposes in the **Software Testing** course. If you like what you see, feel free to contribute and share your suggestions! 💡
