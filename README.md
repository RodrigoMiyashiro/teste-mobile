<h1 align="center">Teste Mobile</h1>

<h3>Tarefas</h3>

Dado o Json abaixo apresente:

````
[
    {
        "company_id": "114",
        "created_at": 1571323199864,
        "name": "Aula Álgebra",
        "id": "114_0v62DokeArxPA9oDSBst_349785",
        "status": "IN_PROGRESS",
        "summary": {
            "percentage": 20
        }
    },
    {
        "company_id": "114",
        "created_at": 1578343188529,
        "name": "Aula Trigonometria",
        "id": "114_3Lj7okST2yBSYXUUByg2_349798",
        "status": "NOT_STARTED",
        "summary": {
            "percentage": null
        }
    },
    {
        "company_id": "114",
        "created_at": 1568918240759,
        "name": "Aula Filosofia",
        "id": "114_3O81FOuWLZIlSDnRJHm1_349798",
        "status": "COMPLETED",
        "summary": {
            "percentage": 100
        }
    },
    {
        "company_id": "114",
        "created_at": 1574361972593,
        "name": "Aula Geografia",
        "id": "114_46keopvfEUvlNP7bd049_349798",
        "status": "IN_PROGRESS",
        "summary": {
            "percentage": 75
        }
    },
    {
        "company_id": "114",
        "created_at": 1571946887159,
        "name": "Aula História",
        "id": "114_5FK4ExJCz3vW4XmS0KVr_349798",
        "status": "NOT_STARTED",
        "summary": {
            "percentage": null
        }
    }
]
````
<h3>Requisitos</h3>
Crie a seguinte interface que contenha uma lista com os itens declarados acima, essa lista deve apresentar as seguintes informações:

- [ ] O nome da aula;
- [ ] A data de criação em dd/MM/yyyy;
- [ ] O ID da Aula;
- [ ] Quando a aula estiver completa deve apresentar um ícone de √ em verde;
- [ ] Quando a aula ainda não estiver iniciada não deverá apresentar nenhum ícone;
- [ ] Quando a aula estiver em andamento deve apresentar a porcentagem do progresso;
- [ ] A lista deve estar ordenada por ordem de criação;
- [ ] Todos os itens devem ter um botão de exclusão funcional;




