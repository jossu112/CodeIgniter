
Code Igniter raamistiku põhjal CRUD näiterakendus


VALMIS CRUD LAHENDUS
1.Klooni repositoorium kuhugi greeny kausta ning ``cd`` sinna kausta. Selle lahendab järgmine rida:

``git clone https://github.com/jossu112/CodeIgniter.git && cd CodeIgniter``

2.Loo db:
```bash
CREATE TABLE `users` (
  `id` int(11) NOT NULL AUTO_INCREMENT,
  `username` varchar(30) NOT NULL,
  `password` varchar(30) NOT NULL,
  `fname` varchar(100) NOT NULL,
PRIMARY KEY(`id`)
) ENGINE=InnoDB DEFAULT CHARSET=latin1;
```
