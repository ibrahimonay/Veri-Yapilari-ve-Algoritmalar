# Proje 2

[16,21,11,8,12,22] -> Merge Sort

Yukar�daki dizinin sort t�r�ne g�re a�amalar�n� yaz�n�z.

	Her ad�mda par�aya ay�rarak tek par�a kalana kadar b�l�yoruz.
	[16,21,11,8,12,22]
	[16,21,11]   [8,12,22]
	[16] [21,11]   [8] [12,22]
	[16] [21] [11]   [8] [12] [22]
	S�ralama yap�p listeyi birle�tiriyoruz.
	[16] [11,21]   [8] [12,22]
	[11,16,21]   [8,12,22]
	[8,11,12,16,21,22]

Big-O g�sterimini yaz�n�z.

	Big-O = O(nlogn)