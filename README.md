--USE TO SET ONE GRADE AT ONE SITE

--Update.Customers

--Set Customers.Buscod = 'NC'

--where SiteID = '154' and Grade = 'KG'



--USE TO SET MORE THAN ONE GRADE AT ONE SITE

--Update.Customers

--Set Customers.Buscod = 'NC'

--Where SiteID = '118' and Grade in ('PK', 'KG', '01', '02', '03', '04', 
'05')




--USE TO SET ONE GRADE AT MORE THAN ONE SITE

--Update.Customers

--Set Customers.Buscod = 'NC'

--Where SiteID in ('131', '127', '144') and Grade ='PK'




--USE TO SET MORE THAN ONE GRADE AT MORE THAN ONE SITE

--Update.Customers

--Set Customers.Buscod = 'NC'

--Where SiteID in ('188', '186')--, '169')

--and   Grade  in ('EE', 'PK', 'KG')--, '02', '03', '04', '05')

--Update.Customers

--Set Customers.Buscod = 'NC'

--Where SiteID = '220' and Grade in ('PK', 'KG')

--Update.Customers

--Set Customers.Buscod = 'NC'

--Where SiteID in ('063', '107', '110', '114', '115', '116', '117', '123', 

'127', '129', '131', '134', '137', '144', '148', '150', '151', '152', 

'154', '156', '161', '167', '177', '184', '187', '207', '209', '216', 

'219', '220', '224', '225', '226', '227') and Grade in ('PK', 'KG')
