-----------------------------------------
------------ ENGLISH VERSION ------------
-------- (italian version below) --------
-----------------------------------------

1. Download SystemC here:
	http://accellera.org/images/downloads/standards/systemc/systemc-2.3.1.tgz

2. Extract the archive and find the MSC80 directory where some old project solutions await you.

3. Open the solution, ignore the complaints, and build the library (x86, Debug and if you want, Release).

4. Move the folder in a convenient path (e.g. D:) with the file "systemC.props" (put it into the systemC directory).

5. Create the system environment variable for the path to the systemC folder (es. D:systemc-2.3.1) with the alias SYSTEMC_DIR

6) Take the SystemC_Project.zip file and put it in the folder inside the Visual Studio user folder (usually in Documents):
	Documents/Visual Studio 2015/Templates/ProjectTemplates/Visual C++ Project

To create a SystemC project:
7. Open Visual Studio:

	a) File -> New -> Project ->
		Templates -> Visual C++ and select "SystemC".

-------- IN CASE OF ERROR --------
In case of a building error related to "gets", click on the error (it should take you to the systemC.h file and comment out (//) the line related to "gets".
This kind of error happens with the latest versions of C++, because they haven't the definition of "gets" anymore, so don't worry about this.

-----------------------------------------
------------ ITALIAN VERSION ------------
-----------------------------------------

1. Scaricare la libreria di systemC qua:
	http://accellera.org/images/downloads/standards/systemc/systemc-2.3.1.tgz

2. Estrarre l'archivio e prendere la cartella MSC80 dove si trova la soluzione di un progetto abbastanza vecchio

3. Aprire la soluzione, ignorare i vari problemi di compatibilità e buildare la libreria (x86, debug e se si vuole anche release).

4. Spostare la cartella in una posizione comoda (es D:) insieme al file "systemC.props" (metterlo dentro la cartella di systemC).

5. Creare la variabile di ambiente di sistema relativa al percorso della cartella (es. D:systemc3.1) sotto il nome di SYSTEMC_DIR

6) Prendere l'archivio SystemC_Project.zip e metterlo nella cartella all'interno della cartella utente di Visual Studio (solitamente nei Documenti):
	Documents/Visual Studio 2015/Templates/ProjectTemplates/Visual C++ Project (o qualcosa di simile)

Per creare un progetto di SystemC:
7. Aprire Visual Studio:
	File -> Nuovo -> Progetto->
		Template -> Visual C++ e seleziona "SystemC".

-------- IN CASO DI ERRORE --------
Nel caso in cui dia errore relativo a "gets", andare a cliccare sull'errore ottenuto e commentare (//) la linea relativa a "gets".
Questo errore succede in quanto nelle ultime versione del C++ non si ha più la definizione di "gets", quindi non preoccupatevi.
