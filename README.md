# python-project
this is python test project
http://localhost:8000/api/get_user_balances/u1 Get Method i have four user u1,u2,u3,u4
http://localhost:8000/api/simplify_balances/
{
    "user_id":"1"
}

http://localhost:8000/api/add_expense/

{"user_id":"1","expense_type":"EQUAL","amount":1000,"participants":["1"]}
{
  "user_id": "1",
  "expense_type": "EXACT",
  "amount": 1000,
  "participants": [
    {
      "user_id": "2",
      "share": 250
    },
    {
      "user_id": "3",
      "share": 300
    },
    {
      "user_id": "4",
      "share": 450
    }
  ]
}
{
  "user_id": "1",
  "expense_type": "PERCENT",
  "amount": 1000,
  "participants": [
    {
      "user_id": "2",
      "percent": 25
    },
    {
      "user_id": "3",
      "percent": 30
    },
    {
      "user_id": "4",
      "percent": 45
    }
  ]
}
