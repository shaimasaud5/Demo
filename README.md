# Demo: a small bookshop site used to test Yaqidh

`demo_app/` is "Maktabti", a small Flask bookshop with problems planted on purpose (SQL injection in the search,
debug mode on, a fake token in the code, old libraries). It is only for testing the Yaqidh release companion.
Do not deploy it. The token in `demo_app/config.py` is fake.

Opening a pull request runs `.github/workflows/yaqidh.yml`, which scans the code and sends the results to Yaqidh.

ُ#Test1
