# 🤖 CodeBot v1.0.0 – Porsche Funktionssoftware-Assistent

**CodeBot** ist ein leistungsstarker KI-gestützter Assistent zur Unterstützung der Fahrzeug-Funktionsentwicklung bei Porsche. Die Anwendung kombiniert dokumentbasiertes Frage-Antworting mit intelligenter Codegenerierung basierend auf bestehenden Codebasen und technischen Dokumenten.

## 🚀 Features

- 📚 **Dokumenten-Chat**  
  Interaktiver Chat mit eigenen PDF-Dokumenten (z. B. Spezifikationen, Normen, Handbücher).  
  ➤ Upload im `./pdfs` Verzeichnis.

- 💻 **Code-Generator**  
  Generiere neue Funktionssoftware auf Basis von existierendem Code.  
  ➤ Upload im `./code_base` Verzeichnis.

- 🧠 **Retrieval-Augmented Generation (RAG)** mit FAISS  
  Nutzt eine Vektor-Datenbank, um relevante Inhalte aus PDFs und Code-Dateien kontextbasiert bereitzustellen.

- 🔐 **Azure OpenAI Integration**  
  Verwendet GPT-4o und Embedding-Modelle über Azure OpenAI.
