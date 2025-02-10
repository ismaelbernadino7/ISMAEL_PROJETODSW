# ISMAEL_PROJETODSW
TDS/3

import pandas as pd

# Dados fictícios
dados = {
    "Data de Check-in": pd.date_range(start='2025-01-01', periods=15, freq='D'),
    "Avaliação": [5, 4, 5, 3, 4, 4, 5, 5, 3, 4, 4, 5, 3, 5, 4],
    "Aparelhos de Treino": ["Esteira", "Bicicleta", "Pesos", "Máquina de Remo", "Elíptico", "Step", "Leg Press", "Supino", "Crossover", "Agachamento", "Lat Pulldown", "Puxada", "Smith Machine", "Abdutor", "Adutor"],
    "Personal Trainer": ["Ana Lima", "Carlos Souza", "Maria Oliveira", "Pedro Fernandes", "Luciana Costa", "Ana Lima", "Carlos Souza", "Maria Oliveira", "Pedro Fernandes", "Luciana Costa", "Ana Lima", "Carlos Souza", "Maria Oliveira", "Pedro Fernandes", "Luciana Costa"],
    "Nome do Aluno": ["João Pereira", "Mariana Silva", "Carlos Souza", "Amanda Lima", "Lucas Costa", "Ana Paula", "Ricardo Mendes", "Julia Santana", "Marcos Teixeira", "Laura Ribeiro", "Pedro Henrique", "Bianca Oliveira", "Felipe Almeida", "Carla Monteiro", "Bruno Martins"],
    "Localidade": ["São Paulo", "Rio de Janeiro", "Belo Horizonte", "Porto Alegre", "Brasília", "Curitiba", "Recife", "Salvador", "Fortaleza", "Manaus", "Florianópolis", "Goiânia", "Natal", "Belém", "Campinas"],
    "Horário de Funcionamento": ["06:00-22:00", "06:00-22:00", "06:00-22:00", "06:00-22:00", "06:00-22:00", "06:00-22:00", "06:00-22:00", "06:00-22:00", "06:00-22:00", "06:00-22:00", "06:00-22:00", "06:00-22:00", "06:00-22:00", "06:00-22:00", "06:00-22:00"],
    "Percentual de Gordura (%)": [18, 20, 15, 22, 17, 16, 19, 21, 20, 18, 17, 23, 24, 25, 19],
    "Peso (kg)": [70, 65, 80, 75, 68, 72, 74, 66, 73, 71, 69, 78, 82, 85, 76],
    "Altura (cm)": [175, 168, 180, 165, 178, 170, 172, 160, 173, 174, 169, 182, 185, 188, 176],
    "Feedback": ["Excelente", "Bom", "Excelente", "Regular", "Bom", "Bom", "Excelente", "Excelente", "Regular", "Bom", "Bom", "Excelente", "Regular", "Excelente", "Bom"],
    "Faixa Etária Mínima (anos)": [16]*15,
    "Email do Aluno": ["joao@example.com", "mariana@example.com", "carlos@example.com", "amanda@example.com", "lucas@example.com", "ana@example.com", "ricardo@example.com", "julia@example.com", "marcos@example.com", "laura@example.com", "pedro@example.com", "bianca@example.com", "felipe@example.com", "carla@example.com", "bruno@example.com"],
    "Telefone do Aluno": ["(11) 99999-0001", "(21) 99999-0002", "(31) 99999-0003", "(51) 99999-0004", "(61) 99999-0005", "(41) 99999-0006", "(81) 99999-0007", "(71) 99999-0008", "(85) 99999-0009", "(92) 99999-0010", "(48) 99999-0011", "(62) 99999-0012", "(84) 99999-0013", "(91) 99999-0014", "(19) 99999-0015"],
    "Idade": [25, 30, 28, 24, 35, 22, 27, 26, 29, 31, 23, 34, 32, 33, 28]
}

df = pd.DataFrame(dados)
print(df)
