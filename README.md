# Logica_Fuzzy

**Antecedentes (entradas)**

Superfície: qual o nível de dificuldade da superfície, em uma escala de 0 a 5?
- fácil, moderada, difícil

Sujeira: qual a quantidade de sujeira, em uma escala de 0 a 5?
- leve, moderada, pesada

**Consequente (saída)**

Sucção: qual o nível de sucção que o aspirador de pó deve ser configurado, entre 0% e 10%?
- baixa, média, alta

Regras
- Se a superfície for *fácil* e a sujeira for *leve* então a sucção será *baixa*
- Se a superfície for *moderada* e a sujeira for *leve* então a sucção será *média*
- Se a superfície for *difícil* ou a sujeira for *pesada* então a sucção será *alta*
- Se a superfície for *moderada* então a sucção será *média*
