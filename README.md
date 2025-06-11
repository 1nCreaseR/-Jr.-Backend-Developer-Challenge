# -Jr.-Backend-Developer-Challenge
Hola
Gracias por tu interés en el puesto de Jr. Backend Developer en nuestra empresa. Como
parte del proceso de selección, requerimos que completes una prueba técnica que nos
ayudará a evaluar tus habilidades y conocimientos relevantes para el rol. A
continuación, te explicaré en qué consiste la prueba y cómo proceder:

Entregables:

Al finalizar deberás compartirnos el repositorio donde habrás respondido (READ ME)
tanto las preguntas de opción múltiple y el código respectivo a los enunciados.

Duración:

Tienes 24horas para completar la prueba a partir del momento en que se haya enviado la
misma.

---

## Pregunta 1

**You're building a high-throughput API for a cryptocurrency trading platform. For this platform, time is extremely important because microseconds count when processing high-volume trade orders. For communicating with the API, you want to choose the verb that is fastest for read-only operations.**

What verb should you choose for retrieving trade orders with the API
server?

SELECT ONLY ONE:

- [ X ] 1. GET
- [ ] 2. UPDATE 
- [ ] 3. DELETE
- [ ] 4. POST

---

## Pregunta 2

**You work for a Customer Relationship Management (CRM) company. The company's clients gain CRM access through a RESTful API. The CRM allows clients to add contact information for customers, prospects, and related persons (e.g., virtual assistants or marketing directors). You want to choose an appropriate API request path so clients can easily retrieve information for a single contact while also being flexible for future software changes.**

Which of the following API paths should you use?

SELECT ONLY ONE:

- [ ] 1. /customers/{customer_id}  
- [ X ] 2. /contacts/{contact_id}  
- [ ] 3. /contacts/{contact_type}/all
- [ ] 4. /customers/all 

---

## Pregunta 3

**You work for a large social media network, and you've been tasked witherror handling for the API. You're trying to Decide on an appropriate errorcode for authentication failures based on non-existent users and incorrect passwords. You want to balance security against brute force attacks with providing descriptive and true error codes.**

Which HTTP error code(s) should you use to keep the system secure and still report
that an error occurred?

SELECT ONLY ONE:

- [ ] 1. 404 if the user doesn't exist, and 403 if the password is wrong.  
- [ ] 2. 403 if the user doesn't exist, and 401 if the password is wrong.  
- [ ] 3. 500 if the user doesn't exist or if the password is wrong.
- [ X ] 4. 401 if the user doesn't exist or if the password is wrong. 

---

## Pregunta 4

**You're writing documentation for requesting information about a given user in your system. Your system uses UUIDS (universally unique identifiers) as user identifiers. In your documentation, you want to show an example..**

True or false: You should put a fake UUID into the example code (instead of just the
text "UUID") as a placeholder.

SELECT ONLY ONE:

- [ X ] 1. TRUE  
- [ ] 2. FALSE 

---

## Pregunta 5

**You're building code to handle errors issued from a remote API server. The response may or may not have an error.**

How much work should your method, handleErrors(response), handle?

SELECT ONLY ONE:

- [ ] 1. Check for the presence of an error. If it exists, then set a class property to the error.  
- [ X ] 2. Check for the presence of an error. If it exists, throw an exception with the error.  
- [ ] 3. Check for the presence of an error. If it exists, set a class property to the error, then throw an exception.

---

## Pregunta 6

**You need to name the private method in your class that handles loopingthrough eCommerce products to collect and parse data. That data gets stored in an array and set as a class property.**

Which of the following should you use to name your method?

SELECT ONLY ONE:

- [ ] 1. loopThroughProductsAndParseData()  
- [ ] 2. loopProductsAndParse()  
- [ X ] 3. parseDataForProducts()
- [ ] 4. parseDataForProductsAndSetArray()

---

## Pregunta 7

**There are multiple places in your codebase that need to access the database. To access the database, you need to supply credentials. You want to balance security with useability**

What strategy should you use to store and access these credentials?

SELECT ONLY ONE:

- [ ] 1. Put them in the code that connects to the database for each place that needs database access.  
- [ ] 2. Put them in a configuration file, then include that file in the code everywhere that needs to access the   database.  
- [ ] 3. Put the credentials into a configuration file, then load them with a database service provider.
- [ X ] 4. Put them in a .env file, load data from it into a configuration system, then request the credentials from a database service provider.
