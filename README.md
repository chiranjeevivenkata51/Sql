
Table:
1	chiranjeevi	10000
2	Venkata	20000
3	Sai	280000
4	Manikanta	30000
5	Chiranjivi	280000

/*creating stored procedure in mysql work bench
CREATE DEFINER=`root`@`localhost` PROCEDURE `a`(in me varchar(20),out op int)
BEGIN
select a into op from emp where b = me;
END

/*Executing
SET @m='Sai';
CALL `test`.`a`(@m, @o);
select @o;

/* if statement
select b,IF(c>18000,"A","B")AS salgrade from ac;
