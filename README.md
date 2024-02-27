# Calculadora.console_Parreiras



CREATE TABLE OperacoesHistorico (
    Id INT PRIMARY KEY IDENTITY(1,1),
    NomeOperacao NVARCHAR(255) NOT NULL,
    Resultado float NOT NULL,
    DataHoraOperacao DATETIME DEFAULT GETDATE()
);