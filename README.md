# 🤖 Agent IA d'automatisation — N8N + Gemini + Airtable + Gmail

Projet réalisé dans le cadre de mon apprentissage de l'IA et de l'automatisation.
Cet agent IA automatise la gestion de stocks Airtable et l'envoi d'emails Gmail,
en s'appuyant sur le modèle **Gemini Flash** de Google via la plateforme N8N.

---

## 🧠 Ce que fait l'agent

- Reçoit un message via le **Chat Trigger** N8N
- Consulte et met à jour les stocks dans **Airtable**
- Extrait automatiquement l'email fournisseur et la référence produit via **Gemini**
- Fusionne les données (**Merge**) et envoie un email de commande via **Gmail**
- Dispose d'une **mémoire de conversation** (Simple Memory) (5)

- ## 📸 Aperçu du workflow

- <img width="1878" height="762" alt="Workflow" src="https://github.com/user-attachments/assets/1a951461-ba4d-4126-8f5e-a075a976926c" />

Première interaction avec l'Agent : 
<img width="1913" height="863" alt="Interactin" src="https://github.com/user-attachments/assets/5be7e952-e9f3-4115-922d-f785cfd92a4d" />
Mettre à jour les stocks : 

<img width="1838" height="805" alt="Agent3" src="https://github.com/user-attachments/assets/d5720c15-e6e5-4fe5-91c6-806233ea8a6e" />

Extrait automatiquement l'email fournisseur et la référence produit : 

<img width="1876" height="869" alt="Agent4" src="https://github.com/user-attachments/assets/a841c1e1-e7f8-4310-918d-9007ed1c9a5f" />

Envoie un email de commande via Gmail : 

<img width="818" height="193" alt="Agent6" src="https://github.com/user-attachments/assets/cc25e048-c6b9-4c31-aaae-ec6c1cc92637" />






