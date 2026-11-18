<style>
.tabs-wrap input[type="radio"]{display:none}
.tab-labels{display:flex;flex-wrap:wrap;gap:6px;border-bottom:2px solid #d0d7de;margin:1.2em 0 0}
.tab-labels label{padding:10px 18px;cursor:pointer;border-radius:8px 8px 0 0;background:#f3f4f6;color:#444;font-weight:600}
.tab-labels label:hover{background:#e5e7eb}
.panel{display:none;padding:20px 8px}
#t1:checked ~ .tab-labels label[for="t1"], #t2:checked ~ .tab-labels label[for="t2"], #t3:checked ~ .tab-labels label[for="t3"], #t4:checked ~ .tab-labels label[for="t4"], #t5:checked ~ .tab-labels label[for="t5"]{background:#0b5cad;color:#fff}
#t1:checked ~ .panels #p1, #t2:checked ~ .panels #p2, #t3:checked ~ .panels #p3, #t4:checked ~ .panels #p4, #t5:checked ~ .panels #p5{display:block}
.facts{width:100%;border-collapse:collapse}
.facts td, .facts th{padding:8px 10px;border-bottom:1px solid #e5e7eb;vertical-align:top;text-align:left}
.facts td:first-child{font-weight:600;width:32%}
.card{border:1px solid #d0d7de;border-radius:10px;padding:14px 18px;margin:12px 0;background:#fafbfc}
.card h4{margin:0 0 4px}
.card small{color:#666}
.refs{font-size:0.92em;color:#444}
</style>

<h1>Terminologische Innovationen im Bereich Internationale Beziehungen: Entstehung und Diffusion</h1>
<p><em>Ein interdisziplinäres, DFG-gefördertes Forschungsprojekt (seit 2023)</em></p>

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

    <!-- ===== 1. ÜBER DAS PROJEKT ===== -->
    <div class="panel" id="p1">
      <p>Das Reden und Schreiben über internationale Beziehungen ist geprägt von abstrakten, oft metaphorischen Begriffen wie <em>internationales System</em>, <em>Gleichgewicht der Mächte</em> oder <em>internationale Anarchie</em>. Viele dieser Begriffe wurden in einem fachsprachlichen Diskurs entwickelt oder dort mit einer neuen, vom alltäglichen Sprachgebrauch abweichenden Bedeutung versehen. Manche dieser Innovationen haben sich über die Wissenschaft hinaus in die politische Praxis verbreitet. Zu den einflussreichsten begrifflichen Innovationen mit eindeutig akademischer Vorprägung gehören „Global Governance“, „Human Development“ und „Human Security“.</p>

      <p>Das Forschungsprojekt hat zum Ziel, systematisch nachzuzeichnen, auf welchen Wegen und in welchem Ausmaß terminologische Innovationen aus dem wissenschaftlichen Fachdiskurs in die politische Alltagssprache gelangen und dort von politischen Akteur*innen aufgegriffen werden. In unserem Kontext ist zu erwarten, dass sich terminologische Innovationen sowohl auf der formalen Seite (Wortbildung) als auch auf der inhaltlichen Seite von Begriffen (Bedeutungswandel) vollziehen. Obwohl diskursanalytische und insbesondere korpuslinguistische Analysemethoden in den IB auf dem Vormarsch sind, wissen wir bislang wenig über die Dynamik dieser Diffusion zwischen Fachsprache und politischer Sprache.</p>

      <p>Empirisch untersucht das Forschungsteam zunächst die Entwicklung des akademischen Vokabulars der Internationalen Beziehungen über einen Zeitraum von 25 Jahren – von der bipolaren Ordnung des Kalten Krieges in den 1970er Jahren bis zur unipolaren Weltordnung unter der Dominanz der USA. Diese sprachlichen Entwicklungen werden dann mit Veränderungen in der Politikberatung und in politischen Diskursen verglichen.</p>

      <p>Die Ergebnisse des Projekts werden neue Einblicke in den Einfluss der wissenschaftlichen Disziplin der Internationalen Beziehungen auf politische Debatten liefern. Dabei geht es nicht um den direkten Transfer wissenschaftlicher Erkenntnisse oder Empfehlungen in die Politik, sondern um dominante Beschreibungen, Interpretationen und Frames, die bestimmen, was in der internationalen Politik als normal, möglich oder wünschenswert gilt. Insofern ist Sprache nicht nur Vehikel für bestimmte Interaktionen zwischen Staaten, sondern auch konstitutiv für den Gegenstand der internationalen Beziehungen, so die sozialkonstruktivistischen Ansätze der IB seit den 1980er Jahren. Die Art und Weise, wie die internationalen Beziehungen beschrieben werden, ist daher von politischer Bedeutung.</p>

      <p>Diese Perspektive auf den Einfluss der Politikwissenschaft unterscheidet das Projekt von bisherigen Studien und ermöglicht eine systematische Analyse der erfolgreichsten Theorieschulen der Internationalen Beziehungen. Damit kann das Projekt langfristig zu einem besseren Verständnis der Rolle wissenschaftlicher Konzeptualisierung in der Politik beitragen.</p>

      <table class="facts">
        <tr><td>Förderzeitraum</td><td>seit 2023</td></tr>
        <tr><td>DFG-Verfahren</td><td>Sachbeihilfen</td></tr>
        <tr><td>DFG-Fachklassifikation</td><td>1.23-04 Politikwissenschaft<br>1.14-03 Angewandte Sprachwissenschaften, Computerlinguistik</td></tr>
        <tr><td>Standort</td><td>TU Darmstadt</td></tr>
      </table>
    </div>

    <!-- ===== 2. KORPUS ===== -->
    <div class="panel" id="p2">
      <h3>Aufbau des Korpus</h3>
      <p>Zur Beantwortung der Forschungsfragen wird ein dreiteiliges Korpus aufgebaut. Es umfasst insgesamt 25.224 Texte mit rund 35,5 Millionen Tokens und bildet drei Diskursbereiche ab, zwischen denen terminologische Innovationen wandern können: der akademische Diskurs, die Politikberatung und die politische Praxis.</p>

      <div class="card">
        <h4>(a) Akademischer Diskurs</h4>
        <small>2.294 Texte · 13.236.245 Tokens</small>
        <p>Wissenschaftliche Fachaufsätze aus fünf ausgewählten deutschsprachigen Zeitschriften des Fachgebiets: <em>Europa-Archiv</em>, <em>Die Friedens-Warte</em>, <em>Zeitschrift für Internationale Beziehungen</em>, <em>Politische Vierteljahresschrift</em> und <em>Internationale Politik</em>.</p>
      </div>

      <div class="card">
        <h4>(b) Politische Beratung</h4>
        <small>989 Texte · 9.566.984 Tokens</small>
        <p>Politikberatende Schriften des Leibniz-Instituts für Friedens- und Konfliktforschung und der Stiftung Wissenschaft und Politik, Materialien der Enquete-Kommissionen sowie Texte der Wissenschaftlichen Dienste des Bundestags.</p>
      </div>

      <div class="card">
        <h4>(c) Politische Praxis</h4>
        <small>21.941 Texte · 12.676.872 Tokens</small>
        <p>Der Sprachgebrauch politischer Akteur*innen: Plenarprotokolle und parlamentarische Antworten zu Themen der internationalen Beziehungen sowie Reden von Außenministern.</p>
      </div>

      <h3>Korpusaufbereitung</h3>
      <p><strong>1. Digitalisierung und Bereinigung.</strong> Die gesammelten Texte werden mittels OCR digitalisiert und mit Python sowie ABBYY FineReader (lizenzierte Software) halbautomatisch bereinigt und sortiert. Dabei werden Fließtext, Fußnoten und Literaturverzeichnis voneinander getrennt.</p>
      <p><strong>2. Korrektur der OCR-Qualität.</strong> Texte mit schlechter OCR-Qualität werden über die API von Gemini 1.5 Flash automatisch nachkorrigiert.</p>
      <p><strong>3. Linguistische Annotation.</strong> Die Texte werden mit Stanza (Peng et al. 2020) tokenisiert, lemmatisiert und mit Wortartinformationen (POS-Tags) versehen.</p>
      <p><strong>4. Metadaten.</strong> Jeder Text erhält eine eindeutige ID. Um die Metadaten über alle Quellen hinweg konsistent zu halten, wurde ein einheitliches Metadatenschema entwickelt; ist ein Attribut nicht verfügbar, wird es einheitlich mit „no_entry“ belegt.</p>
      <p><strong>5. Speicherung und Zugang.</strong> Für jeden Text wird eine vertikale VRT-Datei erzeugt. Das Korpus ist in CQPweb (Hardie 2012) gespeichert und kann dort durchsucht und analysiert werden.</p>

      <h3>Literatur</h3>
      <p class="refs">Hardie, Andrew (2012): CQPweb – Combining Power, Flexibility and Usability in a Corpus Analysis Tool. In: <em>International Journal of Corpus Linguistics</em> 17(3), S. 380–409.</p>
      <p class="refs">Qi, Peng et al. (2020): Stanza: A Python Natural Language Processing Toolkit for Many Human Languages. In: <em>Proceedings of the 58th Annual Meeting of the Association for Computational Linguistics: System Demonstrations</em>, S. 101–108.</p>
    </div>

    <!-- ===== 3. TEAM ===== -->
    <div class="panel" id="p3">
      <div class="card">
        <h4>Prof. Dr. Marcus Müller</h4>
        <small>TU Darmstadt, Institut für Sprach- und Literaturwissenschaft</small>
      </div>
      <div class="card">
        <h4>Prof. Dr. Jens Steffek</h4>
        <small>TU Darmstadt, Institut für Politikwissenschaft</small>
      </div>
      <div class="card">
        <h4>Megan Fellows</h4>
        <small>TU Darmstadt, Institut für Politikwissenschaft</small>
      </div>
      <div class="card">
        <h4>Dariia Shamgunova</h4>
        <small>TU Darmstadt, Institut für Sprach- und Literaturwissenschaft</small>
      </div>
      <div class="card">
        <h4>Qinghui Zhang</h4>
        <small>TU Darmstadt, Institut für Sprach- und Literaturwissenschaft</small>
      </div>
      <div class="card">
        <h4>Mo Han</h4>
        <small>TU Darmstadt, Institut für Sprach- und Literaturwissenschaft</small>
      </div>
    </div>

    <!-- ===== 4. PUBLIKATIONEN ===== -->
    <div class="panel" id="p4">
      <div class="card">
        <h4>Terminologische Innovationen in Internationalen Beziehungen</h4>
        <small>Mo Han, Marcus Müller · 2025 · <em>edition</em> 2, S. 5–12 · ISSN 1862-023X</small><br>
        <small>Schlagwörter: Terminologie, Korpuslinguistik, Internationale Beziehungen, Wortsinndisambiguierung, LLM</small><br>
        <a href="https://edition.dttev.org/ausgaben/edition-2025-2-e-version.pdf">PDF →</a>
      </div>

      <div class="card">
        <h4>Prompting LLM for Term Sense Identification</h4>
        <small>Mo Han, Marcus Müller · 2025 · Konferenzbeitrag (Proceedings, noch nicht erschienen) · 19th International Conference TOTh, 6. Juni 2025</small>
      </div>

      <div class="card">
        <h4>Constructing the Corpus of Terminological Innovations in International Relations</h4>
        <small>Mo Han, Jörn Stegmeier, Marcus Müller, Megan Fellows, Jens Steffek · 2025 · Posterpräsentation · Corpus Linguistics 2025</small><br>
        <a href="https://www.discourselab.de/moodle/mod/resource/view.php?id=389">Poster →</a>
      </div>
    </div>

    <!-- ===== 5. RESSOURCEN ===== -->
    <div class="panel" id="p5">
      <p>Code, Daten und weitere Ressourcen aus dem Projekt werden hier in Kürze zur Verfügung gestellt.</p>
    </div>

  </div>
</div>
