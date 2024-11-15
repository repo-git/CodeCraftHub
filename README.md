# Final Project

# User Service

Questo è un servizio di gestione utenti costruito con Node.js e MongoDB.

## Installazione

1. Clona il repository:
bash git clone <repository-url> cd user-service
2. Installa le dipendenze:
bash npm install
3. Configura le variabili d'ambiente nel file `.env`.

4. Avvia il server:
bash npm start
## API

### Registrazione Utente

- **Endpoint**: `POST /api/users/register`
- **Body**:
json { "username": "string", "email": "string", "password": "string" }

### Login Utente

- **Endpoint**: `POST /api/users/login`
- **Body**:
json { "email": "string", "password": "string" }

## Note

Assicurati di avere MongoDB in esecuzione e di modificare l'URI nel file `.env` in base alla tua configurazione.
