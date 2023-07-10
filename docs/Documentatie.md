---
layout: page-with-side-nav
title: Documenten StUF-koppelvlak Jeugdzorg (CORV)
folder_files:
#  - title: 130131_Leverings_en_acceptatievoorwaarden_versie_2_Definitief.pdf
#    path: documenten/130131_Leverings_en_acceptatievoorwaarden_versie_2_Definitief.pdf
#  - title: 20180910-CORV-KTP-Informatieblad.pdf
#    path: documenten/20180910-CORV-KTP-Informatieblad.pdf
#  - title: Formulier_Aansluiting_CORV_Acc_v20170821.pdf
#    path: documenten/Formulier_Aansluiting_CORV_Acc_v20170821.pdf
#  - title: Gebruikershandleiding_StUF_Testplatform.pdf
#    path: documenten/Gebruikershandleiding_StUF_Testplatform.pdf
  - title: StUF-koppelvlak_Jeugdzorg_-_versie_1.0.6_20200708_-_schemas_(normatieve_versie).zip
    path: documenten/StUF-koppelvlak_Jeugdzorg_-_versie_1.0.6_20200708_-_schemas_(normatieve_versie).zip
    group: 106
  - title: StUF-koppelvlak_Jeugdzorg_-_versie_1.0.6_20200708_-_schemas_(resolved).zip
    path: documenten/StUF-koppelvlak_Jeugdzorg_-_versie_1.0.6_20200708_-_schemas_(resolved).zip
    group: 106
  - title: StUF-koppelvlak_Jeugdzorg_-_versie_1.0.7_20200916_-_schemas_(normatieve_versie).zip
    path: documenten/StUF-koppelvlak_Jeugdzorg_-_versie_1.0.7_20200916_-_schemas_(normatieve_versie).zip
    group: 107
  - title: StUF-koppelvlak_Jeugdzorg_-_versie_1.0.7_20200916_-_schemas_(resolved).zip
    path: documenten/StUF-koppelvlak_Jeugdzorg_-_versie_1.0.7_20200916_-_schemas_(resolved).zip
    group: 107
  - title: StUF-koppelvlak_Jeugdzorg_-_Wijzigingen_in_versie_1.0.6_20200708.zip
    path: documenten/StUF-koppelvlak_Jeugdzorg_-_Wijzigingen_in_versie_1.0.6_20200708.zip
    group: 106
  - title: StUF-koppelvlak_Jeugdzorg_-_Wijzigingen_in_versie_1.0.7_20200916.zip
    path: documenten/StUF-koppelvlak_Jeugdzorg_-_Wijzigingen_in_versie_1.0.7_20200916.zip
    group: 107
  - title: StUF-Koppelvlak_Jeugdzorg_v1.0.6_20200708.zip
    path: documenten/StUF-Koppelvlak_Jeugdzorg_v1.0.6_20200708.zip
    group: 106
  - title: StUF-Koppelvlak_Jeugdzorg_v1.0.7_20200916.zip
    path: documenten/StUF-Koppelvlak_Jeugdzorg_v1.0.7_20200916.zip
    group: 107
  - title: StUF-Kv_Jeugdzorg_-_Referentielijsten_v1.0_20230703.zip
    path: documenten/StUF-Kv_Jeugdzorg_-_Referentielijsten_v1.0_20230703.zip
    group: 107
  - title: StUF-Kv_Jeugdzorg_-_Referentielijsten_v1.0_20230703.zip
    path: documenten/StUF-Kv_Jeugdzorg_-_Referentielijsten_v1.0_20230703.zip
    group: 106
#  - title: Testset_StUF-koppelvlak_Jeugdzorg_1.0.1.zip
#    path: documenten/Testset_StUF-koppelvlak_Jeugdzorg_1.0.1.zip
---
# Documenten

Hieronder kunt u de zipfiles met de documentatie en de XML-Schema's voor
het StUF-koppelvlak Jeugdzorg (CORV) vinden.

## StUF-koppelvlak Jeugdzorg 1.0.7

Dit betreft de actuele documentatie van de 1.0-versie van het koppelvlak
d.d. 16-09-2020. Ten opzichte van versie 1.0.6 zijn hierin in de
koppelvlak specificatie enkele wijzigingen m.b.t. het VT Terugkopperling
bericht aangebracht. In de StUF schema's zijn t.o.v. de 1.0.6 versie
alleen enkele correcties aangebracht m.b.t. de VT Melding en VT
Terugkoppeling berichten. De 1.0-versie is per 24 november 2015 in
productie ('in gebruik') genomen in het berichtenverkeer.

<ul>
	{% for i in page.folder_files %}
		{% if i.group == 107 %} 
			<li>
			  <a href="{{ i.path | base_url }}">
				{{ i.title }}
			  </a>
			</li>
		{% endif %} 
	{% endfor %}
</ul>

## StUF-koppelvlak Jeugdzorg 1.0.6

Dit betreft de actuele documentatie van de 1.0-versie van het koppelvlak
d.d. 10-07-2020. Ten opzichte van versie 1.0.5 zijn hierin alleen in het
VT Terugkoppeling bericht enkele wijzigingen aangebracht. De 1.0-versie
is per 24 november 2015 in productie ('in gebruik') genomen in het
berichtenverkeer.

<ul>
	{% for i in page.folder_files %}
		{% if i.group == 106 %} 
			<li>
			  <a href="{{ i.path | base_url }}">
				{{ i.title }}
			  </a>
			</li>
		{% endif %} 
	{% endfor %}
</ul>
