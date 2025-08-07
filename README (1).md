This project uses a fine-tuned LLaMA 3 model via Ollama to act as a polite, helpful AI assistant in the medical field. The assistant can handle user queries related to:
- Appointments
- Medicine orders
- Lab test bookings
- General medical queries

  Base Model: LLaMA 3
  Tuning Method: Ollama fine-tuning
  Dataset Format: JSONL (prompt-response pairs)

- `Modelfile` – Configuration file to build the model with system prompt
- `training.jsonl` – Fine-tuning dataset used to train the assistant

 1. Pull the base model
cmd:
ollama pull llama3
