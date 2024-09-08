# mlx-imessage
This project fine-tunes a large language model (LLM) locally using iMessage chat history to replicate your communication style. By keeping the process on your device, it ensures privacy, preventing data leakage to external servers. The goal is to create a personalized AI that generates organic, contextually relevant messages, matching how you typically text.

## Setup

```
pip install -r requirements.txt
```

## Usage

Run ```imessage_mlx.ipynb``` in your IDE. 

## Notes / Challenges
- When I experimented with this, it was very effective at capturing my tone and how I texted, but suffered from being a bit too rando
   - 

## Future Work / Ideas
- Incorperating RAG with your message history, attachments, calendar, notes, etc. to create a personal "secretary" and better messages per-person
- Experimenting with adding relationship data while fine-tuning (ie. this is your friend, this is your boss/colleague, this is your husband/wife, this is your mother/father, etc.)


## References / Inspiration
- https://github.com/ShawhinT/YouTube-Blog/tree/main/LLMs/qlora-mlx: Local Fine-tuning on Mac (QLoRA with MLX)
- https://github.com/gavi/mlx-whatsapp:  An mlx project to train a base model on your whatsapp chats using (Q)Lora finetuning
- https://github.com/ishan0102/iClone: Clone your friends with iMessage and MLX
