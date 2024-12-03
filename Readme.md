-- Table structure Auto Usate

id | INT AUTO_INCREMENT PRIMARY KEY (UNIQUE NOT NULL)
targa | VARCHAR(10) UNIQUE NOT NULL,
telaio | VARCHAR(30) UNIQUE NULL,
marca | VARCHAR(30) NOT NULL,
modello | VARCHAR(50) NOT NULL,
cilindrata | SMALLINT NULL,
anno | YEAR | NULL,
chilometraggio | INT NULL,
prezzo | FLOAT(10, 2) NULL,
colore | VARCHAR(30) NULL,
carburante | VARCHAR(20) NULL,
trasmissione |VARCHAR(20) NULL,
descrizione | TEXT(500) NULL,
porte | TINYINT NULL,
ultima_revisione | DATE NULL,
scadenza_bollo | DATE NULL,
n_proprietari | TINYINT NULL,
prezzo_listino | FLOAT(10,2) NULL,
prezzo_finale | FLOAT(10,2) NULL,
foto_url | TEXT(500) NULL,
disponibilità | TINYINT(1) DEFAULT(0)

js
const autoUsate = [
{
id: 1,
marca: 'Ford',
modello: 'Fiesta',
......
}
];
