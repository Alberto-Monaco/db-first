-- Table structure Auto Usate

id | INT AUTO_INCREMENT PRIMARY KEY (UNIQUE NOT NULL)
targa | VARCHAR(10) UNIQUE NOT NULL,
telaio | VARCHAR(30) UNIQUE NULL,
marca | VARCHAR(30) NOT NULL,
modello | VARCHAR(50) NOT NULL,
cilindrata | SMALLINT NULL,
anno | YEAR | NULL,
chilometraggio | MEDIUMINT NOT NULL,
prezzo | DECIMAL (10, 2) NULL,
colore | VARCHAR(30) NULL,
carburante | VARCHAR(20) NULL,
cambio |VARCHAR(20) NULL,
descrizione | TEXT(500) NULL,
porte | TINYINT NULL,
n_posti | TINYINT NULL,
n_proprietari | TINYINT NULL,
prezzo| FLOAT(10,2) NOT NULL,
foto_url | TEXT(500) NULL,
disponibilità | TINYINT DEFAULT(0)
