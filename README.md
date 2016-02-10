BDD
Table x_world :  idCase, X, Y, peuple, idTown, nameTown, idPlayer, namePlayer, idAlly, nameAlly, popTown
	peuple 1=romain, 2=germain , 3=gaulois
Table joueur : id, off/deff
	orientation NULL=?, 1=off, 2=deff
Table village : id, lvl pt, orientation, type
	orientation NULL=?, 1=off, 2=deff, 3=res, 4=spy, 5=capi
Table ally : 
