# MSXDOS-0
Clone des commandes du MSX-DOS des micro-ordinateurs MSX écrit en Pascal

![image](https://user-images.githubusercontent.com/11842176/179816962-9f127fd8-b5ad-45fa-8d2f-f4d5171f3b67.png)

![image](https://user-images.githubusercontent.com/11842176/179816606-e28b7d0b-7302-4245-8398-11d2f4882dad.png)

<h2>Liste des fichiers</h2>

Voici la liste des différents fichiers proposés dans MSXDOS-0 :

<table>
		<tr>
			<th>Nom</th>
			<th>Description</th>	
		</tr>
    <tr>
			<td><b>BASIC.PAS</b></td>
			<td>Cette commande permet de lancer l'interpréteur MSX BASIC.</td>
		</tr>
		<tr>
			<td><b>COMMAND2.PAS</b></td>
			<td>Cette commande permet de lancer l'interpréteur de commande <a href="https://www.gladir.com/OS/MSXDOS/intro.htm">MSX-DOS</a> .</td>
		</tr>
		<tr>
			<td><b>TOOLS\HEAD.PAS</b>
			<td>Cette commande permet d'afficher le début d'un fichier texte.</td>
		</tr>
		<tr>
			<td><b>TOOLS\SORT.PAS</b></td>
			<td>Cette commande permet de trier une fichier texte ASCII et de retourner le résultat.</td>	
		</tr>
		<tr>
			<td><b>TOOLS\TAIL.PAS</b></td>
			<td>Cette commande permet d'afficher la fin d'un fichier texte.</td>
		</tr>
		<tr>
			<td><b>TOOLS\WC.PAS</b></td>
			<td>Cette commande permet de compter le nombre de mots, de lignes ou de caractères.</td>
		</tr>
	</table>

<h2>Compilation</h2>
	
Les fichiers Pascal n'ont aucune dépendances, il suffit de télécharger le fichier désiré et de le compiler avec Free Pascal avec la syntaxe de commande  :

<pre><b>fpc</b> <i>LEFICHIER.PAS</i></pre>
	
Sinon, vous pouvez également le compiler avec le Turbo Pascal à l'aide de la syntaxe de commande suivante :	

<pre><b>tpc</b> <i>LEFICHIER.PAS</i></pre>
	
Par exemple, si vous voulez compiler BASIC.PAS, vous devrez tapez la commande suivante :

<pre><b>fpc</b> BASIC.PAS</pre>

<h2>Licence</h2>
<ul>
 <li>Le code source est publié sous la licence <a href="https://github.com/gladir/MSXDOS-0/blob/main/LICENSE">MIT</a>.</li>
 <li>Le paquet original est publié sous la licence <a href="https://github.com/gladir/MSXDOS-0/blob/main/LICENSE">MIT</a>.</li>
</ul>
