# alpha-cash-infra
Infraestrutura do Alpha Cash (orcamento-api + alpha-cash-web + orcamento_db).

alpha-cash-infra provisiona o produto Alpha Cash: o orcamento-api (resource server de receitas e despesas), o bundle estático do alpha-cash-web e o schema orcamento_db.

É o primeiro *-infra de produto da suíte, e o molde dos próximos. Não provisiona identidade: o auth-api e o user-api vivem em alpha-account-infra e precisam estar no ar antes — sem eles ninguém loga no Cash.

Cobre o ambiente local (Docker Compose + bootstrap do schema) e o provisionamento em produção na AWS.
