// Registration
function registerUser() {
    let username = document.getElementById("regUser").value;
    let password = document.getElementById("regPass").value;

    if(username && password){
        localStorage.setItem("username", username);
        localStorage.setItem("password", password);
        alert("Registration Successful! Redirecting to login...");
        window.location.href = "./login.html";  // ✅ works better on GitHub Pages
    } else {
        alert("Please fill all fields!");
    }
}

// Login
function loginUser() {
    let username = document.getElementById("loginUser").value;
    let password = document.getElementById("loginPass").value;

    let storedUser = localStorage.getItem("username");
    let storedPass = localStorage.getItem("password");

    if(username === storedUser && password === storedPass){
        alert("Login Successful! Redirecting to portfolio...");
        window.location.href = "./portfolio.html";  // ✅ works better on GitHub Pages
    } else {
        alert("Invalid Credentials!");
    }
}
