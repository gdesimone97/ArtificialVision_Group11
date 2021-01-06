# ArtificialVision_Group11
Group_11

- De Simone Giuseppe
- Giaquinto Gennaro
- Marino Christian
- Serritiello Simone

# Fase preliminare
Per poter eseguire entrambi gli esperimenti bisogna caricare i file contenuti nella sezione *Releases/datafiles*, della repository, nella directory *Group_11/*

# Train
Il codice per eseguire il train della rete è contenuto nel file *group11_train.ipynb*.
Insieme al codice è stato fornito una frazione del trainset *train2401_2800.rar* ed il file csv ad esso associato *train2401_2800.csv*.
Per poter riprodurre l'esperimento bisogna caricare tutti i file presenti nella sezione *Releases/trainset/*, della repository, nella directory *Group_11/trainset*

# Test
Il codice per eseguire il test della rete è contenuto nel file *group11_test.ipynb*.
Data l'enoreme quantità di tempo necessaria per esegure il preprocessing dell'intero testset, viene qui fornito un testset già preprocessato (derivante dal testset originale *vggface2_test.tar.gz*). A causa dei limiti di upload imposti da github, tale testset è stato suddiviso in due parti: *test_crop.part1.rar* e *test_crop.part2.rar*.
Nel file di test è stata comunque messa a disposizione una funzione che partendo da un'immagine non preprocessata esegua tutta la pipeline rigurdante il preprocessing e stima dell'età.
Per poter eseguire tale test si necessita che il contenuto della repository debba essere caricato nella home del proprio GoogleDrive.

Per poter eseguire tale esperimento bisogna caricare tutti i file presenti nella sezione *Releases/testset/*, della repository, nella directory *Group_11/testset*.

Viene di seguito fornita il link ad una cartella GoogleDrive già preconfigurata: [https://drive.google.com/drive/folders/1Gd7VNibx_4ZGW9NgPW2fs09avtI_D21V?usp=sharing](https://drive.google.com/drive/folders/1Gd7VNibx_4ZGW9NgPW2fs09avtI_D21V?usp=sharing)
