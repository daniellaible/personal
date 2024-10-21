<script lang="ts">
    import Header from '../../elements/header.svelte';
</script>

<div>
    <Header location="consultant"/>
    <div class="mt-5 ml-20 text-2xl">
        Beratung
    </div>
</div>

<div class="flex justify-center">
    <div class="w-5/6">
        <div class="w-full flex mt-5 text-justify">
            Jedes Unternehmen und jedes Projekt ist einzigartig. Daher biete ich keine Lösungen von der Stange, sondern
            passe meine Beratung gezielt auf Ihre individuellen Bedürfnisse an. Ob kleines Startup oder großes
            Unternehmen – ich finde die Lösung, die zu Ihnen passt.
        </div>

        <div class="w-full flex mt-5 text-justify">
            Softwareprojekte können komplex sein. Von der Auswahl der richtigen Technologien über die Projektplanung bis
            hin zur erfolgreichen Implementierung gibt es viele Hürden, die es zu überwinden gilt. Hier komme ich ins
            Spiel. Mit meiner langjährigen Erfahrung als Entwickler und Manager helfe ich Ihnen, die Herausforderungen
            zu meistern, die richtigen
            Entscheidungen zu treffen und Projekte im geplanten Zeit- und Kostenrahmen erfolgreich abzuschließen.
        </div>

        <div class="w-full mt-5 text-justify">
            <div class="w-full text-xl">
                Projektberatung & -planung
            </div>

            <div class="w-full">
                Gemeinsam entwickeln wir eine klare Vision für Ihr Softwareprojekt. Ich unterstütze Sie bei der
                Definition
                von Anforderungen, der Auswahl geeigneter Technologien und erstelle einen strukturierten Fahrplan für
                den
                Projekterfolg.
            </div>
        </div>

        <div class="w-full mt-5 text-justify">
            <div class="w-full text-xl">
                Technologiewahl & Architekturberatung
            </div>
            <div class="w-full">
                Die richtige Technologie ist der Grundstein für den Erfolg. Ich berate Sie bei der Auswahl der passenden
                Technologien und der Gestaltung einer skalierbaren und robusten Softwarearchitektur.
            </div>
        </div>

        <div class="w-full mt-5 text-justify">
            <div class="w-full text-xl">
                Projektmanagement
            </div>
            <div class="w-full">
                Von der initialen Planung bis zur Endabnahme stehe ich Ihnen als Projektmanager zur Seite. Ich sorge für
                eine reibungslose Kommunikation zwischen den Teams, überwache die Einhaltung von Zeitplänen und Budgets
                und
                löse auftretende Probleme effizient.
            </div>
        </div>

        <div class="w-full  mt-5 text-justify">
            <div class="w-full text-xl">
                Qualitäts- und Risikomanagement
            </div>
            <div class="w-full">
                Ich stelle sicher, dass Ihr Softwareprojekt die höchsten Qualitätsstandards erfüllt. Durch gezieltes
                Risikomanagement identifizieren und minimieren wir potenzielle Gefahren frühzeitig, damit Sie sicher ans
                Ziel kommen.
            </div>
        </div>

        <div class="w-full mt-5 text-justify">
            <div class="w-full text-xl">
                Coaching & Weiterbildung
            </div>
            <div class="w-full">
                Ihre Teams fit für die Zukunft machen: Ich biete individuelles Coaching und Schulungen in agilen
                Methoden,
                Projektmanagement und modernen Technologien an, damit Ihre Mitarbeiter optimal aufgestellt sind.
            </div>
        </div>

        <div class="w-full flex mt-5 text-justify">
            Jedes Unternehmen und jedes Projekt ist einzigartig. Daher biete ich keine Lösungen von der Stange, sondern
            passe meine Beratung gezielt auf Ihre individuellen Bedürfnisse an. Ob kleines Startup oder großes
            Unternehmen – ich finde die Lösung, die zu Ihnen passt.
        </div>

        <div class="w-full mt-5 text-justify">
            <div class="w-full text-2xl">
                Lassen Sie uns gemeinsam Ihr Projekt zum Erfolg führen!
            </div>
            <div class="w-full">
                Kontaktieren Sie mich für ein unverbindliches Erstgespräch. Gemeinsam besprechen wir Ihre Ziele und
                entwickeln eine maßgeschneiderte Strategie für Ihr Softwareprojekt..
            </div>
        </div>

        <div class="w-full mt-12">
            Bitte hinterlassen Sie Ihre Kontaktinformationen für ein unverbindliches Gespräch
        </div>

        <form class="max-w-sm mt-5 ml-24">

            <div class="mb-5">
                <label for="company" class="block mb-2 text-sm font-medium text-gray-900 dark:text-white">Firma</label>
                <input type="text" id="company" class="bg-gray-50 border border-gray-300 text-gray-900 text-sm rounded-lg focus:ring-blue-500 focus:border-blue-500 block w-full p-2.5 dark:bg-gray-700 dark:border-gray-600 dark:placeholder-gray-400 dark:text-white dark:focus:ring-blue-500 dark:focus:border-blue-500" required />
            </div>

            <div class="mb-5">
                <label for="email" class="block mb-2 text-sm font-medium text-gray-900 dark:text-white">Ihre E-Mail Adresse</label>
                <input type="email" id="email" class="bg-gray-50 border border-gray-300 text-gray-900 text-sm rounded-lg focus:ring-blue-500 focus:border-blue-500 block w-full p-2.5 dark:bg-gray-700 dark:border-gray-600 dark:placeholder-gray-400 dark:text-white dark:focus:ring-blue-500 dark:focus:border-blue-500" placeholder="max.mustermann@mustermann.de" required />
            </div>

            <div class="mb-5">
                <label for="phone" class="block mb-2 text-sm font-medium text-gray-900 dark:text-white">Ihre Telefonnummer</label>
                <input type="tel" id="phone" class="bg-gray-50 border border-gray-300 text-gray-900 text-sm rounded-lg focus:ring-blue-500 focus:border-blue-500 block w-full p-2.5 dark:bg-gray-700 dark:border-gray-600 dark:placeholder-gray-400 dark:text-white dark:focus:ring-blue-500 dark:focus:border-blue-500" required />
            </div>

            <div>
                <label for="message" class="block mb-2 text-sm font-medium text-gray-900 dark:text-white">Ihr Anliegen</label>
                <textarea id="message" rows="4"
                          class="block p-2.5 w-full text-sm text-gray-900 bg-gray-50 rounded-lg border border-gray-300 focus:ring-blue-500 focus:border-blue-500 dark:bg-gray-700 dark:border-gray-600 dark:placeholder-gray-400 dark:text-white dark:focus:ring-blue-500 dark:focus:border-blue-500"
                          ></textarea>
            </div>

            <button type="submit" class="mt-5 text-white bg-blue-700 hover:bg-blue-800 focus:ring-4 focus:outline-none focus:ring-blue-300 font-medium rounded-lg text-sm px-5 py-2.5 text-center dark:bg-blue-600 dark:hover:bg-blue-700 dark:focus:ring-blue-800">Senden</button>

        </form>
    </div>
</div>
