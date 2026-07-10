document.getElementById("loginForm").addEventListener("submit", function(event) {
    event.preventDefault();

    const email = document.getElementById("email").value.trim();
    const password = document.getElementById("password").value.trim();
    const message = document.getElementById("message");

    // Client-side validation
    if (email === "" || password === "") {
        message.textContent = "Please fill in all fields.";
        return;
    }

    if (!email.includes("@")) {
        message.textContent = "Please enter a valid email.";
        return;
    }

    if (password.length < 8) {
        message.textContent = "Password must be at least 8 characters.";
        return;
    }

    // Simulated server-side validation
    if (email === "student@example.com" && password === "Password123") {
        message.textContent = "Login successful!";
    } else {
        message.textContent = "Invalid email or password.";
    }
});
