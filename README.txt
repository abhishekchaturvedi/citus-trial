1. Follow https://github.com/citusdata/citus for running citus locally. Step #4 in this takes you to https://docs.citusdata.com/en/stable/get_started/tutorial_multi_tenant.html which has a good multi-tenant use case. The yml file for this is citus.yml.
2. https://github.com/sairamkrish/keycloak-identity-management-demo has keycloak with postgres. deployment file for this is keycloak-postgres.yml
3. combined the two in citus-keycloak.yml. keycloak service can't connect to postgres yet.
