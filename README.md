# tiibproject.github.io

<style>
.tabs-wrap input[type="radio"]{display:none}
.tab-labels{display:flex;flex-wrap:wrap;gap:6px;border-bottom:2px solid #d0d7de;margin:1.2em 0 0}
.tab-labels label{padding:10px 18px;cursor:pointer;border-radius:8px 8px 0 0;background:#f3f4f6;color:#444;font-weight:600}
.tab-labels label:hover{background:#e5e7eb}
.panel{display:none;padding:20px 8px}
#t1:checked ~ .tab-labels label[for="t1"],
#t2:checked ~ .tab-labels label[for="t2"],
#t3:checked ~ .tab-labels label[for="t3"],
#t4:checked ~ .tab-labels label[for="t4"],
#t5:checked ~ .tab-labels label[for="t5"]{background:#0b5cad;color:#fff}
#t1:checked ~ .panels #p1,
#t2:checked ~ .panels #p2,
#t3:checked ~ .panels #p3,
#t4:checked ~ .panels #p4,
#t5:checked ~ .panels #p5{display:block}
.facts{width:100%;border-collapse:collapse}
.facts td{padding:8px 10px;border-bottom:1px solid #e5e7eb;vertical-align:top}
.facts td:first-child{font-weight:600;width:32%}
.card{border:1px solid #d0d7de;border-radius:10px;padding:14px 18px;margin:12px 0;background:#fafbfc}
.card h4{margin:0 0 4px}
.card small{color:#666}
.code{background:#0d1117;color:#e6edf3;padding:12px 16px;border-radius:8px;overflow-x:auto;font-family:monospace;font-size:14px;white-space:pre}
</style>

# Terminologische Innovationen im Bereich Internationale Beziehungen: Entstehung und Diffusion

*Ein interdisziplinäres, DFG-gefördertes Forschungsprojekt (seit 2023)*

<div class="tabs-wrap">
<input type="radio" name="tabs" id="t1" checked>
<input type="radio" name="tabs" id="t2">
<input type="radio" name="tabs" id="t3">
<input type="radio" name="tabs" id="t4">
<input type="radio" name="tabs" id="t5">
<div class="tab-labels">
<label for="t1">Über das Projekt</label>
<label for="t2">Korpus</label>
<label for="t3">Team</label>
<label for="t4">Publikationen</label>
<label for="t5">Ressourcen</label>
</div>
<div class="panels">

<div class="panel" id="p1">
<p>Ziel dieses interdisziplinär angelegten Forschungsprojekts ist die Analyse <b>terminologischen Wandels</b> in Diskursen über internationale Beziehungen. Zudem wird untersucht, wie terminologische Innovationen aus der Fachsprache der politikwissenschaftlichen Teildisziplin „Internationale Beziehungen“ (IB) in Diskurse der politischen Praxis diffundieren.</p>
<p>Das Projekt geht über die reine Deskription hinaus: Es identifiziert vergleichend Muster und Kausalpfade in <b>Begriffskarrieren</b> und zeigt, welche terminologischen Innovationen unter welchen Umständen besonders erfolgreich sind.</p>
<table class="facts">
<tr><td>Förderzeitraum</td><td>seit 2023</td></tr>
<tr><td>DFG-Verfahren</td><td>Sachbeihilfen</td></tr>
<tr><td>DFG-Fachklassifikation</td><td>1.23-04 Politikwissenschaft<br>1.14-03 Angewandte Sprachwissenschaften, Computerlinguistik</td></tr>
<tr><td>Standort</td><td>TU Darmstadt</td></tr>
</table>
</div>

<div class="panel" id="p2">
<p>Zur Beantwortung der Forschungsfragen wird ein <b>dreiteiliges Korpus</b> angelegt:</p>
<div class="card"><h4>(a) Wissenschaftliche Publikationen</h4>Zu den internationalen Beziehungen, gegliedert in internationale, englischsprachige und deutschsprachige Publikationen.</div>
<div class="card"><h4>(b) Politikberatende Schriften</h4>Von Forschungsinstituten und den wissenschaftlichen Diensten des Bundestags.</div>
<div class="card"><h4>(c) Politische Texte</h4>Debatten des Deutschen Bundestags zu Themen der internationalen Beziehungen sowie Dokumente des Auswärtigen Amts.</div>
<p>Damit wird analysiert, wie und in welchem Zeitraum Innovationen aus fachwissenschaftlichen in politikberatende und politische Diskurse übergehen.</p>
</div>

<div class="panel" id="p3">
<h3>Antragsteller</h3>
<div class="card"><h4>Prof. Dr. Marcus Müller</h4><small>TU Darmstadt, Institut für Sprach- und Literaturwissenschaft</small></div>
<div class="card"><h4>Prof. Dr. Jens Steffek</h4><small>TU Darmstadt, Institut für Politikwissenschaft</small></div>
</div>

<div class="panel" id="p4">
<p><i>Publikationsliste folgt.</i></p>
<div class="card"><h4>Titel der Publikation</h4><small>Autor:innen · Jahr · Zeitschrift / Verlag</small><br><a href="#">Link (DOI / PDF)</a></div>
</div>

<div class="panel" id="p5">
<p>Hier teilen wir die Ressourcen aus dem Projekt, damit unsere Ergebnisse nachvollzogen und weiterverwendet werden können.</p>
<div class="card"><h4>Code</h4>Skripte zur Korpusaufbereitung und zur Analyse von Begriffskarrieren.<br><a href="https://github.com/LucienBlue/REPO-NAME">GitHub-Repository →</a></div>
<div class="code">git clone https://github.com/LucienBlue/REPO-NAME.git
cd REPO-NAME
pip install -r requirements.txt</div>
<div class="card"><h4>Daten</h4>Listen von Termini, Annotationen und abgeleitete Datensätze.<br><a href="#">Zenodo / OSF / Download →</a></div>
<div class="card"><h4>Lizenz</h4>Code unter MIT-Lizenz, Daten unter CC BY 4.0 (bitte anpassen).</div>
</div>

</div>
</div>
