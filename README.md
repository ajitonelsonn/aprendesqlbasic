# aprendesqlbasic
Iha ne'e ita sei aprende SQL basiku
SQL (Structured Query Language) mak linguajen programasaun ne'ebé uza atu kria, modifika, no haree dadus iha banku dadus relasional. SQL mak hanesan mekanizmu komunikasaun ida entre aplikasaun sira no banku dadus.

Iha tinan 1970-an, Edgar F. Codd, ema ne'ebé husuva, dezenvolve teoria sira kona-ba banku dadus relasional iha IBM. Kona-ba fulan sira nia laran, estasiona peskiza no dezenvolvimentu sira ne'ebé iha setór informátika hodi halo banku dadus sira tanba la efisiénsia no kompatibilidade ho regras sira ne'ebé aplikavel iha banku dadus sira. SQL mak hatudu nudar linguaje padraun ne'ebé uza hodi kria, modifika, no haree dadus iha banku dadus relasional.

Bele hahú prende SQL husi fundamentu báziku sira hanesan:

1. **Estrutura SQL**: Aprende kona-ba estrutura báziku SQL nian, inklui instrusaun sira hanesan SELECT, INSERT, UPDATE, DELETE, no CREATE TABLE.

2. **Seleksaun Dadus**: Aprende kona-ba kona-ba instrusaun SELECT hodi halo peskiza ba dadus iha banku dadus.

3. **Modifikasaun Dadus**: Aprende kona-ba instrusaun UPDATE no DELETE hodi modifika no hapara dadus sira iha banku dadus.

4. **Kria no Haree Tabela**: Aprende kona-ba instrusaun CREATE TABLE hodi kria tabela foun iha banku dadus no kona-ba instrusaun DESCRIBE hodi haree estrutura tabela nian.

5. **Restriasaun no Ordem**: Aprende kona-ba instrusaun WHERE hodi hatama restriasaun ba peskiza no ORDER BY hodi ordena rezultadu sira.

6. **Funsaun Agregasaun**: Aprende kona-ba funsaun agregasaun sira hanesan SUM, AVG, MIN, MAX hodi kalkula dadus agregadu iha konsulta SQL.

7. **Junsaun Tabela**: Aprende kona-ba konseitu junsaun tabela sira hanesan INNER JOIN, LEFT JOIN, no RIGHT JOIN hodi kombina dadus husi tabela sira ne'ebé asosia.

Ezemplu simples SQL:

```sql
-- Kria tabela foun
CREATE TABLE Empregadu (
    id SERIAL PRIMARY KEY,
    naran VARCHAR(100),
    idade INT,
    salario DECIMAL(10, 2)
);

-- Haree dadus husi tabela
SELECT * FROM Empregadu;

-- Hatama dadus foun iha tabela
INSERT INTO Empregadu (naran, idade, salario) VALUES ('Joao', 30, 1500.00);

-- Haree dadus atu hatama foun
SELECT * FROM Empregadu WHERE idade > 25;

-- Atualiza dadus iha tabela
UPDATE Empregadu SET salario = 1800.00 WHERE naran = 'Joao';

-- Haree dadus atu hatama foun
SELECT * FROM Empregadu WHERE idade > 25;
```