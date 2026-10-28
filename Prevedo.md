| #   | Istruzione                                                                                                         | Prevedo            | Cosa è successo                            |
| --- | ------------------------------------------------------------------------------------------------------------------ | ------------------ | ------------------------------------------ |
| 1   | `UPDATE studenti SET classe_id = 999 WHERE id = 2;`                                                                | `errore id classe` | `(classe_id)=(999) non è presente`         |
| 2   | `INSERT INTO studenti (nome, cognome, email, classe_id) VALUES ('Teo', 'Marino', 'teo.marino@scuolachill.it', 7);` | `errore di VALUES` | `(classe_id)=(7) non è presente`           |
| 3   | `DELETE FROM classi WHERE id = 3;`                                                                                 | `non trova l'id`   | `key id 3 is still referenced in studenti` |
| 4   | `DELETE FROM classi WHERE id = 4;`                                                                                 | `non trova l'id`   | `ha funzionato`                            |
| 5   | `INSERT INTO studenti (nome, cognome, email, classe_id) VALUES ('Teo', 'Marino', 'teo.marino@scuolachill.it', 4);` | `funziona`         | `id 4 is not present in table classi`      |
