---
#title: "Learn2RAG"
permalink: /
#toc: true
#toc_sticky: true
partners:
  - alt: "Universität Paderborn"
    image_path: /assets/images/UPB.svg
    url: https://dice-research.org/
  - alt: "Institut für Digitale Technologien"
    image_path: /assets/images/IfDT.png
    url: https://ifdt.org/
  - alt: "USU GmbH"
    image_path: /assets/images/USU.png
    url: https://www.usu.com/
  - alt: "DRK-Landesverbandes Rheinland-Pfalz e.V."
    image_path: /assets/images/DRK-RLP.svg
    url: https://itc.drk.de/
  - alt: "Fraunhofer IEM"
    image_path: /assets/images/FraunhoferIEM.png
    url: https://www.iem.fraunhofer.de/
  - alt: "it's owl"
    image_path: /assets/images/OWL-Logo.png
    url: https://its-owl.de/en/
assoc_partners:
  - alt: "eco Verband"
    image_path: /assets/images/eco_Logo.PNG
    url: https://www.eco.de/
  - alt: "KI Bundesvarband"
    image_path: /assets/images/KI_Bundesverband_Logo.svg
    url: https://ki-verband.de/
  - alt: "LESSIE Netzwerk"
    image_path: /assets/images/lessie_netzwerk_square.png
    url: https://lessie.network/
sidebar:
#  - title: "Title"
#    image: http://placehold.it/350x250
#    image_alt: "image"
#    text: "Some text here."
  - title: "Auftaktveranstaltung Generative KI für den Mittelstand"
    text: "Am 18. Juni 2025 findet die [Auftaktveranstaltung zum Programm Generative KI für den Mittelstand](https://factsfiction.regasus.de/portal/standard/registration/start) im Forum Digitale Technologien in Berlin statt und auch unser Projekt wird dort vorort sein."
---

In der heutigen schnelllebigen Geschäftswelt sind Unternehmen und öffentliche Einrichtungen
gefordert, ihre Daten effizient zu nutzen, um wettbewerbsfähig zu bleiben. Das
Forschungsprojekt Learn2RAG setzt genau hier an und untersucht die praktischen Mehrwerte
von Retrieval-Augmented Generation (RAG). Durch innovative Ansätze der generativen
Künstlichen Intelligenz (KI) zielt das Projekt darauf ab, die Nutzung von großen Sprachmodellen
(LLMs) für den Mittelstand zu revolutionieren.

## Was ist RAG?

Retrieval-Augmented Generation (RAG) kombiniert generative KI mit Ihren internen Daten. Anfragen an die KI werden mithilfe hinterlegter Daten ergänzt. 

{% include figure popup=true image_path="/assets/images/Learn2RAG-what-is-RAG.png" alt="An overview of the general idea of RAG" %}

So entstehen präzisere Antworten, die einfacher überprüfbar sind und unternehmensspezifische Kontext-informationen berücksichtigen.

## Warum sollten Sie mitmachen?

Haben Sie eine oder mehrere der folgenden Herausforderungen?

* Sie würden KI gerne in Ihre Prozesse einbinden, aber die fehlende Nachvollziehbarkeit oder die Möglichkeit von Halluzinationen der KI halten Sie davon ab.
* Sie wissen nicht, wie Sie Ihre Daten in die Arbeit mit KI-Systemen integrieren können.
* Relevante Informationen liegen in Ihrem Unternehmen verstreut und sind bei Bedarf nicht einsatzbereit verfügbar.
* Die Auswahl und Integration passender RAG-Architekturen ist komplex und übersteigt Ihr spezifisches Know-How.
* Zeit und Fachkräfte fehlen, um neben dem Tagesgeschäft eigene Prototypen zu entwickeln und RAG-Lösungen zu evaluieren.

## Projektziele & Vorgehen
- Entwicklung und Evaluierung eines überwachten maschinellen Lernverfahrens zur automatischen Generierung von RAG-Pipelines, die auf spezifische Unternehmensbedürfnisse abgestimmt sind.
- Ermöglichung des Zugangs zu generativen KI-Technologien für mindestens 150 Unternehmen, insbesondere für KMUs ohne eigene KI-Expertise.
- Bereitstellung einer Open-Source-Plattform, die es Unternehmen ermöglicht, die Vorteile von RAG schnell und kosteneffektiv zu nutzen.

Das Projekt verfolgt einen klaren und strukturierten Ansatz, der von der Forschung über die
Entwicklung bis hin zur praktischen Anwendung reicht. Durch interaktive Workshops, Webinare und
die Bereitstellung von Open-Source-Ressourcen wird sichergestellt, dass die Ergebnisse nachhaltig und
breit genutzt werden können. Ziel ist es, nicht nur die Effizienz in den Unternehmen zu steigern,
sondern auch die Wettbewerbsfähigkeit Deutschlands im globalen Kontext zu fördern.

## Partner & Beteiligte

Mit einem Gesamtvolumen von über 2.7 Millionen Euro wird das Projekt von einem Konsortium führender wissenschaftlicher Institutionen und Softwareentwickler durchgeführt und durch weitreichende Unternehmensnetzwerke unterstützt.

<div class="partners-gallery">
  {% for partner in page.partners %}
    <figure class="partner-item">
      <a href="{{ partner.url }}">
        <img src="{{ partner.image_path | relative_url }}" alt="{{ partner.alt }}">
      </a>
    </figure>
  {% endfor %}
</div>

### Assoziierte Netzwerke

<div class="partners-gallery">
  {% for partner in page.assoc_partners %}
    <figure class="partner-item">
      <a href="{{ partner.url }}">
        <img src="{{ partner.image_path | relative_url }}" alt="{{ partner.alt }}">
      </a>
    </figure>
  {% endfor %}
</div>
