# Rules for every Claude chat on this repo

- Be as efficient as possible with tokens and usage, always: take the shortest path that gets it right, batch tool calls, read only the lines needed, no repeated screenshots or re-reads, no helper agents or workflows unless the job truly needs them.
- Long chats cost the most, because the whole conversation is re-read on every step. Start a fresh chat per task; past ~300K tokens, finish the task, write what the next chat needs into this file, and tell Greg to open a new chat.
- No timers, loops or helper agents running when there is little to do; check in every 30 to 60 minutes, not every 10. Helper agents only for big jobs, with short briefs, on a cheaper model (Sonnet or Haiku) for simple reading or checking.
