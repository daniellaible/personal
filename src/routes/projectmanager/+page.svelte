<script lang="ts">
    import Header from '../../elements/header.svelte';
</script>

<div>
    <Header location="manager"/>

    <div class="mt-5 ml-20 text-2xl">
        Scrum-Master & Product-Owner
    </div>

    <div class="flex justify-center">
        <div class="w-5/6">
            <div class="w-full  mt-5 text-justify">

                <div class="w-full mt-5 text-justify text-2xl">
                    Ich helfe Ihnen:
                </div>

                <div class="w-full mt-5 text-justify">
                    <li>
                        Scrum effektiv einzuführen oder zu optimieren, sodass Sie die vollen Vorteile der agilen
                        Arbeitsweise nutzen können.
                    </li>
                </div>

                <div class="w-full mt-5 text-justify">
                    <li>
                        Ihre ScrumMaster, Product-Owner und Teams zu coachen, damit sie eigenständig arbeiten und
                        kontinuierliche Verbesserungen vorantreiben.
                    </li>
                </div>

                <div class="w-full mt-5 text-justify">
                    <li>Herausforderungen im agilen Arbeitsprozess zu lösen und Barrieren zu beseitigen, die den Erfolg
                        Ihrer Projekte hemmen.
                    </li>
                </div>

                <div class="w-full mt-5 text-justify">
                    <li>
                        Bei der täglichen Arbeit als Scrum-Master oder Product-Owner und unterstütze Ihre Teams bis der agile
                        Ansatz verinnerlicht wurde.
                    </li>
                </div>

                <div class="w-full mt-5 text-justify text-2xl">
                    Meine Leistungen im Überblick
                </div>

                <div class="w-full mt-5 text-justify">
                    <div class="w-full text-xl">
                        Scrum-Einführung und Implementierung
                    </div>
                    <div class="w-full">
                        Ob Sie neu zu Scrum kommen oder bereits erste Erfahrungen haben – ich unterstütze Sie bei der
                        Einführung oder Optimierung agiler Prozesse. Gemeinsam implementieren wir Scrum so, dass es
                        perfekt zu Ihrem Unternehmen passt.
                    </div>
                </div>

                <div class="w-full mt-5 text-justify">
                    <div class="w-full text-xl">
                        Coaching für ScrumMaster und Teams
                    </div>
                    <div class="w-full">
                        Der ScrumMaster ist das Herzstück eines erfolgreichen agilen Teams. Ich biete individuelle
                        Coachings an, um Ihren ScrumMastern die Fähigkeiten und Werkzeuge zu vermitteln, die sie
                        brauchen, um ihre Rolle exzellent auszufüllen. Auch Ihre Teams profitieren von gezieltem
                        Training, um effizient und selbstorganisiert zu arbeiten.
                    </div>
                </div>

                <div class="w-full mt-5 text-justify">
                    <div class="w-full text-xl">
                        Agiles Projektmanagement
                    </div>
                    <div class="w-full">
                        Als erfahrener Berater begleite ich Ihre Scrum-Projekte und sorge dafür, dass sie im Einklang
                        mit den Scrum-Prinzipien durchgeführt werden. Ich helfe Ihnen, Hindernisse zu identifizieren,
                        den Fortschritt zu überwachen und den Wert für den Kunden zu maximieren.
                    </div>
                </div>

                <div class="w-full mt-5 text-justify">
                    <div class="w-full text-xl">
                        Agile Transformation
                    </div>
                    <div class="w-full">
                        Der Wandel zu einer agilen Organisation erfordert Zeit und Veränderungsbereitschaft. Ich
                        unterstütze Sie dabei, eine agile Kultur zu etablieren, die über einzelne Teams hinausgeht und
                        Ihr gesamtes Unternehmen erfasst. Gemeinsam erarbeiten wir eine Roadmap für Ihre agile
                        Transformation
                    </div>
                </div>

                <div class="w-full mt-5 text-justify">
                    <div class="w-full text-xl">
                        Gemeinsam zu agilen Höchstleistungen
                    </div>
                    <div class="w-full">
                        Lassen Sie uns gemeinsam herausfinden, wie Scrum und agile Methoden Ihre Projekte zum Erfolg
                        führen können. Kontaktieren Sie mich für ein unverbindliches Erstgespräch und erfahren Sie, wie
                        ich Sie auf Ihrem Weg unterstützen kann.
                    </div>
                </div>

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

</div>


