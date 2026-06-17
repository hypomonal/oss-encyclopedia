# 📮 Postman

![License](https://img.shields.io/badge/license-Proprietary%2FFree-orange)

| Field | Info |
|-------|------|
| 🏷️ **Category** | 🛠️ Developer Tools |
| 👤 **Made by** | Postman Inc. |
| ⚖️ **License** | Free tier available ✅ |
| 🌐 **Website** | [postman.com](https://postman.com) |
| 💻 **GitHub** | [postmanlabs/postman-app-support](https://github.com/postmanlabs/postman-app-support) |

---

## 📌 What it is

Postman is THE **API development and testing platform** used by over 30 million developers worldwide!! 🌍 Build, test, document, and share APIs — all in one beautiful app!! Whether you're calling someone else's API or building your own, Postman makes it effortless!!

---

## 🔍 What it does

- 🌐 Send HTTP requests — GET, POST, PUT, DELETE & more
- 🧪 Write automated API tests with JavaScript
- 📚 Auto-generate beautiful API documentation
- 🤝 Share API collections with your whole team
- 🔄 Set up environments for dev, staging, production
- 🔒 Test OAuth, JWT, API keys — all auth methods supported

---

## 🚀 How to use it

```bash
# Download from postman.com or:
brew install --cask postman

# Or use the open-source CLI alternative!!
npm install -g newman

# Run a Postman collection from CLI
newman run my-collection.json -e environment.json
```

```javascript
// Example test script in Postman!!
pm.test("Status is 200", () => {
    pm.response.to.have.status(200);
});
pm.test("Response has user id", () => {
    const json = pm.response.json();
    pm.expect(json.id).to.be.a("number");
});
```

---

## 💡 Who it helps

- 🧑‍💻 Backend developers testing their own APIs
- 🌐 Frontend devs calling third-party APIs
- 🧪 QA engineers running automated API test suites
- 📚 Developer advocates creating API documentation
- 🏢 Teams sharing API workflows and test collections

---

## ⚡ Why it's awesome

Before Postman, testing an API meant writing curl commands from memory or building a whole test script!! 😅 Now it's just fill in a form, click Send, and see your response beautifully formatted!! The collaboration features make it essential for any team building APIs!! 🏆

---

*[← Back to DevTools index](./README.md)*

