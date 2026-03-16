models.py   → estrutura do banco
forms.py    → formulário baseado no model
views.py    → lógica do sistema
templates   → página HTML que mostra o formulário

Fluxo real
Usuário preenche formulário
        ↓
HTML envia dados
        ↓
views.py recebe
        ↓
forms.py valida
        ↓
salva no banco