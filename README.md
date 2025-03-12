
Alunos (RA, nome, endereço, cidade)

Disciplinas (COD_DISC, nome_disc, carga_hor)

Professores (COD_PROF, nome, endereço, cidade) Turma (COD_DISC COD TURMA, COD PROF, ANO, horário)

Histórico (RA, COD_DISC, COD_TURMA, COD PROF, ANO, freqüência, nota)


INSERT into ALUNOS values (0912252, 'Aline Bossi'", "Rua manoel', Piracicaba'l

INSERT into HISTORICO values (0912252, 'BD', 'A', 'JAC', '2009', '80', '8.2')

INSERT into HISTORICO values (0912252, 'EDA', 'A', 'RCSV', 2010, 75,7.5)


insert into HISTORICO

select h.RA, BDII,H.COD TURMA, h.COD PROF, 2010, null, null HISTORICO h where h.COD DISC 'BD' and h.ANO 2009 and h. NOTA 5

update HISTORICO

set nota = 4 where nota-4 and nota<5 and cod disc 'BD' and ano 2010'

and cod prof-JAC':

update HISTORICO

set nota-10 where nota>-9.5 and cod_disc = 'BD' and ano 2010 and cod_prof-JAC';

update HISTORICO

set nota nota +0.5 where nota>=5.0 and nota<9.5 and cod disc=BD' and ano 2010 and cod prof-JAC';


delete from HISTORICO

DATUO

19

where RA IN

select RA from Alunos where nome-Jorge dos Santos");

delete from ALUNOS

where nome - Jorge dos Santos';

update Historico h set
h.FREQUENCIA = h.FREQUENCIA + 0.05*
 h. FREQUENCIA where h. FREQUENCIA >45 and h.COD DISC='Bd'  h. FREQUENCIA and h.ANO '2010' and h.Cod prof 'JAC';

update Historico h set h. FREQUENCIA h. FREQUENCIA 1.03 where h. FREQUENCIA <=45 and h.COD DISC='Bd' and h.ANO = '2010' and h.Cod_prof = 'JAC';

INSERT into HISTORICO values (20090301, 'BD', 'A', 'JC', 2009, 60, 8)


update PROFESSORES set nome='Jose Pedro' where nome='Joao Pedro'

update TURMA set cod_prof = 'JAC' where ano 2010 and cod_prof in (select cod_prof from PROFESSORES where nome = 'João")

SELECT Ra FROM HISTORICO WHERE cod_disc='BD' AND ano-2010 AND nota <5

SELECT a.RA, a.NOME, a.NOME from HISTORICO h, ALUNOS a where cod disc-'BD' and ano-2010 and nota <5 and a.RA-h.RA


SELECT distinct (p.NOME) from PROFESSORES P. TURMA where p.COD PROF-L.COD PROF and t.ANO-2010 and t. COD DISC-BD

SELECT a.nome, a.ENDERECO, CIDADE, h.COD DISC from ALUMOS, HISTORICO where a.RA.RA and h. NOTA 5 and h.ano-2010

SELECT distinct a.NOME, a.RA from ALUNOS a, PROFESSORES P, HISTORICO h where h.RA-a.RA and h.COD PROF P.COD PROF and p.NOME like JOSÉ and (h.ANO 2010 or h.ANO 2009) AND A.RA in

(select H.RA from HISTORICO h, PROFESSORES p where h.COD PROF P.COD PROF and p.nome like 'MARCOS%')

select a.RA, a.NOME, h.COD_DISC, d.NOME_DISC,h.ANO, h. FREQUENCIA, h from HISTORICO h, ALUNOS a, DISCIPLINAS d where a.RA h.RA and h. COD DISC = d.COD_DISC and a.NOME like '%ALEX%'


select a.NOME,a.ENDERECO, 'aluno from ALUNOS a where a.CIDADE CAMPINAS' union select p.NOME,P.ENDERECO, 'prof' from PROFESSORES P where p.CIDADE-CAMPINAS'


select a.NOME, P.NOME from ALUNOS a, DISCIPLINAS d, PROFESSORES P, HISTORICO h where a.RA h.RA and  h.COD_DISC and p.COD_PROFh.COD_PROF and
d.COD_DISC d.CARGA HOR<60

select p.NOME

from ALUNOS a, PROFESSORES P, HISTORICO h where a.RA h.ra and

D.COD PROFh.COD PROF and upper (a.NOME) PEDRO PAULO CUNHA AND

h. NOTA<5
