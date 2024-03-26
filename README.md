# Teorija

- API ir programmēšanas saskarne, kas ļauj dažādām programmām un sistēmām savstarpēji komunicēt un datu apmaiņai.

- PHP valodā mainīgos deklarē, izmantojot dollāra zīmi un nosaukumu, kuru seko vērtība, kas tiek piešķirta mainīgajam.

- Laravel izmanto MVC (Model-View-Controller) arhitektūru, kur modelis pārvalda datu loģiku, skats attēlo lietotāja saskarni, un kontrolieris apstrādā lietotāja pieprasījumus, nodrošinot labu kodu organizāciju un uzturēšanu.

- ORM (Object-Relational Mapping) ļauj izmantot objektu orientētu pieeju datu bāzu darbībām, vienkāršojot SQL vaicājumu veidošanu un nodrošinot kodu ar augstāku līmeni abstrakcijas, tādējādi padarot to vieglāk lasāmu un uzturamā

- Izmantojot Eloquent ORM, varētu izveidot šādu pieprasījumu, lai iegūtu visus lietotājus ar reitingu lielāku par 4:

                $users = User::where('rating', '>', 4)->get();

Šeit User ir jūsu modelis, kas atspoguļo lietotāju tabulu datu bāzē. where('rating', '>', 4) nosaka nosacījumu, kur reitings ir lielāks par 4. get() metode iegūst visus atbilstošos ierakstus.

