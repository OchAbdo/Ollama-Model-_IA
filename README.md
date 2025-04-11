# 🤖 Chatbot IA local avec Spring Boot, Spring AI & Ollama

Ce projet Spring Boot montre comment créer un chatbot local en utilisant l'outil [Ollama](https://ollama.com/) et la nouvelle abstraction **Spring AI**, qui simplifie la communication avec les modèles de langage (LLMs).

---

## 🚀 Fonctionnalités

- Intégration simple avec un modèle IA local "openchat"
- Utilisation de Spring AI pour simplifier l’interaction avec les LLMs
- API REST pour discuter avec le chatbot
- Solution 100% locale, aucune dépendance à une API cloud

---

## 🧰 Prérequis

### ✅ Système requis

- Java 17
- Maven
- Ubuntu (ou tout OS compatible avec Ollama)
- Ollama installé (voir ci-dessous)
- Modèle IA téléchargé (openchat)

---

## 🐧 Installation d’Ollama sur Ubuntu

### Étapes d’installation :

1. **Télécharge le script d’installation :**

```bash
curl -fsSL https://ollama.com/install.sh | sh

```
2. **Lance le service Ollama :**

```bash
ollama serve

```
3. **Tire un modèle IA (openchat) :**

```bash
ollama pull openchat

```
4. **Démarre le modèle :**

```bash
ollama run openchat

```
