## ✅ **Summary: Understanding Software Structure and Logistics**

* **ABAP Packages** group related development objects and belong to software components.
* Every development object must be assigned to a **package**, which is part of the ABAP Repository.
* **Transport Requests** are required to move development objects from development to test and production environments.
* Only developers assigned to a transport request can modify its objects.
* Upon completion, the transport request must be **released** to allow import to other systems and unlock 
the objects.

* In this unit, we:

  * Add an existing package `/LRN/S4D400_EXERCISE` to favorites.
  * Create our own package `ZS4D400_##` under the `ZLOCAL` superpackage.

---

## 📝 **Unit: Understanding Software Structure and Logistics – Create an ABAP Package**

| Attribute              | Value                              |
|------------------------|------------------------------------|
| Name                   | ZS4D400_##, where ## is the group number |
| Description            | My ABAP Package                    |
| Add to favorite packages | Checked                          |
| Superpackage           | ZLOCAL                             |
| Package Type           | Development                        |
| Software Component     | ZLOCAL                             |
| Application Component  | Leave this field blank             |
| Transport Layer        | Leave this field blank             |

### 🇩🇪 Deutsch | 🇬🇧 English

---

### 🎯 **Ziel** | **Objective**

✅ Ein ABAP-Paket erstellen können
✅ Be able to create an ABAP package

---

### 📦 **Schritte zum Erstellen eines ABAP-Pakets** | **Steps to Create an ABAP Package**

---

🔹 **1. Paket /LRN/S4D400\_EXERCISE zu Favoriten hinzufügen**
🔹 **1. Add package /LRN/S4D400\_EXERCISE to favorite packages**

* Öffne im linken Bereich „Project Explorer“ dein ABAP Cloud Projekt.
  Open your ABAP Cloud project in the Project Explorer on the left.

* Klicke mit der rechten Maustaste auf **Favorite Packages** → **Add Package ...**
  Right-click **Favorite Packages** → **Add Package ...**

* Gib im Suchfeld ein: `/LRN/S4D400`
  Enter `/LRN/S4D400` in the search field

* Wähle `/LRN/S4D400_EXERCISE` aus der Liste → OK
  Select `/LRN/S4D400_EXERCISE` from the list → OK

---

🔹 **2. Neues ABAP-Paket erstellen**
🔹 **2. Create a new ABAP package**

* Rechtsklicke auf dein ABAP Cloud Project → **New → ABAP Package**
  Right-click your ABAP Cloud Project → **New → ABAP Package**

* **Name:** `ZS4D400_##` (## = deine Gruppennummer)
  **Name:** `ZS4D400_##` (## = your group number)

* **Beschreibung:** *My ABAP Package*
  **Description:** *My ABAP Package*

* **Add to favorite packages:** Aktiviert
  **Add to favorite packages:** Checked

* **Superpackage:** `ZLOCAL`
  **Superpackage:** `ZLOCAL`

* **Package Type:** *Development*
  **Package Type:** *Development*

* Klicke auf **Next**
  Click **Next**

* **Softwarekomponente:** `ZLOCAL`
  **Software Component:** `ZLOCAL`

* **Application Component:** leer lassen
  **Application Component:** leave blank

* **Transport Layer:** leer lassen
  **Transport Layer:** leave blank

* Klicke auf **Next**
  Click **Next**

---

🔹 **3. Transportauftrag auswählen oder erstellen**
🔹 **3. Select or create a transport request**

* Wenn ein Transportauftrag angezeigt wird → auswähle
  If a transport request is shown → select it

* Wenn nicht → **Create a new request** auswählen
  If not → choose **Create a new request**

* **Beschreibung:** z. B. *ABAP Exercises*
  **Description:** e.g., *ABAP Exercises*

* Klicke auf **Finish**
  Click **Finish**

---

🔹 **4. Sicherstellen, dass dein Paket zu Favoriten hinzugefügt wurde**
🔹 **4. Ensure your package is added to favorites**

* Erweitere unter **Favorite Packages** den Knoten
  Expand the **Favorite Packages** node

* Wenn dein Paket nicht angezeigt wird → wie zuvor hinzufügen
  If your package isn’t shown → add it the same way as `/LRN/S4D400_EXERCISE`